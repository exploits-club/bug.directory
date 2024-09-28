tags: #GSM #heap_overflow #linux #kernel
original link:  [Etiquette for dropping PoCs in 2024? A Linux LPE](https://x.com/roddux/status/1795392270616969653?ref=blog.exploits.club)
newsletter link:  [exploits.club Weekly Newsletter 23](https://blog.exploits.club/exploits-club-weekly-newsletter-23/)

---
## Exploits Club Summary:
> What's the right way to drop a PoC? Well thankfully for us, the people on X decided that it was "full exploits with offsets", so that's exactly what [@roddux](https://x.com/roddux?ref=blog.exploits.club) did with his **Linux LPE,** [**germy**](https://github.com/roddux/germy?ref=blog.exploits.club)**.** The GitHub repo [includes a write-up](https://github.com/roddux/germy/blob/main/TECHNICAL_DETAILS.md?ref=blog.exploits.club) as well, complete with an **overview of the root cause, exploit strategy, and mitigation bypasses.** The bug stems from **3 seemingly inconsequential issues that, when taken in total, lead to an overflow.** 