# Implementing a new debug plugin



# Interface

## libr/include/r\_debug.h

# Internals

## libr/bp

The "bp" subsystem of radare implements all the necessary details for dealing with breakpoints on any given architecture. It handles managing the list of breakpoints and more.

## libr/debug/debug.c

Main functionalities of the debug are implemented here

## libr/core/cmd\_debug.c

The debugger shell commands are implemented here

# Debug Plugins 

* Brainfuck: libr/debug/p/debug\_bf.c
* Bochs: libr/debug/p/debug\_bochs.c
* ESIL: libr/debug/p/debug\_esil.c
* GDB: libr/debug/p/debug\_gdb.c
* Native: libr/debug/p/debug\_native.c
* QNX: libr/debug/p/debug\_qnx.c
* RAP: libr/debug/p/debug\_rap.c
* WinDBG: libr/debug/p/debug\_windbg.c



TODO: add a short documentation, links to the code

