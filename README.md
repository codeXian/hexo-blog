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
