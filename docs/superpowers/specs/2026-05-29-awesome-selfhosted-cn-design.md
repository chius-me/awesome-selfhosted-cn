# Design Specification: awesome-selfhosted-cn

## 1. Overview
This project aims to build a Chinese counterpart to the popular `awesome-selfhosted` repository. Instead of a direct mirror, it is a curated ecosystem specifically tailored for Chinese HomeLabbers. It highlights projects that are either developed by Chinese developers, have excellent Chinese localization, or are particularly popular/useful within the domestic network environment.

## 2. Document Structure (Architecture)
The `README.md` will be structured as follows:
- **Header**: Project Title and standard Awesome list badges (e.g., "Awesome", "PRs Welcome").
- **Introduction**: A brief philosophy stating the curated nature of this list and its focus on the Chinese homelab ecosystem.
- **Tags Legend**: 
  - `[🇨🇳 国产]` - Chinese Origin (developed domestically).
  - `[🔥 热门]` - Popular (widely used in the community).
  - `[🌐 汉化]` - Good Chinese UI/Translation.
- **Table of Contents**: Linked to the respective categories.
- **Category Sections**: The core content, organized by use case (e.g., NAS & Dashboards, Media Centers).

## 3. Categories & Entry Format (Components)
The initial MVP will cover the following categories:
- NAS Systems & Dashboards (e.g., CasaOS, 1Panel)
- Media Centers & Scrapers (e.g., MoviePilot, Nas-Tools, Jellyfin)
- Networking, Proxies & Tunnels (e.g., Frp, NPS, Tailscale)
- Downloaders & File Sharing (e.g., Aria2, Xunlei, Alist)
- Blogs, Notes & Wikis (e.g., Halo, SiYuan)

Each entry will follow a strict format:
`- [Project Name](Link) - Short Description in Chinese. Tags.`
*Example*:
`- [CasaOS](https://github.com/IceWhaleTech/CasaOS) - 简单、易用、优雅的开源家庭云系统。 [🇨🇳 国产] [🔥 热门]`

## 4. Contribution Guidelines (Data Flow)
A section at the bottom explaining how to contribute:
- Submissions must be suitable for Chinese users.
- New entries must be alphabetized within their category.
- Contributors must maintain the specific tag format for consistency.
