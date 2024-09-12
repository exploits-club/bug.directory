tags: #firmware #car_hacking #iot
original link:  [Recovering an ECU firmware using disassembler and branches](https://blog.quarkslab.com/recovering-an-ecu-firmware-using-disassembler-and-branches.html?ref=blog.exploits.club)
newsletter link:  [exploits.club Weekly Newsletter 26](https://blog.exploits.club/exploits-club-weekly-newsletter-26/)
 

---
## Exploits Club Summary:
> A new post out of [Quarkslab](https://www.quarkslab.com/?ref=blog.exploits.club) this week walks through an i**nteresting challenge the team recently faced on a black box assessment while trying to dump the firmware.** After your typical `binwalk` failed, the team ended up **digging deep into the internals of the FAT filesystem.** They then whipped up a **Python script to identify function prologues, which helped identify some valid firmware chunks.** Iterating on this idea, they added some script improvements by analyzing branch instructions, **allowing them to slowly put the clusters of valid ARM functions into the correct order and export it to a new binary, recovering most of the firmware.**