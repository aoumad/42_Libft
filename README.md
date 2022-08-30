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

Libc functions 				| Bonus Functions
:----------- |
memset		| ft_memalloc		| ft_lstnew
bzero		| ft_memdel		| ft_lstdelon
memcpy		| ft_strnew		| ft_lstdel  
memccpy		| ft_strdel		| ft_lstadd  
memmove		| ft_strclr		| ft_lstiter
memchr		| ft_striter		| ft_lstmap
memcmp		| ft_striteri
strlen		| ft_strmap
strdup		| ft_strmap
strcpy		| ft_strequ	
strncpy		| ft_strnequ
strcat		| ft_strsub		
strlcat		| ft_strjoin	
strchr		| ft_strtrim	
strrchr		| ft_strsplit	
strstr		| ft_itoa		  
strnstr		| ft_putchar	
strcmp		| ft_putstr		
strncmp		| ft_putendl	
atoi		  | ft_putnbr 
isalpha		| ft_putchar_fd
isdigit		| ft_putstr_fd
isalnum		| ft_putendl_fd
isascii		| ft_putnbr_fd
isprint		| ft_isupper  
toupper   	| ft_putnstr
tolower   	| ft_lstaddback

### How do I use the library?

==> Clone this repo and cd into it, make sure it's called `42_Libft`:
		
		git clone https://github.com/aoumad/42_Libft
		cd 42_Libft/
   		make
