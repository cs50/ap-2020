## Compiling

For a few weeks now, we've dabbled in the process of writing simple source code and simple programs, and have brought those programs to life by way of typing `make`. But what, exactly, does  `make` do? How does the arcane syntax of C get translated to the 0s and 1s that a computer understands? In the videos and resources presented in this section, David looks behind the curtain of `make` to the underlying compiler, `clang`, and demonstrates just how useful it is to have a program like `make` to abstract away some of the details of how to create that mashup of 0s and 1s, possibly linking together your code with the code of others.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/EApk15pCIEA?start=905&end=1029)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/1?t=15m5s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/1/lecture1-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/1/lecture1.html#compiling)

- ### Short
  - [Compilers (Rob)](https://www.youtube.com/embed/CSZLNYF4Klo)

- ### Notes
  - [Compiling]({{"/assets/pdfs/unit2/compiling.pdf" | relative_url }})

- ### Supplementary Resources
  - Ben Eater on [Comparing C to Machine Language](https://www.youtube.com/embed/yOyaJXpAYZQ)

- ### Thought Questions
  - If we have to go through all the trouble of this compilation process, why do we write in higher level languages like C?
  - Why might people choose to write in assembly?
  - Did you think that C's toolkit was already pretty limited? What do you think about the size of that toolkit now that you know how limited the number of instructions there are in assembly language is?
  - What are the advantages and disadvantages of writing in higher or lower level languages?

- ### Problems
  - [Me, Myself, and UI](https://docs.cs50.net/2018/ap/problems/ui/ui.html)
  - [Reverse Engineer](https://docs.cs50.net/2018/ap/problems/reverse/reverse.html)
