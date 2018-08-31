## Tries

A trie is a tree-like data structure in which data is stored in association with keys, which are typically strings. Tries are made of nodes, usually consisting of an array of pointers to other nodes and one other field that gives the programmer more information about the node and indicates if that node represents a key. Tries use large amounts of memory, but trade this for constant time _(O(1))_ lookup and insertion. In this section, we will discuss the basics of tries, and see an example for their implementation, in a dictionary.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/eZQBx8YJ6Zs?start=6001&end=6258)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/5?t=1h40m1s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/5/lecture5-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/5/lecture5.html#trees)

- ### Shorts
  - [Tries](https://www.youtube.com/embed/MC-iQHFdEDI)
  - [Tries (Kevin)](https://www.youtube.com/embed/NKr6gWcXkIM)

- ### Supplementary Resources
  - Julia Geist on [The Trie Data Structure (Prefix Tree)](https://medium.freecodecamp.org/trie-prefix-tree-algorithm-ee7ab3fe3413)
  - Joseph Crick on [Practical Data Structures for Frontend Applications: When to Use Tries](https://hackernoon.com/practical-data-structures-for-frontend-applications-when-to-use-tries-5428a565eba4)
  - Vaidehi Joshi on [Trying to Understand Tries](https://medium.com/basecs/trying-to-understand-tries-3ec6bede0014)

- ### Thought Questions
  - Why can we say that tries have constant time lookup and insertion?
  - What real world situations could a trie be useful for besides a dictionary?
  - What are the trade-offs involved in using a trie, and what are situations where one side matters more than the other?

- ### Problem
  - [Autocomplete](https://docs.cs50.net/2018/ap/problems/autocomplete/autocomplete.html)