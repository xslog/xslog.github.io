# Kyle's Blog

> 离开世界之前 一切都是过程

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/xslog/xslog.github.io)
[![Jekyll](https://img.shields.io/badge/jekyll-4.3.4-blue.svg)](https://jekyllrb.com/)
[![License](https://img.shields.io/badge/license-Apache%202.0-green.svg)](LICENSE)

![Blog Preview](https://xslog.github.io/img/blog-desktop.jpg)


[User Manual 👉](_doc/Manual.md)
--------------------------------------------------

## 🚀 快速开始

### 环境要求

- [Ruby](https://www.ruby-lang.org/en/) 2.6.10+
- [Bundler](https://bundler.io/) 1.17.2+
- [Jekyll](https://jekyllrb.com/) 4.3.4+

### 安装步骤

1. **克隆仓库**
```bash
git clone https://github.com/xslog/xslog.github.io.git
cd xslog.github.io
```

2. **安装依赖**
```bash
bundle install
```

3. **启动开发服务器**
```bash
bundle exec jekyll serve
```

4. **访问网站**
打开浏览器访问 `http://localhost:4000`

### 🔧 开发命令

```bash
# 启动开发服务器（带自动重载）
bundle exec jekyll serve --livereload

# 构建静态网站
bundle exec jekyll build

# 清理缓存并重新构建
bundle exec jekyll clean && bundle exec jekyll build
```

### Development (Build From Source)

To modify the theme, you will need [Grunt](https://gruntjs.com/). There are numbers of tasks you can find in the `Gruntfile.js`, includes minifing JavaScript, compiling `.less` to `.css`, adding banners to keep the Apache 2.0 license intact, watching for changes, etc. 

Yes, they were inherited and are extremely old-fashioned. There is no modularization and transpilation, etc.

Critical Jekyll-related code are located in `_include/` and `_layouts/`. Most of them are [Liquid](https://github.com/Shopify/liquid/wiki) templates.

This theme uses the default code syntax highlighter of jekyll, [Rouge](http://rouge.jneen.net/), which is compatible with Pygments theme so just pick any pygments theme css (e.g. from [here](http://jwarby.github.io/jekyll-pygments-themes/languages/javascript.html) and replace the content of `highlight.less`.


### Interesting to know more? Checkout the [full user manual](_doc/Manual.md)!


Other Resources
---------------

Ports
- [**Hexo**](https://github.com/Kaijun/hexo-theme-huxblog) by @kaijun
- [**React-SSR**](https://github.com/LucasIcarus/
- kylesblog.github.io/tree/ssr) by @LucasIcarus

[Starter/Boilerplate](https://github.com/huxpro/huxblog-boilerplate)
- Out of date. Helps wanted for updating it on par with the main repo

Translation
- [🇨🇳  中文文档（有点过时）](https://github.com/Huxpro/kylesblog.github.io/blob/master/_doc/README.zh.md)


License
-------

Apache License 2.0.
Copyright (c) 2015-present Huxpro

Kyle Blog is derived from [Clean Blog Jekyll Theme (MIT License)](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll/)
Copyright (c) 2013-2016 Blackrock Digital LLC.
