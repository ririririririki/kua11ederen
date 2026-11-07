# GitHub 发布版作品集

本目录来自你提供的完整 HTML，保留 27 个项目、14 个分组、209 张项目图片和 13 个项目视频。背景按要求改为纯白。

## 上传到 GitHub

1. 先解压 ZIP。上传目录里面的 index.html、assets 文件夹、.nojekyll 和其他文件，保持相对位置。不要把 ZIP 本身当成网站上传。
2. 推荐使用 GitHub Desktop：将这些文件复制进仓库本地目录，提交并 Push。网页手动上传也可以，但素材较多，请分批上传并保留 assets 内的目录结构。
3. 仓库 Settings → Pages → Deploy from a branch，选择 main 分支和 /(root)，保存。
4. 等待 Pages 部署完成，使用 GitHub 给出的网页地址查看。

所有发布文件均小于 25 MiB；站点总量小于 1 GB。无需 Git LFS。

## 本地预览与编辑

直接打开 index.html 可浏览页面；请始终保持 assets 文件夹与它一起。

要在本地编辑并导出完整独立 HTML，请先在此目录运行：

    node preview.cjs

然后打开终端显示的 http://127.0.0.1 地址。Node.js 未安装时，也可以先上传 GitHub Pages 后，在网站地址下编辑和导出。使用完本地预览后按 Ctrl+C 关闭。

页面内“保存”只保存在当前浏览器，不会直接修改 GitHub 仓库。修改完成后下载最新 HTML，重新整理发布目录再更新仓库。原始完整 HTML 是你的原画质编辑备份，请继续保留。

## 压缩方式

- 图片：WebP，质量 90，长边最多 2560 像素，不放大小图。
- 视频：已满足网页规格的保留原画面编码并优化封装；其余转换 H.264、AAC，长边最多 1280 像素，最高 30fps，开启 Fast Start。
- 发布副本经过有损压缩，原始 HTML 和原素材未修改。
- 原文件引用的失效背景视频已按要求移除，背景为纯白。一个未启用的旧 Logo 引用也已清理，当前页眉文字和链接保留。

GitHub 官方限制：
https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github
https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
