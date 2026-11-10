# HuoLe163.github.io

个人主页 · 静态站点，由 **GitHub Pages** 托管。

- 访问地址：<https://huole163.github.io/>
- 技术栈：纯 HTML + CSS（无框架、无构建步骤）
- 部署方式：`git push` 到 `main` 分支，GitHub Pages 自动构建发布

## 目录结构

```
.
├── index.html      # 单页主页（关于 / 技能 / 项目 / 联系）
├── style.css       # 全部样式（深色主题、响应式布局）
└── README.md       # 本文件
```

## 本地预览

直接双击 `index.html`，或启动一个本地服务器：

```bash
python -m http.server 8000
# 浏览器打开 http://127.0.0.1:8000
```

## 部署步骤（复现）

```bash
git clone https://github.com/HuoLe163/HuoLe163.github.io.git
cd HuoLe163.github.io
# 修改后提交
git add .
git commit -m "update site"
git push origin main
```

推送到 `main` 后约 1 分钟内，GitHub Pages 会完成构建并更新站点。

## 说明

本项目为「远程虚拟化 / 云服务平台」课程作业的部署演示，站点内容为个人介绍示例。
