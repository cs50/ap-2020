## Pointers

Pointers allow us to access addresses in memory, and what is inside of those addresses, instead of just values. In C, all variables passed to a function are passed by reference, or only as copies of their value. Passing pointers instead of values allows us to change multiple variables (see the swap example in Rob's short below) where before we could only return one value. In this section, we will discuss the basics of pointers and their operators (* and &), which will become a key piece of the foundation for the remaining C programs in the course.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/Zn8OJMYT-gc?start=4916&end=5133)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/4?t=1h21m56s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/4/lecture4-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/4/lecture4.html#strings)

- ### Shorts
  - [Pointers](https://www.youtube.com/embed/XISnO2YhnsY)
  - [Pointers (Rob)](https://www.youtube.com/embed/gv6i2CJm57Q)

- ### Supplementary Resources
  - Puneet Sapra on [No more fear of pointers](https://medium.com/the-mighty-programmer/variable-and-pointer-fb637566bfd9)
  - Stanford CS on [Pointer Fun with Binky](https://www.youtube.com/embed/6pmWojisM_E)

- ### Thought Questions
  - What are the advantages of being able to access addresses in memory?
  - What are the dangers of using pointers?
  - If pointers are so great, why do we ever pass by value? 