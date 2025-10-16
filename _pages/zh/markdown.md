---
permalink: /zh/markdown/
title: "站点使用指南"
author_profile: true
lang: "zh-CN"
locale: "zh-CN"
lang_ref: "guide"
---

{% include toc title="目录" %}

这里提供一个中文版本的使用说明，请根据需要补充或翻译更多细节。

## 关键文件位置

* 基础配置：`_config.yml`
* 顶部导航：`_data/navigation.yml`
* 单页内容：`_pages/`
* 文章集合：
  * `_publications/`
  * `_portfolio/`
  * `_posts/`
  * `_teaching/`
  * `_talks/`
* 页脚：`_includes/footer.html`
* 静态资源（如 PDF）：`/files/`
* 个人头像（可在 `_config.yml` 中设置）：`images/profile.png`

## 提示

* 将文件命名为 `.md` 会使用 Markdown 渲染；命名为 `.html` 则会按 HTML 渲染。
* 可以在 GitHub 网页端直接编辑这些文件，点击文件右上角的铅笔图标即可。
* Academic Pages 使用 [Jekyll Kramdown](https://jekyllrb.com/docs/configuration/markdown/)，大部分 GitHub 风格的 Markdown 写法都支持。

## 数学公式

支持使用 MathJax 来渲染公式，例如：

$$E = mc^2$$

## Mermaid 图表

可以使用 Mermaid 语法生成流程图等图形：

```mermaid
graph LR
A[开始] --> B[下一步]
```
