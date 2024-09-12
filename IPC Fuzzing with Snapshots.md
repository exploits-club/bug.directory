tags: #firefox #fuzzing #ipc
original link: [IPC Fuzzing with Snapshots](https://blog.mozilla.org/attack-and-defense/2024/06/24/ipc-fuzzing-with-snapshots/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 27](https://blog.exploits.club/exploits-club-weekly-newsletter-27/)

---
## Exploits Club Summary:
>  [@mozdeco](https://x.com/mozdeco?lang=en&ref=blog.exploits.club) from Mozilla released a post on the company's security blog **detailing the new IPC fuzzing technique they have implemented for Firefox.** The technical implementation uses **Nyx for full-vm snapshots and AFL++ as the frontend.** There is also an [**open-source**](https://github.com/MozillaSecurity/snapshot-fuzzing?ref=blog.exploits.club) **custom agent which handles a handful of things.** The write-up then details how this stack can effectively be used to **fuzz a single IPC message, and how code coverage is tracked.**