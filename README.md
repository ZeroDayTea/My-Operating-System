# My-Operating-System
## Created in collaboration with @ardupper
Operating System written in C++ that can print text and manage input from a keyboard

Created by following the tutorial series at: https://www.youtube.com/watch?v=1rnA6wpF0o4&list=PLHh55M_Kq4OApWScZyPl5HhgsTJS9MZ6M and then following my own path with help from http://wiki.osdev.org

Run in a virtual machine or boot using qemu most preferrably (I am not responsible for any damage to your hard drive if you choose to boot from the operating system files)

## Information: ##
----

Created on a Linux Mint 18.3 (Sylvia) system

Created using C++ with exception to some necessary assembler files

Includes support for all alphanumerical keyboard keys and special characters including (";", "'", ",", ".", "/", "\n", " ")
* If you want to add additional support for more keyboard keys add a case to the keyboard.cpp file under the switch(key) switch and compile with something like gcc to keyboard.o
* If you want to modify Operating System activity at startup modify the kernel.cpp file under the kernelMain() function and compile with somethign like gcc to kernel.o
