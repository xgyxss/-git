在 GitHub 上查找资源时，可以发现很多项目被创建成了 GitHub Pages，遂想为单个项目创建 GitHub Pages，网上的教程很多，顺便也学习记录一下创建步骤：

1. 打开一个项目

2. Settings

3. Pages

   - 如果是私人仓库，会提示：Upgrade or make this repository public to enable Pages

     GitHub Pages is designed to host your personal, organization, or project pages from a GitHub repository.

     [Upgrade](https://github.com/account/upgrade)

   - 如果是共有仓库，将 Source 处改为：Github Actions。然后根据提示，可配置主题、域名、HTTPS。

4. GitHub Actions

5. 选择/创建 workflows

此时，在该项目的 About 处即可添加 Edit repository details（单击 About 右侧的齿轮⚙️图标），可以看到默认的 Website 就是 xgyxss.github.io/git/，由于 xgyxss.github.io 已经设置了域名 yexingshusheng.com，且本项目没有设置域名，则该链接会跳转到对应的 yexingshusheng.com/git 下。

> rf.
>
> [官方的创建步骤](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow)
>
> [用Github搭建一个静态页面，公开和私有设置](https://blog.csdn.net/weixin_44786530/article/details/123976291)

