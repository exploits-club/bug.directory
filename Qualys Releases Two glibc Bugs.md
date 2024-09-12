tags: #glibc #heap_overflow #OOB_write #OOB_read
original link:  [Qualys Releases Two glibc Bugs](https://www.qualys.com/research/security-advisories/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 06](https://blog.exploits.club/exploits-club-weekly/)

---
## Exploits Club Summary:
> Qualys released advisories for **two vulnerabilities they identified in glibc**. [The first](https://www.qualys.com/2024/01/30/qsort.txt?ref=blog.exploits.club) was an **OOB read and write in `qsort()`** due to a missing bounds check. [The second](https://www.qualys.com/2024/01/30/cve-2023-6246/syslog.txt?ref=blog.exploits.club) was a **heap-based buffer overflow affecting** `syslog()` 