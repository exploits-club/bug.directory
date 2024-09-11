tags: [[fuzzing]], [[methodology]], [[libfuzzer]], [[learning resource]]
original link: [Ring Around The Regex: Lessons learned from fuzzing regex libraries (Part 2)](https://secret.club/2024/08/23/ring-around-the-regex-2.html?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 36 - Regex Fuzzing, C++ Metadata, Kernel Streaming, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-36-regex-fuzzing-c-metadata-kernel-streaming-and-more/)

---
## Exploits Club Summary:
> Everyone's **_second_ favorite club** is back this week with a new fuzzing post. In Part 2 installment into the regex fuzzing series, [@addisoncrump_vr](https://x.com/addisoncrump_vr?ref=blog.exploits.club) continues his **journey breaking down the uses and limitations around fuzzing, specifically in the context of evaluating regex libraries.** This time, he looks at [PCRE2](https://github.com/PCRE2Project/pcre2?ref=blog.exploits.club). The library is **already in OSS-Fuzz**, but as Addison explains, this **doesn't mean all hope is lost**. The post then discusses some challenges, including an interesting insight into how **coverage-guided fuzzing doesn't reflect a code region's behavior.** Overall, the **fuzzer found a handful of non-critical bugs** - which sparked some additional philosophical questions touched on towards the end of the post. 



---
backlinks:
[[Ring Around The Regex - Lessons learned from fuzzing regex libraries (Part 1)]]