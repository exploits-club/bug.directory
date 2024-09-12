tags: #methodology #learning_resource #ida
original link: [C++ Unwind Exception Metadata: A Hidden Reverse Engineering Bonanza](https://www.msreverseengineering.com/blog/2024/8/20/c-unwind-metadata-1?ref=blog.exploits.club) 
newsletter link:  [exploits.club Weekly Newsletter 36 - Regex Fuzzing, C++ Metadata, Kernel Streaming, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-36-regex-fuzzing-c-metadata-kernel-streaming-and-more/)

---
## Exploits Club Summary:
> An exceptionally well-written post from [@RolfRolles](https://x.com/RolfRolles?ref=blog.exploits.club) was released this week discussing how **C++ exception metadata is a wealth of information when it comes to reversing**. In particular, the post looks at `wind` and `unwind` metadata, which the compiler includes to ensure deconstructors are called in the case of an exception. This **metadata includes the deconstructor for each of the individual subobjects within the struct, which can be useful for type information, struct nesting recovery, and inheritance relationships.** 