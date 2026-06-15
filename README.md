# sudokuPlayground

A C++ scratch project for experimenting with Sudoku ideas. Currently a skeleton: a
single `main.cpp` entry point with the build wired up, ready to grow solver/generator
code into.

## Build

```sh
cmake -B build -S .
cmake --build build
```

Requires CMake >= 3.12 and a C++17 compiler.

## Run

```sh
./build/sudokuPlayground
```
