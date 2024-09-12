tags: #linux #lpe #integer_overflow #kernel
original link:  [Linux Kernel Int Overflow Leading To Priv Esc](https://ssd-disclosure.com/ssd-advisory-linux-kernel-nft_validate_register_store-integer-overflow-privilege-escalation/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 24](https://blog.exploits.club/exploits-club-weekly-newsletter-24/)

---
## Exploits Club Summary:
> [SSD Secure Disclosure Team](https://ssd-disclosure.com/?ref=blog.exploits.club) released a Linux privesc write-up this week which was patched in July of 2023. **The bug is a straightforward int overflow which results in a OOB read and write primitive.** The post ends with a **full PoC which uses `nft_payload` to leak stack info and bypass KASLR, overwrite the return address, and ROP to overwrite modprobe.**