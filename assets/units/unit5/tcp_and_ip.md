## TCP and IP

Assuming you have viewed the routers section, IP (Internet Protocol) is the system we've just seen, that works with routers to ensure packets of data are split into pieces, sent to the correct destination, and pieced back together. We also, however, want to have a system of "guaranteed" delivery, wherein the destination system knows if not all packets have arrived successfully. This is where TCP, or Transmission Control Protocol, comes into play. It ensures data is properly marked when it is split into pieces, so if one packet does not arrive, the sender is notified and can resend. TCP is also responsible for separating data by type and sending them via separate ports.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/PUPDGbnpSjw?start=2540&end=3089)
  - [Watch on the CS50 Video Player](https://video.cs50.net/2017/fall/lectures/6?t=0h42m20s)
  - [Download Lecture](http://cdn.cs50.net/2017/fall/lectures/6/lecture6-720p.mp4?download)
  - [Lecture Notes](https://docs.cs50.net/2017/fall/notes/6/lecture6.html#http)

- ### Shorts
  - [IP](https://www.youtube.com/embed/A1g9SokDJSU)
  - [TCP](https://www.youtube.com/embed/GP7uvI_6uas)
  
- ### Notes
  - [TCP and IP]({{"/assets/pdfs/unit5/tcp_and_ip.pdf" | relative_url }})

- ### Supplementary Resources
  - Khan Academy on [Packet, Routers, and Reliability](https://www.youtube.com/embed/aD_yi5VjF78).

- ### Thought Questions
  - Why does the data we want to send and receive be divided into packets?
  - What exactly is TCP in charge of? Keeping with the mail delivery analogy, what is TCP's "job" in the complicated process that is sending and receiving data on the Internet?
  - How do TCP and IP work together to ensure efficient and reliable packet delivery across the Internet?