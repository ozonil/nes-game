# nes-game
NES game

# steps:

1. Download the cc65 compiler/assembler toolchain to assemble your code. On linux: `sudo apt-get install cc65`
2. Run `ca65 hello.asm` to generate the object file.
3. Run `ld65 hello.o -t nes -o hello.nes` runs the linker and generates our .nes file.
4. You can now run your .nes file in an emulator like fceux: `fceux hello.nes`
