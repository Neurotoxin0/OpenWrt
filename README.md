# 基于Leon的源码及Kenzok8提供的附加软件源编译的OpenWrt固件
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

## 源码 & 组件来源 / Source Codes & Packages Contributer：
+ [![Lean](https://img.shields.io/badge/OpenWrt%20Source%20Code-Lean-brightgreen?style=flat-square&logo=appveyor)](https://github.com/coolsnowwolf/lede) 
+ [![Kenzok8](https://img.shields.io/badge/OpenWrt%20Extra%20Packages-Kenzok8-brightgreen?style=flat-square&logo=appveyor)](https://github.com/kenzok8/openwrt-packages) 
+ [![P3TERX](https://img.shields.io/badge/Github%20WorkFlow%20Auto%20Build-P3TERX-brightgreen?style=flat-square&logo=appveyor)](https://github.com/P3TERX/Actions-OpenWrt)

----

- 固件包括但不限于以下程序:
- Packages compiled include but not limited to: 
  + ADByBy Plus, ADGuardHome, Advanced, Argon New(Theme), ARP-Bind, Auto Reboot
  + Baidu-PCS, Commands, iFit(Theme), OpenClash, QOS, Serverchan, Flow Offload, 
  + uHTTPd, Unblockmusic, UU Game Booster, VerySync(limited), KMS Server, VSFTPD, 
  + Wifi Schedule, WOL, XunLei Accelerator, ZeroTier

- 每48小时自动更新, 支持发布 & 修改源码时自动更新
- Update every 48 hours, support auto-update when source codes are being published or altered

- 发布的固件 & 工作流将被保留最新的7个版本(2周)
- Releases & WorkFlows will be kept with the 7 latest versions (2 weeks)

----

- 目标系统 / Target: X86-64
- 引导程序 / Boot Loader: EFI & BIOS
- 内核大小 / Kernel Size: 16 mb
- 磁盘大小 / Rom Size: 1024 mb
+ 默认 IP / Default IP: 192.168.31.2
+ 默认用户名 / Default Username: root
+ 默认密码 / Default Password: password

----
- 考虑到img文件过大，建议从工作流中下载对应的zip文件后解压(~ 110 mb) 
- Considering the size of the img file, it is recommended to download the corresponding zip file from the workflow and unzip it (~ 110mb)
