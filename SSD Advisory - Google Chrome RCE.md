tags: #type_confusion #wasm #chrome #sbx
original link: [SSD Advisory: Google Chrome RCE](https://ssd-disclosure.com/ssd-advisory-google-chrome-rce/?ref=blog.exploits.club)
newsletter link:  [exploits.club Weekly Newsletter 34 - V8 Confusions, Smart Speaker Spying, Summer Camp Round-Up, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-34-v8-confusions-smart-speaker-spying-summer-camp-round-up-and-more-2/)

---
## Exploits Club Summary:
> An RCA and exploit for a **type confusion bug identified during TyphoonPWN 2024.** The post walks through the vulnerability, which is a **type confusion between canonicalized type id and `wasm::HeapType`.** This bug can be elevated to arbitrary type confusion between WASM objects. The post goes on to say that leveraging this into **basic exploit constructs was very similar to that of** [**@\_manfp**](https://x.com/_manfp?ref=blog.exploits.club) [**Pwn2Own winning exploit**](https://www.zerodayinitiative.com/blog/2024/5/2/cve-2024-2887-a-pwn2own-winning-bug-in-google-chrome?ref=blog.exploits.club)**.** The last step is the **escape the V8 sandbox, which was successfully done by abusing abusing `PartitionAlloc`**