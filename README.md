# Decentralization and AI Lab Website

这是一个基于Jekyll的实验室网站，可以轻松部署到GitHub Pages。

## 本地开发

### 前提条件
- Ruby 2.7.0 或更高版本
- RubyGems
- GCC 和 Make

### 安装步骤

1. 克隆仓库
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. 安装依赖
```bash
bundle install
```

3. 启动本地服务器
```bash
bundle exec jekyll serve
```

4. 在浏览器中访问 `http://localhost:4000`

## 部署到GitHub Pages

### 方法1：使用GitHub Actions（推荐）

1. 在仓库根目录创建 `.github/workflows/jekyll.yml` 文件
2. 推送代码到GitHub
3. 在仓库设置中启用GitHub Pages，选择"GitHub Actions"作为源

### 方法2：手动部署

1. 构建网站
```bash
bundle exec jekyll build
```

2. 将 `_site` 文件夹的内容推送到 `gh-pages` 分支

## 网站结构

- `_layouts/` - Jekyll布局文件
- `assets/` - CSS、JS和图片资源
- `_config.yml` - Jekyll配置文件
- `index.md` - 首页内容

## 自定义

- 修改 `_config.yml` 来更改网站标题、描述等基本信息
- 编辑 `index.md` 来更新首页内容
- 在 `assets/css/main.scss` 中自定义样式

## 许可证

MIT License 