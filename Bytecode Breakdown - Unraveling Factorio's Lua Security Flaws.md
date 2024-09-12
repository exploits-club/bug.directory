tags: #game_hacking #lua #bytecode #type_confusion
original link:  [Bytecode Breakdown: Unraveling Factorio's Lua Security Flaws](https://memorycorruption.net/posts/rce-lua-factorio/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 29](https://blog.exploits.club/exploits-club-weekly-newsletter-29/) 

---
## Exploits Club Summary:
> If anyone knows the author of this post, please let us know because it has got to be **one of the cleanest write-ups we have seen in a long time.** Everything is carefully explained and broken down, and the whole thing flows in a manner that makes sense even without prior context. While it is long, there's lots to cover. The **post addresses the way Lua bytecode can be manipulated in a malicious manner in order to achieve remote code execution.** The author demonstrates this by first **causing a type confusion to leak a memory addresses, before diving into creating fake objects and gaining control of the instruction pointer.** They then demonstrate the a**ttack on the popular game** [**Factorio**](https://www.factorio.com/?ref=blog.exploits.club)**, which will run the exploit when they connect to the malicious game server.** 