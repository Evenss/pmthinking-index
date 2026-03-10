# 📝 Pmthinking Blog

植物主题博客系统，包含 477 篇精选文章。

## ✨ 特点

- **内容丰富**：内置 477 篇植物相关文章
- **轻量快速**：纯静态页面，无需数据库
- **响应式设计**：全平台适配
- **易于部署**：一行命令启动

## 🚀 快速开始

### 本地预览

```bash
# Python 3
python3 -m http.server 8889

# 访问 http://localhost:8889
```

### 部署

```bash
# 克隆项目
git clone git@github.com:Evenss/pmthinking-index.git

# 启动服务
cd pmthinking-index
python3 -m http.server 8889
```

## 📁 文件结构

```
pmthinking-index/
├── index.html      # 博客主页
└── articles.json   # 文章数据 (477 篇)
```

## 📊 数据说明

### articles.json 格式

```json
{
  "articles": [
    {
      "title": "文章标题",
      "date": "2024-01-01",
      "category": "分类",
      "content": "文章内容...",
      "tags": ["标签 1", "标签 2"]
    }
  ]
}
```

## 🔧 自定义

### 添加新文章

编辑 `articles.json`，在 `articles` 数组中添加：

```json
{
  "title": "新文章标题",
  "date": "2024-03-10",
  "category": "植物科普",
  "content": "文章内容...",
  "tags": ["植物", "科普"]
}
```

### 修改页面样式

编辑 `index.html` 中的 `<style>` 部分，调整配色、字体等。

## 📱 浏览器支持

- Chrome / Edge (推荐)
- Firefox
- Safari
- 移动端浏览器

## 📄 许可证

MIT License

---

**在线预览**: http://172.20.13.101:8889
