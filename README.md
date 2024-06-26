<h1 align="center">
<a href="https://github.com/f-corvaro/LIBFT/tree/main">
	<img src="https://github.com/f-corvaro/LIBFT/blob/main/.extra/libft.png" alt="Libft">
  </a>
</h1>

<p align="center">
	<b><i>"A solid foundation for system programming in C."</i></b><br>
</p>
<p align="center" style="text-decoration: none;">
    <a href="https://github.com/f-corvaro/LIBFT/blob/main/.extra/en.subject.pdf"><img alt="subject" src="https://img.shields.io/badge/subject-libft-yellow" /></a>
    <a href="https://github.com/f-corvaro/LIBFT"><img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/f-corvaro/LIBFT?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/LIBFT"><img alt="Code language count" src="https://img.shields.io/github/languages/count/f-corvaro/LIBFT?color=yellow" /></a>
    <a href="https://github.com/f-corvaro/LIBFT"><img alt="GitHub top language" src="https://img.shields.io/github/languages/top/f-corvaro/LIBFT?color=blueviolet" /></a>
    <a href="https://github.com/f-corvaro/LIBFT"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/f-corvaro/LIBFT?color=yellow" /></a>
</p>

<h3 align="center">Index</h3>

<p align="center">
  <a href="#libft">LIBFT</a><br>
  <a href="#index">Index</a><br>
  <a href="#0---about">0 - About</a><br>
  <a href="#1---folder-structure">1 - Folder Structure</a><br>
  <a href="#2---whats-in-it">2 - What's in it?</a><br>
  <a href="#3---functions-index">3 - Functions Index</a><br>
  <a href="#4---running-tests">4 - Running Tests</a><br>
  <a href="#5---evaluation">5 - Evaluation</a><br>
  <a href="#51---tester">5.1 - Tester</a><br>
  <a href="#52---correction-sheet">5.2 - Correction Sheet</a><br>
  <a href="#53---my-moulinette-results">5.3 - My Moulinette Results</a><br>
  <a href="#6---special-thanks">6 - Special Thanks</a><br>
  <a href="#support-me">Support Me</a><br>
  <a href="#skills-developed">Skills developed</a><br>
  <a href="#author">Author</a>
</p>

<br>

## 0 - About
<p align="justify">
The journey in 42 Schools starts from here, this is the first project you face it. The purpose of the project is to re-code some libc functions and other common utility functions and include in an archive library, that it will be very helpful for the future projects. In this project there is norminette and Moulinette, so you will be checked from peers and Moulinette.

You can find my complete static C library [here](https://github.com/f-corvaro/my_static_C_library).

</p>
<br>

## 1 - Folder Structure

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


## 2 - What's in it?

There are 4 sections:

1. **Libc Functions:** <p align="justify"> Some of the standard C functions;</p>
2. **Additional Functions:** <p align="justify">Functions that will be useful for other projects;</p>
3. **Bonus Functions:** <p align="justify">Functions that will be useful for linked list manipulation;</p>
4. **Other:** <p align="justify"> makefile and libft.h.</p>

After the compiling, you will have also .o files and the libft.a file.

<br>

## 3 - Functions Index

<p align="center">


| Libc functions  | Additional functions | Bonus part |  other |
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

## 4 - Running Tests

<p align="justify">

To build the library use the ```make``` command. To get an overview of all make commands run:

```bash
make info
```

 <a href="https://github.com/f-corvaro/LIBFT"><img align="center" alt="running test" width="650" src="https://github.com/f-corvaro/LIBFT/blob/main/.extra/make.gif">

</p>
<br>

## 5 - Evaluation

### 5.1 - Tester

<p align="justify"> To test my project before the Moulinette and peers corrections, use the: </p>

[Supreme Tester](https://github.com/FranFrau/Supreme-Tester-Libft) of [@FranFrau]( https://github.com/FranFrau )

### 5.2 - Correction Sheet

<a href="https://github.com/f-corvaro/LIBFT"><img width="650" src="https://github.com/f-corvaro/LIBFT/blob/main/.extra/libft_cs.png">

### 5.3 - My Moulinette Results

 <a href="https://projects.intra.42.fr/projects/42cursus-libft/projects_users/3049229">
  <img align="center" img src="https://github.com/f-corvaro/LIBFT/blob/main/.extra/moulinette_libft.png">
 </a>
</p>
<br>

## 6 - Special Thanks

[@dieremy]( https://github.com/dieremy ) <p align="justify">  helped me to test and resolve leaks in my functions. Furthermore, he introduced to me this project: explaining to me some functions and some theory about it. </p>
[@MirkokriM]( https://github.com/MirkokriM ) <p align="justify"> for the gif idea.</p>
<br>

## Support Me

<p align="justify">
Remember to ⭐ the repository.
If you want to support me:</p>

<p align="center">
<a href="https://ko-fi.com/fcorvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-ko-fi.svg"><alt=""></a>
<a href="https://github.com/sponsors/f-corvaro"><img width="180" img align="center" src="https://github.com/f-corvaro/42.common_core/blob/main/.extra/support-me-github.svg"><alt=""></a>

<br>

## Skills developed

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,c,vim,vscode" />
  </a>
</p><br>

## Author

<p align="center"><a href="https://profile.intra.42.fr/users/fcorvaro"><img style="height:auto;" src="https://avatars.githubusercontent.com/u/102758065?v=4" width="100" height="100"alt=""></a>
<p align="center">
<a href="mailto:fcorvaro@student.42roma.it"><kbd>Email</kbd><alt=""></a>
<a href="https://github.com/f-corvaro"><kbd>Github</kbd><alt=""></a>
<a href="https://www.linkedin.com/in/f-corvaro/"><kbd>Linkedin</kbd><alt=""></a>
<a href="https://42born2code.slack.com/team/U050L8XAFLK"><kbd>Slack</kbd><alt=""></a>

<hr/>
