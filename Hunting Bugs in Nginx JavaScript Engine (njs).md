tags: #type_confusion #OOB_read #codeQL #fuzzing
original link: [Hunting Bugs in Nginx JavaScript Engine (njs)](https://0xbigshaq.github.io/2024/05/24/njs-vr-bugs/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 23](https://blog.exploits.club/exploits-club-weekly-newsletter-23/) 

---
## Exploits Club Summary:
> [@0x_shaq](https://x.com/0x_shaq?ref=blog.exploits.club) released a write-up this week on his research into the Nginx Javascript Interpreter. After some **initial fuzzing, he was able to identify two bugs: a type confusion and an OOB read.** He then was able to **codify the type confusion pattern into a CodeQL query,** which found two additional variants. 