# 全屏粒子爱心

基于 [Ares006-007/HEART-ANIMATION](https://github.com/Ares006-007/HEART-ANIMATION) 的原始粒子轨迹与心跳算法，修复手机画幅过小的问题。

## 使用

本仓库是无需构建的静态网页。将 GitHub Pages 的发布来源设为 `main` 分支、`/ (root)` 目录即可发布。分享 Pages 网站链接，对方用手机浏览器打开即可看到动画，无需登录或安装应用。

本地使用时，保留 `index.html`、`script.js`、`style.css` 及 `assets/` 目录的相对位置，打开 `index.html`。

## HJR 定制

页面底部不显示原作文字水印；爱心中心显示花体 `HJR`。原作者署名保留在本说明、HTML 注释及 `script.js` 中。

花体字体使用 [Great Vibes](https://github.com/google/fonts/tree/main/ofl/greatvibes)，由本站托管，不依赖第三方字体服务。字体版权属于 The Great Vibes Pro Project Authors，按 SIL Open Font License 1.1 使用与分发，完整许可见 `assets/OFL.txt`。

## 手机适配

- 修正 HTML、viewport 与样式链接拼写。
- Canvas 填满网页可视区域，不再使用原版手机宽高减半的设置。
- 根据横竖屏尺寸调整心形，监听窗口与 visualViewport 的尺寸变化。
- 保留原作的红色粒子、轨迹与心跳效果。
- 防止粒子到达目标点时出现除以零。

“全屏”指网页画布填满浏览器可视区域；手机浏览器地址栏由浏览器控制。

## 原作者及使用范围

原作者：[Ares006-007](https://github.com/Ares006-007)。本仓库保留原作者署名。

上游 README 允许学习与个人使用、修改和复用，要求发布修改版时署名原作者。请遵循上游提供的使用说明；本仓库不将该授权改称为 MIT 等其他许可证。
