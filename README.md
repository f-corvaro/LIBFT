<h1 align="center">
<a href="https://github.com/f-corvaro/LIBFT/tree/main">
	<img src="https://github.com/f-corvaro/LIBFT/blob/main/.extra/libft.png" alt="Libft">
  </a>
</h1>

<p align="center">
	<b><i>"A solid foundation for system programming in C."</i></b><br>
</p>
<p align="center" style="text-decoration: none;">
    <a href="https://github.com/f-corvaro/LIBFT"><img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/f-corvaro/LIBFT?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/LIBFT"><img alt="Code language count" src="https://img.shields.io/github/languages/count/f-corvaro/LIBFT?color=yellow" /></a>
    <a href="https://github.com/f-corvaro/LIBFT"><img alt="GitHub top language" src="https://img.shields.io/github/languages/top/f-corvaro/LIBFT?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/LIBFT"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/f-corvaro/LIBFT?color=yellow" /></a>
</p>

<h3 align="center">Index</h3>
<p align="center">
 <a href="#introduction">Introduction</a><br>
 <a href="#folder-structure">Folder Structure</a><br>
 <a href="#contents-overview">Contents Overview</a><br>
 <a href="#building-the-library">Building the Library</a><br>
 &nbsp;&nbsp;<a href="#visual-guide-to-running-tests">Visual Guide to Running Tests</a><br>
 <a href="#evaluation-process">Evaluation Process</a><br>
 &nbsp;&nbsp;<a href="#pre-submission-testing">Pre-Submission Testing</a><br>
 &nbsp;&nbsp;<a href="#moulinette-feedback">Moulinette Feedback</a><br>
 <a href="#acknowledgments">Acknowledgments</a><br>
 <a href="#developed-skills">Developed Skills</a><br>
 <a href="#support-and-contributions">Support and Contributions</a><br>
 <a href="#author">Author</a><br>
</p>
<br>

## Introduction

<p align="justify">

The journey at 42 Schools begins with this foundational project. It challenges students to reimplement certain standard C library functions, along with other utility functions, and compile them into a static library. This serves as a crucial resource for future projects. Adherence to the Norminette coding standards and passing the Moulinette tests are key aspects of this project, ensuring that both peers and automated systems will evaluate your work.

Explore my complete static C library [here](https://github.com/f-corvaro/my_static_C_library).

This project demands a solid understanding of the C programming language, including data types, loops, conditionals, functions, and memory management. Students must also develop proficiency in debugging, testing, and documentation to ensure their code is reliable and understandable. Mastery of these skills is essential for tackling the complexities of software development and contributes significantly to the success in the Libft project and beyond.

</p>
<br>

## Folder Structure

```
.
├── 00-libft
│   ├── libft
│   │   ├── ft_atoi.c
│   │   ├── ft_bzero.c
│   │   ├── ft_calloc.c
│   │   ├── ft_isalnum.c
│   │   ├── ft_isalpha.c
│   │   ├── ft_isascii.c
│   │   ├── ft_isdigit.c
│   │   ├── ft_isprint.c
│   │   ├── ft_itoa.c
│   │   ├── ft_lstadd_back.c
│   │   ├── ft_lstadd_front.c
│   │   ├── ft_lstclear.c
│   │   ├── ft_lstdelone.c
│   │   ├── ft_lstiter.c
│   │   ├── ft_lstlast.c
│   │   ├── ft_lstmap.c
│   │   ├── ft_lstnew.c
│   │   ├── ft_lstsize.c
│   │   ├── ft_memchr.c
│   │   ├── ft_memcmp.c
│   │   ├── ft_memcpy.c
│   │   ├── ft_memmove.c
│   │   ├── ft_memset.c
│   │   ├── ft_putchar_fd.c
│   │   ├── ft_putendl_fd.c
│   │   ├── ft_putnbr_fd.c
│   │   ├── ft_putstr_fd.c
│   │   ├── ft_split.c
│   │   ├── ft_strchr.c
│   │   ├── ft_strdup.c
│   │   ├── ft_striteri.c
│   │   ├── ft_strjoin.c
│   │   ├── ft_strlcat.c
│   │   ├── ft_strlcpy.c
│   │   ├── ft_strlen.c
│   │   ├── ft_strmapi.c
│   │   ├── ft_strncmp.c
│   │   ├── ft_strnstr.c
│   │   ├── ft_strrchr.c
│   │   ├── ft_strtrim.c
│   │   ├── ft_substr.c
│   │   ├── ft_tolower.c
│   │   ├── ft_toupper.c
│   │   ├── libft.h
│   │   └── Makefile
```

## Contents Overview

<p align="justify">

This section is divided into four categories:

1. **Libc Functions:** Standard C library functions reimplemented.
2. **Additional Functions:** Useful functions for future projects.
3. **Bonus Functions:** Functions specifically designed for linked list manipulation.
4. **Other Components:** Includes the Makefile and libft.h header file.

Compiling the library generates object `.o` files and the static library file `libft.a`.

</p>

<p align="center">

| Libc Functions  | Additional Functions | Bonus Functions |  other Components |
| ------------- | ------------- | ------------- |  ------------- |
| [ft_atoi.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_atoi.c)| [ft_itoa.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_itoa.c)  | [ft_lstadd_back.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstadd_back.c)  | [libft.h](https://github.com/f-corvaro/LIBFT/blob/main/libft/libft.h) |
| [ft_bzero.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_bzero.c) | [ft_putchar_fd.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_putchar_fd.c)  | [ft_lstadd_front.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstadd_front.c)  | [makefile](https://github.com/f-corvaro/LIBFT/blob/main/libft/Makefile)  |
| [ft_calloc.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_calloc.c)  | [ft_putendl_fd.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_putendl_fd.c)  | [ft_lstclear.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstclear.c)  |
| [ft_isalnum.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_isalnum.c) | [ft_putnbr_fd.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_putnbr_fd.c)  | [ft_lstdelone.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstdelone.c)  |
| [ft_isalpha.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_isalpha.c)  | [ft_putstr_fd.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_putstr_fd.c)  | [ft_lstiter.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstiter.c)  |
| [ft_isascii.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_isascii.c)  | [ft_split.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_split.c)  | [ft_lstlast.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstlast.c)  |
| [ft_isdigit.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_isdigit.c)  | [ft_striteri.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_striteri.c)  | [ft_lstmap.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstmap.c)  |
| [ft_isprint.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_isprint.c)  | [ft_strjoin.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strjoin.c)  | [ft_lstnew.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstnew.c)  |
| [ft_memchr.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_memchr.c)  | [ft_strmapi.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strmapi.c)  | [ft_lstsize.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_lstsize.c)  |
| [ft_memcmp.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_memcmp.c)  | [ft_strtrim.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strtrim.c)  |
| [ft_memcpy.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_memcpy.c) | [ft_substr.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_substr.c)  |
| [ft_memmove.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_memmove.c)  |
| [ft_memset.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_memset.c) |
| [ft_strchr.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strchr.c)  |
| [ft_strdup.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strdup.c)  |
| [ft_strlcat.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strlcat.c)  |
| [ft_strlcpy.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strlcpy.c)  |
| [ft_strlen.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strlen.c)  |
| [ft_strncmp.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strncmp.c)  |
| [ft_strnstr.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strnstr.c)  |
| [ft_strrchr.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_strrchr.c)  |
| [ft_tolower.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_tolower.c)  |
| [ft_toupper.c](https://github.com/f-corvaro/LIBFT/blob/main/libft/ft_toupper.c)  |

</p>
<br>

## Building the Library

<p align="justify">

To compile the library, utilize the following command:

```bash
make
```

For a detailed list of commands available within the `make` utility, execute:

```bash
make info
```

### Visual Guide to Running Tests

<p align="center">
 <a href="https://github.com/f-corvaro/LIBFT">
  <img width="650" src="https://github.com/f-corvaro/LIBFT/blob/main/.extra/make.gif">
 </a>
</p>
<br>

## Evaluation Process

### Pre-Submission Testing

<p align="justify"> 

To ensure your project is ready for submission and peer reviews, it's recommended to test it using the [Supreme Tester](https://github.com/FranFrau/Supreme-Tester-Libft) provided by [@FranFrau](https://github.com/FranFrau).

</p>

### Moulinette Feedback

<p align="justify"> 

After submission, the Moulinette (an automated grading system) will evaluate your project. You can view the results and feedback here:

</p>

 <a href="https://projects.intra.42.fr/projects/42cursus-libft/projects_users/3049229">
  <img align="center" img src="https://github.com/f-corvaro/LIBFT/blob/main/.extra/moulinette_libft.png">
 </a>
</p>
<br>

## Acknowledgments

<p align="justify">

- **[@dieremy](https://github.com/dieremy)**: Helped with testing and resolving leaks in functions. Additionally, provided an introduction to the project, explaining various functions and theoretical aspects.
- **[@MirkokriM](https://github.com/MirkokriM)**: Inspired the idea for the GIF.

</p>
<br>

## Developed Skills

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,c,vim,vscode" />
  </a>
</p><br>

## Support and Contributions

<p align="center">
If you find this repository helpful, please consider starring it to show your support. Your support is greatly appreciated!</p>

<p align="center">
<a href="https://ko-fi.com/fcorvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-ko-fi.svg"><alt=""></a>
<a href="https://github.com/sponsors/f-corvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-github.svg"><alt=""></a>

<br>

## Author

<p align="center"><a href="https://profile.intra.42.fr/users/fcorvaro"><img style="height:auto;" src="https://avatars.githubusercontent.com/u/102758065?v=4" width="100" height="100"alt=""></a>
<p align="center">
<a href="mailto:fcorvaro@student.42roma.it"><kbd>Email</kbd><alt=""></a>
<a href="https://github.com/f-corvaro"><kbd>Github</kbd><alt=""></a>
<a href="https://www.linkedin.com/in/f-corvaro/"><kbd>Linkedin</kbd><alt=""></a>
<a href="https://42born2code.slack.com/team/U050L8XAFLK"><kbd>Slack</kbd><alt=""></a>

<hr/>
