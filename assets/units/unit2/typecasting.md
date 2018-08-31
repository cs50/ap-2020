## Typecasting

Sometimes you create a variable of one data type but actually need to (for one reason or another) use that variable in another context (using an integer as a character, or discarding some precision by using double as a float instead). What to do? One approach is to simply create another variable of the new type with the same exact value, but that seems wasteful. Another option we can take advantage of with C is the ability to cast (temporarily change) one data type into another with the same or less precision (e.g. we can cast a double to a float, but not vice versa), which might be more efficient from a design standpoint. In this section, we briefly examine the mechanism and some use cases for typecasting.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/IJNPHorTqQs?start=4033&end=4265)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/2?t=1h7m13s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/2/lecture2-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/2/lecture2.html#strings-arrays)

- ### Shorts
  - [Typecasting (Jordan)](https://www.youtube.com/embed/4XTSxFSs3kI)

- ### Notes
  - [Typecasting]({{"/assets/pdfs/unit2/typecasting.pdf" | relative_url }})

- ### Thought Questions
  - Why is it perhaps "better" to typecast a variable instead of creating a second variable of the correct type?
  - When might it be preferable to create that second variable instead of typecasting it?
  - How does typecasting relate to how data types are internally defined?

- ### Problem
  - [Caesar](http://docs.cs50.net/2018/ap/problems/caesar/caesar.html)