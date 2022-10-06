# Awesome Iran Freedom
In this repository we have collected all awesome tools for iranian people

# Table of Content
- [Telegram Proxy](#telegram-proxy)
- [VPS Provider](#vps-provider)

# Telegram Proxy
 **[`^        back to top        ^`](#table-of-content)**
 - [Official Python](https://github.com/alexbers/mtprotoproxy) Easy to setup
 - [Official Python Docker](https://hub.docker.com/r/alexbers/mtprotoproxy) Easy to setup
 - [Official C++](https://github.com/TelegramMessenger/MTProxy) Hard to setup
 
# Anti-Filter
**[`^        back to top        ^`](#table-of-content)**
## Server
**[`^        back to top        ^`](#table-of-content)**
- [Gost](https://github.com/ginuerzh/gost) Easy to setup but powerful and support nearly all proxy protocol such as tls tunnel ssh golang udp http2 socks5 shadowsocks kcp quic tuntap sni obfs4 dns 
- [Shadowsocks](https://shadowsocks.org/en/index.html) - A secure proxy, designed to protect your Internet traffic.
- [Outline](https://getoutline.org/fa/get-started/#step-1) - A secure socks5 proxy, designed to protect your Internet traffic.


## Client
**[`^        back to top        ^`](#table-of-content)**
### Clash
 A Rule Based proxy (based on GEOIP, IP-CIDR, Domain, fallback, load balance) that support many protocols such as Shadowsocks(R), VMess, Trojan, Snell, SOCKS5, HTTP(S) that can be retrive by a link
 #### Clash Download
- [Android: Google Play](https://play.google.com/store/apps/details?id=com.github.kr328.clash) [Android: APK](https://github.com/Kr328/ClashForAndroid/releases/download/v2.5.11/cfa-2.5.11-premium-universal-release.apk) [Android: Repository](https://github.com/Kr328/ClashForAndroid)
- [Windows](https://github.com/Fndroid/clash_for_windows_pkg/releases/download/0.20.4/Clash.for.Windows.Setup.0.20.4.exe)
- [macOS](https://github.com/Fndroid/clash_for_windows_pkg/releases/download/0.20.4/Clash.for.Windows-0.20.4.dmg) 
- [macOS M1](https://github.com/Fndroid/clash_for_windows_pkg/releases/download/0.20.4/Clash.for.Windows-0.20.4-arm64.dmg)  
- [Linux](https://github.com/Fndroid/clash_for_windows_pkg/releases/download/0.20.5/Clash.for.Windows-0.20.5-x64-linux.tar.gz)
- [iOS: Shadowrocket not free](https://apps.apple.com/us/app/shadowrocket/id932747118?platform=iphone)  [iOS: Stash not free](https://apps.apple.com/app/stash/id1596063349?platform=iphone) not free
 
 #### Clash example configuration for Iran
 - [only pass filtered sites to proxy](https://github.com/hiddify/config/blob/main/clash/lite.yml)  
 It is useful when you want to use always the proxy without having any issues to all other sites. `Fastest solution` `lowest overhead on server`
 - [only pass non-iranian sites to proxy](https://github.com/hiddify/config/blob/main/clash/normal.yml)
 It uses direct connection for irannian sites (50% off in price) and  the non-iranian sites will pass to the proxy so you can avoid external sanctions.
 - [pass all sites to proxy](https://github.com/hiddify/config/blob/main/clash/all.yml) 

### ServerLess!!! 
This approach works by changing packets to scape filtering! 
- requirment: a working DNS over HTTPS (DoH) is needed. [setup a DoH server]()
- [Android](https://github.com/zhenyolka/DPITunnel-android)
- [Windows: GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI) [Windows: GreenTunnel](https://github.com/SadeghHayeri/GreenTunnel)
### OpenVpn
### Shadowsocks
- [iOS: Shadowlink](https://apps.apple.com/us/app/shadowlink-shadowsocks-vpn/id1439686518)
### Outline
- [Outline](https://getoutline.org/fa/get-started/#step-3)


# VPS Provider
**[`^        back to top        ^`](#table-of-content)**
- [Hetzner](https://www.hetzner.com/cloud?country=ot) Cheap but high quality vps (starts from 3.79€/m for a vps with 2GB of RAM)
- [OVH](https://www.ovhcloud.com/fr/vps/) (starts from 3.5€/m for a vps with 2GB of RAM)
- [Azure](https://azure.microsoft.com/en-us/free/students/)  Free for students to setup 2 VPS (0.5 GB of RAM) with two IPs 

# Public Free AntiFilter
**[`^        back to top        ^`](#table-of-content)**
- [Tor Project](https://snowflake.torproject.org/)
- [Psiphon: Android](https://play.google.com/store/apps/details?id=com.psiphon3.subscription), [Psiphon: Android Apk](https://psiphon.ca/PsiphonAndroid.apk) [Psiphon: Windows](https://psiphon.ca/psiphon3.exe), [Psiphon: iOS](https://apps.apple.com/app/psiphon/id1276263909), [Psiphon: macOS](https://apps.apple.com/app/psiphon/id1276263909), [Psiphon: By Email](mailto:get@psiphon3.com)
- [Ultrasurf: iOS](https://apps.apple.com/us/app/ultrasurf-vpn/id1563051300), [Ultrasurf: Android](https://play.google.com/store/apps/details?id=us.ultrasurf.mobile.ultrasurf&hl=en_US&gl=US), [Ultrasurf: Windows](https://ultrasurf.us/download/usf.zip), [Ultrasurf: chrome/edge browser](https://chrome.google.com/webstore/detail/ultrasurf-security-privac/mjnbclmflcpookeapghfhapeffmpodij)

<!--
# Public Free AntiFilter
**[`^        back to top        ^`](#table-of-content)**
-->