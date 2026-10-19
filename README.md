# 个人主页

这是一个无需构建步骤的静态个人网站，入口文件是 `index.html`。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个 **Public** 仓库。
2. 把本目录中的文件推送到仓库的 `main` 分支。
3. 打开仓库的 **Settings → Pages**，在 **Build and deployment → Source** 中选择 **GitHub Actions**。
4. 打开 **Actions**，等待 `Deploy to GitHub Pages` 工作流运行完成。
5. 发布网址会显示在工作流的部署结果和仓库 **Settings → Pages** 页面中，通常格式为 `https://<用户名>.github.io/<仓库名>/`。

之后每次推送到 `main`，网站都会自动重新部署。也可以在 **Actions** 中手动运行部署工作流。

## 本地预览

直接在浏览器中打开 `index.html` 即可。

上线前，请在 `index.html` 中将“你的名字”、示例项目和 `hello@example.com` 替换为自己的资料。
