## Exit Codes

We've already seen return values in the context of functions, and by now it's hopefully apparent that the main purpose of a return value is to communicate a value back to the calling function so that it may use it in some meaningful way. But why, then, does `main()` sometimes `return 0;` or `return 1;`? If `main()` is the function that drives our entire program... to what is it returning? In this very short section, we won't dabble too much in where `main()`'s return values (which are occasionally referred as exit codes, as when `main()` returns the program necessarily ends) go, but we will touch on why and how we might use them as programmers.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/2zPEHYoiyfc?start=6146&end=6397)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2016/fall/lectures/2?t=1h42m26s)
  - [Download Lecture](https://cdn.cs50.net/2016/fall/lectures/2/week2-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2016/fall/notes/2/week2.html#command-line-arguments)

- ### Notes
  - [Exit Codes]({{"/assets/pdfs/unit2/exit_codes.pdf" | relative_url }})

- ### Thought Questions
  - What is the value of exit codes?
  - If we don't specify an exit code value (as likely hasn't happened much), what happens?
  - Given the purpose of exit codes, why do you think we use 0 (which normally means false in C) to indicate a successful program conclusion, but non-zero (specifically and most frequently 1) to indicate a failure?
  
- ### Problems
  - [Old Friends](https://docs.cs50.net/2018/ap/problems/friends/friends.html)
  - [Calc](https://docs.cs50.net/2018/ap/problems/calc/calc.html)
