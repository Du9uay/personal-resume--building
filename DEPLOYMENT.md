# 📦 部署指南

## ✅ 部署状态

项目已成功配置GitHub Pages自动部署！

## 🚀 快速访问

**在线地址**: https://du9uay.github.io/personal-resume-wenlv/

> ⏰ 首次部署需要等待3-5分钟生效

## 📋 部署步骤

### 1. 启用 GitHub Pages（必须）

1. 访问: https://github.com/Du9uay/personal-resume-wenlv/settings/pages
2. 在 **Source** 部分选择 **GitHub Actions**
3. 点击 **Save** 保存设置
4. 等待部署完成（约3-5分钟）

### 2. 检查部署状态

访问: https://github.com/Du9uay/personal-resume-wenlv/actions

查看工作流运行状态：
- ✅ 绿色勾号 = 部署成功
- 🟡 黄色圆圈 = 正在部署
- ❌ 红色叉号 = 部署失败

### 3. 访问网站

部署成功后，访问: https://du9uay.github.io/personal-resume-wenlv/

## 🔧 故障排除

### 问题1: 404错误
- **解决**: 确保GitHub Pages已启用，Source选择"GitHub Actions"

### 问题2: 样式或图片不显示
- **解决**: 清除浏览器缓存，使用Ctrl+F5强制刷新

### 问题3: 地图不显示
- **解决**: 等待所有资源加载完成，worldZH.json文件较大(4MB)

### 问题4: Actions失败
- **解决**: 检查 https://github.com/Du9uay/personal-resume-wenlv/actions 查看错误信息

## 📝 更新部署

每次推送代码到main分支，网站会自动更新：

```bash
git add .
git commit -m "更新内容"
git push
```

## 🌍 其他部署选项

### Vercel（推荐备用）
1. 访问 https://vercel.com
2. 点击 "Import Git Repository"
3. 选择 personal-resume-wenlv
4. 点击 Deploy

### Netlify
1. 访问 https://app.netlify.com
2. 拖拽项目文件夹到页面
3. 自动部署

### Cloudflare Pages
1. 访问 https://pages.cloudflare.com
2. 连接GitHub账号
3. 选择项目部署

## 📊 性能优化建议

1. **图片优化**: 考虑压缩图片大小
2. **CDN加速**: 使用CDN加载ECharts库
3. **缓存策略**: 配置浏览器缓存

## 💡 提示

- GitHub Pages完全免费
- 支持自定义域名
- 自动HTTPS证书
- 全球CDN加速

---

**最后更新**: 2024-08-22
**状态**: 🟢 已配置，等待启用