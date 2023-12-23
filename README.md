<div align="center">
<h1>Only</h1>
A Native, Simple, Oppose Flashy theme for Hugo
</div>

## Introduction
Just a slight modification to the native theme.

## Overview
![](./images/screenshot1.png)
![](./images/screenshot2.png)
![](./images/screenshot3.png)

## Configuration
For `config.toml` or `hugo.toml`
```toml
baseURL = ''
languageCode = 'zh-CN'
title = "Solsist's Blog"
theme = "Only"

[[menus.main]]
name = 'Home'
pageRef = '/'
weight = 10

[[menus.main]]
name = 'Tags'
pageRef = '/tags'
weight = 30

[[menus.main]]
name = 'Categories'
pageRef = '/categories'
weight = 30

[[menus.main]]
name = 'Tags'
pageRef = '/tags'
weight = 30

[module]
  [module.hugoVersion]
    extended = false
    min = "0.116.0"

[taxonomies]
  tag = "tags"
  category = "categories"

[markup]
  [markup.highlight]
    guessSyntax = true
    lineNoStart =1
    lineNos = true
    lineNumbersInTable = true
    style = "abap"
    tabWidth = 4

[params]
  bio = "知ってることだけ"
  github = "sols1st"
  email = "sols1st@outlook.com"
```

## Installation
In the directory of project and run :
```bash
git submodule add https://github.com/sols1st/only themes/only
```

In `config.toml` or `hugo.toml`

```toml
theme = "only"
```
