# Hello
Basic "Hello World" In Assembly
## Dependencies
Linux x64 (Any Distro)  
NASM for Linux  
LD for Linux
## How To Build
Install the **nasm** package for your distro  
After it installs, clone this repo with **git**  
After cloning run `nasm -f elf64 -o hello.o main.asm`  
After it builds the **.o** file run this command:  
`ld -o Hello hello.o` and it will build the executable file
