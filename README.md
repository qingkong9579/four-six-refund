# 四六级退款 - 趣味个人主页

一个有趣的恶搞网页，以"四六级退款"为噱头，最终展示个人信息的创意主页。

## 🌐 在线演示

- **GitHub仓库**：https://github.com/qingkong9579/four-six-refund
- **在线预览**：https://cet4-6.sfunction.top/

## 🎯 项目简介

这是一个创意满满的个人主页项目，通过三个阶段的交互设计，从恶搞开始，逐步引导用户了解作者：

1. **第一阶段**：显示"四六级退款"标题，吸引用户点击
2. **第二阶段**：点击后弹出恶搞弹窗，告诉用户"想得美"
3. **第三阶段**：引导用户了解作者，展示个人信息和联系方式

## ✨ 主要特性

### 🎨 视觉效果
- **动态背景**：集成随机图片API，每次刷新显示不同背景
- **毛玻璃效果**：现代化的backdrop-filter模糊效果
- **渐变设计**：精美的渐变色彩搭配
- **动画交互**：流畅的CSS动画和过渡效果

### 📱 响应式设计
- 完美适配桌面端和移动端
- 灵活的布局调整
- 触摸友好的交互设计

### 🎭 交互体验
- 三层递进式交互设计
- 键盘快捷键支持（ESC关闭弹窗）
- 点击背景关闭弹窗
- 悬停动画效果

### 🌐 个人展示
- 个人头像展示
- 社交媒体链接集成
- SVG图标美化
- 个人博客链接

## 🛠️ 技术栈

- **HTML5**：语义化结构
- **CSS3**：
  - Flexbox布局
  - CSS动画和过渡
  - backdrop-filter毛玻璃效果
  - 媒体查询响应式设计
- **JavaScript**：
  - DOM操作
  - 事件监听
  - 异步图片加载
  - 错误处理

## 📂 项目结构

```
four-six/
├── index.html          # 主页面文件
└── README.md          # 项目说明文档
```

## 🚀 快速开始

### 本地运行

1. 克隆或下载项目文件
2. 直接在浏览器中打开 `index.html`
3. 开始体验交互流程

### 在线部署

支持部署到任何静态网站托管平台：

- **Cloudflare Pages** ⭐ 推荐
- **GitHub Pages**
- **Vercel** 
- **Netlify**

## 🎮 使用说明

### 交互流程

1. **页面加载**：显示加载动画，获取随机背景图片
2. **点击标题**：点击"四六级退款"显示第一个弹窗
3. **第一个弹窗**：恶搞内容，点击"好吧，我知道了"继续
4. **第二个弹窗**：引导了解作者，点击"好的，看看吧"
5. **个人主页**：展示个人信息和联系方式

### 快捷键

- `ESC`：关闭当前打开的弹窗
- 点击弹窗背景：关闭弹窗

## 🔧 自定义配置

### 修改个人信息

在 `index.html` 中找到以下部分进行修改：

```html
<!-- 修改标题 -->
<h1 class="profile-title">您的名称</h1>

<!-- 修改介绍文案 -->
<p class="profile-subtitle">
    您的个人介绍<br>
    第二行介绍
</p>

<!-- 修改主要链接 -->
<a href="您的博客链接" target="_blank" class="main-link">
    📖 点此前往个人博客
</a>
```

### 修改头像

替换头像链接：

```html
<!-- 网页图标 -->
<link rel="icon" type="image/webp" href="您的头像链接">

<!-- 页面头像 -->
<img src="您的头像链接" alt="头像" class="avatar">
```

### 修改联系方式

在联系方式部分添加或修改链接：

```html
<div class="contact-links">
    <a href="您的链接" target="_blank" class="contact-link">
        <img src="图标SVG链接" width="32" height="32"> 联系方式名称
    </a>
</div>
```

### 修改背景图片API

如需更换背景图片源，修改CSS中的API地址：

```css
.background-image {
    background-image: url("您的图片API地址") !important;
}
```

## 🎨 设计灵感

项目设计参考了现代网页设计趋势：

- **毛玻璃拟态设计**：backdrop-filter效果
- **渐变色彩**：现代化的色彩搭配
- **微交互**：精致的悬停和点击效果
- **极简主义**：简洁清晰的信息层次

## 📱 浏览器兼容性

- ✅ Chrome 76+
- ✅ Firefox 72+
- ✅ Safari 13+
- ✅ Edge 79+

> 注意：backdrop-filter效果需要较新的浏览器支持

## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进项目：

1. Fork 项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开Pull Request

## 📄 许可证

本项目使用 MIT 许可证。详情请参阅 [LICENSE](LICENSE) 文件。

## 🎉 致谢

- 感谢 [SVGRepo](https://www.svgrepo.com) 提供的精美图标
- 感谢随机图片API提供动态背景支持

## 📧 联系方式

如有问题或建议，欢迎通过以下方式联系：

- 📖 [个人博客](https://blog.sfunction.top)
- 🍃 [酷安主页](https://www.coolapk.com/u/1073606)
- 🎮 [Steam](https://steamcommunity.com/profiles/76561198837891376/)
- 💻 [GitHub](https://github.com/qingkong9579)

---

⭐ 如果这个项目对您有帮助，请给它一个星星！
