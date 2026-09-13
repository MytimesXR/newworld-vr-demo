# 新世界 · 鱼眼互动电影

GitHub Pages 静态网页版本，无依赖、无需构建。保留鱼眼展开、拖动环视、参数校准、全屏及 A/B 汇合逻辑。

## 发布

1. 在 GitHub 新建仓库（例如 newworld-vr-demo）。免费个人账号可用公开仓库。
2. 将本包解压后的 index.html 与 README.md 上传到仓库根目录并提交。使用 Git 上传时同时保留 .nojekyll 和 .gitignore。
3. 仓库 Settings → Pages → Source 选择 Deploy from a branch。
4. Branch 选择 main，目录选择 /(root)，点击 Save。
5. 等待 Pages 部署完成，在同一设置页点击 Visit site。

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 使用视频

默认点击“选择四段视频”，一次选入：
- 9-3接9-4.mp4：共同开场
- 9-5（A）.mp4：分支 A
- 9-6（B）.mp4：分支 B
- 9-7.mp4：共同后续

文件通过浏览器本地读取，不会上传。每位访问者需要自己选择本机视频；刷新后重新选择。仅发布网页不会让其他人直接看到你电脑里的视频。

“播放站点视频”保留相对路径 videos/原文件名 加载能力，只有你另行把对应视频部署到该路径才可用。本包不含视频。

完整原画与鱼眼展开可切换。展开参数为近似预览，未进行镜头标定。代码语法检查通过；尚未完成浏览器实际播放及线上部署验证。
