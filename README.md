# Assembly Playground

Here is a simple area to dabble with the likes of Assembly.

## Getting Started

Once you've written some assembly, you'll need to assemble into an object file.

`nasm -f elf32 ex1.asm -o ex1.o`

Next, it'll need to be linked to get your executable binary.

`ld -m elf_i386 ex1.o -o ex1`
