# 叶炳材的个人主页

🌿 我的个人主页，纯 HTML / CSS / JavaScript 单文件实现，竹林绿深色主题，适配桌面与移动端，通过 GitHub Pages 自动部署。

## 在线访问

- 主页：<https://ybcyyds.github.io/Project/>
- 猜数游戏：<https://ybcyyds.github.io/Project/guess.html>

## 功能

- 个人介绍与技能标签
- 项目展示与联系方式（GitHub、QQ）
- 🎯 猜数小游戏（`guess.html`，由我的 C 语言小程序改编）
- 响应式布局，手机 / 电脑均可正常浏览
- 无任何外部依赖，无需构建

## 本地预览

直接用浏览器打开 `index.html` 即可；或在项目目录启动一个静态服务器：

```bash
python -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 目录结构

```text
.
├── index.html      # 主页（全部样式与脚本内联）
├── guess.html      # 猜数小游戏
├── 404.html        # GitHub Pages 404 页面
└── README.md
```

## 部署

推送到 `main` 分支后，GitHub Pages 会自动更新（仓库 Settings → Pages 中已配置 `main` 分支根目录）。
