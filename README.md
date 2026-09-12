# liushucheng111.github.io

个人主页 · 基于 GitHub Pages 的静态站点。

## 内容板块
- 姓名与一句话简介
- 教育背景（时间线）
- 研究方向
- 技能列表
- 联系方式

## 技术说明
- 纯静态：`index.html` + `style.css` + `main.js`，无任何外部依赖，离线可用。
- 响应式设计：桌面与手机自适应，含移动端折叠菜单。
- 深色 / 浅色主题切换（选择记忆在 `localStorage`）。
- 滚动出现动画（IntersectionObserver）。

## 本地预览
直接双击 `index.html` 即可在浏览器打开；或使用本地服务器：

```bash
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 自定义
打开 `index.html`，替换以下占位内容：
- 姓名、一句话简介
- 教育背景中的学校 / 时间 / 描述
- 研究方向卡片
- 技能标签
- 联系方式中的邮箱与链接

## 部署
仓库开启 GitHub Pages（Source 选择 `main` 分支根目录），站点地址：
`https://liushucheng111.github.io`
