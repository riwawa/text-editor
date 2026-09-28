# Terminal Text Editor in C

A small terminal-based text editor written in C, inspired by [Kilo](https://viewsourcecode.org/snaptoken/kilo/index.html).

This project is currently under development and is being built as a hands-on way to study low-level programming, terminal behavior, memory management, and systems programming concepts.

## What I'm Learning

- raw terminal mode with `termios`
- byte-by-byte keyboard input
- ANSI escape sequences
- cursor movement and screen rendering
- terminal window size detection
- dynamic memory with `malloc`, `realloc`, and `free`
- pointers and `structs`
- low-level I/O with `read()` and `write()`
- keyboard escape sequence parsing
- editor state management

## Current Features

- raw mode
- arrow key support
- Home / End
- Page Up / Page Down
- cursor movement
- terminal size detection
- dynamic output buffer
- screen redraw
- exit with `Ctrl-Q`

## In Development

Next steps include:

- file loading
- editable text buffers
- character insertion and deletion
- scrolling
- file saving
- status bar
- search
- syntax highlighting

## Build

```bash
gcc -Wall -Wextra text-editor.c -o editor
./editor
```

## Status

Work in progress — currently focused on building the terminal, input, rendering, and cursor infrastructure before implementing full text editing.