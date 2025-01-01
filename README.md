# astext
A simple text editor written in C

## Getting Started

### Build

To build, simply run `make`. The executable will be placed in the `build` folder.

Techinically, I should be using CMake but I don't care. This is a dependency-less project

## Usage

You can either load an existing file via `./astext <filename>` or run it on it's own via `./astext`

### Commands

`Crtl-S`: Save. If no file is passed during the programs instantiation, you will be prompted to Save As
<br>
`Ctrl-Q`: Quit. If you are quitting without saving, you will be prompted to press `Ctrl-Q` twice to confirm
<br>
`Ctrl-F`: Search. Use the arrow keys to search thorugh all matches. Keywords that are matched will be highlighted
<br>

## Fun Features

This text editor supports syntax highlighting for Cxx language. Try it out!