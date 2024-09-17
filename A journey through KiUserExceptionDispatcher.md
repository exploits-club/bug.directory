tags:  #windows #emulation
original link: [A journey through KiUserExceptionDispatcher](https://momo5502.com/posts/2024-09-07-a-journey-through-kiuserexceptiondispatcher/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 38 - Linux Races, Blind Memory Corruption, LLM Java Fuzzing, and More](https://blog.exploits.club/exploits-club-weekly-newsletter-38-linux-races-blind-memory-corruption-llm-java-fuzzing-and-more/)

---
## Exploits Club Summary:
> Who doesn't love a good emulator dev post? [@momo5502](https://x.com/momo5502?ref=blog.exploits.club) wrote up some of his **recent findings and struggles in this devlog-style post about his battles with Exceptions while building his user-space emulator.** This required quite a **bit of reversing of `KiUserExceptionDispatcher` to understand how to implement a proper stack layout.** It's a fun post that makes you want to break out your code editor and IDA. 