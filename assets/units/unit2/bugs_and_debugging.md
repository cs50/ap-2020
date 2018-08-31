## Bugs and Debugging

Bugs. Ugh. Nobody likes them but every programmer will surely encounter them, regardless of how much experience he or she has. A bug is an error in our code, logical or otherwise, such that the behavior is not quite what we expect, whether it be that we allow inputs from users that cause our program to fail, that our program suffers a segmentation fault, or that our program crashes every time we run it. In this section, we explore techniques for rooting out bugs in our programs using certain tools, in particular `eprintf()`, a CS50 library function; `help50`, a command-line tool that helps us understand messages from clang and other tools; and `debug50`, a graphical debugger built upon a popular command-line debugger called gdb.

- ### Lecture (Part 0)
  - [Watch on Youtube](https://www.youtube.com/embed/IJNPHorTqQs?start=2601&end=3268)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/2?t=0h43m21s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/2/lecture2-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/2/lecture2.html#c-continued)

- ### Lecture (Part 1)
  - [Watch on Youtube](https://www.youtube.com/embed/IJNPHorTqQs?start=322&end=451)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/2?t=0h5m22s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/2/lecture2-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/2/lecture2.html#printing-debugging)

- ### Notes
  - [Bugs and Debugging]({{"/assets/pdfs/unit2/bugs_and_debugging.pdf" | relative_url }})

- ### Thought Questions
  - `debug50` is noticeably more complex than simply writing printf statements in our code. Why should we bother using it? What advantages and/or disadvantages exist there?
  - What types of bugs/logical errors seem particularly easy to make?
  - What other kinds of bugs are there besides logical bugs? (Bugs where your program works, but doesn't have the desired effect?)
  - What types of bugs have you encountered in terms of compiler messages you don't understand? 

- ### Problems
  - [Crack](https://docs.cs50.net/2018/ap/problems/crack/crack.html)
  - [Vigenére](https://docs.cs50.net/2018/ap/problems/vigenere/vigenere.html)