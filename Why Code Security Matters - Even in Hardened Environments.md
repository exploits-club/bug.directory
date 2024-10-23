tags: #rop #arbitrary_file_write #javascript #nodejs
original link: [Why Code Security Matters - Even in Hardened Environments](https://www.sonarsource.com/blog/why-code-security-matters-even-in-hardened-environments/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 42 - Glitching With A Lighter, Pixel 9 Baseband Security, Node.js Pipe Madness, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-42-glitching-with-a-lighter-pixel-9-baseband-security-node-js-pipe-madness-and-more/)

---
## Exploits Club Summary:
> **This post is a banger front to back... half-tempted to just leave it at that and force you to go read it for yourself.** The premise is this: y**ou have an arbitrary file write via a Node.js server on a Linux read-only filesystem. Can you get RCE?** These researchers figured out that the answer is yes, by **abusing the pipes that Node's async capabilities are built on top of.** The strategy involves a **custom fake-object/rop gadget finder, and a handful of thoughtful restriction bypasses. Intrigued yet?** You should be. 