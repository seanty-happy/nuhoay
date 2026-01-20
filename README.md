# nuhoay.github.io

个人随笔网站 - 记录生活点滴与内心感悟

## 📁 项目结构

```
nuhoay.github.io/
├── index.html              # 首页入口文件（必须在顶级目录）
├── _layouts/               # 页面布局模板
│   ├── base.html          # 基础布局模板
│   ├── page.html          # 页面布局
│   └── post.html          # 文章布局
├── _includes/              # 可重用组件
│   ├── header.html        # 导航栏
│   └── footer.html        # 页脚
├── _config/                # 配置文件
│   └── site.yml           # 网站配置
├── posts/                  # 文章页面
│   ├── index.html         # 文章列表页面
│   └── post1.html         # 示例文章
├── pages/                  # 静态页面
│   ├── about.html         # 关于页面
│   └── contact.html       # 联系页面
├── assets/                 # 静态资源
│   ├── css/
│   │   ├── style.css      # 主要样式文件
│   │   └── components/    # 组件样式（预留）
│   ├── js/
│   │   ├── main.js        # 主要脚本
│   │   └── components/    # 组件脚本（预留）
│   └── images/            # 图片资源
└── README.md
```

## 🎨 设计特色

- **简约现代风格**：极简主义设计，专注内容
- **移动优先响应式**：完美适配各种设备
- **性能优化**：静态站点，快速加载
- **SEO友好**：完整的元数据和语义化HTML

## 🚀 部署

网站已配置为GitHub Pages，直接推送到主分支即可自动部署。

## 📝 写作指南

### 添加新文章

1. 在 `posts/` 目录下创建新的HTML文件
2. 使用以下模板结构：

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>文章标题 - 个人随笔</title>
    <!-- 其他meta标签 -->
    <link rel="stylesheet" href="../assets/css/style.css">
</head>
<body>
    <!-- 导航栏 -->
    <!-- 文章内容 -->
    <!-- 页脚 -->
    <script src="../assets/js/main.js"></script>
</body>
</html>
```

### 添加新页面

在 `pages/` 目录下创建新的HTML文件，路径引用需要相应调整。

## 🔧 自定义

- **样式定制**：修改 `assets/css/style.css`
- **功能扩展**：修改 `assets/js/main.js`
- **布局调整**：修改 `_layouts/` 中的模板
- **配置更新**：修改 `_config/site.yml`

## 📄 许可证

本项目仅用于个人博客展示。
