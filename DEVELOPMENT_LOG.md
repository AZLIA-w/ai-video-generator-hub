# AI Video Generator Hub - 开发日志

## 项目概述
- 项目名：Now_trending / AI Video Generator Hub
- 主题：AI Video Generator（热词快站）
- 路径：/home/azlia/projects/Now_trending

## 当前进度

### 已完成
- [x] GitHub 仓库创建
- [x] 推送代码到 GitHub（ai-video-generator-hub）
- [x] Vercel 部署
- [x] 落地页内容（What is / Why / How to / FAQ，1200+词）
- [x] Google Search Console 验证通过（域名：https://ai-video-generator-hub.vercel.app/）

### 待完成
- [ ] 提交 sitemap 到 Google Search Console
- [ ] 发外链推广（AI 导航站、V2EX、Reddit 等）
- [ ] 自定义域名绑定（当前用 vercel.app 域名，AdSense 需要独立域名）
- [ ] 变现接入（AdSense / 联盟营销）

## 技术栈
- 前端：HTML + CSS + JS（静态页面）
- 部署：Vercel
- 源码托管：GitHub

## 关键链接
- 网站：https://ai-video-generator-hub.vercel.app/
- GitHub：https://github.com/AZLIA-w/ai-video-generator-hub

## 部署步骤（备忘）

### 1. 本地修改后推送到 GitHub
```bash
cd ~/projects/Now_trending
git add .
git commit -m "commit message"
git push -u origin main
```
Vercel 会自动检测更新并重新部署。

### 2. 自定义域名绑定（未来）
- 域名注册：dnshe（免费域名 aitvideomaker.bbroot.com，但后缀不理想）
- DNS：Cloudflare（接管 dnshe 的域名）
- 绑定到 Vercel 项目的 Domains 设置

### 3. Google Search Console
- 验证文件路径：`/google4f8f5e3c8c8c8c8c.html` 和 `/googlee9b6fc8d8f90a1ad.html`
- 验证通过域名：ai-video-generator-hub.vercel.app

## 热词快站教程参考
- 教程文件：/home/azlia/projects/Now_trending/自建web.txt
- 核心流程：发现热词 → 快速建站 → 抢占搜索位 → 变现

## 下次启动建议
1. 先读 README.md 和 CLAUDE.md 了解项目状态
2. 检查 GitHub 和 Vercel 状态确认部署情况
3. 按"待完成"清单继续推进