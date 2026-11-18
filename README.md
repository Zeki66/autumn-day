# autumn-day · 我在秋假外出的一天

一个纯静态的单页网站：可以写下这一天的文字记录、上传照片，内容保存在浏览器本地（localStorage），不上传服务器。

## 在线访问

https://zeki66.github.io/autumn-day/

## 目录结构

```
autumn-day/
└── index.html   # 整站只有一个文件：样式、交互、逻辑都在里面
```

## 本地预览

直接用浏览器打开 `index.html` 即可；也可以在本目录下启动任意静态服务器：

```bash
python -m http.server 8080
# 然后访问 http://localhost:8080
```

## 说明

- 记录只保存在当前浏览器本地，换设备或清理浏览器数据后不会同步。
- 照片以 base64 形式存入 localStorage，容量约 5MB，照片较多时可能提示保存失败。

## 发布方式

GitHub Pages，来源为 `main` 分支根目录，每次向 `main` 推送即自动重新部署。
