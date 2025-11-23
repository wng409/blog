个人技术博客项目

📝 项目简介

这是一个基于HTML5和CSS3构建的个人技术博客网站，采用华为官网的设计风格，以红白配色为主题，展示个人技术项目和开发经验。

https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80

✨ 功能特性

· 🎨 华为设计风格 - 采用红白配色方案，模仿华为官网的简洁专业设计
· 📱 响应式布局 - 完美适配桌面端、平板和移动设备
· ⚡ 现代化交互 - 平滑滚动、悬停动画等交互效果
· 🚀 单页面应用 - 所有内容在一个页面内展示，加载快速
· 🌐 GitHub集成 - 直接链接到GitHub项目仓库

🛠️ 技术栈

· 前端: HTML5, CSS3, JavaScript
· 图标: Font Awesome 6.4.0
· 字体: Segoe UI, Microsoft YaHei
· 部署: GitHub Pages

📁 项目结构

```
个人博客/
├── index.html          # 主页面文件
├── README.md          # 项目说明文档
├── images/            # 图片资源目录（可选）
└── assets/            # 其他资源文件（可选）
```

🎯 页面结构

1. 顶部导航栏

· 品牌Logo和网站名称
· 主要导航链接（首页、技术与项目、关于我、联系）

2. 英雄区域

· 网站主标题和描述
· 行动号召按钮

3. 技术与项目

· 项目卡片展示
· 每个项目包含：
  · 项目图片
  · 项目标题和描述
  · 技术标签
  · GitHub链接

4. 关于我

· 个人介绍
· 技能标签展示
· 个人照片区域

5. 页脚

· 快速链接
· 联系信息
· 社交媒体链接
· 版权信息

🚀 快速开始

本地运行

1. 克隆或下载项目文件
2. 直接在浏览器中打开 index.html 文件
3. 或者使用本地服务器：
   ```bash
   # 使用Python
   python -m http.server 8000
   
   # 使用Node.js
   npx http-server
   ```

部署到GitHub Pages

1. 将项目文件上传到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 选择部署分支（通常是main或gh-pages）
4. 访问 https://[用户名].github.io/[仓库名]

📋 项目展示

当前展示项目

1. HTML5视频播放器

· 技术: HTML5, CSS3, JavaScript
· 描述: 探索HTML5作为播放器并支持在线离线播放功能
· 链接: GitHub仓库

2. 生日祝福网页

· 技术: HTML5, GitHub Pages
· 描述: 运用HTML5技术为好友创建生日祝福网页
· 链接: 在线演示

3. 希沃限制解除工具

· 技术: Python, 系统工具
· 描述: 解除希沃集控对电脑的不合理限制
· 链接: GitHub仓库

🎨 自定义配置

修改配色方案

在CSS变量中修改颜色值：

```css
:root {
    --hw-red: #e60012;     /* 主色调-红色 */
    --hw-white: #ffffff;   /* 背景色-白色 */
    --hw-dark-gray: #333333; /* 文字色-深灰 */
    /* 更多颜色变量... */
}
```

添加新项目

在HTML中添加新的项目卡片：

```html
<article class="blog-card">
    <div class="card-image" style="background-image: url('图片URL');"></div>
    <div class="card-content">
        <div class="card-meta">
            <span><i class="far fa-calendar"></i> 日期</span>
            <span><i class="far fa-folder"></i> 分类</span>
        </div>
        <h3>项目标题</h3>
        <p>项目描述</p>
        <a href="项目链接" class="read-more">查看项目 <i class="fas fa-arrow-right"></i></a>
    </div>
</article>
```

更新个人信息

修改"关于我"部分的内容：

```html
<div class="about-content">
    <h2>关于我</h2>
    <p>个人介绍...</p>
    <div class="skills">
        <span class="skill-tag">技能1</span>
        <span class="skill-tag">技能2</span>
        <!-- 更多技能标签 -->
    </div>
</div>
```

🔧 浏览器兼容性

· ✅ Chrome 60+
· ✅ Firefox 55+
· ✅ Safari 12+
· ✅ Edge 79+

📄 许可证

本项目采用 MIT 许可证 - 详见 LICENSE 文件

🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

📞 联系信息

· 邮箱: mc52634903@163.com
· GitHub: wng409
· 位置: 中国

🙏 致谢

· 感谢华为官网的设计灵感
· 感谢Font Awesome提供的图标
· 感谢Unsplash提供的免费图片资源

---

最后更新: 2025年11月
版本: 1.0
维护者: wng409
