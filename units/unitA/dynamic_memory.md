## Dynamic Memory

Dynamic memory allocation, through the use of functions like `malloc()` and `realloc()`, is a powerful tool that allows programmers to manipulate memory and variable storage. In this section, we go over how to use `malloc()`, and its counterpart `free()`, in relation to using pointers, as well as some good practices when allocating memory. Additionally, a few common mistakes are explained, many of which can be found using Valgrind.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/Zn8OJMYT-gc?start=3083&end=3572)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/4?t=0h51m23s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/4/lecture4-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/4/lecture4.html#memory)

- ### Short
  - [Dynamic Memory Allocation](https://www.youtube.com/embed/9uhSYDY4sxA)

- ### Supplementary Resources
  - Man pages on [`malloc()`, `realloc()`, `calloc()`, and `free()`](http://linux.die.net/man/3/malloc)
  - Tutorials Point on [C library function - malloc](https://www.tutorialspoint.com/c_standard_library/c_function_malloc.htm)
  - Microsoft Developer Network on [malloc](https://msdn.microsoft.com/en-us/library/6ewkz86d.aspx)

- ### Thought Questions
  - What does dynamic memory allocation allow us to do?
  - How can we translate `malloc()` and `free()` into pseudocode?
  - Should we always have an equal number of calls to `malloc()` and `free()`?