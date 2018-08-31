## Valgrind

Valgrind is a powerful tool that can help us track down memory leaks in our programs. Run in the terminal, Valgrind tracks memory reads and writes in programs, as well as making sure that `free()` is appropriately applied to any `malloc()`, `calloc()`, or `realloc()` call. This section will go over the basics of how to use Valgrind. For the rest of the course, students will be expected to use Valgrind to track down memory leaks in their code.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/eZQBx8YJ6Zs?start=2265&end=2653)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/5?t=0h37m45s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/5/lecture5-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/5/lecture5.html#debugging)

- ### Short
  - [Valgrind (Nate)](https://www.youtube.com/embed/fvTsFjDuag8)

- ### Supplementary Resources
  - Valgrind.org on [The Valgrind Quick Start Guide](http://valgrind.org/docs/manual/quick-start.html)
  - Katrik Anand on [Developer toolkit -- Using valgrind](https://medium.com/@exqu17/developer-toolkit-using-valgrind-13e114444838)

- ### Thought Questions
  - Why is it important to track down memory leaks? (Hint: Think about why it would be bad for memory to be "definitely lost.")
  - How does using Valgrind help us debug our code?
  - What are some strategies for breaking down and understanding long, complicated error messages that contain important information?

- ### Problems
  - [Leaky](https://docs.cs50.net/2018/ap/problems/leaky/leaky.html)