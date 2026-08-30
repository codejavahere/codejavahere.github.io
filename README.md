# CodeJavaHere Diary

一个基于 GitHub Pages 的极简 Markdown 日记本。

## 写一篇日记

1. 在 `diary/` 新建 Markdown 文件，例如 `2026-08-30-my-day.md`。
2. 在 `diary/index.json` 添加对应的标题、日期、摘要和标签。
3. 提交到 `main` 分支，GitHub Pages 更新后即可在首页时间线看到。

## 目录

```text
.
├── index.html          # 首页时间线
├── post.html           # Markdown 日记详情页
├── about.html          # 关于页面
├── assets/
│   ├── style.css       # 黑白极简响应式样式
│   └── app.js          # 时间线、搜索与筛选
└── diary/
    ├── index.json      # 日记索引
    └── *.md            # 日记正文
```

Markdown 在浏览器端渲染，正文通过 DOMPurify 清理后展示。
