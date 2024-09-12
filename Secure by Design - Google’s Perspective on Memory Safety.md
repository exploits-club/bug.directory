tags: #mitigation
original link: [Secure by Design: Google’s Perspective on Memory Safety](https://research.google/pubs/secure-by-design-googles-perspective-on-memory-safety/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 11](https://blog.exploits.club/exploits-club-weekly-newsletter-10-2/)

---
## Exploits Club Summary:
> Google is aiming to be President Biden's favorite child. Just a week after the [White House's cry for memory safety](https://www.whitehouse.gov/oncd/briefing-room/2024/02/26/memory-safety-statements-of-support/?ref=blog.exploits.club), the tech giant released a **12 page paper detailing the company's approach to mitigating memory corruption bugs.** The paper includes a brief history on the bug class, before jumping into Google's thoughts on how to irradiate it. **The approach involves adapting their** [**Safe Coding**](https://github.com/google/safe-html-types/blob/main/doc/index.md?ref=blog.exploits.club#introduction-to-safe-coding) **strategy to low-level languages, employing better exploit mitigations, and using static analysis and fuzzing to identify bugs ahead of deployment.** Don't worry fanboys, they do talk about **Rust**.