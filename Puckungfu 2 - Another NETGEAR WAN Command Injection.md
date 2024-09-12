tags: #router #pwn2own #command_injection
original link: [Puckungfu 2: Another NETGEAR WAN Command Injection](https://research.nccgroup.com/2024/02/09/puckungfu-2-another-netgear-wan-command-injection/?ref=blog.exploits.club) 
newsletter link: [exploits.club Weekly Newsletter 08](https://blog.exploits.club/exploits-club-weekly-newsletter-08/)

---
## Exploits Club Summary:
> [NCC Group](https://research.nccgroup.com/?ref=blog.exploits.club) released a follow up to their original [Puckungfu](https://research.nccgroup.com/2022/12/22/puckungfu-a-netgear-wan-command-injection/?ref=blog.exploits.club) post, detailing a **different command injection bug they were able to use in Pwn2Own 2022** after Netgear patched their original one just days before the competition. For this bug, the cron job which served as the entry to the buggy code path only triggered randomly between 1:00AM-4:00AM. For Pwn2Own, the team devised a **strategy to trigger the job by remotely altering the device's time zone and accurately predicting the cron job's 'random' timing within a minute.** 