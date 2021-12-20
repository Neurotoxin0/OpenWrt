# 基于Leon的源码及Kenzok8提供的附加软件源编译的OpenWrt固件

----

[1]: https://img.shields.io/badge/Issue-Welcome-brightgreen
[2]: https://github.com/Neurotoxin0/OpenWrt/issues/new
[3]: https://img.shields.io/badge/PRs-Welcome-brightgreen
[4]: https://github.com/Neurotoxin0/OpenWrt/pulls
[5]: https://img.shields.io/github/workflow/status/Neurotoxin0/OpenWrt/Project%20Openwrt%20CL
[6]: https://github.com/Neurotoxin0/OpenWrt/actions
[7]: https://img.shields.io/github/v/release/Neurotoxin0/OpenWrt
[8]: https://github.com/Neurotoxin0/OpenWrt/releases

[![欢迎发Issue][1]][2]
[![欢迎Pull Request][3]][4]
[![工作流][5]][6]
[![固件发布][7]][8]
- [English Version](https://github.com/Neurotoxin0/OpenWrt/blob/master/README_EN.md "English Version")


## 源码 & 组件来源
+ [![Lean](https://img.shields.io/badge/OpenWrt%20Source%20Code-Lean-brightgreen?style=flat-square&logo=appveyor)](https://github.com/coolsnowwolf/lede) 
+ [![Kenzok8](https://img.shields.io/badge/OpenWrt%20Extra%20Packages-Kenzok8-brightgreen?style=flat-square&logo=appveyor)](https://github.com/kenzok8/openwrt-packages) 
+ [![P3TERX](https://img.shields.io/badge/Github%20WorkFlow%20Auto%20Build-P3TERX-brightgreen?style=flat-square&logo=appveyor)](https://github.com/P3TERX/Actions-OpenWrt)

----

+ 固件包括但不限于以下程序: 

|名称|功能 & 描述
-|-
|ADByBy Plus|去广告|
|ADGuardHome|去广告|
|Advanced|高级工具组|
|Argonne Config|"Argonne"主题的自定义配置|
|Argonne|主题|
|ARP-Bind|ARP绑定|
|Auto Reboot|自动重启|
|Commands|脚本(定时)执行面板|
|Diskman|btrfs & lsblk; 磁盘管理|
|DNSMASQ|全功能版|
|DockerMan*|Docker容器及图形化界面；仅模组|
|EasyMesh|在多个Openwrt路由器间组成mesh网络|
|EQOS|网速限速|
|Flow Offload|Openwrt官方硬件级加速器|
|iFit|主题|
|Ipsec-vpnd|IPsec VPN 服务端|
|MWAN3|多Wan多拨支持|
|OpenClash|支持的协议: Clash|
|Passwall|支持的协议及组件: Brook, ChinaDNS-NG, Hysteria, Kcptun, PDNSD, Socks5, SS, SSR, Trojan-Go, Trojan-Plus, V2ray, Xray; 包括服务端支持|
|PushBot|推送服务|
|QBittorrent|下载器；仅模组|
|QOS|网速限速|
|Serverchan|推送服务|
|Softenthervpn|VPN全家桶|
|SSR Plus|支持的协议及组件: Brook, ChinaDNS-NG, Kcptun, Socks5, SS, SSR, Trojan-Go, Trojan-Plus, V2ray, Xray; 包括服务端支持|
|uHTTPd|为Openwrt提供HTTPS加密|
|Unblockmusic|多平台音乐解锁|
|UU Game Booster|富家子弟加速器|
|VerySync|微力同步；使用前需更新|
|VM-Tools|-|
|VSFTPD|KMS 服务器|
|Wifi Schedule|无线排程|
|WOL|网络唤醒|
|XunLei Accelerator|迅雷快鸟|
|ZeroTier|虚拟局域网软件|

- 每24小时自动更新, 支持发布 & 修改源码时自动更新
- 发布的固件 & 工作流将被保留最新的7个版本(2周)

----

- 目标系统: X86-64
- 引导程序: EFI & BIOS
- 内核大小: 64 mb
- 磁盘大小: 1024 mb
+ 默认 IP: 192.168.31.2
+ 默认用户名: root
+ 默认密码: password

----

+ 如需了解固件配置信息以及编译好的luci软件包，请转至工作流。
- 考虑到img文件过大，建议从工作流中下载对应的zip文件后解压(~ 300 mb) 
+ [点我跳转至工作流](https://github.com/Neurotoxin0/OpenWrt/actions "工作流")
