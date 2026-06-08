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
- [fnOS](https://www.fnnas.com/) - 国产 NAS 系统，界面媲美群晖，内置丰富国情化应用。
- [ImmortalWrt](https://github.com/immortalwrt/immortalwrt) - 针对国内网络深度优化的 OpenWrt 分支，包源丰富，运行稳定。
- [iStoreOS](https://github.com/istoreos/istoreos) - 基于 OpenWrt 的轻量路由与 NAS 系统，界面友好，内置应用商店。
- [OpenMediaVault](https://github.com/openmediavault/openmediavault) - 基于 Debian 的开源 NAS 系统，模块化设计，适合旧硬件改装。
- [OpenWrt](https://github.com/openwrt/openwrt) - 经典开源嵌入式路由系统，具备高级路由、防火墙与丰富插件生态。
- [Proxmox VE](https://github.com/proxmox) - 企业级开源虚拟化平台，整合 KVM 与 LXC，提供直观的 Web 管理界面。
- [TrueNAS](https://github.com/truenas) - 基于 ZFS 的专业存储/NAS 系统，以数据安全性与完整性著称。
- [Unraid](https://github.com/unraid) - 灵活的非传统 RAID 存储与虚拟化系统，支持不同容量硬盘混用，Docker 和虚拟机体验出色。

## 媒体影音
- [AutoBangumi](https://github.com/EstrellaXD/Auto_Bangumi) - 专为新番设计的全自动追番工具，配合 RSS 实现自动下载、重命名并推送刮削。
- [bili-sync](https://github.com/amtoaer/bili-sync) - 轻量无痛的 B 站视频与番剧本地同步工具，自动下载追更并归档。
- [BililiveRecorder](https://github.com/BililiveRecorder/BililiveRecorder) - 全平台 B 站直播间自动录制工具，支持切片与开播提醒。
- [Immich](https://github.com/immich-app/immich) - 自托管照片与视频备份平台，体验对标 Google Photos，内置 AI 人脸识别。
- [Jellyfin](https://github.com/jellyfin/jellyfin) - 免费开源自建媒体服务器（Emby 分支），无高级功能限制，支持硬件解码。
- [Komga](https://github.com/gotson/komga) - 专为漫画与电子书打造的自托管媒体服务器，支持多端阅读进度同步。
- [MetaTube](https://github.com/metatube-community/jellyfin-plugin-metatube) - Jellyfin 元数据刮削插件，专治中文/日韩影视刮削难题。
- [MeTube](https://github.com/alexta69/metube) - 基于 yt-dlp 的现代化音视频下载 Web 界面，一键下载 YouTube、Bilibili 等平台视频。
- [MoviePilot](https://github.com/jxxghp/MoviePilot) - 基于 PT/BT 的自动化观影闭环系统，集检索、订阅、下载、整理、刮削、洗版于一体。
- [Navidrome](https://github.com/navidrome/navidrome) - 轻量级自托管音乐流媒体服务器，兼容 Subsonic API，支持主流音乐客户端。
- [PhotoPrism](https://github.com/photoprism/photoprism) - 基于 AI 的智能照片管理服务，支持自动标签、地理位置聚类与人脸识别。

## 网络
- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) - 全网广告拦截与本地 DNS 防污染服务器，保护全家终端隐私。
- [Anubis](https://github.com/TecharoHQ/anubis) - 轻量防 AI 爬虫安全防火墙，通过特征请求精准拦截训练爬虫。
- [Cloudflared](https://github.com/cloudflare/cloudflared) - Cloudflare Tunnel 客户端，免公网 IP 将内网 Web 服务安全暴露。
- [DDNS-Go](https://github.com/jeessy2/ddns-go) - 极简动态域名解析客户端，支持阿里、腾讯、Cloudflare 等主流服务商。
- [frp](https://github.com/fatedier/frp) - 高性能内网穿透反向代理工具，支持多协议流量安全转发。
- [HAProxy](https://github.com/haproxy/haproxy) - 高可靠 TCP/HTTP 负载均衡器，广泛用于流量分发、高可用与 TLS 终结。
- [Lucky](https://github.com/gdy666/lucky) - 国人家庭网络工具箱，集成 DDNS、反代、端口转发、内网穿透与 WOL 唤醒。
- [MetaCubeXD](https://github.com/MetaCubeX/metacubexd) - Mihomo/Clash-Meta 内核的现代 Web 监控与控制面板。
- [Mihomo](https://github.com/MetaCubeX/mihomo) - Clash-Meta 的继任者，基于可定制规则的多协议网络代理内核。
- [NetBird](https://github.com/netbirdio) - 基于 WireGuard 的开源零信任 Full Mesh 虚拟组网平台。
- [Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager) - 可视化 Nginx 反代管理面板，内置 Let's Encrypt SSL 自动申请与续期。
- [NPS](https://github.com/ehang-io/nps) - 带 Web 页面的高性能内网穿透/代理服务器，配置简单，功能齐全。
- [OpenClash](https://github.com/vernesong/OpenClash) - OpenWrt/iStoreOS 路由器下的规则网络代理客户端。
- [Tailscale](https://github.com/tailscale) - 基于 WireGuard 的零配置虚拟组网工具，轻松实现跨域内网互联。
- [ZeroTier](https://github.com/zerotier) - 采用 SDN 技术的自组网穿透工具，将分布各地的设备连入同一虚拟局域网。

## 文件管理
- [Alist](https://github.com/alist-org/alist) - 多云盘文件列表程序，支持几十种网盘挂载，统一提供 WebDAV 与离线下载。
- [MinIO](https://github.com/minio/minio) - 高性能、兼容 S3 API 的自托管的轻量对象存储。
- [OpenList](https://github.com/OpenListTeam/OpenList) - 国人主导的 Alist 社区分支，专注性能优化与自定义聚合。
- [Syncthing](https://github.com/syncthing/syncthing) - 去中心化端到端文件同步工具，设备间点对点传输，不依赖中心服务器。

## 下载
- [Aria2](https://github.com/aria2/aria2) - 轻量多协议命令行下载工具，支持 HTTP、FTP、BT、Magnet，资源占用极低。
- [qBittorrent](https://github.com/qbittorrent/qBittorrent) - 开源高性能 BT/PT 客户端，内置搜索引擎、RSS 订阅与 Web UI 远程管理。

## 密码管理
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - Rust 重写的 Bitwarden 轻量后端，资源占用极低，解锁原版全部付费功能。

## 笔记与文档
- [Excalidraw](https://github.com/excalidraw/excalidraw) - 手绘风格在线白板与流程图工具，支持多人实时协作与移动端适配。
- [Memos](https://github.com/usememos/memos) - 基于 SQLite 的超轻量个人随笔与闪念笔记，类微博/Twitter 体验，支持 Markdown。
- [Outline](https://github.com/outline/outline) - 高颜值团队知识库与 Wiki 系统，支持 Markdown 实时协作与全文检索。

## 书签
- [Linkding](https://github.com/sissbruecker/linkding) - 轻量自托管书签管理器，支持可定制标签与批量搜索，无多余功能。

## 工具
- [EVE-NG](https://www.eve-ng.net/) - 多厂商网络设备模拟平台，支持 Cisco、Juniper、华为等数百种设备镜像，适合网络实验与认证备考。
- [Glance](https://github.com/glanceapp/glance) - 极简个人聚合首页，将 RSS、天气、书签与网络状态汇总于一张卡片式仪表盘。
- [it-tools](https://github.com/CorentinTh/it-tools) - 开发者在线工具箱，内置上百种编码转换、加密调试与实用算法。
- [Kiwix](https://github.com/kiwix) - 离线百科阅读器，支持维基百科、StackOverflow 等离线数据库，适合断网环境。
- [Mealie](https://github.com/mealie-recipes/mealie) - 精致食谱与饮食计划管理系统，支持自动解析网络食谱并生成购物清单。
- [Reactive-Resume](https://github.com/AmruthPillai/Reactive-Resume) - 免费自建个人简历生成器，支持多模板切换与实时 PDF 预览。
- [SearXNG](https://github.com/searxng/searxng) - 隐私优先的元搜索引擎，聚合各大搜索引擎结果，不追踪用户。
- [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - 全功能本地 PDF 处理器，支持合并、拆分、OCR、格式转换与去水印。

## 监控与运维
- [1Panel](https://github.com/1Panel-dev/1Panel) - 现代化国产 Linux 面板，通过 Docker 一键安装运维 HomeLab 应用，内置容器化、备份与证书管理。
- [Grafana](https://github.com/grafana/grafana) - 开源可视化监控面板，将 Prometheus、InfluxDB 等数据源转化为精美图表。
- [Portainer](https://github.com/portainer/portainer) - 轻量容器管理面板，提供 Docker/Kubernetes 的图形化监控与运维。
- [Prometheus](https://github.com/prometheus/prometheus) - 云原生时序数据库与监控告警引擎，云原生生态的事实标准。
- [Traccar](https://github.com/traccar/traccar) - GPS 实时位置追踪平台，支持上千种硬件设备与手机客户端。
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - 高颜值服务状态监控看板，支持飞书、钉钉、微信、Telegram 等渠道低延迟告警。

## 智能家居
- [Home Assistant](https://github.com/home-assistant/core) - 开源智能家居平台，将千百种不同协议的智能设备统一接入，实现高级联动。

## AI
- [AstrBot](https://github.com/AstrBotDevs/AstrBot) - 支持多 IM 平台的 AI Agent 开发框架，集成了 QQ、Telegram、Discord 等渠道与 LLM/插件体系，可替代 OpenClaw 实现个人 AI 助手。
- [Cherry Studio](https://github.com/cherry-studio/cherry-studio) - 高颜值多模型 AI 桌面客户端，适配自托管 AI 网关与本地开源模型。
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - 基于节点工作流的 AI 图像生成界面，Stable Diffusion 工业级出图的首选。
- [Dify](https://github.com/langgenius/dify) - 可视化 LLM 应用开发平台，支持 RAG、工作流编排与 Agent 智能代理。
- [Hermes Agent](https://github.com/NousResearch/hermes-agent) - Nous Research 出品的通用 AI 智能体框架，带来未来自动化开发的更多可能。
- [LobeHub](https://github.com/lobehub/lobe-chat) - 现代化 AI 聊天客户端，支持丰富插件与多模型切换。
- [n8n](https://github.com/n8n-io/n8n) - 可自托管的低代码自动化工作流平台，支持接入各类 AI 模型与互联网服务。
- [New API](https://github.com/songquanpeng/new-api) - 大模型 API 中转、分发与多商户计费管理，对标上游 One API 做了深度优化。
- [Open WebUI](https://github.com/open-webui/open-webui) - 类 ChatGPT 界面的自建大语言模型 Web UI，完美适配 Ollama 离线模型。
- [OpenClaw](https://github.com/openclaw/openclaw) - 自托管、高扩展性的个人 AI 语音与即时通信助手。

## 开发与部署
- [Argo CD](https://github.com/argoproj/argo-cd) - Kubernetes 声明式 GitOps 持续交付平台，应用状态与 Git 仓库自动同步。
- [Authentik](https://github.com/goauthentik/authentik) - 一站式开源身份认证提供商，支持 SSO、LDAP、SAML 与多因素认证。
- [CloudBeaver](https://github.com/dbeaver/cloudbeaver) - Web 端数据库管理面板，免客户端直连 PostgreSQL、MySQL、ClickHouse 等。
- [Docker Registry](https://github.com/distribution/distribution) - 官方 Docker 镜像仓库分发工具，自建 CI/CD 中存储与管理容器镜像的核心组件。
- [Forgejo](https://forgejo.org) - 社区驱动的轻量级 Git 托管平台，Gitea 的完全独立分支。
- [Gitea](https://github.com/go-gitea/gitea) - 性能优异的轻量级自托管 Git 服务，全能型代码仓库平台。
- [GitLab](https://about.gitlab.com/) - 企业级 DevOps 协同平台，内置完整的 CI/CD 流程与项目管理。
- [itzg/minecraft-server](https://github.com/itzg/docker-minecraft-server) - Docker Minecraft 私服一键部署镜像，高度自动化，支持多版本与模组。
- [K3s](https://github.com/k3s-io/k3s) - 专为边缘与轻量硬件打造的极简 K8s 发行版，HomeLab 容器编排首选。
- [NapCat](https://github.com/NapNeko/NapCatQQ) - 轻量 Linux QQ 机器人运行框架，无需桌面环境与扫码。

## 博客与社交
- [Ghost](https://github.com/TryGhost/Ghost) - 基于 Node.js 的专业博客与媒体订阅平台，支持内容变现。
- [GoToSocial](https://gotosocial.org/) - Go 编写的轻量 ActivityPub 社交实例，可与 Mastodon 联邦互通。
- [Halo](https://github.com/halo-dev/halo) - 国产精美建站与博客系统，支持模块化插件与可定制模板。
- [Hexo](https://github.com/hexojs/hexo) - Node.js 静态博客生成框架，主题生态成熟，社区资源丰富。
- [Hugo](https://github.com/gohugoio/hugo) - Go 开发的极速静态网站生成器，数万页面瞬间渲染。
- [SiYuan](https://github.com/siyuan-note/siyuan) - 本地优先的个人知识库，支持双向链接与块级富文本编辑。
- [Typecho](https://github.com/typecho/typecho) - 极简 PHP 博客程序，资源消耗低，轻量优雅的代表。
- [WordPress](https://github.com/WordPress/WordPress) - 全球使用最广泛的开源 CMS 与博客平台，插件与主题生态无出其右。

## 贡献指南 (Contributing)
欢迎提交 Pull Request！新项目请保持分类内字母顺序排列，并附上简要描述。
