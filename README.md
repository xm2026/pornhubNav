# WebNav Hub 🚀 | [English](README_EN.md)

一个简约的网址导航网站，UI 设计灵感来自 Pornhub 的黑橙配色方案。

## 特点 ✨

- 🎨 经典的黑橙配色方案
- 📱 完全响应式设计，支持所有设备
- 🌙 深色模式优先
- ⚡ 纯静态网站，加载迅速
- 🎯 分类清晰的导航系统
- 💡 简洁直观的卡片式布局
- 🔍 包含多个实用分类：
  - AI 搜索工具
  - 社交媒体
  - 实用工具
  - 科技资讯
  - 云存储
  - 电子邮箱

## 在线预览 🌐

- GitHub Pages: `https://你的用户名.github.io/webnav-hub`
- Cloudflare Pages: `https://你的项目名.pages.dev`

## 部署指南 🚀

### GitHub Pages 部署

1. Fork 这个仓库
2. 进入仓库设置 Settings > Pages
3. Source 选择 main 分支
4. 保存后等待部署完成

### Cloudflare Pages 部署

1. 登录 Cloudflare Dashboard
2. 进入 Pages 板块
3. 创建新项目并连接此仓库
4. 部署设置：
   - 构建命令：留空
   - 构建输出目录：留空
5. 保存并部署

## 本地开发 💻

```bash
# 克隆仓库
git clone https://github.com/你的用户名/webnav-hub.git

# 进入项目目录
cd webnav-hub

# 使用任意 HTTP 服务器运行
# 例如 Python 的 HTTP 服务器
python -m http.server 8080
```

## 自定义 🔧

- 修改 `index.html` 中的网站链接和分类
- 调整 CSS 变量更改配色方案：

  ```css
  :root {
    --primary-bg: #000000;    /* 主背景色 */
    --secondary-bg: #1b1b1b;  /* 次背景色 */
    --hover-bg: #272727;      /* 悬停背景色 */
    --text-color: #ffffff;    /* 文字颜色 */
    --accent-color: #ff9000;  /* 强调色（橙色） */
  }
  ```

## 贡献 🤝

欢迎提交 Issue 和 Pull Request 来完善这个项目！

## 许可证 📄

MIT License - 查看 [LICENSE](LICENSE) 文件了解更多详情

## 致谢 🙏

- [Font Awesome](https://fontawesome.com/) - 图标库
- 所有网站收录均来自网络整理

## 免责声明 ⚠️

本项目仅供学习交流使用，请遵守当地法律法规。
