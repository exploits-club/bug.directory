tags: #windows #lpe #kernel #streaming_service #double_fetch #arbitrary_increment 
original link:  [Streaming vulnerabilities from Windows Kernel - Proxying to Kernel - Part II](https://devco.re/blog/2024/10/05/streaming-vulnerabilities-from-windows-kernel-proxying-to-kernel-part2-en/?ref=blog.exploits.club)
newsletter link:   [exploits.club Weekly Newsletter 42 - Glitching With A Lighter, Pixel 9 Baseband Security, Node.js Pipe Madness, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-42-glitching-with-a-lighter-pixel-9-baseband-security-node-js-pipe-madness-and-more/)

---
## Exploits Club Summary:
>  Following up their [blog post a little over a month ago](https://devco.re/blog/2024/08/23/streaming-vulnerabilities-from-windows-kernel-proxying-to-kernel-part1-en/?ref=blog.exploits.club), **DEVCORE have returned with more bugs in the kernel streaming attack surface.** After Pwn2Own, the team took a look KS Event and identified **a similar bug in which the conversion of a 32-bit request into a 64-bit one is mishandled.** The post then details the ramifications of this, and how it can be **used to perform a specific IOCTL with KernelMode.** The team is able to **convert this into an arbitrary increment primitive.** After reviewing some of the traditional techniques one may use with this primitive, **the team ends up working out their own exploit strategy to take this to full EoP.**


---
backlinks: [[Streaming vulnerabilities from Windows Kernel (Part 1) - Proxying to Kernel]]