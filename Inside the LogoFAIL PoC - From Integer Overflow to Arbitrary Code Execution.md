tags: #fuzzing #UEFI #heap_overflow
original link:  [Inside the LogoFAIL PoC: From Integer Overflow to Arbitrary Code Execution](https://binarly.io/posts/inside_the_logofail_poc_from_integer_overflow_to_arbitrary_code_execution/index.html?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 06](https://blog.exploits.club/exploits-club-weekly/)

---
## Exploits Club Summary:
> In early December, [Binarly.io](https://binarly.io/?ref=blog.exploits.club) presented the technical details on [**LogoFAIL**](https://binarly.io/posts/finding_logofail_the_dangers_of_image_parsing_during_system_boot/?ref=blog.exploits.club)**, a vulnerability class resulting from custom images being parsed during boot.** This week, the team **released a detailed write-up on creating a PoC for one-such vulnerability.** The blog post walks through identifying an integer overflow via fuzzing and escalating that primitive to a heap-overflow resulting in code execution. 