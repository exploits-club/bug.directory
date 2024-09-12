tags: #iot #bluetooth #auth_bypass
original link:  [Do a firmware update for your AirPods...now](https://blogs.gnome.org/jdressler/2024/06/26/do-a-firmware-update-for-your-airpods-now/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 28](https://blog.exploits.club/exploits-club-weekly-newsletter-28/) 

---
## Exploits Club Summary:
>  A quick hitter blog post on a recent AirPods vulnerability. While **the post itself doesn't go too deep on the technicals** (though the author notes he will do a follow-up post), it does hit at the key points. Namely, **there is a proprietary protocol from Apple called "Fast Connect", which helps to simplify the connection process by only taking 4 back-and-forth messages**, as opposed to the complex process that takes place with regular Bluetooth devices. While trying to re-implement this protocol from his Linux machine, **the author noticed no authentication check for non-Apple devices over this protocol,** meaning that anyone can connect and listen to your AirPods as long as they know the fixed Bluetooth Mac Address.