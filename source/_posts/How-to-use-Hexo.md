title: 开篇第一帖－使用Hexo的正确姿势
date: 2015-07-05 11:13:39
tags:
  - 程序
categories:
  - Hexo
description: 使用Hexo的正确姿势
---


## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)


### Edit a post
Edit the file under source/_posts/ Directory.
build tags and categories for this blog

``` bash
title: 开篇第一帖－使用Hexo的正确姿势
date: 2015-07-05 11:13:39
tag:
  - 程序
categories:
  - Hexo
description: 使用Hexo的正确姿势
---
```

### Hexo Tags Plugins
It would be very helpful, when you want to make a concise markdown document.
More info: [Tags Plugin](https://hexo.io/docs/tag-plugins.html)


### Tips
Clean Hexo and Rebuild

``` bash
hexo clean
hexo generate -p
```

Hexo Watch

``` bash
hexo generate --watch
```

