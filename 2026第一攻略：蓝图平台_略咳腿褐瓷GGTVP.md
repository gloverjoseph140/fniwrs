蓝图平台【Q-——333307——】蓝图平台【 辋芷《888yx●vip》 】
蓝图平台【Q-——333307——】蓝图平台【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

你是否想过拥有一个完全属于自己的技术博客？无需购买服务器，不用备案，甚至不需要懂太多代码——GitHub Pages + Hexo 组合就能帮你实现。这篇文章手把手教你从零搭建，全程免费，还能顺便提升你的 GitHub 活跃度。

 为什么选择 Hexo + GitHub Pages？

优点非常明确：
- 零成本：托管在 GitHub 上，完全免费，无限流量
- 极速访问：GitHub Pages 全球 CDN 加速，国内访问速度也可接受
- Markdown 写作：专注内容，无需关心排版
- SEO 友好：静态页面，搜索引擎收录率高（本文就附带 `keywords` 标签优化建议）

 第一步：环境准备（5分钟）

你需要准备：
- GitHub 账号（没有的话先去注册）
- Node.js 环境（建议 v18+，官网下载 LTS 版本）
- Git 工具（Windows 用户推荐 Git Bash）

> 小提示：在终端输入 `node -v` 和 `git --version` 可验证安装是否成功。

 第二步：安装 Hexo 并初始化项目

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

三条命令搞定框架安装。初始化完成后，你的本地博客已经可以运行了：

```bash
hexo s
```

浏览器访问 `http://localhost:4000` 即可预览默认主题。

 第三步：部署到 GitHub Pages

1. 在 GitHub 新建仓库，命名为 `你的用户名.github.io`
2. 修改站点配置文件 `_config.yml`：
   ```yaml
   deploy:
     type: git
     repo: https://github.com/用户名/用户名.github.io.git
     branch: main
   ```
3. 安装部署插件并推送：
   ```bash
   npm install hexo-deployer-git --save
   hexo d
   ```

完成！ 访问 `https://你的用户名.github.io`，你的博客已经上线了。

 第四步：发布第一篇文章

```bash
hexo new post "我的第一篇博客"
```

编辑 `source/_posts/` 下的 Markdown 文件，在头部添加标签：

```yaml
---
title: 我的第一篇博客
tags: [教程, GitHub]
keywords: GitHub Pages, Hexo, 个人博客, 免费建站
description: 手把手教你用 GitHub Pages 和 Hexo 搭建免费个人博客，含完整步骤和SEO优化技巧
---
```

写完后执行 `hexo g && hexo d`，文章就发布到线上啦！

---

互动引导 🔥：
- 如果你在搭建过程中遇到任何报错，欢迎在评论区留言，我看到后会逐一回复
- 觉得有用的话，点个「赞」让更多小伙伴看到
- 关注我，后续会更新「Hexo 主题美化」「自定义域名绑定」等高阶教程

标签：`GitHub Pages` `Hexo` `个人博客` `免费建站` `前端开发` `SEO优化`

祝你早日拥有自己的技术花园！🌱

相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E7%A7%91%E6%8A%80%E7%9B%98%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80%E5%AE%98%E7%BD%91_%E5%A4%9C%E6%9E%B7%E8%BF%AB%E5%88%83%E6%8B%96ZTNOI.md

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

相关推荐：

https://github.com/leebradley6/ubrqlg/commit/83a859d62dd07bf3a723e35a0b967ac1867b86cb

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/blob/main/2026%E5%AE%98%E7%BD%91%E7%A7%91%E6%99%AE%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80%E6%B3%A8%E5%86%8C_%E6%97%B1%E5%92%B3%E7%88%AC%E7%93%B7%E9%9F%B5XXMBP.md

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/commit/7eea1d4df447f834ea708e86b505073f2102a29f

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
