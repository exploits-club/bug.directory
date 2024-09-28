tags: #browser #arc
original link: [gaining access to anyones browser without them even visiting a website](https://kibty.town/blog/arc/)
newsletter link: [exploits.club Weekly Newsletter 40 - iOS Kernel Exploitation, CET Bypasses, Elgato Hardware Repair, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-40-ios-kernel-exploitation-cet-bypasses-elgato-hardware-repair-and-more/)

---
## Exploits Club Summary:
> When we think browser 0day, we typically do not think Firebase...and maybe thats our problem. In a new post,  [@xyz3va](https://x.com/xyz3va) talks through a crazy vuln she found in [Arc browser](https://arc.net/). Essentially, with Frida and some ObjectiveC, she was able to identify the browser seemed to be using Firestore. From there, she realized these things called "Arc boosts" (basically just ways to customize certain websites inside Arc) are also stored in Firestore for each user, and can contain arbitrary Javascript. These are retrieved via userId and....yep you can just change your own userId. So she created a "malicious" Arc boost, and then changed her userId to a victim Id and boom, popped the victims browser. 