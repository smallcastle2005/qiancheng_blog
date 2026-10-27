---
title: "你好，世界：用 GitHub Pages 搭起这个博客"
date: 2026-10-27
categories: 随笔
tags: [GitHub Pages, 建站]
---

为什么选择用 GitHub 写博客？因为它把**写作、版本管理、发布**合成了一件事：写一个 Markdown 文件，`git push` 上去，网站自动更新。没有服务器，没有数据库，全站就是一堆纯文本。

## 搭建只花了三步

1. 在 GitHub 建一个名为 `用户名.github.io` 的仓库；
2. 往里放 Markdown 文章（放在 `_posts/` 目录，文件名 `年-月-日-标题.md`）；
3. 仓库 Settings → Pages 里开启部署。

## 写一篇文章的流程

每篇文章就是一个 `.md` 文件，开头用 YAML 声明元信息（Jekyll 叫它 front matter）：

```yaml
---
title: 文章标题
date: 2026-10-27
categories: 随笔
---

正文用 Markdown 写，GitHub 内置的 Jekyll 会自动把它渲染成网页。
```

> 以后每篇学习笔记都是一次 commit，文章历史 = 学习历史。

这篇文章本身就是一个 demo：当你看到它时，说明整个流程已经跑通了。
