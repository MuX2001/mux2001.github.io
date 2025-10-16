---
layout: archive
title: "简历"
permalink: /zh/cv/
author_profile: true
lang: "zh-CN"
locale: "zh-CN"
lang_ref: "cv"
redirect_from:
  - /zh/resume
---

这里可以放置你的中文简历内容。你可以复制英文版本 `_pages/cv.md` 中的内容并翻译成中文，或者直接在此编写全新的简历。

## 教育背景
* 示例：2018 年，版本控制理论博士，GitHub 大学

## 工作经历
* 示例：2024 年春，Academic Pages 协作者

## 技能
* 示例：技能 1

## 出版物
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## 报告与演讲
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>

## 教学
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
