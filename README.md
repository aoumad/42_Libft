# 42_Libft

### TOC
* [What is libft?](#what-is-libft)
* [What kind of functions should I implement?](#What-kind-of-functions-should-I-implement?)
* [How do I use the library?](#how-do-i-use-the-library)

### What is libft?
[Libft][1] is an individual project at [42][2] that requires us to re-create some standard C library functions including some additional ones that can be used later to build a library of useful functions for the rest of the program.
Disclaimer: *Reinventing the wheel is bad, 42 makes us do this just so we can have a deeper understanding of data structures and basic algorithms. At 42 we're not allowed to use some standard libraries on our projects, so we have to keep growing this library with our own functions as we go farther in the program.*

### What kind of functions should I implement?

there are 2 sections:

1.  **Libc Functions:** Some of the standard C functions
2.  **Bonus Functions:** Functions 42 deems will be useful for linked list manipulation

### Functions from `<ctype.h>` library

* [`ft_isascii`](ft_isascii.c)		- test for ASCII character.
* [`ft_isalnum`](ft_isalnum.c)		- alphanumeric character test.
* [`ft_isalpha`](ft_isalpha.c)		- alphabetic character test.
* [`ft_isdigit`](ft_isdigit.c)		- decimal-digit character test.
* [`ft_isprint`](ft_isprint.c)		- printing character test (space character inclusive).
* [`ft_tolower`](ft_tolower.c)		- upper case to lower case letter conversion.
* [`ft_toupper`](ft_toupper.c)		- lower case to upper case letter conversion.

### Functions from `<stdlib.h>` library

* [`ft_atoi`](ft_atoi.c)		- convert ASCII string to integer.
* [`ft_calloc`](ft_calloc.c)	- memory allocation.

### Functions from `<strings.h>` library

* [`ft_bzero`](ft_bzero.c)		- write zeroes to a byte string.
* [`ft_memset`](ft_memset.c)		- write a byte to a byte string.
* [`ft_memchr`](ft_memchr.c)		- locate byte in byte string.
* [`ft_memcmp`](ft_memcmp.c)		- compare byte string.
* [`ft_memmove`](ft_memmove.c)	- copy byte string.
* [`ft_memcpy`](ft_memcpy.c)		- copy memory area.
* [`ft_memccpy`](ft_memccpy.c)	- copy string until character found.

### Functions from `<string.h>` library

* [`ft_strlen`](ft_strlen.c)				- find length of string.
* [`ft_strchr`](ft_strchr.c)				- locate character in string (first occurrence).
* [`ft_strrchr`](ft_strrchr.c)			- locate character in string (last occurence).
* [`ft_strnstr`](ft_strnstr.c)			- locate a substring in a string (size-bounded).
* [`ft_strncmp`](ft_strncmp.c)			- compare strings (size-bounded).
* [`ft_strnrcmp`](ft_strnrcmp.c)			- reversely compare strings (size-bounded).
* [`ft_strdup`](ft_strdup.c)				- save a copy of a string (with malloc).
* [`ft_strlcpy`](ft_strlcpy.c)			- size-bounded string copying.
* [`ft_strlcat`](ft_strlcat.c)			- size-bounded string concatenation.

### Non-standard functions

* [`ft_putchar_fd`](ft_putchar_fd.c)		- output a character to given file.
* [`ft_putstr_fd`](ft_putstr_fd.c)		- output string to given file.
* [`ft_putendl_fd`](ft_putendl_fd.c)		- output string to given file with newline.
* [`ft_putnbr_fd`](ft_putnbr_fd.c)		- output integer to given file.
* [`ft_itoa`](ft_itoa.c)					- convert integer to ASCII string.
* [`ft_substr`](ft_substr.c)				- extract substring from string.
* [`ft_strtrim`](ft_strtrim.c)			- trim beginning and end of string with the specified characters.
* [`ft_strjoin`](ft_strjoin.c)			- concatenate two strings into a new string (with malloc).
* [`ft_split`](ft_split.c)				- split string, with specified character as delimiter, into an array of strings.
* [`ft_strmapi`](ft_strmapi.c)			- create new string from modifying string with specified function.

### Linked list functions

* [`ft_lstnew`](ft_lstnew.c)				- create new list.
* [`ft_lstsize`](ft_lstsize.c)			- count elements of a list.
* [`ft_lstlast`](ft_lstlast.c)			- find last element of list.
* [`ft_lstadd_back`](ft_lstadd_back.c)	- add new element at end of list.
* [`ft_lstadd_front`](ft_lstadd_front.c)	- add new element at beginning of list.
* [`ft_lstdelone`](ft_lstdelone.c)		- delete element from list.
* [`ft_lstclear`](ft_lstclear.c)			- delete sequence of elements of list from a starting point.
* [`ft_lstiter`](ft_lstiter.c)			- apply function to content of all list's elements.
* [`ft_lstmap`](ft_lstmap.c)				- apply function to content of all list's elements into new list.

### How do I use the library?

==> Clone this repo and cd into it, make sure it's called `42_Libft`:
		
		git clone https://github.com/aoumad/42_Libft
		cd 42_Libft/
   		make
