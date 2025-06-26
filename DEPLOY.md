# 部署说明 - CoinPrice Pro

## 🚀 本地开发

```bash
# 克隆项目
git clone <repository-url>
cd coinprice

# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 访问 http://localhost:3000
```

## 📦 构建生产版本

```bash
# 构建静态文件
npm run build

# 预览构建结果
npm run preview
```

## 🌐 部署选项

### Vercel (推荐)
1. 连接 GitHub 仓库
2. 自动检测为 Vite 项目
3. 一键部署

### Netlify
1. 上传 `dist` 文件夹
2. 或连接 Git 仓库自动部署

### GitHub Pages
```bash
npm run build
# 将 dist 文件夹内容上传到 gh-pages 分支
```

### 传统服务器
1. 运行 `npm run build`
2. 将 `dist` 文件夹内容上传到服务器
3. 配置 nginx 或 Apache

## ⚡ 性能优化建议

- 启用 gzip 压缩
- 配置 CDN
- 设置适当的缓存头
- 启用 HTTP/2

## 🔧 环境配置

项目使用公共 WebSocket API，无需额外环境变量配置。

## 📱 SEO 优化

项目已包含：
- 完善的 meta 标签
- Open Graph 支持
- Twitter Cards
- 结构化数据

## 🛡️ 安全建议

- 配置 HTTPS
- 设置 CSP 头
- 启用 HSTS 