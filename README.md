<h1 align="center">Codex Mate</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c8415a50-d0af-49c5-b10e-cf5807c9dc58" width="460" alt="Codex Mate menu bar preview" />
</p>

<p align="center">
  一个轻量、可信赖的 Codex 余量查看器。<br />
  在 macOS 菜单栏查看 <strong>5 小时余量</strong>、<strong>7 天余量</strong> 和 <strong>tokens 统计</strong>，并通过 <strong>CloudKit</strong> 同步到 iPhone、Apple Watch 与 Widget。
</p>

<p align="center">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-14%2B-111111?style=for-the-badge&logo=apple&logoColor=white" />
  <img alt="SwiftUI" src="https://img.shields.io/badge/SwiftUI-Native-0A84FF?style=for-the-badge&logo=swift&logoColor=white" />
  <img alt="CloudKit" src="https://img.shields.io/badge/CloudKit-iCloud%20Sync-34C759?style=for-the-badge&logo=apple&logoColor=white" />
  <img alt="Privacy" src="https://img.shields.io/badge/Privacy-Local%20%2B%20Private%20iCloud-6E7781?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://github.com/ElvishR/CodexMate/releases"><img alt="Download for macOS" src="https://img.shields.io/badge/Download-macOS%20Release-1F6FEB?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

> [!IMPORTANT]
> 所有数据仅保存在你的设备本地和你的私人 iCloud 私有数据库中。开发者不读取、不上传、不持有任何使用数据。

## 核心功能

| 功能 | 说明 |
| --- | --- |
| 5 小时余量 | 在 macOS 菜单栏直接显示当前 5 小时剩余额度 |
| 7 天余量 | 在主界面查看最近 7 天额度状态与重置时间 |
| tokens 统计 | 统计每天、每周、每月、总计的 tokens 使用量 |
| 多端同步 | 通过 CloudKit 同步到 iOS App、Apple Watch 和 Widget |
| 隐私优先 | 数据只保存在本地与私人 iCloud，不经过开发者服务器 |

## 平台说明

| 平台 | 作用 |
| --- | --- |
| macOS | 真实采集入口，负责读取额度、展示菜单栏状态并写入 CloudKit |
| iOS | 读取 macOS 已同步的数据，作为移动端查看入口 |
| Apple Watch / Widget | 快速查看最近同步的余量信息 |

## 下载方式

### macOS 端

点击下载：

[Codex Mate 下载](https://github.com/ElvishR/CodexMate/releases/)

<p align="center">
  <img src="https://github.com/user-attachments/assets/7f75caf1-0889-4191-bbba-d07a16087c06" width="1000" alt="Codex Mate macOS screenshots" />
</p>

### iOS 端

在 App Store 搜索 **Codex Mate** 下载。  
iOS 端显示的数据来自 macOS 端同步到 iCloud 的最新结果。

<p align="center">
  <img src="https://github.com/user-attachments/assets/05b5d5a5-dc3c-4778-9baf-278da93f683f" width="1000" alt="Codex Mate iOS screenshots" />
</p>

## 适合谁

- 想在菜单栏快速查看 Codex 余量的人
- 需要在 iPhone、Apple Watch 或 Widget 上同步查看额度的人
- 在意隐私，不希望把使用数据交给第三方服务的人

## 一句话说明

Codex Mate 专注做一件事：把你的 Codex 余量和 tokens 使用情况，用原生、轻量、私密的方式同步到你自己的设备上。
