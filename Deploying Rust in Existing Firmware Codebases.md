tags: #rust #methodology #firmware #learning_resource #android
original link: [Deploying Rust in Existing Firmware Codebases](https://security.googleblog.com/2024/09/deploying-rust-in-existing-firmware.html?ref=blog.exploits.club)
newsletter link:  [exploits.club Weekly Newsletter 37 - Juicy Overflows, The Art Of Exploitation, Rust in Firmware, and More](https://blog.exploits.club/exploits-club-weekly-newsletter-37-juicy-overflows-the-art-of-exploitation-rust-in-firmware-and-more/)

---
## Exploits Club Summary:
> The Android team over at Google released a **practical walkthrough for deploying Rust into existing firmware codebases.** The post walks through the **potential use cases** and challenges, what components might make good **candidates for replacement**, how to pick a well-maintained, `no_std` **compatible crate (or port one) for standard parsing operations**, and more. It then talks about **additional technical considerations** that should be reviewed when attempting to **create a 1-for-1 drop-in replacement where your C/C++ once stood** and some final comments on memory safety.