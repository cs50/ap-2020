## Abstraction and API

Abstraction is a manner in which a person interacts with a program or system without directly working with more complex details "under the hood" or in a "black box", so to speak. Complex details that may not be of interest are abstracted away so that the programmer works with only what is necessary to him. Abstraction is a key part of computer science and even in life in general. Earlier in the curriculum, students have seen that, although perhaps not of the highest level, C is a high level language, with machine/assembly code a level below, and binary code even further below. Such lower level languages are abstracted away so that the user can program in C without necessarily needing to know what goes on under the hood in machine code and binary. Similarly, APIs (Application Program Interfaces) are a level of abstraction used so that others may use function calls without needing to know what exactly happens when the function is called.

In this section, we'll go over the idea of abstraction in the context of the CS50 library function `get_string();`, our own functions, strings in C, and the Google Maps API. By building upon preexisting creations in the computer science community, we can avoid "reinventing the wheel" and instead focus on innovating above and beyond what we have today.

- ### Lecture (Part 0)
  - [Watch on Youtube](https://www.youtube.com/embed/EApk15pCIEA?start=1922&end=2279)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/1?t=0h32m2s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/1/lecture1-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/1/lecture1.html#functions)

- ### Lecture (Part 1)
  - [Watch on Youtube](https://www.youtube.com/embed/EApk15pCIEA?start=4154&end=4591)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/1?t=1h9m14s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/1/lecture1-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/1/lecture1.html#functions)

- ### Lecture (Part 2)
  - [Watch on Youtube](https://www.youtube.com/embed/IJNPHorTqQs?start=3598&end=4787)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/2?t=0h59m58s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/2/lecture2-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/2/lecture2.html#strings-arrays)

- ### Lecture (Part 3)
  - [Watch on Youtube](https://www.youtube.com/embed/4qQW1uSoxRg?start=5560&end=6049)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/11?t=1h32m40s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/11/lecture11-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/11/lecture11.html#ajax)

- ### Lecture (Part 4)
  - [Watch on Youtube](https://www.youtube.com/embed/6V1sr0XV_Ng)

- ### Supplementary Resources
  - Abstraction:
    - Java Papers on [Java Abstraction](https://javapapers.com/core-java/java-abstraction/)
    - Stack Overflow on [Abstraction](https://stackoverflow.com/questions/7028242/what-is-abstraction)
  - APIs:
    - Brian Proffitt on [What APIs Are and Why They're Important](https://readwrite.com/2013/09/19/api-defined/)
    - Jenn Chen on [What is an API and Why Does It Matter?](https://sproutsocial.com/insights/what-is-an-api/)

- ### Thought Questions
  - Why do we use abstractions and why are they necessary?
  - What are some real world level of abstractions?
  - What is the highest level of abstraction that we can think of?
    - (One example might be a website that creates a website for you - no programming is involved for the user.)
  - Can you think of a downfall of using abstractions?
  - When would it be better to use a "lower" level language, such as C, rather than a "higher" level language, such as Python?