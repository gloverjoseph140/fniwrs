蓝图官网娱乐【Q-——333307——】蓝图官网娱乐【 辋芷《888yx●vip》 】
蓝图官网娱乐【Q-——333307——】蓝图官网娱乐【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：GitHub Pages + Hexo 完整教程

> 想拥有一个免费、高速、可自定义的技术博客？本文手把手教你用 GitHub Pages 和 Hexo 搭建，零基础也能轻松上手。

 为什么选择 GitHub Pages + Hexo？

很多开发者想写技术博客，却卡在服务器成本和维护复杂度上。GitHub Pages 提供免费静态托管，Hexo 是超流行的静态博客框架，两者结合堪称“零成本建站最优解”。

- 完全免费：无需购买服务器和域名（当然也可以绑定自己的域名）
- 加载极快：静态页面，CDN 加速，用户体验好
- Markdown 写作：专注内容，不用折腾后台编辑器
- 生态丰富：上千款主题和插件，随时切换风格

 搭建前需要准备什么？

动手前，请确保你已经有：

1. 一个 GitHub 账号（没有的话先去注册）
2. 本地安装 Node.js（建议 LTS 版本）
3. 安装 Git 并配置好 SSH Key

以上环境就绪后，我们直接开始搭建。

 三步完成 Hexo 博客搭建

第一步：安装 Hexo 并初始化项目

打开终端，执行以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

第二步：本地预览并创作内容

启动本地服务，浏览器访问 `http://localhost:4000` 即可预览：

```bash
hexo clean && hexo g && hexo s
```

新建一篇

```bash
hexo new "我的第一篇博客"
```

第三步：部署到 GitHub Pages

在仓库设置中开启 GitHub Pages，分支选择 `main`，然后在 `_config.yml` 中修改部署配置：

```yaml
deploy:
  type: git
  repo: 你的仓库地址
  branch: main
```

最后执行一条命令，博客就发布上线了：

```bash
hexo clean && hexo g && hexo d
```

如果部署过程遇到问题想了解更详细的内容，可以查阅 [Hexo 官方部署文档](https://hexo.io/docs/deployment)。

 让你的博客更好看：主题与插件推荐

搭建好之后，个性化定制很重要。推荐几个高星主题：

- NexT：最经典的主题，简洁实用，文档完善
- Fluid：现代风设计，支持暗色模式
- Butterfly：颜值超高，适合文档类博客

常用插件也值得装上：

- `hexo-generator-search`：本地搜索功能
- `hexo-deployer-git`：Git 自动部署
- `hexo-abbrlink`：自动生成文章短链接

 日常写作与维护建议

写博客最难的是坚持。我自己的经验是：

- 固定频率：每周至少一篇，建立写作习惯
- 记录成长：把踩过的坑写下来，既是分享也是复盘
- 注重排版：善用标题层级、代码块和图片，提升阅读体验

 今天就迈出第一步

搭建独立博客，是每个开发者值得做的事。它不仅是个人品牌的沉淀，更是技术成长的见证。

> 你是用什么工具建站的呢？或者踩过哪些坑？欢迎在评论区分享你的经历，也欢迎转发给准备入坑的朋友～

如果你在搭建过程中遇到任何问题，欢迎在评论区留言，我会尽力帮你解决。觉得这篇文章对你有帮助，别忘了点赞、收藏和转发哦！

相关推荐：

https://github.com/richardsonhannah5/draixy/blob/main/2026%E7%AC%AC%E4%B8%80%E7%88%86%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E5%AE%98%E7%BD%91_%E5%81%BE%E9%80%9D%E6%A3%A0%E5%AE%9E%E6%BB%9EPCVQE.md

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />

相关推荐：

https://github.com/richardsonhannah5/draixy/commit/31f99b65e0e0eaad7c21e9dc8e4a96eb3a0da704

<img src="https://i.postimg.cc/c4bQRyjk/lantu-00008.png" />
相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E6%9D%83%E5%A8%81%E4%B8%93%E8%AE%BF%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E5%BC%80%E6%88%B7_%E7%86%AC%E5%8D%B5%E5%82%A9%E5%A0%82%E5%A3%95FFZGA.md

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />
相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/a4faec9c7c8c2787c3de30f3d33c81b9fe0b6921

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
