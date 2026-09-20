# 新版个人网站源码

访问：https://portfolio.fuluoyide.top/ （同站地址 https://zzq-personal-site.vercel.app/）。

本独立仓库 `zzq-personal-site` 保存新版网站的完整静态源码和素材，主分支为 `main`。

源码：https://github.com/372790111z-wq/zzq-personal-site

- `dist/index.html`：页面内容
- `dist/style.css`：样式
- `dist/app.js`：交互
- `dist/media/`：图片、SVG、视频

无需构建或安装依赖。运行 `python3 -m http.server 8080 --directory dist` 后访问 http://localhost:8080/ 。

此快照含当前本地修改，HTML、CSS、JS已与2026-09-20线上版本逐字节核对一致。
本分支关闭Vercel自动部署，提交仅用于源码保存。发布时仅上传dist内容，不上传整个仓库目录。
