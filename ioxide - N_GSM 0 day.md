tags: #linux #kernel #race_condition #uaf #GSM
original link: [ioxide: N_GSM 0 day](https://github.com/roddux/ixode/blob/main/notes.md?ref=blog.exploits.club) 
newsletter link: [exploits.club Weekly Newsletter 35 - NPU exploits, Phrack 71, 2014 Tablet Hacks, and More](https://blog.exploits.club/exploits-club-weekly-newsletter-35-npu-exploits-phrack-71-2014-tablet-hacks-and-more/)

---
## Exploits Club Summary:
> [@roddux](https://x.com/roddux?ref=blog.exploits.club) dropped a what _was_ a second 0day in n_gsm. Following just a **few months after his release of** [**germy**](https://github.com/roddux/germy?ref=blog.exploits.club)**,** the new repo published this week **includes a crash PoC and some notes on the bug itself.** The core issue revolves around a **race condition leading to a UAF.** The notes also include a KASAN splat an**d some ideas on how a full exploit for this might be written.** (Un)fortunately, this was mitigated in a [patch](https://github.com/torvalds/linux/commit/67c37756898a5a6b2941a13ae7260c89b54e0d88?ref=blog.exploits.club) released this month. 