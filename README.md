<p align="center">
   <img src="https://github.com/AhmadHirzallah/Libft/blob/main/banner.png">
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Libft-125%2F100-brightgreen?style=flat-square"/>
   <img src="https://img.shields.io/badge/language-C-blue.svg?style=flat-square"/>
</p>

# 📚 Overview

Libft is a foundational project in the 42 school curriculum. The aim is to recreate essential C standard library functions along with additional utilities. This experience enhances understanding of C programming and prepares students for more complex projects.

# ✨ Features

- **C Standard Library Functions**: Implementations of functions like `ft_memset`, `ft_bzero`, `ft_strlen`, etc.
- **Additional Functions**: Utilities such as `ft_substr`, `ft_strjoin`, `ft_split`, and `ft_itoa`.
- **Linked List Management**: Functions for linked list operations including `ft_lstnew`, `ft_lstadd_front`, and more.

# 📂 Source Files

### 📜 Standard Functions
- `ft_memset.c`, `ft_bzero.c`, `ft_memcpy.c`, `ft_memmove.c`, `ft_memchr.c`, `ft_memcmp.c`
- `ft_strlen.c`, `ft_isalpha.c`, `ft_isdigit.c`, `ft_isalnum.c`, `ft_isascii.c`, `ft_isprint.c`
- `ft_toupper.c`, `ft_tolower.c`, `ft_strchr.c`, `ft_strrchr.c`, `ft_strncmp.c`
- `ft_strlcpy.c`, `ft_strlcat.c`, `ft_strnstr.c`, `ft_atoi.c`, `ft_calloc.c`, `ft_strdup.c`

### 🔧 Additional Functions
- `ft_substr.c`, `ft_strjoin.c`, `ft_strtrim.c`, `ft_split.c`, `ft_itoa.c`, `ft_strmapi.c`
- `ft_putchar_fd.c`, `ft_putstr_fd.c`, `ft_putendl_fd.c`, `ft_putnbr_fd.c`, `ft_striteri.c`

### 🔗 Bonus Functions (Linked List)
- `ft_lstnew_bonus.c`, `ft_lstadd_front_bonus.c`, `ft_lstsize_bonus.c`, `ft_lstlast_bonus.c`
- `ft_lstadd_back_bonus.c`, `ft_lstdelone_bonus.c`, `ft_lstclear_bonus.c`, `ft_lstiter_bonus.c`, `ft_lstmap_bonus.c`

# ⚙️ Compilation

The Makefile is designed to compile the library efficiently:

- `make`: Compiles all source files into `libft.a`.
- `make bonus`: Compiles the bonus linked list functions and adds them to `libft.a`.
- `make clean`: Removes object files.
- `make fclean`: Removes object files and the compiled library `libft.a`.
- `make re`: Cleans and recompiles the library.

# 🛠️ Installation

```bash
git clone https://github.com/AhmadHirzallah/Libft.git
cd Libft
make
