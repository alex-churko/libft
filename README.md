🌿  Libft — My First 42 Project
────────────────────────────────────────────────────────────────────

Libft is my first project at 42 Wolfsburg.  
The goal of this project is to rebuild essential standard C library 
functions and create a reusable custom library for future projects.

This project helps develop a deep understanding of:

	• memory management
	• pointer logic
	• string manipulation
	• low-level C programming concepts


📌  Project Overview
────────────────────────────────────────────────────────────────────

The library includes three parts:


🧱  Mandatory Part
	Reimplementation of core libc functions, including:
		- character validation
		- string handling
		- memory operations


🧰  Additional Functions
	Custom utility functions, such as:
		- ft_split
		- ft_itoa
		- ft_strjoin
		- and more


🧩  Bonus (optional)
	Linked list utilities implemented using the `t_list` structure.

The compilation output is a static library file:

	libft.a


⚙️  Compilation Instructions
────────────────────────────────────────────────────────────────────

Available Makefile commands:

		make        → compile the library
		make clean  → remove object files
		make fclean → remove object files and libft.a
		make re     → rebuild everything
		make bonus  → compile with bonus functions


🛠️  How to Use the Library
────────────────────────────────────────────────────────────────────

Include the header in your program:

	#include "libft.h"

Compile with the library:

	gcc your_file.c libft.a


📖  Rules & Requirements
────────────────────────────────────────────────────────────────────

	✔ Follows the 42 Norm
	✔ Only allowed external functions are used
	✔ No memory leaks
	✔ No global variables


🎯  Status
────────────────────────────────────────────────────────────────────

This library will continue to grow and evolve throughout the 42 curriculum.


👤  Author
────────────────────────────────────────────────────────────────────

	Oleksandr Churko  
	42 Wolfsburg 🇩🇪
