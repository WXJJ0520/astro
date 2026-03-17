---
title: 博客开张：为什么先用 Astro + Cloudflare Pages
description: 先把站搭起来，再慢慢往里填内容。这篇记录我为什么选了 Astro 和 Cloudflare Pages。
pubDate: 2026-03-17
heroImage: ../../assets/blog-placeholder-1.jpg
---

这个博客的第一原则很简单：**先上线，再打磨**。

我不想一开始就陷进复杂框架、服务器运维和一堆没必要的功能里，所以第一版直接选了：

- Astro
- Markdown 写作
- Cloudflare Pages 托管
- 子域名部署

## 为什么是 Astro

Astro 对个人博客很友好：

1. 静态输出快
2. 写内容的心智负担低
3. SEO 和 RSS 这些基础能力比较顺手
4. 后面想扩展 React / Vue 组件也不难

## 为什么是 Cloudflare Pages

主要是省心：

- 免费额度对个人博客足够
- 接子域名方便
- 自动 HTTPS
- GitHub push 后自动部署

## 这一版先做什么

第一版不追求花哨，只做必要功能：

- 首页
- 博客列表
- 关于页
- 文章详情页
- RSS
- sitemap

评论、搜索、统计这些都可以后面再加。

先把写作和发布流程跑顺，才是最重要的。
