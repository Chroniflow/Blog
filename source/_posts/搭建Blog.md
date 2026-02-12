---
title: 搭建Blog
date: 2026-02-11 17:33:44
tags:
---

> 咱就是说...搭建这个blog花了我好一段时间...

# 寻找引擎

咱最开始用的是`Wordpress`，但是发现太不好用了（?， 于是就找了半天找到了[hexo](https://hexo.io)

# 寻找主题

找到了引擎然后就该找主题了，主题咱翻了半天找到了[Sw-blog](https://github.com/winmin/Sw-blog)这个主题。但是有两个缺陷:

- Archive时间过长
- 不好看(?
- ~~Star过少~~
总之呢最后没有使用。

下面就找到了另一个主题: [ShokaX](https://github.com/theme-shoka-x/hexo-theme-shokaX)

这个主题十分好，但是唯一的缺点就是:

- 我 不 会 用 !
  > 我按照文档安装了，但是一直报错`Image list must have at least 6 images`
  > 所以也没能成功使用

最后终于找到了现在使用的主题: [Redefine](https://github.com/EvanNotFound/hexo-theme-redefine)

当然也踩过坑，比如:

- `Redefine`打成了`Redifine`(神人)
- 报错`Failed: error occurred while updating repository submodules`
  > 这个的解决方案就是使用git submodule来安装而不是使用clone来安装

最后终于完成了这个Blog

# 获取资源

或许你需要一些我使用的资源，你可以在这里找到:

- [\_config.redefine.yml](/raw/config.redefine.yml)
- [.gitmodules](/raw/.gitmodules)

感谢你阅读到最后! 期待下次再会!
