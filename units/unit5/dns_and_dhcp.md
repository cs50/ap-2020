## DNS and DHCP

There are two servers and services crucial to the successful connection of your laptop to the rest of the internet. DHCP, also known as the Dynamic Host Configuration Protocol, dynamically assigns IP addresses to devices connecting to a network. DNS, the Domain Name System, is responsible for translating URLs of websites to IP addresses and vice versa. We need both IP addresses to be able to form a successful connection from sender to receiver.

- ### Lecture
  - [Watch on Youtube](https://www.youtube.com/embed/n_KghQP86Sw?start=215&end=708)
  - [Watch on the CS50 Video Player](https://video.cs50.net/cscie1a/2017/fall/lectures/internet?t=3m35s)
  - [Download Lecture](https://cdn.cs50.net/cscie1a/2017/fall/lectures/internet/internet-720p.mp4?download)
  - [Lecture Notes](https://cdn.cs50.net/cscie1a/2017/fall/lectures/internet/notes/internet.html)

- ### Notes
  - [DNS and DHCP]({{"/assets/pdfs/unit5/dns_and_dhcp.pdf" | relative_url }})

- ### Supplementary Resources
  - Microsoft on [Domain Name System (DNS)](https://docs.microsoft.com/en-us/windows-server/networking/dns/dns-top)
  - Microsoft on [Dynamic Host Configuration Protocol (DHCP)](https://docs.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-top)
  - Tim Fisher on [What is DHCP?](https://www.lifewire.com/what-is-dhcp-2625848)
  - Khan Academy on [IP Addresses and DNS](https://www.youtube.com/embed/MwxMsaFFycg)

- ### Thought Questions
  - Why do we need DHCP? (Hint: What are the benefits of DHCP dynamically allocating IP addresses versus assigning them permanently?)
  - Why do we need (or rather, why is it nice to have) DNS?
  - What can happen if the DNS server returns an incorrect translation, otherwise known as [DNS spoofing](https://en.wikipedia.org/wiki/DNS_spoofing) or poisoning?