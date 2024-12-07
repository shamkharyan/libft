# About Libft

Libft (library of functions) is the first project in 42 Yerevan common core.

In this project, you should implement the basic functions of the C standard library along with other useful functions that you will use in many projects.

## How to use

- Add libft repository to the root directory of the project.
- Go to the libft repository and use `make` command to build the library.
- Use `make bonus` command to build the library with bonus Linked list functions.
- Include the header file of the library in your .c files using `#include "libft"`.
- When compiling your project, add the path to libft and the libft.a library file. If you're using a Makefile, you can do this:
 ```Makefile
LIBFT_PATH = path/to/libft
LIBFT = $(LIBFT_PATH)/libft.a

SRC = main.c  # Your source code files

all:
    gcc -o my_program $(SRC) $(LIBFT)  # Add libft.a during compilation
```

## Libft functions

### Functions from `<ctype.h>`

- [`ft_isalpha`](ft_isalpha.c) - checks whether the passed character is alphabetic.
- [`ft_isdigit`](ft_isdigit.c) - checks whether the passed character is decimal digit.
- [`ft_isalnum`](ft_isalnum.c) - checks whether the passed character is alphanumeric.
- [`ft_isascii`](ft_isascii.c) - checks whether the passed character fits into the ASCII character set.
- [`ft_isprint`](ft_isprint.c) - checks whether the passwd character is printable character.
- [`ft_tolower`](ft_tolower.c) - converts uppercase letters to lowercase.
- [`ft_toupper`](ft_toupper.c) - converts lowercase letters to uppercase.

### Functions from `<string.h>`

- [`ft_strlen`](ft_strlen.c) - returns the length of a string, excluding the null terminator.
- [`t_memset`](ft_memset.c) - fills memory with a constant byte.
- [`ft_bzero`](ft_bzero.c) - sets memory to zero.
- [`ft_memcpy`](ft_memcpy.c) - copies memory from one area to another.
- [`ft_memmove`](ft_memmove.c) - moves memory from one area to another, handling overlapping memory.
- [`ft_strlcpy`](ft_strlcpy.c) - copies a string to a destination buffer, ensuring null-termination and preventing buffer overflow.
- [`ft_strlcat`](ft_strlcat.c) - appends a string to a destination buffer, ensuring null-termination and preventing buffer overflow.
- [`ft_strchr`](ft_strchr.c) - locates the first occurrence of a character in a string.
- [`ft_strrchr`](ft_strrchr.c) - locates the last occurrence of a character in a string.
- [`ft_strncmp`](ft_strncmp.c) - compares up to a specified number of characters from two strings.
- [`ft_memchr`](ft_memchr.c) - locates the first occurrence of a character in memory.
- [`ft_memcmp`](ft_memcmp.c) - compares memory blocks.
- [`ft_strdup`](ft_strdup.c) - allocates memory and returns a duplicate of the string.

### Functions from `<stdlib.h>`

- [`ft_atoi`](ft_atoi.c) - converts a string to an integer.
- [`ft_calloc`](ft_calloc.c) - allocates memory for an array and initializes it to zero.

### Additional Functions

- [`ft_substr`](ft_substr.c) - allocates and returns a substring starting from a specified position with a given length.
- [`ft_strjoin`](ft_strjoin.c) - allocates and returns the concatenation of given two strings.
- [`ft_strtrim`](ft_strtrim.c) - allocates and returns a string with trimed leading and trailing given characters.
- [`ft_split`](ft_split.c) - splits a string into an array of substrings based on a delimiter.
- [`ft_itoa`](ft_itoa.c) - allocates and converts an integer to a string.
- [`ft_strmapi`](ft_strmapi.c) - applies a function to each character of a string and returns a new allocated string.
- [`ft_striteri`](ft_striteri.c) - applies a function to each character of a string.
- [`ft_putchar_fd`](ft_putchar_fd.c) - outputs the character to the given file descriptor.
- [`ft_putstr_fd`](ft_putstr_fd.c) - outputs the string to the given file descriptor.
- [`ft_putendl_fd`](ft_putendl_fd.c) - outputs the string to the given file descriptor followed by a new line.
- [`ft_putnbr_fd`](ft_putnbr_fd.c) - outputs the integer to the given file descriptor.

### Bonus Linked list functions

 - [`ft_lstnew`](ft_lstnew.c) - allocates and returns a new node.
 - [`ft_lstadd_front`](ft_lstadd_front.c) - adds the given node at the beginnig of the list.
 - [`ft_lstsize`](ft_lstsize.c) - counts the number of nodes in the list.
 - [`ft_lstlast`](ft_lstlast.c) - returns the last node of the list.
 - [`ft_lstadd_back`](ft_lstadd_back.c) - adds the given node at the end of the list.
 - [`ft_lstdelone`](ft_lstdelone.c) - frees the given node content using given funcion.
 - [`ft_lstclear`](ft_lstclear.c) - frees the given node and every successor of that node using given function.
 - [`ft_lstiter`](ft_lstiter.c) - iterates the list and applies the given function on the content of each node.
 - [`ft_lstmap`](ft_lstmap.c) - iterates the list and applies the given function on the content of each node allocating new list.




 
