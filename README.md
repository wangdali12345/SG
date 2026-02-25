# 国工科技公司网站

一个响应式的企业官网模板，基于纯HTML/CSS/JavaScript构建。

## 项目结构

```
company-website/
├── index.html          # 主页面
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # 交互脚本
├── images/             # 图片文件夹
└── README.md           # 项目说明
```

## 功能特性

- ✅ 响应式设计，支持PC/平板/手机
- ✅ 轮播Banner
- ✅ 平滑滚动导航
- ✅ 产品展示
- ✅ 解决方案介绍
- ✅ 新闻动态
- ✅ 联系表单
- ✅ 移动端适配

## 如何使用

### 1. 本地预览

直接在浏览器中打开 `index.html` 文件即可预览。

### 2. 上传到GitHub Pages

```bash
# 1. 在GitHub创建新仓库（例如：company-website）

# 2. 初始化本地仓库
cd company-website
git init

# 3. 添加文件
git add .
git commit -m "Initial commit"

# 4. 关联远程仓库
git remote add origin https://github.com/你的用户名/company-website.git

# 5. 推送代码
git branch -M main
git push -u origin main

# 6. 在GitHub仓库设置中启用GitHub Pages
# Settings -> Pages -> Source -> 选择main分支
```

### 3. 自定义内容

#### 修改公司信息
编辑 `index.html` 中的以下内容：
- 公司名称（logo部分）
- 联系信息（地址、电话、邮箱）
- 产品信息
- 新闻内容

#### 修改样式
编辑 `css/style.css` 中的CSS变量：
```css
:root {
    --primary-color: #1e3c72;    /* 主色调 */
    --secondary-color: #2a5298;  /* 次色调 */
    --accent-color: #00a8e8;     /* 强调色 */
}
```

#### 添加图片
将图片放入 `images/` 文件夹，然后在HTML中引用：
```html
<img src="images/your-image.png" alt="描述">
```

## 浏览器兼容性

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 技术栈

- HTML5
- CSS3 (Flexbox + Grid)
- JavaScript (ES6+)
- Font Awesome 图标

## 许可证

MIT License
