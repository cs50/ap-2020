## Structures and Encapsulation

At a certain point, the usual suspect data types no longer suffice for the kind of work we need to do. Rather, we need to be able to encapsulate data more broadly, allowing us to group information together, but where all of that information relates to some large entity. For example, students have names (probably represented by strings) and ages (probably represented by integers) and grade-point averages (probably represented by floating-point numbers), but none of those things matters independently--instead, all of these things come together and are part of some larger overall entity: namely, the student. Wouldn't it be nice to be able to "bundle" these things together, perhaps allowing us to abstract away from some of the underlying specifics? In more modern programming languages, we might do this with a so-called object, but in C we have a more basic mechanism for this: the structure.

- ### Lecture (Part 0)
  - [Watch on Youtube](https://www.youtube.com/embed/Zn8OJMYT-gc?start=5996&end=6100)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/4?t=1h39m56s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/4/lecture4-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/4/lecture4.html#images)

- ### Lecture (Part 1)
  - [Watch on Youtube](https://www.youtube.com/embed/eZQBx8YJ6Zs?start=70&end=285)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/5?t=0h1m10s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/5/lecture5-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/5/lecture5.html#structs)

- ### Shorts
  - [Structures](https://www.youtube.com/embed/N5pA7RvvQDg)
  - [Structures (Rob)](https://www.youtube.com/embed/EzRwP7NV0LM)

- ### Notes
  - [Structures and Encapsulation]({{"/assets/pdfs/unit4/structures_and_encapsulation.pdf" | relative_url }})

- ### Thought Questions
  - We've already seen arrays as collections of information. In which ways are structures different?
  - What might the advantage be of having a struct in the first place, from a design perspective?
  - Why do we sometimes term the process of creating a structure as _abstraction_ or _encapsulation_?

- ### Problem
  - [Sudoku](http://docs.cs50.net/2018/ap/problems/sudoku/sudoku.html)

