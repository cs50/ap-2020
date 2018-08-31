## Functions

Functions are an amazing tool that we can use to organize, simplify, and reuse the code that we write. We organize our code by pulling everything out of `main`, grouping code into more logical chunks. We simplify our code because smaller pieces of code are easier to write and, perhaps increasingly importantly, easier to debug. Wouldn't you much rather debug something that's breaking that consists only of 10 lines of code, rather than 100 or 1000? We can reuse our code by writing a function once and then directing our other programs to use the function that we wrote a single time. In fact, every time you use the CS50 Library that's what you do. We wrote those functions once, in 2009, and now they can be reused. We don't have to copy the lines of code that comprise things like `get_int();` we can just rely on the fact that they once were written and now exist in a file. In this section, we discuss using functions -- declaring, defining, and calling them -- and how to make use of passing information back and forth between functions by way of `return` statements.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/EApk15pCIEA?start=1922&end=4591)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/1?t=32m02s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/1/lecture1-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/1/lecture1.html#functions)

- ### Short
  - [Functions](https://www.youtube.com/embed/n1glFqt3g38)
  - [Variables and Scope](https://www.youtube.com/embed/GiFbdVGjF9I)

- ### Notes
  - [Functions]({{"/assets/pdfs/unit2/functions.pdf" | relative_url }})

- ### Thought Questions
  - Are functions necessary? Are functions optimal?
  - What are some of the conveniences provided by functions? What are some of the inconveniences?
  - What are some of the conveniences of passing copies of variables as arguments to functions? Would it be better to pass the actual variable, or worse?
  - What are some problems with local and global variable scope, an implication of functions?
  - If functions were not something we were able to work with in our programs, how might that change your coding strategy? More importantly, how might it impact your debugging strategy?
