# 个人主页

> 一个现代简约风格的个人主页，使用 Tailwind CSS 构建

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-部署成功-brightgreen)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwind-css&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue)

## 🌐 在线预览

访问 [https://bosswang926.github.io/test01/](https://bosswang926.github.io/test01/) 查看实时效果

## ✨ 特性

- 🎨 **现代设计** - 采用简洁优雅的 UI 设计
- 📱 **完全响应式** - 适配各种设备屏幕（手机/平板/桌面）
- ⚡ **轻量级** - 纯静态页面，无需构建工具
- 🚀 **快速加载** - 使用 CDN 加速资源加载
- 🎯 **SEO 友好** - 良好的语义化 HTML 结构
- 🔗 **平滑滚动** - 优化的滚动体验
- 💫 **动画效果** - 精致的悬停和过渡动画

## 🛠️ 技术栈

- **HTML5** - 页面结构
- **Tailwind CSS 3.x** - 样式框架（CDN）
- **Google Fonts** - 字体资源
  - Poppins（标题字体）
  - Open Sans（正文字体）

## 📁 项目结构

```
test01/
├── index.html          # 主页面
├── README.md          # 项目说明文档
├── 部署指南.md        # 部署说明
└── .gitignore         # Git 忽略文件配置
```

## 🚀 快速开始

### 本地运行

1. **克隆仓库**
   ```bash
   git clone https://github.com/BossWang926/test01.git
   cd test01
   ```

2. **直接打开**
   - 直接用浏览器打开 `index.html`
   - 或使用本地服务器：
     ```bash
     # 使用 Python
     python -m http.server 8000

     # 使用 Node.js
     npx serve

     # 使用 VS Code Live Server 插件
     ```

3. **访问页面**
   - 打开浏览器访问 `http://localhost:8000`

### 部署到 GitHub Pages

1. **Fork 或克隆此仓库**

2. **启用 GitHub Pages**
   - 进入仓库 **Settings** → **Pages**
   - Source 选择 **Deploy from a branch**
   - Branch 选择 **master** → **/ (root)**
   - 点击 **Save**

3. **等待部署完成**
   - 通常需要 1-2 分钟
   - 访问 `https://你的用户名.github.io/test01/`

## 📄 页面结构

- **导航栏** - 固定顶部，带毛玻璃效果
- **英雄区** - 主标题和 CTA 按钮
- **特性展示** - 三个专业领域卡片（网页设计/前端开发/品牌设计）
- **关于我** - 个人介绍和数据统计
- **联系 CTA** - 呼吁行动区域
- **页脚** - 社交媒体链接和版权信息

## 🎨 自定义

### 修改内容

直接编辑 `index.html` 中的文本内容：

```html
<!-- 修改标题 -->
<h1>你的标题</h1>

<!-- 修改描述 -->
<p>你的描述文本</p>

<!-- 修改颜色 -->
<script>
tailwind.config = {
  theme: {
    extend: {
      colors: {
        primary: '#你的颜色',
        cta: '#你的CTA颜色',
      }
    }
  }
}
</script>
```

### 修改字体

替换 Google Fonts 链接：

```html
<link href="https://fonts.googleapis.com/css2?family=你的字体&display=swap" rel="stylesheet">
```

### 修改联系方式

```html
<a href="mailto:你的邮箱@example.com">联系我</a>
```

## 📱 响应式断点

- **移动端**：< 768px
- **平板**：768px - 1024px
- **桌面**：> 1024px

## 🔧 浏览器支持

- Chrome（最新版）
- Firefox（最新版）
- Safari（最新版）
- Edge（最新版）

## 📝 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 👨‍💻 作者

BossWang926

## 📮 联系方式

- GitHub: [@BossWang926](https://github.com/BossWang926)
- Email: your.email@example.com

## 🙏 致谢

- [Tailwind CSS](https://tailwindcss.com/)
- [Google Fonts](https://fonts.google.com/)
- [GitHub Pages](https://pages.github.com/)

---

⭐ 如果这个项目对你有帮助，请给个 Star！
