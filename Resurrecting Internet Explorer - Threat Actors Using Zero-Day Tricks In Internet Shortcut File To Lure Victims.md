tags: #ITW #internet_explorer
original link:  [Resurrecting Internet Explorer: Threat Actors Using Zero-Day Tricks In Internet Shortcut File To Lure Victims](https://research.checkpoint.com/2024/resurrecting-internet-explorer-threat-actors-using-zero-day-tricks-in-internet-shortcut-file-to-lure-victims-cve-2024-38112/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 29](https://blog.exploits.club/exploits-club-weekly-newsletter-29/) 

---
## Exploits Club Summary:
> [Check Point Research](https://research.checkpoint.com/?ref=blog.exploits.club) was busy this week. In addition to the V8 bytecode tooling, they also released a post on a **trick threat actors have been employing against windows users.** This attack leverages the **`.url` extension on a fake PDF file, which is opened by the decommissioned browser Internet Explorer.** Sooo they just pop an 0-day in the inherently less secure browser? Nope, not even that complex - instead, they **force the download of a `.hta` file on the victim, resulting in code exec on the victim's machine.** 