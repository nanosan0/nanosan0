<!-- nanosan0 · 个人主页 -->
<!-- 这个文件就是主页的全部内容：纯 Markdown + 几个外部图片服务。没有任何隐藏配置。 -->
<!-- 想改配色就改下面的 color= 参数；想删某个板块，删掉对应的段落即可。 -->
<!-- 2026-10-28 整理：补上 VIDAA 电视恢复包 / HP 迷你主机 EFI / 云原神助手，原有板块结构未动。 -->

<div align="center">

![banner](https://capsule-render.vercel.app/api?type=waving&color=0:0d7d74,50:1f6feb,100:1c1917&height=200&section=header&text=nanosan0&fontColor=ffffff&fontSize=64&fontAlignY=36&desc=%E9%BB%91%E8%8B%B9%E6%9E%9C%20%C2%B7%20OpenCore%20%C2%B7%20%E6%8A%98%E8%85%BE%E8%AE%B0%E5%BD%95&descAlignY=58&descSize=18&animation=fadeIn)

[![打字机](https://readme-typing-svg.demolab.com?font=Noto+Sans+SC&weight=500&size=22&duration=3200&pause=700&color=0d7d74&center=true&vCenter=true&width=760&lines=%E6%8A%8A%E6%AF%8F%E4%B8%80%E8%A1%8C%20OpenCore%20%E9%85%8D%E7%BD%AE%E9%83%BD%E8%BF%BD%E6%BA%AF%E5%88%B0%E5%AE%98%E6%96%B9%E6%96%87%E6%A1%A3;B760M%20%2B%20i5-12400F%20%2B%20RTX%204060%20%E8%B7%91%20macOS%2026;%E9%A1%BA%E6%89%8B%E4%B9%9F%E6%8A%98%E8%85%BE%E7%94%B5%E8%A7%86%E5%8E%BB%E8%86%A8%E8%83%80%E3%80%81%E8%BF%B7%E4%BD%A0%E4%B8%BB%E6%9C%BA%E8%A3%85%20macOS;%E4%B8%8D%E6%8A%84%E5%88%AB%E4%BA%BA%E7%9A%84%20EFI%EF%BC%8C%E4%B9%9F%E4%B8%8D%E7%95%99%E6%9D%A5%E8%B7%AF%E4%B8%8D%E6%98%8E%E7%9A%84%E9%94%AE)](#)

<a href="https://github.com/nanosan0"><img src="https://hits.sh/github.com/nanosan0.svg?style=flat-square&label=%E4%B8%BB%E9%A1%B5%E8%AE%BF%E9%97%AE&color=0d7d74&labelColor=555555" alt="主页访问"></a>
<a href="https://github.com/nanosan0?tab=followers"><img src="https://img.shields.io/github/followers/nanosan0?label=%E5%85%B3%E6%B3%A8&style=flat-square&color=1f6feb" alt="关注"></a>
<a href="https://github.com/nanosan0?tab=repositories"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fnanosan0&query=public_repos&label=%E4%BB%93%E5%BA%93&style=flat-square&color=1c1917" alt="仓库数"></a>

</div>

---

### 🎯 我在做什么

把一台 **B760M + i5-12400F + RTX 4060** 的机器装成 macOS 26，
再把每一条 OpenCore 配置翻回官方文档核对一遍。

顺手也折腾别的：电视去膨胀、迷你主机装 macOS、把「抢排队」这种破事交给程序。
原则只有一条 —— **不抄别人的 EFI，也不留来路不明的键**。

不是开发者，纯粹爱折腾。折腾出来的东西都放在下面。

---

### 🚀 主力项目 — B760M 黑苹果 EFI

<div align="center">

[![release](https://img.shields.io/github/v/release/nanosan0/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi?style=for-the-badge&label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC&color=0d7d74)](https://github.com/nanosan0/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi/releases)
[![downloads](https://img.shields.io/github/downloads/nanosan0/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi/total?style=for-the-badge&label=%E6%80%BB%E4%B8%8B%E8%BD%BD&color=0E8A16)](https://github.com/nanosan0/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi/releases)
[![stars](https://img.shields.io/github/stars/nanosan0/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi?style=for-the-badge&label=%E6%98%9F%E6%A0%87&color=FFD700)](https://github.com/nanosan0/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi)

</div>

**ASUS TX GAMING B760M WIFI D4 · i5-12400F · AX201 · RTX 4060 · OpenCore 1.0.8**

- 通过官方 `ocvalidate` 1.0.8 校验：**No issues found**
- 6 个 SSDT、5 个 UEFI 驱动、22 个 kext —— 每一项都写了「为什么是这么配」
- 记录了两个真实故障的修法：`FixupAppleEfiImages` 缺失，以及 **升级 macOS 26 后文件保险箱（FileVault）正确密码也解不开**
- 说明文档中文 / English 双语，网页版可一键切换

[📖 说明文档](https://nanosan0.github.io/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi/) · [🌐 English](https://nanosan0.github.io/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi/?lang=en) · [⬇️ 下载 v1.0.1](https://github.com/nanosan0/B760m-i5-12400f-AX201-RTX4060-Hackintosh-oc-efi/releases/tag/v1.0.1)

---

### 🧩 最近在折腾

| 项目 | 是什么 | 值得一看的点 |
| :--- | :--- | :--- |
| **[`vidaa-tv-restore-kit`](https://github.com/nanosan0/vidaa-tv-restore-kit)**<br><img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell"> | 海信 VIDAA 电视（MT9632 / Android 9）去膨胀 + Apple TV 风格桌面**一键恢复包** | 禁 29 个厂商包、换自制桌面接管 Home 键；全程只走 ADB，**每一步可逆**，不刷机不 root |
| **[`hp-elitedesk-800-g4-dm-efi`](https://github.com/nanosan0/hp-elitedesk-800-g4-dm-efi)**<br><img src="https://img.shields.io/badge/OpenCore-0d7d74?style=flat-square" alt="OpenCore"> | HP EliteDesk 800 G4 DM 35W 的引导配置（Q370 / i3-8100 / UHD 630，伪装 `iMac20,1`） | 从实机运行配置导出；三码已抹、EDID 硬编码这些**必须自己改的定制点全部写明** |
| **[`Genshin-Cloud-Auto`](https://github.com/nanosan0/Genshin-Cloud-Auto)**<br><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> | 云·原神自动化助手：定时开客户端、识图点「开始游戏」、蹲过排队 | Tkinter GUI + OpenCV 模板匹配，不依赖固定坐标；微信 / 企微 / 邮箱三通道推送 |

---

### 🗂 更早的仓库

| 仓库 | 是什么 |
| --- | --- |
| [`Acer-A315-53G-5790-forc-mac-os`](https://github.com/nanosan0/Acer-A315-53G-5790-forc-mac-os) | 宏碁 A315-53G 的 OpenCore 配置（2022 年的早期折腾） |
| [`vercel-onemanager`](https://github.com/nanosan0/vercel-onemanager) | OneManager 的 Vercel 部署码源 |

<details>
<summary>fork 来的（<code>macos-iso-builder</code> / <code>hackintosh-skills</code> / <code>yt6801-for-macOS</code> 等）</summary>

| 仓库 | 是什么 |
| --- | --- |
| [`macos-iso-builder`](https://github.com/nanosan0/macos-iso-builder) | 用 GitHub Actions 直接从 Apple 服务器拉取并生成 macOS 安装镜像 |
| [`hackintosh-skills`](https://github.com/nanosan0/hackintosh-skills) | 黑苹果相关的技能 / 脚本集合 |
| [`yt6801-for-macOS`](https://github.com/nanosan0/yt6801-for-macOS) | 裕太（Motorcomm）YT6801 网卡的 DriverKit 驱动，macOS 15+ |
| [`WindowsSimplify`](https://github.com/nanosan0/WindowsSimplify) | Windows 精简项目 |
| [`YesPlayMusic-windows-on-arm`](https://github.com/nanosan0/YesPlayMusic-windows-on-arm) | 网易云第三方播放器的 Windows on ARM 版本 |

</details>

完整列表 → <https://github.com/nanosan0?tab=repositories>

---

### 🛠 我在用的

<p align="center">
  <img src="https://img.shields.io/badge/OpenCore-1.0.8-0d7d74?style=flat-square" alt="OpenCore">
  <img src="https://img.shields.io/badge/macOS-26%20Tahoe-1c1917?style=flat-square&logo=apple&logoColor=white" alt="macOS">
  <img src="https://img.shields.io/badge/Windows-Win11-0078D6?style=flat-square&logo=windows11&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/NVIDIA-RTX%204060-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
</p>

---

### 📊 数据

<div align="center">

<!-- 打卡图：按 commit 统计。刚建号时数字会比较小，正常。不想要就删掉这一节。 -->
<a href="https://github.com/nanosan0"><img src="https://streak-stats.demolab.com?user=nanosan0&locale=zh_CN&theme=default&hide_border=true&date_format=Y.n.j&ring=0d7d74&fire=0d7d74&currStreakLabel=0d7d74&sideLabels=1f6feb&dates=555555" alt="提交连续天数" width="70%" /></a>

<br><br>

<!-- 蛇吃贡献格子：由 .github/workflows/snake.yml 每天生成到 output 分支。
     第一次要在 Actions 里手动跑一次（Run workflow），否则这里是裂图。 -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nanosan0/nanosan0/output/github-contribution-grid-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/nanosan0/nanosan0/output/github-contribution-grid-snake.svg" alt="蛇吃贡献格子" width="100%">
</picture>

</div>

---

<div align="center">

<sub>
徽章与统计均来自第三方服务（shields.io / hits.sh / streak-stats / capsule-render），数据缓存约 1 小时；
蛇吃贡献格子每天 08:15 由 Actions 重新生成。
本页只是 <code>nanosan0/nanosan0</code> 这个仓库的 README，没有别的魔法。
</sub>

![footer](https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:1c1917,50:1f6feb,100:0d7d74)

</div>
