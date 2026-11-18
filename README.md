# autumn-day · 我在秋假外出的一天

秋假傍晚的香港，一篇图文记录页：粉紫色的暮光、中环的灯火、维港对岸的 ICC。

纯静态网站，任何人打开都能看到全部文字和照片，不需要登录、不依赖浏览器本地存储。

## 在线访问

https://zeki66.github.io/autumn-day/

## 目录结构

```
autumn-day/
├── index.html          # 整站单文件：版式、文字、图片引用都在这里
└── images/
    ├── central-dusk.jpg    # 暮光 · 中环
    ├── ifc-evening.jpg     # 仰望 · 国际金融中心
    └── icc-night.jpg       # 夜色 · 维港对岸 ICC
```

## 修改方式

- 改文字：编辑 `index.html` 里 `<article>` 中的三段正文。
- 换照片：用同名文件覆盖 `images/` 下的图片即可（建议长边 1600px 以内）。
- 改标题、副标题、页脚：`index.html` 顶部 `<header>` 与底部 `<footer>`。

## 本地预览

直接用浏览器打开 `index.html`，或在本目录启动静态服务器：

```bash
python -m http.server 8080
```

## 发布

GitHub Pages，来源为 `main` 分支根目录，每次推送到 `main` 即自动重新部署（约 1 分钟）。
