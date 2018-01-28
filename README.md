# hexo-blog
> Hexo 是一个快速、简洁且高效的博客框架。Hexo 使用 Markdown（或其他渲染引擎）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。

## hexo 部署

> 😎 hexo 基于node.js 请务必下载node.js

```bash
# 下载脚手架
npm install -g hexo-cli
# hexo初始化,hexo依赖git下载,请务必下载好git
hexo init blog
cd blog
npm install
```

## 目录结构
```
.
├── _config.yml                 // 网站的配置信息
├── package.json                // 应用程序的信息
├── scaffolds                   // 模板文件夹
├── source                      // 用户资源文件夹
|   ├── _drafts
|   └── _posts
└── themes                      // 主题文件夹
```
## hexo 常用命令
  ```bash
  # 本地启动服务器, 默认情况下, 访问网址为:http://localhost:4000/
  hexo server
  ```

## hexo 注意点

```bash
# 引入图片, 为了保证书写简单, 适应Markdown语法
npm install hexo-asset-image --save
# 书写格式
![xxxx图片名称](xxx.jpg)
```

language: zh-Hans (简体中文)
### hexo主题选择

* next

#### [next主题配置](http://theme-next.iissnan.com/getting-started.html#select-scheme)

* Muse - 默认 Scheme，这是 NexT 最初的版本，黑白主调，大量留白
* Mist - Muse 的紧凑版本，整洁有序的单栏外观
* Pisces - 双栏 Scheme，小家碧玉似的清新

分类和标签需要

```bash
hexo new page "categories"
hexo new page "tags"
```

加载上述命令行并配置才能进行点击显示

文章显示更多--主题配置文件

```yml
# Automatically Excerpt. Not recommand.
# Please use <!-- more --> in the post to control excerpt accurately.
auto_excerpt:
  enable: true
  length: 150
```
