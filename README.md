# Fun AI Blog

一个基于 Astro 的技术博客，默认部署目标为 **Cloudflare Pages**，站点域名预设为：

- `https://blog.fun-ai.xyz`

## 本地开发

```bash
npm install
npm run dev
```

## 构建

```bash
npm run build
```

构建产物在：

- `dist/`

## Cloudflare Pages 部署参数

- Framework preset: `Astro`
- Build command: `npm run build`
- Build output directory: `dist`
- Node version: `22`

## 自定义域名

建议绑定：

- `blog.fun-ai.xyz`

如果域名已经托管在 Cloudflare：

1. 进入 Workers & Pages
2. 选择该项目
3. 打开 `Custom domains`
4. 添加 `blog.fun-ai.xyz`
5. 按提示自动或手动完成 DNS 记录配置

## 目录说明

- `src/content/blog/`：博客文章
- `src/pages/`：页面
- `src/components/`：组件
- `src/styles/`：全局样式

## 后续可扩展

- 评论系统
- 标签 / 归档
- 项目页
- 访问统计
- 搜索
