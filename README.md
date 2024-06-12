<header>

<!--
  <<< 作者注释：课程标题 >>>
  包括一张 1280×640 的图片、句子格式的课程标题和一段重点说明的简短描述。
  在您的仓库设置中：启用模板仓库，添加您的 1280×640 社交图片，自动删除 head 分支。
  添加您的开源许可证，GitHub 使用 MIT 许可证。
-->

# GitHub Pages

_使用 GitHub Pages 从您的 GitHub 仓库创建网站或博客。_

</header>

<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked the file path. Previous version checked the front matter formatting.
-->

## 步骤 4：创建一篇博文

_您的主页看起来棒极了！:cowboy_hat_face:_

GitHub Pages 使用 Jekyll。在 Jekyll 中，我们可以使用特殊命名的文件和 Frontmatter 来创建博客。 文件必须命名为 `_posts/YYYY-MM-DD-title.md`。 您还必须在 Frontmatter 中包含 `title` 和 `date`。

**什么是 _frontmatter_？**: Jekyll 文件使用的语法称为 YAML frontmatter。 它位于文件顶部，如下所示：

```yaml
---
title: "Welcome to my blog"
date: 2019-01-20
---
```

有关配置 Frontmatter 的更多信息，请参阅 [Jekyll Frontmatter 文档](https://jekyllrb.com/docs/frontmatter/)。

### :keyboard: 活动：创建一篇博文

1. 浏览到 `my-pages` 分支。
1. 单击 `Add file` 下拉菜单，然后单击 `Create new file`。
1. 将文件命名为 `_posts/YYYY-MM-DD-title.md`。
1. 将 `YYYY-MM-DD` 替换为今天的日期，并根据需要更改您的第一篇博文的 `title`。
   > 如果您确实编辑了标题，请确保单词之间有连字符。
   > 如果您的博文日期不符合正确的日期约定，您将收到错误消息，并且您的网站将无法构建。 有关更多信息，请参阅“[页面构建失败：帖子日期无效](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/troubleshooting-jekyll-build-errors-for-github-pages-sites)”。
1. 在博文顶部键入以下内容：
   ```yaml
   ---
   title: "YOUR-TITLE"
   date: YYYY-MM-DD
   ---
   ```
1. 将 `YOUR-TITLE` 替换为您的博文标题。
1. 将 `YYYY-MM-DD` 替换为今天的日期。
1. 键入您的博文快速草稿。 请记住，您以后随时可以对其进行编辑。
1. 将您的更改提交到您的分支。
1. 等待大约 20 秒，然后刷新此页面（您正在按照说明操作的页面）。 [GitHub Actions](https://docs.github.com/en/actions) 将自动更新到下一步。

<footer>

<!--
  <<< 作者注释：页脚 >>>
  添加获取支持的链接、GitHub 状态页面、行为准则、许可证链接。
-->

---

获取帮助：[在我们的讨论区发帖](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [查看 GitHub 状态页面](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [行为准则](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT 许可证](https://gh.io/mit)

</footer>
