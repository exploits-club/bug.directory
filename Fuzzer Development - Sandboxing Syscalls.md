tags: #fuzzing #methodology #emulation
original link:  [Fuzzer Development: Sandboxing Syscalls](https://h0mbre.github.io/Lucid_Context_Switching/?ref=blog.exploits.club#)
newsletter link: [exploits.club Weekly Newsletter 09](https://blog.exploits.club/exploits-club-weekly-newsletter-09/)

---
## Exploits Club Summary:
> [@hombre](https://twitter.com/h0mbre_?ref=blog.exploits.club) put out his **second part of the "Fuzzer Development"** series he is running on his [blog](https://h0mbre.github.io/?ref=blog.exploits.club). The **fuzzer sandboxes a** [**Bochs**](https://bochs.sourceforge.io/?ref=blog.exploits.club) **emulator for easy system emulation and snapshot fuzzing**. This post details the implementation of the **"Bochs-to-fuzzer context switch"**, which takes place in order to handle syscalls.