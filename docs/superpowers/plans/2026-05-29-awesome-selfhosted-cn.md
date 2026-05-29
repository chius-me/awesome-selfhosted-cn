# awesome-selfhosted-cn Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Initialize the `awesome-selfhosted-cn` repository with a structured, Chinese-ecosystem focused README.

**Architecture:** A single `README.md` file featuring a header, introduction, tagged categories (NAS, Media, Proxy, Downloaders, Blogs), and contribution guidelines.

**Tech Stack:** Markdown

---

### Task 1: Initialize README Structure and Header

**Files:**
- Modify: `/home/chius/repo/github/awesome-selfhosted-workspace/awesome-selfhosted-cn/README.md`

- [ ] **Step 1: Write initial README structure**

```markdown
# Awesome Self-Hosted CN

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

一个专为中国 HomeLabber 整理的自托管（Self-hosted）项目精选列表。

与原版 [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) 不同，本项目并非直接镜像，而是优先收录：
- 🇨🇳 国内开发者主导的优秀项目
- 🔥 在国内网络环境下极其流行、易用的项目
- 🌐 拥有高质量中文本地化支持的项目

## 标签说明 (Tags Legend)
- `[🇨🇳 国产]` - 国内团队或个人开发
- `[🔥 热门]` - 社区中非常流行、讨论度高
- `[🌐 汉化]` - 官方原生支持中文或有优秀的中文汉化分支

## 目录 (Table of Contents)
- [NAS 系统与面板 (NAS Systems & Dashboards)](#nas-系统与面板-nas-systems--dashboards)
- [媒体中心与刮削 (Media Centers & Scrapers)](#媒体中心与刮削-media-centers--scrapers)
- [网络、代理与穿透 (Networking, Proxies & Tunnels)](#网络代理与穿透-networking-proxies--tunnels)
- [下载器与文件分享 (Downloaders & File Sharing)](#下载器与文件分享-downloaders--file-sharing)
- [博客、笔记与 Wiki (Blogs, Notes & Wikis)](#博客笔记与-wiki-blogs-notes--wikis)

---

## 贡献指南 (Contributing)
欢迎提交 PR！请确保推荐的项目符合本列表的初衷（适合国内用户）。添加新项目时，请保持分类内的**字母顺序**排列，并正确使用上述标签。
```

- [ ] **Step 2: Commit changes**

```bash
cd /home/chius/repo/github/awesome-selfhosted-workspace/awesome-selfhosted-cn
git add README.md
git commit -m "feat: initialize awesome-selfhosted-cn README structure"
```

### Task 2: Populate Initial Categories

**Files:**
- Modify: `/home/chius/repo/github/awesome-selfhosted-workspace/awesome-selfhosted-cn/README.md` (Append content before the Contributing section)

- [ ] **Step 1: Append category content**

Modify `README.md` to insert the following content right above the `## 贡献指南 (Contributing)` section:

```markdown
## NAS 系统与面板 (NAS Systems & Dashboards)
- [1Panel](https://github.com/1Panel-dev/1Panel) - 现代化、开源的 Linux 服务器运维管理面板。 `[🇨🇳 国产]` `[🔥 热门]`
- [CasaOS](https://github.com/IceWhaleTech/CasaOS) - 一个简单、易用、优雅的开源家庭云系统。 `[🇨🇳 国产]` `[🔥 热门]`

## 媒体中心与刮削 (Media Centers & Scrapers)
- [Jellyfin](https://github.com/jellyfin/jellyfin) - 免费软件媒体系统，Emby 的分支，无任何高级功能限制。 `[🌐 汉化]` `[🔥 热门]`
- [MoviePilot](https://github.com/jxxghp/MoviePilot) - 基于 NASTool 重构的基于 PT 站的自动化观影应用。 `[🇨🇳 国产]` `[🔥 热门]`

## 网络、代理与穿透 (Networking, Proxies & Tunnels)
- [frp](https://github.com/fatedier/frp) - 一个专注于内网穿透的高性能的反向代理应用，支持 TCP、UDP、HTTP、HTTPS 等多种协议。 `[🇨🇳 国产]` `[🔥 热门]`
- [NPS](https://github.com/ehang-io/nps) - 一款轻量级、高性能、功能强大的内网穿透代理服务器。 `[🇨🇳 国产]`
- [Tailscale](https://github.com/tailscale/tailscale) - 基于 WireGuard 的零配置 VPN 组网工具。 `[🔥 热门]`

## 下载器与文件分享 (Downloaders & File Sharing)
- [Alist](https://github.com/alist-org/alist) - 一个支持多种存储，支持网页浏览和 WebDAV 的文件列表程序。 `[🇨🇳 国产]` `[🔥 热门]`
- [Aria2](https://github.com/aria2/aria2) - 轻量级多协议和多源命令行下载工具。 `[🌐 汉化]`

## 博客、笔记与 Wiki (Blogs, Notes & Wikis)
- [Halo](https://github.com/halo-dev/halo) - 强大易用的开源建站工具。 `[🇨🇳 国产]` `[🔥 热门]`
- [SiYuan](https://github.com/siyuan-note/siyuan) - 融合块、大纲和双向链接的本地优先个人知识管理系统。 `[🇨🇳 国产]`
```

- [ ] **Step 2: Commit changes**

```bash
cd /home/chius/repo/github/awesome-selfhosted-workspace/awesome-selfhosted-cn
git add README.md
git commit -m "feat: populate initial project categories"
```
