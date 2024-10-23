tags: #windows #info_leak #OOB_write #OOB_read #kernel  
original link:  [Vulnerabilities of Realtek SD card reader driver, part 1](https://zwclose.github.io/2024/10/14/rtsper1.html?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 43 - Variant Analysis at Scale, SD Card Driver Bugs, TTE Trends, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-43-variant-anal/)

---
## Exploits Club Summary:
> [@zwclose](https://x.com/zwclose?ref=blog.exploits.club) decided to take a look at the **Realtek SD card reader driver running on their Windows machine and...well lets just say it was particularly fruitful**. The blog covers the **6 vulnerabilities** identified and reported, **ranging info leaks to arbitrary kernel read/write.** It walks through each vulnerability, covering t**he basic necessary information required to understand the data flow and pinpoint the bug.** The conclusion mentions **a 7th vulnerability allowing access to physical memory with the card reader's DMA capability, which will be covered in a future entry.**