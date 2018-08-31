## Linked Lists

A linked list is a dynamically-resizable alternative to an array, made of nodes that contain pointers to other nodes. The main advantage of a linked list is its dynamism: that is to say it can be used to store data even if the programmer does not know how much data must be stored. This dynamism, however, comes at the cost of (a) memory, as extra space is required to store all the pointers, as well as (b) time, as binary search is no longer a possibility without random access. Linked lists are an alternative to arrays when implementing stacks and queues, earlier sections in this chapter. In this section, we will discuss singly linked lists in detail, as well as briefly touch on doubly linked lists, go over the trade-offs associated with using this data structure, as well as revisit stacks and queues to see how they can be implemented with a linked list.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/eZQBx8YJ6Zs?start=3004&end=4498)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/5?t=0h50m4s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/5/lecture5-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/5/lecture5.html#data-structures)

- ### Shorts
  - [Singly-Linked Lists](https://www.youtube.com/embed/zQI3FyWm144)
  - [Doubly-Linked Lists](https://www.youtube.com/embed/FHMPswJDCvU)
  - [Singly-Linked Lists (Jackson)](https://www.youtube.com/embed/5nsKtQuT6E8)

- ### Supplementary Resources
  - Pankaj Rai on [Know your data structure - Linked List](https://medium.com/@pankaj.rai16/know-your-data-structure-linked-list-4b00fcfbda93)
  - David Pynes on [Linked lists: introducing data structures](https://towardsdatascience.com/linked-lists-why-what-and-how-f96b04790ac4)
  - Michael Olorunnisola on [How Linked Lists Work](https://medium.freecodecamp.org/a-gentle-introduction-to-data-structures-how-linked-lists-work-5adc793897dd)

- ### Thought Questions
  - What are some trade-offs between using an array, a singly linked list, or a doubly linked list?
  - How would one implement a stack and a queue using linked lists?
  - When would one want to implement a stack and a queue using a linked list?

- ### Problem
  - [Decisions](https://docs.cs50.net/2018/ap/problems/decisions/decisions.html)
  