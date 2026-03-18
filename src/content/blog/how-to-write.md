---
title: '以后怎么发文章'
description: '给未来的自己留个最短操作说明。'
pubDate: '2026-03-18'
heroImage: '../../assets/blog-placeholder-5.jpg'
---

以后发文其实很简单：

## 1. 新建文章文件

在 `src/content/blog/` 里创建一个新的 `.md` 文件，比如：

```md
---
title: '文章标题'
description: '一句话摘要'
pubDate: '2026-03-18'
---

这里开始写正文。
```

## 2. 本地预览

```bash
npm run dev
```

然后打开本地地址看效果。

## 3. 提交并推送

```bash
git add .
git commit -m "feat: publish new post"
git push
```

推上 GitHub 之后，GitHub Pages 会自动重新部署。

## 4. 可选项

如果文章需要封面图，可以继续在 frontmatter 里加：

```md
heroImage: '../../assets/blog-placeholder-1.jpg'
```

就这么点事，别把发文流程搞复杂。
