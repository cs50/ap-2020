## File I/O

Though nearly every program we've written to date has been over without a trace as soon as its final line has been executed, C is not limited to only programs that do this. Indeed, C has the capability of file I/O as a means of storing persistent data that exists after our programs have finished running and to read information from a file during the course of the program's execution. In this section, you are introduced to some of the basic file I/O functions they have at their disposal through `stdio.h`, and are guided through the process of writing some powerful I/O programs, including replicating several Linux commands they may have been using throughout the course of CS50 AP.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/eZQBx8YJ6Zs?start=285&end=597)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/5?t=0h4m45s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/5/lecture5-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/5/lecture5.html#structs)

- ### Shorts
  - [File Pointers](https://www.youtube.com/embed/bOF-SpEAYgk)
  - [File I/O (Jason)](https://www.youtube.com/embed/KwvObCA04dU)

- ### Notes
  - [File I/O]({{"/assets/pdfs/unit4/file_io.pdf" | relative_url }})

- ### Thought Questions
  - How do we "read from" and "write to" files? What are these functions called? (Be sure to consult [CS50 Reference](https://reference.cs50.net/stdio) for additional information on how to correctly use them.) Consider drawing a diagram mapping the relationship between "infiles" and "outfiles."
  - Whenever we open a file, what must we remember to do after we are done working with it? Why is this important?
  - What information do you think is bound up in the FILE data type?
  - How does the way we interact with a file vary by its type? For instance, what do we do with a Word document that we wouldn't do with a JPEG.

- ### Problems
  - [Finder](https://docs.cs50.net/2018/ap/problems/finder/finder.html)
  - [Music](https://docs.cs50.net/2018/ap/problems/music/music.html)