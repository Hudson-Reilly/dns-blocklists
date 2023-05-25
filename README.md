![GitHub last commit](https://img.shields.io/github/last-commit/hagezi/dns-blocklists)![GitHub issues](https://img.shields.io/github/issues/hagezi/dns-blocklists)![GitHub closed issues](https://img.shields.io/github/issues-closed/hagezi/dns-blocklists)![GitHub repo size](https://img.shields.io/github/repo-size/hagezi/dns-blocklists)[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhagezi%2Fdns-blocklists&count_bg=%23754400&title_bg=%235F5F5F&icon=awesomelists.svg&icon_color=%23E7E7E7&title=visitors&edge_flat=false)](https://github.com/hagezi/dns-blocklists)[![shields.io Stars](https://img.shields.io/github/stars/hagezi/dns-blocklists)](https://github.com/hagezi/dns-blocklists/stargazers)
## DNS Blocklists - *For a better internet!*

### *Made with :heartbeat: for a safer and cleaner internet! It always seems impossible until it’s done.*
*If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)! Thanks for your support!* 

### Table of Contents
1. [Overview](#overview)
2. [Multi light](#light) - *Hand brush: Light protection*
3. [Multi normal](#normal) - *Broom: All-round protection*
4. [Multi pro](#pro) - *Big broom: Extended protection*
5. [Multi pro++](#proplus) - *Sweeper: Maximum protection (more aggressive)*
6. [Multi ultimate](#ultimate) - *Ultimate Sweeper: Aggressive protection*
7. [Fake](#fake) - *Protects against internet scams, traps & fakes!*
8. [Threat Intelligence Feeds](#tif) - *Increases security significantly!*
9. [DoH/VPN/TOR/Proxy Bypass](#bypass) - *Prevent methods to bypass your DNS!*
10. [Safesearch not supported](#safesearch) - *Prevent the use of search engines that do not support safesearch!*
11. [Dynamic DNS](#dyndns) - *Protects against the malicious use of dynamic DNS services!*
12. [Badware Hoster](#hoster) - *Protects against the malicious use of free host services!*
13. [Most Abused TLDs](#tlds) - *Protects against known malicious Top Level Domains!*
14. [Anti Piracy](#piracy) - *Protects against piracy!*
15. [Gambling](#gambling) - *Protects against gambling content!*
16. [Personal](#personal) - *My manually maintained denylist*
17. [Native Tracker](#native) - *Broadband tracker of devices, services and operating systems*
18. [Credits](#credits)
19. [Supporter](https://github.com/hagezi/dns-blocklists/stargazers) - *Leave a star (top right)!*
20. [Recommendation](#recommendation)
22. [Online DNS Services](#dnsservices) : [RethinkDNS](#rethinkdns) - [DNSforge](#dnsforge) - [DNSwarden](#dnswarden) - [AdGuardDNS](#adguarddns) - [ControlD](#controld) - [NextDNS](#nextdns)
22. [About](#about) : [Contact](#contact) - [Groups](#groups) - [Repository](#repository) - [Referral Domains](#referral) - [Support Me](#support)
23. [Sources/Statistics](usedsources.md) - [All known sources](knownsources.md) 
24. [Mirror](https://gitlab.com/hagezi/mirror/-/tree/main/dns-blocklists) - *Mirrored files of the block lists on GitLab*

### ***Multi - Cleans the Internet and protects your privacy!*** <a name="overview"></a>
*An all in one DNS blocklist in **various versions (light, normal, pro, pro++ and ultimate)**. It can be used as a stand alone blocklist. For every region. Blocks ads, affiliate, tracking, metrics, telemetry, fake, phishing, malware, scam, coins and other "crap". Based on [various blocklists](usedsources.md).*

#### ***Multi blocklist version and size overview:***
| Version | Domains<br>Compressed | Pro++ | Pro | Normal | Light | [Fake](#fake) | [TIF<br>full](#tif) | [TIF<br>light](#tif) | [Personal](#personal) | [Native](#native) |
|:--------|---:|:---:|:------:|:-----:|:----:|:---:|:------:|:----------:|:----------:|:----------:|
| [Light](#light)             | 581706<br>121788     | |   |   |  | :green_circle: | | :green_circle: | :green_circle: | :yellow_square: |
| [Normal](#normal)       | 945807<br>303308     | |   |  | :green_circle: | :green_circle: | | :green_circle: | :green_circle: | :yellow_square: |
| [Pro](#pro)              | 1086414<br>385967         | |  | :green_circle: | :green_circle: | :green_circle: | | :green_circle: | :green_circle: | :yellow_square: |
| [Pro++](#proplus)    | 1355447<br>460755 | | :green_circle: | :green_circle: | :green_circle: | :green_circle: | | :green_circle: | :green_circle: | :green_circle: |
| [Ultimate](#ultimate)    | 2464519<br>979965 | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: |
           
*:green_circle: = contains the list named in the column caption*       
*:yellow_square: = partially contains (aggressive domains were allowed) the list named in the column caption*       
              
---
         
### ***Multi LIGHT*** - **Light protection** <a name="light"></a>
      
*Hand brush - Cleans the Internet and protects your privacy! Blocks Ads, Tracking, Metrics, some Malware and Fake.*
          
**Entries:** *581706 domains/hosts - 121788 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#light)         
         
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/light.txt) | PiHole (FTL < v5.22), Blocky, Diversion, OpenSnitch, PersonalBlocklist, pfBlockerNG | 
| Hosts    | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/light.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard  |
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/light.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/light.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/light.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/light.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/light.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/light-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/light-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/light.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### ***Multi NORMAL*** - **All-round protection** <a name="normal"></a>
      
*Broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
**Entries:** *945807 domains/hosts - 303308 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#multi)        
          
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/multi.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/multi.txt) | PiHole (FTL < v5.22), Blocky, Diversion, OpenSnitch, PersonalBlocklist, pfBlockerNG | 
| Hosts    | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/multi.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/multi.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard  |
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/multi.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/multi.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/multi.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/multi.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/multi.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/multi.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/multi.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/multi-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/multi-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/multi.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/multi.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### ***Multi PRO*** - **Extended protection (Recommended)** <a name="pro"></a>
      
*Big broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
**Entries:** *1086414 domains/hosts - 385967 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#pro)        
           
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/pro.txt) | PiHole (FTL < v5.22), Blocky, Diversion, OpenSnitch, PersonalBlocklist, pfBlockerNG | 
| Hosts    | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/pro.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard  |
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/pro.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/pro.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/pro.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### ***Multi PRO++*** - **Maximum protection** <a name="proplus"></a>

*Sweeper - Aggressive cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Coins and other "Crap".*
         
*More aggressive version of the Multi PRO blocklist. It may contain few false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains will be removed from the list!*

**Entries:** *1355447 domains/hosts - 460755 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#proplus)    
                                                
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/pro.plus.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/pro.plus.txt) | PiHole (FTL < v5.22), Blocky, Diversion, OpenSnitch, PersonalBlocklist, pfBlockerNG | 
| Hosts    | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/pro.plus.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/pro.plus.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard  |
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.plus.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.plus.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, TechnitiumDNS, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/pro.plus.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/pro.plus.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/pro.plus.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.plus.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.plus.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.plus.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/pro.plus-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.plus-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/pro.plus.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/pro.plus.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
                  
### ***Multi ULTIMATE*** - **Aggressive protection** <a name="ultimate"></a>

*Ultimate Sweeper - Strictly cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking (+Referral), Metrics, Telemetry, Phishing, Malware, Scam, Free Hoster, Fake, Coins and other "Crap".*
         
*Stricter version of the Multi PRO++ blocklist. It may contain false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains. Reported false positive domains will be removed from the list!*

**Entries:** *2464519 domains/hosts - 979965 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#ultimate)    
                                                
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/ultimate.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/ultimate.txt) | PiHole (FTL < v5.22), Blocky, Diversion, OpenSnitch, PersonalBlocklist, pfBlockerNG | 
| Hosts    | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/ultimate.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/ultimate.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard  |
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/ultimate.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/ultimate.txt) | PiHole (FTL >= v5.22), AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, TechnitiumDNS, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/ultimate.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/ultimate.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/ultimate.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/ultimate.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/ultimate.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/ultimate.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/ultimate-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/ultimate-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/ultimate.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/ultimate.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
                         
**Expires:** *24 hours (update frequency)*

---

### ***Fake - Protects against internet scams, traps & fakes!*** <a name="fake"></a>
*An blocklist for blocking fake stores, -news, -science, -streaming, rip-offs, cost traps and co.*         
        
**Entries:** *12280 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#fake)
       
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/fake.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/fake.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/fake.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/fake.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/fake.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/fake.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/fake.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/fake.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/fake-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/fake-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/fake.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/fake.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### ***Threat Intelligence Feeds - Increases security significantly!*** <a name="tif"></a>
*An blocklist for blocking malware, cryptojacking, scam, spam and phishing. Blocks domains known to spread malware, launch phishing attacks and host command-and-control servers.*         
        
***The block list exists in two versions:***
       
#### ***Full Edition*** <a name="tif_full"></a>

**Entries:** *1251405 domains/hosts - 717434 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#tif)
         
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/tif.txt) | PiHole (FTL < v5.22), Blocky, Diversion, OpenSnitch, PersonalBlocklist, pfBlockerNG | 
| Hosts    | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/tif.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/tif.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard  |
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/tif.txt) | PiHole (FTL >= v5.22), AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, TechnitiumDNS, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/tif.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/tif.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/tif.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/tif.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/tif.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/tif.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *24 hours (update frequency)*
        
#### ***Light Edition*** <a name="tif_light"></a>

**Entries:** *110292 domains/hosts - 71469 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#tiflight)
         
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/tif.light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/tif.light.txt) | PiHole (FTL < v5.22), Blocky, Diversion, OpenSnitch, PersonalBlocklist, pfBlockerNG | 
| Hosts    | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/tif.light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/tif.light.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard  |
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/tif.light.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, TechnitiumDNS, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/tif.light.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/tif.light.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/tif.light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/tif.light.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif.light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.light.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/tif.light-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.light-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/tif.light.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/tif.light.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *24 hours (update frequency)*

---

### ***DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS!*** <a name="bypass"></a>

*Prevent method to bypass your DNS. To ensure the bootstrap is your DNS server you must redirect or block standard DNS outbound (TCP/UDP 53) and block all DNS over TLS (TCP 853) outbound.*
          
***The block list exists in two versions:***

#### ***Complete Edition - Encrypted DNS Servers, VPN, TOR, Proxies*** <a name="bypass_all"></a>
       
**Entries:** *2132 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#doh-vpn-proxy-bypass)
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/doh-vpn-proxy-bypass.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh-vpn-proxy-bypass.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/doh-vpn-proxy-bypass.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh-vpn-proxy-bypass.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/doh-vpn-proxy-bypass.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-vpn-proxy-bypass.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-vpn-proxy-bypass.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-vpn-proxy-bypass-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-vpn-proxy-bypass-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/doh-vpn-proxy-bypass.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/doh-vpn-proxy-bypass.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

#### ***Encrypted DNS Servers only*** <a name="bypass_dns"></a>
       
**Entries:** *886 domains/hosts - 761 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#doh)
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/doh.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/doh.txt) | PiHole (FTL < v5.22), Blocky, Diversion, OpenSnitch, PersonalBlocklist, pfBlockerNG | 
| Hosts    | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/doh.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/doh.txt) | AdAway, uMatrix, DNS66, GasMask, NetGuard  |
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/doh.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/doh.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/doh.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/doh.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/doh.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/doh-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/doh.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/doh.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### ***Safesearch not supported - Prevent the use of search engines that do not support safesearch!*** <a name="safesearch"></a>
*An blocklist for blocking search engines that do not support safesearch.*         
        
**Entries:** *138 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#nosafesearch)
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nosafesearch.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/nosafesearch.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/nosafesearch.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/nosafesearch.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/nosafesearch.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/nosafesearch.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nosafesearch.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/nosafesearch.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/nosafesearch-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/nosafesearch-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/nosafesearch.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/nosafesearch.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### ***Dynamic DNS blocking - Protects against the malicious use of dynamic DNS services!*** <a name="dyndns"></a>
*An blocklist for blocking dynamic DNS services to protect against malicious use in phishing campaigns and others.*         
        
**Entries:** *1556 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#dyndns)
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/dyndns.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/dyndns.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/dyndns.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/dyndns.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/dyndns.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/dyndns.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/dyndns.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/dyndns.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/dyndns-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/dyndns-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/dyndns.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/dyndns.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### ***Badware Hoster blocking - Protects against the malicious use of free host services!*** <a name="hoster"></a>
*An blocklist for blocking known free hosters that also host badware via user content to prevent the use of these hosters for malicious purposes.*         
                      
**Entries:** *1886 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#hoster)
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/hoster.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/hoster.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/hoster.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/hoster.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/hoster.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/hoster.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/hoster.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/hoster.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/hoster-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/hoster-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/hoster.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/hoster.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### ***Most Abused TLDs - Protects against known malicious Top Level Domains!*** <a name="tlds"></a>
*An blocklist for blocking Top Most Abused Top Level Domains, merged from @Yokoffing, @DandelionSprout and SpamHaus.*         
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| AdGuard | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds.txt) | AdGuard, AdGuard Home |
| uBlock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds-ublock.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds-ublock.txt) | uBlock |
| AdBlock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds-adblock.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds-adblock.txt) | PiHole (only Dev/Nightly FTL > v5.22), AdBlock, TechnitiumDNS |
| RegEx | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/regex/spam-tlds-pihole.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/regex/spam-tlds-pihole.txt) | PiHole (FTL <= v5.22) RegEx denylist (Copy & Paste) |

**Expires:** *Updated regularly*

---

### ***Anti Piracy - Protects against piracy!*** <a name="piracy"></a>
*Blocks websites and services that are mainly used for illegal distribution of copyrighted content.*         
        
**Entries:** *6751 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#antipiracy)
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/anti.piracy.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/anti.piracy.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/anti.piracy.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/anti.piracy.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/anti.piracy.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/anti.piracy.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/anti.piracy.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/anti.piracy.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/anti.piracy-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/anti.piracy-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/anti.piracy.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/anti.piracy.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### ***Gambling - Protects against gambling content!*** <a name="gambling"></a>
*Blocks gambling content.*         
        
**Entries:** *84857 compressed domains* | [Sources/Statistics](https://github.com/hagezi/dns-blocklists/blob/main/usedsources.md#gambling)
            
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/gambling.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/gambling.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/gambling.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/gambling.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/gambling.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/gambling.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/gambling.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/gambling-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/gambling.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/gambling.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### ***Personal - My manually maintained denylist*** <a name="personal"></a>
*My personal blocklist, an extension for known blocklists. Blocks ads, trackers, native device trackers, badware and more. Not intended to be used as a standalone blocklist, it serves as a addition for other blocklists!*         
        
**Entries:** *40651 compressed domains*
       
| Format | Links | Can be used for |
|:-------|:-----|:----------------|
| Adblock  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/personal.txt) | PiHole (FTL >= v5.22), AdGuard, AdGuard Home, eBlocker, uBlock, AdBlock, AdBlock Plus, Opera, Vivaldi, Brave, AdNauseam |
| Unbound  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/personal.blacklist.conf)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/unbound/personal.blacklist.conf) | Unbound                                                              |
| DNSMasq  | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/personal.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/personal.txt) | DNSMasq                                                              | 
| Wildcard<br>Asterisk | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/personal.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/personal.txt) | DNSCloak, YogaDNS |
| Wildcard<br>Domains | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/personal-onlydomains.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/personal-onlydomains.txt) | DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/personal.txt)<br>[Mirror](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/personal.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

**Expires:** *Updated regularly*

---

### ***Native Tracker - Broadband tracker of devices, services and operating systems*** <a name="native"></a>
*Blocks native broadband tracker from devices, services and operating systems that track your activity.*         
                         
| Device/Service | Domains | Hosts | Adblock | Unbound | DNSMasq | Wildcard<br>Asterisk | Wildcard<br>Domains | RPZ |
|:-------|:--------:|:------:|:--------:|:--------:|:--------:|:---------:|:--------:|:--------:|
| Apple (iOS, macOS, tvOS) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.apple.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.apple.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.apple-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.apple.txt) |
| Huawei (Devices) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.huawei.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.huawei.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.huawei-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.huawei.txt) |
| Microsoft (Windows, Office, MSN) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.winoffice.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.winoffice.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.winoffice-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.winoffice.txt) |
| TikTok (Fingerprinting) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.tiktok.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.tiktok.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.tiktok-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.tiktok.txt) |
| LG webOS | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/unbound/native.lgwebos.blacklist.conf) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/dnsmasq/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.lgwebos.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/wildcard/native.lgwebos-onlydomains.txt) | [Link](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/rpz/native.lgwebos.txt) |

**Expires:** *Updated regularly*

---

### ***Credits*** <a name="credits"></a>

**A huge thank you to the following list maintainers of the [sources that were partially used](knownsources.md), alphabetical order:**

*abpindo, abpvn, abuse.ch, adaway, adguardteam, adroitadorkhan, amnestytech, anti-ad, anudeepnd, assoechap, azorult-tracker.net, badmojr, barbblock, bigdargon, bkrucarci, blahdns, bongochong, botvrij.eu, cats-team, cbuijs, cert-agid.gov.it, cipherops, cmiksche, craiu, d3ward, dandelionsprout, davidonzo, developerdan, dibdot, digitalside.it, dogino, drsdavidsoft, durablenapkin, easylist, easylist-lithuania, easylist-thailand, elliotwutingfeng, fademind, fanboy, firebog.net, frogeye.fr, gioxx, guardicore, hblock, hexxiumcreations, hole.cert.pl, hoshsadiq, hpthreatresearch, hufilter, iam-py-test, ihgalis, infinitytec, jarelllama, jawz101, jdlingyu, jkrejcha, joewein.net, kargig, kees1958, kevinthomas0, kriskintel.com, laicure, laniksj, lassekongo83, latvian-list, list-kr, logroid, malware-filter, manic-code, marco-acorte, matomo-org, metamask, migueldemoura, mitchellkrogza, molinero.dev, mvps.org, netlab.360, nextdns, nitrohorse, notonmyshift, notracking, oisd.nl, olbat, oneoffdallas, ookangzheng, paulgb, perflyst, phishing.army, piperun, piquark6046, polishfiltersteam, prodaft, quidsup, rescure.me, scafroglia93, shadowwhisperer, shallalist, shreyasminocha, sjhgvr, smed79, someonewhocares.org, stamparm, stanev.org, stevenblack, stopforumspam.com, symbuzzer, systemjargon, t145, th3m3, tiuxo, tweedge, tomasko126, ublockorigin, ultimate-hosts, uniartisan, ut1, velesila, wally3k, yokoffing, yourduskquibbles, yous, yoyo.org, zerodot1, zoso.ro and more*
         
---

### ***Recommendation*** <a name="recommendation"></a>

*As a network-wide DNS blocker, I recommend using [PiHole](https://pi-hole.net/), [Adguard Home](https://adguard.com), [TechnitiumDNS](https://technitium.com/dns/), [Blocky](https://github.com/0xERR0R/blocky) (advanced users) or [eBlocker](https://eblocker.org/).*
            
*DNS blocker offer a good protection of privacy by blocking tracking, metrics and telemetry. They can be used to block the vast majority of ads, malware, scam, fake and co, but not everything can be blocked at the DNS level!         
Therefore, I* ***additionally*** *recommend the use of a browser content blocker such as [AdGuard](https://adguard.com), [uBlock](https://ublockorigin.com) or [Ghostery](https://www.ghostery.com/).*
                     
*Check out yokoffing's [Recommended Filters for uBlock Origin](https://github.com/yokoffing/filterlists) for content blocker filter lists.*
*For a browser recommendation see also yokoffing's [What browser should I use that has adblocking?](https://github.com/yokoffing/NextDNS-Config#what-browser-should-i-use-that-has-adblocking)*

---

### ***Online DNS Services*** <a name="dnsservices"></a>        

*If you don't run your own DNS server on your home network or if you are looking for additional protection for your mobile devices when they are not connected to the home network, then I recommend one of the following DNS services:*

### ***RethinkDNS - free*** <a name="rethinkdns"></a>

*In [RethinkDNS](https://rethinkdns.com) you can use my light, multi, pro, pro++, ultimate and tif list.*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS | Apple Mobileconfig |
|:-----------|:---------------|:-------------|:-------------------|
| Normal (PRO + TIF)  | `https://sky.rethinkdns.com/1:AAoACBAA` | `1-aafaacaqaa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:AAoACBAA) and click on the red apple  |
| Aggressive (PRO plus + TIF) | `https://sky.rethinkdns.com/1:AAoACAgA` | `1-aafaacaiaa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:AAoACAgA) and click on the red apple |
| Strikt (ULTIMATE) | `https://sky.rethinkdns.com/1:gAAAQA==` | `1-qaaaaqa.max.rethinkdns.com` | [Visit](https://sky.rethinkdns.com/1:gAAAQA==) and click on the red apple |
            
### ***DNSforge (Germany) - free*** <a name="dnsforge"></a>

*[DNSforge](https://dnsforge.de/) uses my light blocklist:*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS | DNS-over-QUIC |
|:-----------|:---------------|:-------------|:-------------------|
| Normal (LIGHT + more) | `https://dnsforge.de/dns-query` | `dnsforge.de` | `quic://dnsforge.de:853`  |
            
### ***DNSwarden - free*** <a name="dnswarden"></a>

*In [DNSwarden](https://dnswarden.com/customfilter.html) you can use my light, multi, pro, pro++, ultimate and tif list.*
            
### ***AdGuardDNS - limited free/paid*** <a name="adguarddns"></a>        
          
*My blocklist recommendations for [AdGuardDNS](https://adguard-dns.io) are:*          

| General  |
|:---------|
| [HaGeZi Personal Black & White](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/personal-blackwhite.txt) + OISD Big |
          
### ***ControlD - free/paid*** <a name="controld"></a>

*In [ControlD](https://controld.com/free-dns) you can use [my blocklists](https://kb.controld.com/en/3rd-party-filters):*

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC |
|:-----------|:---------------|:-------------|
| Normal | `https://freedns.controld.com/x-hagezi-normal` | `x-hagezi-normal.freedns.controld.com` |
| Pro | `https://freedns.controld.com/x-hagezi-pro` | `x-hagezi-pro.freedns.controld.com` |
| Pro Plus | `https://freedns.controld.com/x-hagezi-proplus` | `x-hagezi-proplus.freedns.controld.com` |

### ***NextDNS - limited free/paid*** <a name="nextdns"></a>        

*In [NextDNS](https://nextdns.io/?from=jvpyfdfc) you can use my light, multi, pro, pro++ and ultimate list.*
               
*Check out @yokoffing [NextDNS Config Guide](https://github.com/yokoffing/NextDNS-Config) for recommended [NextDNS](https://nextdns.io/?from=jvpyfdfc) configuration settings.*

---

### ***About*** <a name="about"></a>

<p align="center"><a href="https://github.com/hagezi/dns-blocklists/graphs/contributors"><img src="https://contrib.rocks/image?repo=hagezi/dns-blocklists" /></a></p>
<p align="center"><i><b>"If the plan doesn‘t work, change the plan but never the goal."<br>There's no place like 127.0.0.1!</b></i></p>

*The blocklists are based on [various sources](usedsources.md) and my own denylists/extensions. They were designed to avoid [false positive domains](whitelist.txt) as much as possible without losing effectiveness and efficiency. Dead hosts are regularly removed from the lists to keep them as small as possible. Made with :heartbeat: for a safer and cleaner internet.*         
*All lists were tested against 6000 websites from the Cisco Umbrella Top 1 million list. It was checked whether the pages load, the page content is displayed correctly, navigation links work, images load, videos start and much more.*                 
*They are updated and maintained daily.*

*No, it's not just blocklists cobbled together from multiple sources. They have been optimized and extended to efficiently "clean the Internet" in all areas.*                   
            
*[Cover Your Tracks](https://coveryourtracks.eff.org/): "Our tests indicate that you have strong protection against Web tracking."*
                  
*Test them, give [feedback](https://github.com/hagezi/dns-blocklists/discussions) and [report false positive](https://github.com/hagezi/dns-blocklists/issues) domains.*

#### Contact <a name="contact"></a>

| Telegram | Matrix | Discord | Reddit | NextDNS | Mail |
|:---------:|:-------:|:--------:|:------:|:-------:|:-----:|
| [@hagezi](https://t.me/hagezi)  | @hagezi:matrix.org | HaGeZi#7513 | [u/hagezi](https://www.reddit.com/user/hagezi) | [@hagezi](https://help.nextdns.io/profile/x2hylgc) | hagezi@protonmail.com |

#### Groups <a name="groups"></a>

| Telegram | Matrix | Discord |
|:---------:|:-------:|:-----:|
[Link](https://t.me/hagezi_g) | [Link](https://matrix.to/#/#hagezi:matrix.org) | [CipherOps' Pi-hole & AdGuard Home](https://discord.gg/jg9CKkhC7M) |

#### Repository <a name="repository"></a>

*The repository is occasionally compressed (reinitialised) to reduce the overall size. Among other things, this invalidates forks and cleans up the commit history.*

#### Referral Domains <a name="referral"></a>

*Affiliate and tracking links (referral domains) that appear frequently on offer web pages, in emails or in search results are allowed in my lists. These are mostly called only after manual clicking on a link and are not used to display advertising.
If these are blocked, the first hit links from search results, for example, no longer work.* 
          
*[Referral domains](whitelist-referral.txt) have been removed from all lists except from the ultimate list, only some of them were removed but not all!*
         
*Allowing referral domains in my lists is equivalent to the [NextDNS](https://nextdns.io/?from=jvpyfdfc) feature "Privacy > Allow Affiliate & Tracking Links".*
          
#### Support Me <a name="support"></a>

*I do not want any money donations. If you don't know what to do with your money, invest it in aid or similar projects, do something good with it. There is enough misery in the world.*             
*Accepting money donations would also be absolutely unfair to the maintainers of the sources used, that's not my way. Without the existing lists. these lists would be simply nothing.*
                                    
*If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)!* 
                                
*Give feedback, show me your ideas, report domains to be blocked, report false positve domains and help to keep the internet safe and clean.*               
*Help and cooperation of any kind is welcome!*
         
***Thanks for your support!***
           
[![Stargazers repo roster for @hagezi/dns-blocklists](https://reporoster.com/stars/dark/hagezi/dns-blocklists)](https://github.com/hagezi/dns-blocklists/stargazers)
           
[![Star History Chart](https://api.star-history.com/svg?repos=hagezi/dns-blocklists&type=Date)](https://star-history.com/#hagezi/dns-blocklists&Date)

---

### ***Keep the internet clean!*** - Groups: [Matrix](https://matrix.to/#/#hagezi:matrix.org) / [Telegram](https://t.me/hagezi_g) / [Discord - CipherOps'](https://discord.gg/jg9CKkhC7M)

---
