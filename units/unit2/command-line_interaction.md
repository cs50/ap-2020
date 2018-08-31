## Command-Line Interaction

In this section, we'll talk about how to interact with your computer via the terminal, a command line interface. The first lecture will show you how to use text-based commands to compile and run your program as well as a few more useful commands.

You can also enable your programs to use the command line. Up to this point in the course, if your programs have been collecting data or input from the user, it's likely done so by using the `get_` functions that are part of the CS50 Library. To that end, you can only collect information from the user as the program is running. Wouldn't it be nice to collect input from the user _before_ the program starts running, perhaps allowing the program to take different paths through the code depending on what the user provided at the command line? C has the capability to accept and process command-line arguments, and in this module we discuss what changes you need to make to your program(s) in order to work with them.

- ### Lecture (Part 0)
  - [Watch on Youtube](https://www.youtube.com/embed/EApk15pCIEA?start=1262&end=1907)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/1?t=21m2s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/1/lecture1-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/1/lecture1.html#compiling)

- ### Lecture (Part 1)
  - [Watch on Youtube](https://www.youtube.com/embed/IJNPHorTqQs?start=5378&end=57157)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/2?t=1h29m38s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/2/lecture2-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/2/lecture2.html#c-continued)

- ### Shorts
  - [Command Line](https://www.youtube.com/embed/BnJ013X02b8)
  - [Command-Line Arguments](https://www.youtube.com/embed/AI6Ccfno6Pk)
  - [Command-Line Interaction (Chris)](https://www.youtube.com/embed/X8PmYwnbLKM)

- ### Notes
  - [Command-Line Interaction]({{"/assets/pdfs/unit2/command-line_interaction.pdf" | relative_url }})

- ### Thought Questions
  - What is the relationship between argc and argv? Specifically, what does argc tell us about how far we can iterate through argv?
  - What is the data type of argv?
  - What is the data type of the elements of argv?
  - What does that mean if the user inputs, say, "18" or "5.22" at the command line?
  - Why might we want to collect information at the command line instead of after the program has started running?to variables?
