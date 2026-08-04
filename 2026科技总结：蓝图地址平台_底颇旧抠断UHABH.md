蓝图地址平台【Q-——333307——】蓝图地址平台【 辋芷《888yx●vip》 】
蓝图地址平台【Q-——333307——】蓝图地址平台【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hugo 完整教程

还在羡慕别人炫酷的技术博客？其实你只需要一个 GitHub 账号，就能免费搭建出属于自己的静态博客。今天这份 GitHub Pages 搭建教程，手把手带你完成从环境配置到域名绑定的全流程，建议先收藏再慢慢操作。

 为什么选择 GitHub Pages + Hugo？

GitHub Pages 免费托管 自带 HTTPS 加密，支持自定义域名，且无限流量。而 Hugo 静态博客生成器 以秒级构建速度著称，无需数据库，Markdown 写文章自动生成页面。两者结合，是目前 程序员建站的最佳方案。

 环境准备（3分钟）

首先安装 Homebrew（macOS）或 Chocolatey（Windows），然后执行：

```bash
brew install hugo   或 choco install hugo
git --version        确认已安装Git
```

 五步搭建你的博客

第一步：创建站点
```bash
hugo new site my-blog && cd my-blog
```

第二步：安装主题
推荐 [LoveIt](https://github.com/dillonzq/LoveIt) 主题，支持暗色模式和代码高亮：

```bash
git init && git submodule add https://github.com/dillonzq/LoveIt.git themes/LoveIt
```

第三步：写第一篇文章
```bash
hugo new posts/first-post.md
```
编辑 `first-post.md`，添加 `draft: false` 即可发布。

第四步：本地预览
```bash
hugo server -D
```
浏览器访问 `http://localhost:1313` 就能实时预览效果。

第五步：部署到 GitHub
```bash
hugo   生成静态文件
git add . && git commit -m "首次提交"
git remote add origin 你的仓库地址
git push -u origin main
```
然后在仓库 Settings → Pages 中，将 Source 选为 `main` 分支的 `/docs` 目录，保存即可。

 进阶技巧：绑定自定义域名

在仓库根目录创建 `CNAME` 文件，内容填你的域名（如 `blog.example.com`），再到域名 DNS 商处添加 CNAME 记录指向 `你的用户名.github.io`，等待 DNS 生效即可。

 常见问题排查

- 页面 404：检查仓库名是否为 `用户名.github.io`
- 样式丢失：确认主题配置文件 `config.toml` 中的 `baseURL` 是否填对了
- 图片加载失败：静态文件路径需以 `/` 开头，如 `/images/cover.jpg`

完成部署后记得回来评论分享你的博客地址，我会去访问学习！遇到任何问题也可以在下方留言，我会逐一解答。关注我获取更多 GitHub 技巧 和 前端开发 干货！

---

本文已收录于「GitHub 从入门到精通」系列，持续更新中。

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E5%AE%98%E6%96%B9%E7%A7%91%E6%99%AE%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E5%BC%80%E6%88%B7_%E6%8C%9B%E5%96%82%E8%92%99%E5%AF%90%E5%AF%90CJYAQ.md

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/c169a9186980931100132b03d3527ed9b11f2696

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/blob/main/%E6%82%A6%E4%BA%AB%E6%96%87%E9%9F%B5%E6%97%B6%E5%85%89%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E7%BD%91%E5%9D%80_%E7%94%B7%E8%AE%B2%E7%A4%81%E6%97%B1%E6%B7%98NMNWQ.md

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/commit/9d1b484058738f17e85d73c7b2342ca5830cf739

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
