# Lean's OpenWrt source with extra packages provided by Kenzok8

----

[1]: https://img.shields.io/badge/Issue-Welcome-brightgreen
[2]: https://github.com/Neurotoxin0/OpenWrt/issues/new
[3]: https://img.shields.io/badge/PRs-Welcome-brightgreen
[4]: https://github.com/Neurotoxin0/OpenWrt/pulls
[5]: https://img.shields.io/github/workflow/status/Neurotoxin0/OpenWrt/Project%20Openwrt%20CL
[6]: https://github.com/Neurotoxin0/OpenWrt/actions
[7]: https://img.shields.io/github/v/release/Neurotoxin0/OpenWrt
[8]: https://github.com/Neurotoxin0/OpenWrt/releases

[![Issue Welcome][1]][2]
[![PRs Welcome][3]][4]
[![Actions][5]][6]
[![Releases][7]][8]
- [中文版](https://github.com/Neurotoxin0/OpenWrt/blob/master/README.md "中文版")

----

## Source Codes & Packages Contributer：
+ [![Lean](https://img.shields.io/badge/OpenWrt%20Source%20Code-Lean-brightgreen?style=flat-square&logo=appveyor)](https://github.com/coolsnowwolf/lede) 
+ [![Kenzok8](https://img.shields.io/badge/OpenWrt%20Extra%20Packages-Kenzok8-brightgreen?style=flat-square&logo=appveyor)](https://github.com/kenzok8/openwrt-packages) 
+ [![P3TERX](https://img.shields.io/badge/Github%20WorkFlow%20Auto%20Build-P3TERX-brightgreen?style=flat-square&logo=appveyor)](https://github.com/P3TERX/Actions-OpenWrt)

----

+ Packages compiled include but not limited to: 

|Name|Usage & Comment
-|-
|ADByBy Plus|Ad Blocker|
|ADGuardHome|Ad Blocker|
|Advanced|Advanced Toolset|
|Argonne Config|Custom Config For "Argonne" Theme|
|Argonne|Theme|
|ARP-Bind|-|
|Auto Reboot|-|
|Commands|Custom Shell Command|
|Diskman|btrfs & lsblk|
|DNSMASQ|FULL SET|
|DockerMan*|Docker Helper; MODULE ONLY|
|EasyMesh|Support mesh for multiple Openwrt router|
|EQOS|Quality of Service module|
|Flow Offload|Openwrt Official Hardware Accelerater|
|iFit|Theme|
|Ipsec-vpnd|IPsec VPN Server|
|MWAN3|Multiple WAN Support|
|OpenClash|Support Protocol: Clash|
|Passwall|Support Protocol & Component: Brook, ChinaDNS-NG, Hysteria, Kcptun, PDNSD, Socks5, SS, SSR, Trojan-Go, Trojan-Plus, V2ray, Xray; also with corresponding server-side support|
|PushBot|Publish Service|
|QBittorrent|Downloader; MODULE ONLY|
|QOS|Quality of Service module|
|Serverchan|Publish Service|
|Softenthervpn|VPN Server with multiple protocol supports|
|SSR Plus|Support Protocol & Component: Brook, ChinaDNS-NG, Kcptun, Socks5, SS, SSR, Trojan-Go, Trojan-Plus, V2ray, Xray; also with corresponding server-side support|
|uHTTPd|HTTPS Support for Openwrt Interface|
|Unblockmusic|-|
|UU Game Booster|-|
|VerySync|Limited Version; upgrade required before using|
|VM-Tools|-|
|VSFTPD|KMS Server|
|Wifi Schedule|-|
|WOL|Wake on Lan|
|XunLei Accelerator|-|
|ZeroTier|Virtual-Lan|

- Update every 24 hours, support auto-update when source codes are being published or altered
- Releases & WorkFlows will be kept with the 7 latest versions (2 weeks)

----

- Target: X86-64
- Boot Loader: EFI & BIOS
- Kernel Size: 64 mb
- Rom Size: 1024 mb
+ Default IP: 192.168.31.2
+ Default Username: root
+ Default Password: password

----

+ For BuildInfo and compiled luci packages, please visit the workflow
- Considering the size of the img file, it is recommended to download the corresponding zip file from the workflow and unzip it (~ 300 mb)
+ [WorkFlow](https://github.com/Neurotoxin0/OpenWrt/actions "WorkFlow")
