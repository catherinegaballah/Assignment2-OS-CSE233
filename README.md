
# Assignment 2 — Operating Systems (CSE233)

This repository contains code examples of Assignment 2 for the Operating Systems include:
process creation, process management, the role of the linker and loader, 
and building programs with Makefiles.

## Description

This project demonstrates:

- Creating processes with fork()

- Managing processes (start, stop, background, resume)

- Understanding the linker through multi-file C programs

- Understanding the loader using dynamic libraries (ldd)

- Building programs using a Makefile, Compilation and automation 

## Project structure
- process_creation.c 
- file1.c and file2.c 
- simple_program.c 
- Makefile 
- answers.txt 
- README.md 
- LICENSE 

## Installation
- Ubuntu Linux
- Install GCC (GNU Compiler Collection)
  ```bash
  sudo apt install gcc
- Install make
  ```bash
  sudo apt install make
 
## Usage
- Run using gcc
 ```bash
 # run fork()
 gcc process_creation.c -o process_creation
 ./process_creation

 ```bash
 # Run linker
 gcc file1.c file2.c -o output_program
 ./output_creation

 ```bash
 # Run inspect loader output
 gcc simple_program -o simple_program
 ./simple_program

- Run executables after building:
  ```bash
  make
 ```bash
 ./process_creation
 ```bash
 ./output_program
 ```bash
 ldd simple_program

## Authors
Catherine Adel Zaki Gaballah

## License
 MIT
