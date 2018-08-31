
## Arrays and Strings

Arrays are a fundamental data structure, and they are extremely useful. We use arrays to hold values of the same type at contiguous memory locations. In particular, the use of arrays allows us to create "groups" or "clusters" of variables without needing to give a unique variable name to each, but still allowing us to individually index into the elements of the array. If you haven't started counting from zero yet, now is the time, because in C, arrays are zero-indexed which means the first element of a k-element array is located at array index `0` and the last element is located at array index `k-1`. 

Strings are a special case of arrays -- in C, a string is an array of characters (more modern programming languages have strings as their own data type related to but distinct from characters). Later in the course, we'll examine this special case a bit further, but for now, it suffices to group and discuss arrays and strings together. In this section, you will learn how to create and manipulate arrays.

- ### Lecture 
  - [Watch on Youtube](https://www.youtube.com/embed/IJNPHorTqQs?start=3597&end=5377)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/2?t=59m57s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/2/lecture2-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/2/lecture2.html#strings-arrays)

- ### Short
  - [Arrays](https://www.youtube.com/embed/K1yC1xshF40)
  - [Arrays (Rob)](https://www.youtube.com/embed/7mOJN1c1JEo)
  - [Strings (Chris)](https://www.youtube.com/embed/z3j-gK1u6Kg)

- ### Notes
  - [Arrays and Strings]({{"/assets/pdfs/unit2/arrays_and_strings.pdf" | relative_url }})

- ### Thought Questions
  - Is there ever a situation where it might be better to have 2, 3, or n separate variables instead of having a 2-, 3-, or n-element array?
  - Because we have to specify the size of an array before we start using it, how might we respond to needing extra elements?
  - What if we need to insert an element between two other elements we've already defined in our array? 
  - If we don't otherwise know the number of elements in an array, how might we be able to calculate it? What other information do we need to know in order to do so?

- ### Problem
  - Initials
    - [less](http://docs.cs50.net/2018/ap/problems/initials/less/initials.html)
    - [more](http://docs.cs50.net/2018/ap/problems/initials/more/initials.html)
