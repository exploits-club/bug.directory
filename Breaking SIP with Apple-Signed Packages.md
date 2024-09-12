tags: #macos #sip #auth_bypass
original link:  [Breaking SIP with Apple-Signed Packages](https://www.l3harris.com/newsroom/editorial/2024/03/breaking-sip-apple-signed-packages?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 21](https://blog.exploits.club/exploits-club-weekly-newsletter-21/)

---
## Exploits Club Summary:
> [L3Harris](https://www.l3harris.com/?ref=blog.exploits.club) dropped a post this week discussing their research into bypassing Apple's System Integrity Protection (SIP). **The core idea of the vulnerability class revolves around finding command injection vulnerabilities present in installation scripts of Apple-signed packages with valid certificates.** If these packages have the `com.apple.rootless.install.heritables` entitlement, this allows them (and subsequently...attackers), to write to SIP protected locations. The post goes into some of the downsides of this bug class, before discussing the fixes implemented by Apple. 