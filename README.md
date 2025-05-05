# Libft

*Oh brave coder, embark on a journey to forge your own library of functions, a treasure trove of tools to aid you in the grand odyssey of programming!*

Within this repository lies **Libft**, the foundation stone of mastery in C programming. Here, you shall craft a library of essential functions to support your future conquests.

## Prelude

*Oh noble navigator of code, welcome to the repository of Libft!*

In this project, you shall recreate several standard C library functions, such as `strlen` and `strdup`, and implement additional utility functions to extend your arsenal.

## Table of Contents

- [The Quest](#the-quest)
- [Features](#features)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Functions Implemented](#functions-implemented)
- [Testing](#testing)
- [Acknowledgments](#acknowledgments)

## The Quest

*Embark, O valiant coder, on this grand odyssey!*

Your goal is to implement a robust and versatile library of functions, honoring the following requirements:
- Reimplement classic C standard library functions like `strncmp`, `memcpy`, and `atoi`.
- Add new utility functions for string manipulation, memory management, and linked lists.
- Design your library to be modular, reusable, and efficient.

Libft is not only a toolset but also a rite of passage to sharpen your skills in C and memory management.

## Features

*Behold the marvels of Libft:*

- **Memory Management**: Functions like `malloc` and `free` will be your allies in dynamic memory allocation.
- **String Manipulation**: Recreate functions for string copying, concatenation, and comparison.
- **Linked List Operations**: Build your own singly and doubly linked lists for dynamic data structures.
- **Extensibility**: Add your own custom functions to expand this library as you see fit.

## Requirements

*To forge this library, gather these tools:*

- **Compiler**: GCC or Clang.
- **Libraries**: Standard C library (`<unistd.h>`, `<stdlib.h>`, `<string.h>`).
- **Makefile**: Create a Makefile to automate compilation with targets `all`, `clean`, `fclean`, and `re`.

## Getting Started

*Let us hoist the sails and set course!*

Clone this repository and navigate to the `libft` directory:
```bash
git clone https://github.com/nsilva-n/42CC-0-libft.git
cd 42CC-0-libft
make
```

Use your library in other projects by including `libft.a` in your compilation:
```bash
gcc -Wall -Wextra -Werror -L. -lft main.c -o main
```

## Functions Implemented

*With these tools, conquer the world of C programming:*

### Part 1: Libc Functions
- `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memccpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`
- `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`
- `ft_atoi`, `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- `ft_toupper`, `ft_tolower`

### Part 2: Additional Functions
- `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_itoa`, `ft_strmapi`
- `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus: Linked List Functions
- `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`
- `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

*Expand the library with your own creations to meet your needs!*

## Acknowledgments

*With gratitude to the authors of the C Standard Library and the 42 curriculum, we dedicate this work.*

May your journey through the seas of Libft bring you wisdom and mastery over the arcane arts of programming.
