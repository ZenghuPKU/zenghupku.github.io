## 导航栏配置

1、menu中创建 对应的文件
```
#about.md  文件名

---
layout: page   使用的html 模板也就是 _layouts中的 page的模板
title: Welcome to Lagrange!   页面的标题
permalink: /about    页面对应的 path路径 也就是 setting文件中的path
---

Lagrange is a minimalist Jekyll theme. The purpose of this theme is to provide a simple, clean, content-focused blogging platform for your personal site or blog. Below you can find everything you need to get started.

### Getting Started

[Getting Started]({{ site.github.url }}{% post_url 2015-10-10-getting-started %}): getting started with installing Lagrange, whether you are completely new to using Jekyll, or simply just migrating to a new Jekyll theme.

### Example Content

[Text and Formatting]({{ site.github.url }}{% post_url 2014-01-01-text-formatting-examples %})

### Questions?

This theme is completely free and open source software. You may use it however you want, as it is distributed under the [MIT License](http://choosealicense.com/licenses/mit/). If you are having any problems, any questions or suggestions, feel free to [tweet at me](https://twitter.com/intent/tweet?text=My%question%about%Lagrange%is:%&amp;via=paululele), or [file a GitHub issue](https://github.com/lenpaul/lagrange/issues/new).

```


2、配置文件中 配置 导航对应的path 也就是上面 permalink的路径

```
_data/setting.yml

menu:
- {name: 'About',   url: 'about.html'}
- {name: 'Blog', url: 'blog.html'}
- {name: 'Contact', url: 'contact.html'}
- {name: 'Home',   url: ''}
- {name: 'Join', url: 'join.html'}
- {name: 'Publications', url: 'publications.html'}
- {name: 'Research', url: 'research.html'}
- {name: 'Team', url: 'team.html'}
```


## 样式调整

layout中html 模板中 html 样式需要写在 _sass文件夹中，如果新建sass文件需要在 _-sections-dir.scss中引入

```

```


## 页面变量

setting文件中 的变量 对应layout中的变量