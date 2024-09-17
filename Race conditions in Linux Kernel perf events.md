tags: #race_condition #page_reuse  #lpe #kernel #linux
original link:  [Race conditions in Linux Kernel perf events](https://binarygecko.com/race-conditions-in-linux-kernel-perf-events/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 38 - Linux Races, Blind Memory Corruption, LLM Java Fuzzing, and More](https://blog.exploits.club/exploits-club-weekly-newsletter-38-linux-races-blind-memory-corruption-llm-java-fuzzing-and-more/)

---
## Exploits Club Summary:
> [Binary Gecko](https://binarygecko.com/?ref=blog.exploits.club) has been on a roll recently with the blog posts. We first covered their Chrome write-up just [two weeks ago](https://blog.exploits.club/exploits-club-weekly-newsletter-36-regex-fuzzing-c-metadata-kernel-streaming-and-more/), and now they are back with **a Linux bug they recently disclosed to the kernel security team**. The core issue (as the title suggests) is **a race condition in perf events that leads to a page reuse primitive.** The blog is highly technical, covering all the structs and code paths you need to understand the core issue and the team's exploit. 