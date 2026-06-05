# 🚀 Quick Start Guide - ROMOSS Website

## 📍 Local Access (立即访问)

### 方法 1: 直接打开文件 (最简单)

1. 打开文件夹: `d:\luomas\romoss-en\`
2. 双击 `index.html` 文件
3. 网站将在浏览器中打开

---

### 方法 2: Python 本地服务器 (推荐)

在 PowerShell 中运行:

```powershell
cd d:\luomas\romoss-en
python -m http.server 8000
```

然后访问: **http://localhost:8000**

停止服务器: 按 `Ctrl + C`

---

## 🌍 GitHub Pages 部署 (获得免费公开URL)

### 步骤 1: 创建 GitHub 账号

1. 访问: https://github.com
2. 注册免费账号
3. 验证邮箱

---

### 步骤 2: 创建新仓库

1. 点击右上角 **+** 图标
2. 选择 **"New repository"**
3. 填写信息:
   - **仓库名**: `romoss-website`
   - **描述**: `ROMOSS Power Bank Official Website`
   - **权限**: 选择 **Public** (必须)
4. 点击 **"Create repository"**

---

### 步骤 3: 上传文件

**方法 A: 网页上传 (简单)**

1. 在仓库页面点击 **"uploading an existing file"**
2. 将以下文件拖入:
   - `index.html`
   - `products.html`
   - `rd.html`
   - `company.html`
   - `service.html`
   - `news.html`
   - `careers.html`
   - `team.html`
3. 填写提交信息: `Initial website upload`
4. 点击 **"Commit changes"**

**方法 B: Git 命令行 (高级)**

```powershell
cd d:\luomas\romoss-en
git init
git add .
git commit -m "Initial website upload"
git remote add origin https://github.com/YOUR_USERNAME/romoss-website.git
git branch -M main
git push -u origin main
```

---

### 步骤 4: 启用 GitHub Pages

1. 进入仓库 **Settings** (齿轮图标)
2. 左侧点击 **Pages**
3. 在 **Source** 下选择:
   - **Deploy from a branch**
   - **main** 分支
   - **/(root)** 文件夹
4. 点击 **Save**

---

### 步骤 5: 访问您的网站

等待 1-2 分钟后，访问:

```
https://YOUR_USERNAME.github.io/romoss-website/
```

**示例:** 如果用户名是 `johnsmith`，URL 就是:
```
https://johnsmith.github.io/romoss-website/
```

✅ 现在任何人都可以通过这个URL访问您的网站了！

---

## 📱 网站页面清单

| 页面 | 文件 | 功能 |
|------|------|------|
| 首页 | index.html | 品牌展示、核心优势、热门产品 |
| 产品展示 | products.html | 全系列产品、分类筛选、购买按钮 |
| 研发技术 | rd.html | 核心技术、专利、产品迭代历程 |
| 公司概况 | company.html | 发展历程、企业文化、全球布局 |
| 售后服务 | service.html | 质保政策、FAQ、服务网点 |
| 新闻活动 | news.html | 最新新闻、即将举办的活动 |
| 招贤纳士 | careers.html | 招聘岗位、公司文化、员工福利 |
| 团队介绍 | team.html | 6名核心团队成员、任务分配 |

---

## ✅ 测试清单

### 功能测试

- [ ] 所有页面正常加载
- [ ] 导航链接正常工作
- [ ] 产品筛选功能正常
- [ ] FAQ 折叠展开正常
- [ ] 移动端菜单正常
- [ ] 表单验证正常

### 响应式测试

- [ ] 桌面端 (1920x1080)
- [ ] 平板端 (768x1024)
- [ ] 手机端 (375x667)
- [ ] 横屏模式
- [ ] 竖屏模式

### 浏览器兼容性

- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Edge

---

## 🎨 自定义修改

### 修改品牌颜色

在所有 HTML 文件中替换:

- 主蓝色: `#3b82f6`
- 次青色: `#06b6d4`
- 深色背景: `#0f172a`
- 浅色背景: `#f8fafc`

### 修改团队信息

编辑 `team.html` 文件，找到团队成员卡片并修改:

```html
<div class="team-card">
    <div class="avatar">缩写</div>
    <h3>姓名</h3>
    <div class="role">职位</div>
    <p>职责描述</p>
</div>
```

### 修改产品信息

编辑 `products.html` 文件，找到产品卡片并修改:

```html
<div class="product-card">
    <img src="图片URL" alt="产品名称">
    <div class="product-info">
        <h3>产品名称</h3>
        <p>产品描述</p>
        <div class="product-price">$XX.XX</div>
    </div>
</div>
```

---

## 🆘 常见问题

**Q: 图片无法加载？**  
A: 确保已连接互联网，图片从 Unsplash CDN 加载。

**Q: 样式没有应用？**  
A: 清除浏览器缓存 (Ctrl+Shift+Delete) 并刷新页面。

**Q: GitHub Pages 没有更新？**  
A: 等待 1-2 分钟让部署完成，然后清除缓存并强制刷新 (Ctrl+F5)。

**Q: 移动端菜单不工作？**  
A: 确保浏览器中已启用 JavaScript。

---

## 📞 技术支持

- 📧 Email: support@romoss.com
- 📞 Phone: +1-800-ROMOSS
- 💬 Live Chat: www.romoss.com/chat

---

**最后更新:** 2024年1月  
**版本:** 1.0.0

祝您使用愉快！🎉