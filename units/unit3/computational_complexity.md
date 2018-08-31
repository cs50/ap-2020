## Computational Complexity

The subject of computational complexity (also known as time complexity and/or space complexity) is one of the most math-heavy topics we discuss in CS50 AP, but also perhaps one of the most fundamentally important in the real-world. As we begin to write programs that process larger and larger sets of data, analyzing those data sets systematically, it becomes increasingly important to understand exactly what effect those algorithms have in terms of taxing our computers. How much time do they take to process? How much RAM do they consume? In this section, you will begin to discuss the way in which computer scientists measure this, in particular considering the theoretical worst-case and best-case scenarios when running programs.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/U9o49qwa6hk?start=2716&end=3543)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/3?t=0h45m16s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/3/lecture3-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/3/lecture3.html#running-time)

- ### Shorts
  - [Computational Complexity](https://www.youtube.com/embed/YoZPTyGL2IQ)
  - [Asymptotic Notation (Jackson)](https://www.youtube.com/embed/iOq5kSKqeR4)

- ### Notes
  - [Computational Complexity]({{"/assets/pdfs/unit3/computational_complexity.pdf" | relative_url }})

- ### Thought Questions
  - In what ways can we measure the resources that our programs consume?
  - Is it always better to choose an algorithm that runs in _O(n)_ over one that runs in _O(n²)_? Why or why not?
  - Why do you think that we analyze algorithms from a theoretical standpoint using asymptotic notation, instead of just counting runtime in seconds or the like? 
  - In what ways does this adherence to asymptotic notation (disregarding constants and lower order terms) hinder our ability to speak about algorithms in the real world?
  - How might we use time complexity analysis to our benefit as programmers before we even write any code?
  
- ### Problem
  - [Scramble (Part 1)](http://docs.cs50.net/2018/ap/problems/scramble/1/scramble1.html)