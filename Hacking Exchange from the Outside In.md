tags: #fuzzing #afl #jackalope #exchange #supply_chain #uaf #OOB_read #OOB_write
original link:  [Hacking Exchange from the Outside In](https://www.atredis.com/blog/2024/4/22/hacking-exchange-from-the-outside-in?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 18](https://blog.exploits.club/exploits-club-weekly-newsletter-18/)

---
## Exploits Club Summary:
> Sticking with the Microsoft Theme, [**Atredis**](https://www.atredis.com/?ref=blog.exploits.club) **released a blog post this week digging into Oracle's "Outside in" libraries.** These libraries were **used in Microsoft Exchange 2019 up until a few months ago, and were used to parse specific file types if an attachment inspection mail flow had been enabled.** The write-up digs into the fuzzing set-up using AFL and Jackalope, before providing a crash-dump of the teams 3 finds (UAF, OOB read, OOB write)