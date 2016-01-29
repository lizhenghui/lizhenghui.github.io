---
layout: page
title: 关于
menu: About
---
{% assign current_year = site.time | date: '%Y' %}


## 概况

- 邮箱：lizhenghui.dlu#gmail.com
- 微博：[@摆渡你自己](http://weibo.com/zhaolizhenghui)

计算机专业毕业，{{ current_year | minus: 2010 }} 年在职工作经验，{{ current_year | minus: 2010 }} 年 web 开发经验。

## 教育
- 大连大学 计算机系 — 本科 2006 - 2010

## keywords
<div class="btn-inline">
{% for keyword in site.skill_keywords %} <button class="btn btn-outline" type="button">{{ keyword }}</button> {% endfor %}
</div>

### 综合技能

| 名称 | 熟悉程度
|--:|:--|
| PHP | ★★★★★ |
| javascript | ★★★★☆ |
| Linux | ★★★★☆ |
| Nodejs | ★★★★☆ |
| Markdown | ★★★★★ |
| C | ★★★☆☆ |
| Photoshop | ★★★★☆ |
