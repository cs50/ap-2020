## Merge Sort

The other sorting algorithms we've covered in the class -- selection sort, insertion sort, and bubble sort -- all suffer from the same general limitations and thus suffer the same, generally slow, worst-case runtime of _O(n²)_. Merge sort, though, behaves in a fundamentally different manner, leveraging recursion to "pass the buck" of sorting but also accomplishing something drastically superior -- _O(n log n)_ runtime.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/U9o49qwa6hk?start=4355&end=5382)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/3?t=1h12m35s)
  - [Download Lecture](https://cdn.cs50.net/2016/fall/lectures/3/week3-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/3/lecture3.html#merge-sort)

- ### Shorts
  - [Merge Sort](https://www.youtube.com/embed/Ns7tGNbtvV4)
  - [Merge Sort (Rob)](https://www.youtube.com/embed/EeQ8pwjQxTM)
  
- ### Notes
  - [Merge Sort]({{"/assets/pdfs/unit4/merge_sort.pdf" | relative_url }})

- ### Supplementary Resources
  - Khan Academy on [Merge Sort](https://www.khanacademy.org/computing/computer-science/algorithms/merge-sort/a/divide-and-conquer-algorithms).

- ### Thought Questions
  - What are the most significant tradeoffs associated with merge sort that we don't have to deal with in any of the _n²_ sorts we've seen thus far?
  - In what situations is merge sort the best option for sorting?
  - How would you compare and contrast the sorting algorithms we've already looked at? Take care to consider their respective time and space complexities.
