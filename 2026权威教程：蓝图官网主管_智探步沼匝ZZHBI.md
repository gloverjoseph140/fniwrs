蓝图官网主管【Q-——333307——】蓝图官网主管【 辋芷《888yx●vip》 】
蓝图官网主管【Q-——333307——】蓝图官网主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

你是不是也想拥有一个属于自己的技术博客，却苦于服务器成本高、维护麻烦？别担心，GitHub Pages 免费托管 + Hexo 静态博客框架，就是最适合开发者的解决方案。本文手把手带你从零开始，20分钟上线你的第一个个人网站。

 为什么选择 GitHub Pages ?

- 完全免费：无限流量，无需购买服务器
- 版本管理：Markdown 写作，Git 提交，天然适配开发者习惯
- 速度极快：静态页面，CDN 加速，全球访问流畅
- 自定义域名：支持绑定自己的域名，彰显个人品牌

 一、环境准备（3分钟）

首先确保你的电脑已安装：
- Node.js（建议 v16+）
- Git
- GitHub 账号

没有安装？前往 [nodejs.org](https://nodejs.org) 和 [github.com](https://github.com) 下载即可，一路默认安装。

 二、搭建 Hexo 框架（5分钟）

打开命令行，执行以下命令：

```bash
 全局安装 hexo-cli
npm install -g hexo-cli

 初始化博客项目
hexo init my-blog
cd my-blog

 安装依赖
npm install

 本地预览
hexo server
```

浏览器访问 `http://localhost:4000`，看到默认页面就说明成功了。

 三、部署到 GitHub Pages（8分钟）

1. 创建仓库：在 GitHub 新建仓库，命名为 `你的用户名.github.io`

2. 安装部署插件：
```bash
npm install hexo-deployer-git --save
```

3. 配置 _config.yml 文件：
```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

4. 一键部署：
```bash
hexo clean && hexo generate && hexo deploy
```

稍等片刻，访问 `https://你的用户名.github.io`，你的博客就上线了！

 四、优化与个性化

- 更换主题：在 [Hexo Themes](https://hexo.io/themes/) 挑选喜欢的主题，下载到 themes 目录，修改配置即可
- 评论系统：集成 Gitalk 或 Valine，让读者能与你互动
- SEO 优化：安装 `hexo-generator-seo-friendly-sitemap`，生成站点地图

 遇到问题怎么办？

评论区告诉我你卡在哪一步，我会第一时间回复。如果觉得这个教程有用，点个赞让更多开发者看到。

---

行动号召：动手实践是学习的最佳路径，今天就去申请你的 GitHub Pages 吧！欢迎在评论区分享你的博客地址，大家一起交流进步。关注我，后续带来更多部署技巧和写作效率工具分享。

相关推荐：

https://github.com/martinezkelly827/fwhecg/blob/main/2026%E6%9D%83%E5%A8%81%E8%AE%B2%E8%A7%A3%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E5%AE%A2%E6%9C%8D_%E9%80%9F%E5%8F%8A%E6%8E%80%E6%AD%89%E6%85%B0HOPCW.md

<img src="https://i.postimg.cc/c4bQRyjk/lantu-00008.png" />

相关推荐：

https://github.com/martinezkelly827/fwhecg/commit/e50b9765bfac6ef803bde9cd3e39de22d305017d

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />
相关推荐：

https://github.com/rhodesandrea462/zjvmux/blob/main/%E6%B2%89%E9%86%89%E6%96%87%E5%BF%83%E5%AF%BB%E6%A2%A6%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E6%B7%98%E6%99%AE%E5%A3%81%E5%B7%B1%E9%92%BEBHCWJ.md

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />
相关推荐：

https://github.com/rhodesandrea462/zjvmux/commit/08709123d9dd809143ec2a8c4c886e5a7c2b462a

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
