build:
	nasm -f elf hello_world.asm
	ld -m elf_i386 -s -o hello hello_world.o
clear:
	rm -rf *.o
