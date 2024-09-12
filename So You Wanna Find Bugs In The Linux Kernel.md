tags: #linux #kernel #learning_resource #methodology
original link: [So You Wanna Find Bugs In The Linux Kernel](https://github.com/sam4k/talk-slides/blob/main/so_you_wanna_find_bugs_in_the_linux_kernel.pdf?ref=blog.exploits.club)
newsletter link:  [exploits.club Weekly Newsletter 26](https://blog.exploits.club/exploits-club-weekly-newsletter-26/)

---
## Exploits Club Summary:
> [@sam4k1](https://x.com/sam4k1?ref=blog.exploits.club) uploaded his [TyphoonCon 24](https://typhooncon.com/?ref=blog.exploits.club) slides on attacking the Linux Kernel. **The slides first provide a wealth of knowledge on the state of the kernel VR before diving into specifics.** It covers w**hat makes a good subsystem to target, auditing workflow, and the use of tooling like syzcaller and CodeQL.** The presentation ends with a case study, demonstrating the outlined process in action. Sam picked an interesting subsystem, performed a code audit, identified limitations in the current fuzzing coverage, modified syzcaller, and dropped a bug.