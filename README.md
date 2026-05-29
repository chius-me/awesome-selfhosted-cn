# Awesome Self-Hosted CN

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

一个专为中国 HomeLabber 整理的自托管项目精选列表。

与原版 [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) 不同，本项目并非其中文译版，而是优先收录：
- 🇨🇳 国内开发者主导的优秀项目
- 🔥 在国内网络环境下极其流行、易用的项目
- 🌐 拥有高质量中文本地化支持的项目

## 目录
- [操作系统](#操作系统)
- [媒体影音](#媒体影音)
- [网络](#网络)
- [文件管理](#文件管理)
- [下载](#下载)
- [密码管理](#密码管理)
- [笔记与文档](#笔记与文档)
- [书签](#书签)
- [工具](#工具)
- [监控与运维](#监控与运维)
- [智能家居](#智能家居)
- [AI](#ai)
- [开发与部署](#开发与部署)
- [博客与社交](#博客与社交)

---

## 操作系统
- [fnOS](https://www.fnnas.com/) - 国产优秀 NAS 系统，界面类群晖、简单易用，内置丰富的国情应用。
- [ImmortalWrt](https://github.com/immortalwrt/immortalwrt) - 针对国内网络环境深度优化的 OpenWrt 分支，软件包丰富，运行稳定。
- [iStoreOS](https://github.com/istoreos/istoreos) - 基于 OpenWrt 的轻量级路由与 NAS 操作系统，界面友好，内置应用商店。
- [OpenMediaVault](https://github.com/openmediavault/openmediavault) - 基于 Debian 的开源轻量级 NAS system，模块化设计，适合旧硬件榨干性能。
- [OpenWrt](https://github.com/openwrt/openwrt) - 经典的开源嵌入式 Linux 路由器系统，拥有极强的高级路由、防火墙和插件扩展能力。
- [Proxmox VE](https://github.com/proxmox) - 企业级开源虚拟化平台，整合 KVM 虚拟机和 LXC 容器，提供强大直观的 Web 管理界面。
- [TrueNAS](https://github.com/truenas) - 基于强大的 ZFS 文件系统的专业存储/NAS 操作系统，提供极高的数据安全性与保护。
- [Unraid](https://github.com/unraid) - 灵活易用的非传统 RAID 存储与虚拟化系统，支持阵列中不同容量硬盘混用，Docker/虚拟机体验极佳。

## 媒体影音
- [AutoBangumi](https://github.com/EstrellaXD/Auto_Bangumi) - 专为新番设计的全自动追番工具，配合 RSS 实现自动下载、重命名并推送刮削。
- [bili-sync](https://github.com/amtoaer/bili-sync) - 轻量、无痛的 B 站视频与番剧本地同步工具，自动下载追番更新并进行归档。
- [BililiveRecorder](https://github.com/BililiveRecorder/BililiveRecorder) - 功能强大、多平台支持的 B 站直播间自动化录制工具，支持切片及开播提醒。
- [Immich](https://github.com/immich-app/immich) - 自托管的照片与视频备份管理平台，界面与操作体验对标 Google Photos，内置高效的 AI 面部识别。
- [Jellyfin](https://github.com/jellyfin/jellyfin) - 免费开源的自建媒体服务器（Emby 分支），100% 免费且无任何高级功能限制，支持强大的硬件解码。
- [Komga](https://github.com/gotson/komga) - 专为漫画、电子书量身定制的自托管媒体服务器，支持多端阅读进度云同步。
- [MetaTube](https://github.com/metatube-community/jellyfin-plugin-metatube) - 专为中文/日韩特种影视设计的 Jellyfin 元数据刮削插件，解决小姐姐刮削难题。
- [MeTube](https://github.com/alexta69/metube) - 基于 yt-dlp 的现代化音视频下载 Web 界面，轻松一键下载 YouTube、Bilibili 等平台的视频。
- [MoviePilot](https://github.com/jxxghp/MoviePilot) - 新一代基于 PT/BT 的自动化观影闭环管理系统，集检索、订阅、下载、整理、刮削、洗版于一体。
- [Navidrome](https://github.com/navidrome/navidrome) - 自托管轻量级音乐流媒体服务器，兼容 Subsonic API，支持绝大多数第三方音乐客户端。
- [PhotoPrism](https://github.com/photoprism/photoprism) - 基于 TensorFlow 的 AI 照片管理服务，支持高精度自动标签、地理位置聚类和人脸检索。

## 网络
- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) - 全网广告拦截、有害网站拦截与本地 DNS 防污染服务器，保护全家终端隐私。
- [Anubis](https://github.com/TecharoHQ/anubis) - 轻量高效的防 AI 爬虫流量安全防火墙，根据特征请求精准拦截训练爬虫。
- [Cloudflared](https://github.com/cloudflare/cloudflared) - Cloudflare Tunnel 客户端，安全、免公网 IP 地将局域网内的 Web 服务安全暴露。
- [DDNS-Go](https://github.com/jeessy2/ddns-go) - 极简、好用的动态域名解析（DDNS）客户端，支持多接口及阿里、腾讯、CF 等主流域名服务商。
- [frp](https://github.com/fatedier/frp) - 高性能、专注于内网穿透的反向代理工具，支持多协议的流量安全转发。
- [Lucky](https://github.com/gdy666/lucky) - 专为国人家庭大内网设计的网络神器，整合 DDNS、Web 反代、端口转发、内置内网穿透（Stun/IPv6）以及 WOL 唤醒。
- [MetaCubeXD](https://github.com/MetaCubeX/metacubexd) - 针对 Mihomo/Clash-Meta 内核的现代化 Web 监控与控制面板。
- [Mihomo](https://github.com/MetaCubeX/mihomo) - Clash-Meta 分支的强力继承者，基于高度可定制规则的多协议网络代理内核。
- [NetBird](https://github.com/netbirdio) - 基于 WireGuard 的开源零信任、全网状（Full Mesh）虚拟局域网和内网组网平台。
- [Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager) - 极简可视化的 Nginx 反向代理和免费 Let's Encrypt SSL 证书自动申请与续期管理面板。
- [NPS](https://github.com/ehang-io/nps) - 带有强劲 Web 页面、配置简单但功能齐全的高性能内网穿透/代理服务器。
- [OpenClash](https://github.com/vernesong/OpenClash) - 在 OpenWrt/iStoreOS 路由器下使用的高性能规则网络代理客户端。
- [Tailscale](https://github.com/tailscale) - 基于 WireGuard 协议构建的傻瓜式免配置虚拟局域网、跨域安全内网互联工具。
- [ZeroTier](https://github.com/zerotier) - 采用软件定义网络（SDN）技术的自组网穿透工具，轻松将分布在世界各地的物理设备连入同一虚拟局域网。

## 文件管理
- [Alist](https://github.com/alist-org/alist) - 极其强大的多云盘文件列表程序，支持挂载几十种网盘和本地存储，并统一提供 WebDAV、Aria2 离线下载。
- [MinIO](https://github.com/minio/minio) - 高性能、高可用、兼容 Amazon S3 API 的轻量化自托管对象存储。
- [OpenList](https://github.com/OpenListTeam/OpenList) - 国人主导的 Alist 开源社区分支，注重性能优化和自定义聚合。
- [Syncthing](https://github.com/syncthing/syncthing) - 去中心化、安全的端到端文件同步工具，直接在设备间点对点安全传输，不依赖中心化服务器。

## 下载
- [Aria2](https://github.com/aria2/aria2) - 轻量、支持多协议（HTTP、FTP、BT、Magnet）的高速多源命令行下载工具，占用资源极低。
- [qBittorrent](https://github.com/qbittorrent/qBittorrent) - 开源免费的高性能 BT/PT 下载客户端，内置强劲的搜索引擎、RSS 订阅和 Web UI 远程管理。

## 密码管理
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - 采用 Rust 重写的非官方 Bitwarden 轻量后端，资源占用微乎其微，完美解锁原版所有高级付费功能。

## 笔记与文档
- [Excalidraw](https://github.com/excalidraw/excalidraw) - 手绘艺术风格的在线白板与流程图绘制工具，拥有极佳的移动端适配和多人实时协作体验。
- [Memos](https://github.com/usememos/memos) - 基于 SQLite 数据库构建的超轻量、极简个人随笔与闪念胶囊（类似微博/Twitter），支持 Markdown 格式。
- [Outline](https://github.com/outline/outline) - 高颜值、现代化的团队知识库与 Wiki 系统，界面精美绝伦，支持 Markdown 实时协作和全文检索。

## 书签
- [Linkding](https://github.com/sissbruecker/linkding) - 轻量化、速度极快、不掺杂任何多余设计的自托管个人书签管理器，支持高度可定制的标签与批量搜索。

## 工具
- [Glance](https://github.com/glanceapp/glance) - 现代极简的个人聚合首页与仪表盘，将 RSS、天气、书签和网络状态汇总在单张精美卡片中。
- [it-tools](https://github.com/CorentinTh/it-tools) - 专为开发者和技术人设计的超级在线工具箱，内置上百种编码转换、加密调试和常用实用算法。
- [Kiwix](https://github.com/kiwix) - 离线网络百科阅读器，支持下载维基百科、StackOverflow 等离线数据库，非常适合完全断网的环境。
- [Mealie](https://github.com/mealie-recipes/mealie) - 极其精美的自托管食谱与每周饮食计划管理系统，支持全自动网络食谱配方解析与购物清单。
- [Reactive-Resume](https://github.com/AmruthPillai/Reactive-Resume) - 强大且完全免费的自建个人简历设计与生成器，支持多模板切换、自定义组件和实时预览 PDF。
- [SearXNG](https://github.com/searxng/searxng) - 强力保护隐私、绝对不追踪用户痕迹的元搜索引擎，汇聚并聚合各大搜索引擎的干净结果。
- [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - 功能极其强大、完全本地化的自建 PDF 处理器，支持合并、拆分、OCR 识别、格式转换、去水印等一切 PDF 处理。

## 监控与运维
- [1Panel](https://github.com/1Panel-dev/1Panel) - 新一代现代化、高颜值的国产 Linux 面板，通过 Docker 轻松一键安全地安装和维护各种 HomeLab 应用，支持便捷的容器化、备份及证书管理。
- [Grafana](https://github.com/grafana/grafana) - 开源的可视化与监控面板神器，能完美地将 Prometheus、InfluxDB 或数据库中的监控指标转化为绝佳图表。
- [Portainer](https://github.com/portainer/portainer) - 轻量易用的 Docker/Kubernetes 远程图形化容器管理与监控看板。
- [Prometheus](https://github.com/prometheus/prometheus) - 经典的云原生生态时序数据库和高可用系统级监控告警引擎，监控一切底层硬件与系统性能。
- [Traccar](https://github.com/traccar/traccar) - 功能成熟的 GPS 实时位置追踪平台，支持上千种硬件定位设备以及各类手机客户端的无痛自建。
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - 极高颜值且简单易用的自托管服务状态监控与看板，支持飞书、钉钉、微信、Telegram 和邮件的多种低延迟告警。

## 智能家居
- [Home Assistant](https://github.com/home-assistant/core) - 无冕之王般的开源智能家居平台，能将千百种不同协议、品牌和厂商的智能硬件统统接入一个平台，实现极致的高级联动。

## AI
- [Cherry Studio](https://github.com/cherry-studio/cherry-studio) - 超高颜值、国人主导的多模型 AI 桌面客户端，完美适配自托管 AI 网关中转和各类本地开源模型。
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - 基于节点工作流的高自由度 AI 图像与艺术生成界面，是目前生成 Stable Diffusion 工业级图像的最佳平台。
- [Dify](https://github.com/langgenius/dify) - 开箱即用的可视化大模型（LLM）应用开发平台，支持高级 RAG、可视化工作流和 Agent 智能代理编排。
- [Hermes Agent](https://github.com/NousResearch/hermes-agent) - Nous Research 出品的强大通用 AI 智能体框架，为未来自动化开发提供无限想象。
- [LobeHub](https://github.com/lobehub/lobe-chat) - 现代化、支持自定义丰富插件和模型的下一代个人 AI 聊天客户端。
- [n8n](https://github.com/n8n-io/n8n) - 可自托管的低代码自动化工作流编排平台，可轻松接入各类主流 AI 模型与互联网应用服务。
- [New API](https://github.com/songquanpeng/new-api) - 对标并深度优化上游 One API 的大模型 API 中转、分发与多商户计费管理神器。
- [Open WebUI](https://github.com/open-webui/open-webui) - 目前市面上功能最完整、界面最像 ChatGPT 的自建大语言模型 Web 界面，完美适配 Ollama 离线模型。
- [OpenClaw](https://github.com/openclaw/openclaw) - 自托管、高拓展性的个人 AI 语音和即时通信助手。

## 开发与部署
- [Argo CD](https://github.com/argoproj/argo-cd) - Kubernetes 声明式 GitOps 持续交付平台，实现应用基础设施状态与 Git 仓库的自动同步。
- [Authentik](https://github.com/goauthentik/authentik) - 一站式、高可用的开源身份与访问安全提供商，支持 SSO、LDAP、SAML 与多因素认证（MFA）。
- [CloudBeaver](https://github.com/dbeaver/cloudbeaver) - 基于 Web 端的专业数据库统一管理面板，免装客户端即可直连 PostgreSQL、MySQL、ClickHouse 等。
- [Forgejo](https://forgejo.org) - 由社区主导、致力于完全独立自由的 Gitea 开源轻量级 Git 代码托管平台分支。
- [Gitea](https://github.com/go-gitea/gitea) - 性能优异、占用极其省省的轻量级自托管 Git 服务，全能型代码仓库。
- [GitLab](https://about.gitlab.com/) - 功能无所不包的顶级企业级 DevOps 协同平台，内置极其强大的 CICD 流程。
- [itzg/minecraft-server](https://github.com/itzg/docker-minecraft-server) - Docker 经典 Minecraft 我的世界私服一键部署端，高度自动化，支持多版本模组。
- [K3s](https://github.com/k3s-io/k3s) - 专为边缘、轻量级硬件、HomeLab 打造的极简轻量级 K8s 运行分发版。
- [NapCat](https://github.com/NapNeko/NapCatQQ) - 无需桌面、无扫码负担的轻量级 Linux QQ 机器人运行框架。

## 博客与社交
- [Ghost](https://github.com/TryGhost/Ghost) - 基于 Node.js 构建的专业级博客、现代媒体订阅与自媒体内容变现平台。
- [GoToSocial](https://gotosocial.org/) - 采用 Go 编写的极度轻量、资源友好的 ActivityPub 自托管社交实例，可与 Mastodon 完美实现全网联邦。
- [Halo](https://github.com/halo-dev/halo) - 国产新一代精美建站与个人博客系统，支持模块化插件与高度可定制模板。
- [Hexo](https://github.com/hexojs/hexo) - 经典的 Node.js 开源静态博客生成框架，主题和插件生态成熟丰富。
- [Hugo](https://github.com/gohugoio/hugo) - 采用 Go 语言开发的极速静态网站生成器，多线程极速渲染数万页面。
- [SiYuan](https://github.com/siyuan-note/siyuan) - 本地优先、支持双向链接与块级（Block-level）富文本的高级个人知识库管理系统。
- [Typecho](https://github.com/typecho/typecho) - 极简主义、低资源消耗的 PHP 开源个人博客程序，轻量优雅的极致之选。
- [WordPress](https://github.com/WordPress/WordPress) - 全球使用最广泛、老牌且生态无比繁荣的开源 CMS 内容与博客平台。

## 贡献指南 (Contributing)
欢迎提交 Pull Request！新项目请保持分类内字母顺序排列，并附上简要描述。
