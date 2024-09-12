tags: #iot #router #tp-link #stack_overflow #rop
original link:  [SSD Advisory: TP-LINK VIGI onvif_discovery Overflow](https://ssd-disclosure.com/ssd-advisory-tp-link-vigi-onvif_discovery-overflow/?ref=blog.exploits.club)
newsletter link:  [exploits.club Weekly Newsletter 26](https://blog.exploits.club/exploits-club-weekly-newsletter-26/)

---
## Exploits Club Summary:
> [SSD Secure Disclosure](https://ssd-disclosure.com/?ref=blog.exploits.club) team released a write-up for a **buffer overflow on TP-Link's VIGI security camera.** The vulnerability resides in `onvif_discovery`, which listens on port 5001 and is reachable while unauthenticated. The root cause for the vulnerability here is pretty straightforward, **as attacker-controlled data is copied from one stack buffer to another, smaller buffer without performing any sort of bounds checking.** The advisory walks through the call stack and shows the RE where the vulnerability resides. **While it doesn't go in-depth on the exploitation, it provides a full PoC, which looks to do some standard ROP.**