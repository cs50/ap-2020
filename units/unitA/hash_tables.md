## Hash Tables

Hash tables are a data structure in which nodes are sorted into different "buckets" by a hash function, and, in the ultimate combination of data structures, chained together in linked lists. Hash tables can thus store large amounts of data and still allow for quick lookup, while requiring significantly less memory than a trie. The hash function must give the same value for a key every time the key is passed (determinism), but it should not give each key its own unique hash value. Keys are then sorted into buckets according to hash value. Thus, when looking something up, we can focus on the bucket that that item would have been placed in had it been inserted. In this section, we will discuss the basics of hash tables and hash functions.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/eZQBx8YJ6Zs?start=5682&end=6001)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/5?t=1h34m42s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/5/lecture5-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/5/lecture5.html#data-structures)

- ### Shorts
  - [Hash Tables](https://www.youtube.com/embed/nvzVHwrrub0)
  - [Hash Tables (Lauren)](https://www.youtube.com/embed/h2d9b_nEzoA)

- ### Supplementary Resources
  - Brian Barto on [Hash Crash: The Basics of Hash Tables](https://medium.com/@bartobri/hash-crash-the-basics-of-hash-tables-bef82a8ea550)
  - Bilal Ahmad Khan on [Hash Tables](https://medium.com/@bilalak90/hash-tables-c84d1b7aeb96)
  - Prashanth Irudayaraj on [Distributed Hash Tables](https://blog.keep.network/distributed-hash-tables-49721094403d)
  - Patrick Woodhead on [Hash functions explained with Emojis](https://medium.com/swlh/this-simple-yet-powerful-invention-is-changing-the-world-d04688c25f13)

- ### Thought Questions
  - What real world situation is a hash table useful for?
  - Hash tables and tries can often accomplish similar tasks. What are the benefits of using each?

- ### Problem
  - [Mispellings](https://docs.cs50.net/2018/ap/problems/mispellings/mispellings.html)
  