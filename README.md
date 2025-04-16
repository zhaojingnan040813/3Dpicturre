# 3D旋转立方体

这是一个使用HTML、CSS和JavaScript创建的3D旋转立方体展示项目。立方体的六个面分别展示了不同的前端技术图标，包括Vue、React、Electron、Flutter、Vite和Webpack。

## 功能特点

- 3D立方体展示，每个面显示不同的技术图标
- 鼠标拖拽功能，可以自由旋转立方体
- 点击按钮触发3秒的自动旋转动画
- 响应式设计

## 在线演示

本项目已部署到GitHub Pages，你可以通过以下链接访问：
[https://你的用户名.github.io/仓库名](https://你的用户名.github.io/仓库名)

## 部署说明

本项目使用GitHub Actions自动部署到GitHub Pages。

### 部署步骤

1. Fork或克隆此仓库到你的GitHub账号
2. 进入仓库设置 (Settings)
3. 在左侧菜单找到 "Pages"
4. 在 "Build and deployment" 部分，选择 "GitHub Actions" 作为源
5. 推送代码到main分支后，GitHub Actions会自动构建并部署项目

### CI/CD配置

项目已配置GitHub Actions工作流，每当推送到main分支时，会自动部署到GitHub Pages。工作流配置文件位于 `.github/workflows/deploy.yml`。

## 本地开发

由于项目是纯HTML/CSS/JS，你可以直接在浏览器中打开index.html文件进行本地预览。

## 许可证

MIT