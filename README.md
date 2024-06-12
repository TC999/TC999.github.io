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
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

## Step 2: Configure your site

_You turned on GitHub Pages! :tada:_

We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

### :keyboard: Activity: Configure your site

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
   ```yml
   theme: minima
   ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. (optional) Create a pull request to view all the changes you'll make throughout this course. Click the **Pull Requests** tab, click **New pull request**, set `base: main` and `compare:my-pages`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< 作者注释：页脚 >>>
  添加获取支持的链接、GitHub 状态页面、行为准则、许可证链接。
-->

---

获取帮助：[在我们的讨论区发帖](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [查看 GitHub 状态页面](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [行为准则](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT 许可证](https://gh.io/mit)

</footer>
