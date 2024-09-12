tags: #enterprise_app #java #deserialization
original link:  [“To live is to fight, to fight is to live! - IBM ODM Remote Code Execution](https://labs.watchtowr.com/double-k-o-rce-in-ibm-operation-decision-manager/?ref=blog.exploits.club)
newsletter link: 

---
## Exploits Club Summary:
> **Watchtowr labs** released a write-up on their research into the [IBM Operational Decision Manager](https://www.ibm.com/products/operational-decision-manager?utm_content=SRCWW&p1=Search&p4=43700074487969878&p5=e&gad_source=1&gclid=Cj0KCQiA84CvBhCaARIsAMkAvkKpBPPnJkG5gNPR-f1b1wm9EPrN29xXGdDHSjjGXcpja-PJJQRCLMoaAlCwEALw_wcB&gclsrc=aw.ds&ref=blog.exploits.club). The post details the **two bugs they found, a deserialization vuln and a JNDI injection.** The team was able to take the **JNDI injection all the way to RCE**, and both vulns were given CVEs ([CVE-2024-22319](https://nvd.nist.gov/vuln/detail/CVE-2024-22319?ref=blog.exploits.club), [CVE-2024-22320](https://nvd.nist.gov/vuln/detail/CVE-2024-22320?ref=blog.exploits.club)).