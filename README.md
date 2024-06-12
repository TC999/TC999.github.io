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

## 步骤 2：配置您的站点

_您已开启 GitHub Pages！🎉_

我们将在 `my-pages` 分支中进行操作，我已经为您创建了该分支，以便让您的站点看起来很棒。✨

Jekyll 使用名为 `_config.yml` 的文件来存储站点的设置、主题以及可重复使用的内容，例如站点标题和 GitHub 用户名。您可以在代码库的**代码**选项卡上查看 `_config.yml` 文件。

我们需要使用一个博客主题。在本活动中，我们将使用名为“minima”的主题。

### :keyboard: 活动：配置您的站点

1. 浏览到 `my-pages` 分支中的 `_config.yml` 文件。
2. 在右上角，打开文件编辑器。
3. 添加设置为 **minima** 的 `theme:`，使其在 `_config.yml` 文件中如下所示：
   ```yml
   theme: minima
   ```
4. （可选）您可以修改其他配置变量，例如 `title:`、`author:` 和 `description:`，来自定义您的站点。
5. 提交您的更改。
6. （可选）创建一个“拉取请求”，查看您将在本课程中进行的所有更改。点击**拉取请求**选项卡，点击**新建拉取请求**，设置 `base: main` 和 `compare:my-pages`。
7. 等待大约 20 秒，然后刷新此页面（您正在按照说明操作的页面）。[GitHub Actions](https://docs.github.com/zh/actions) 将自动更新到下一步。
<footer>

<!--
  <<< 作者注释：页脚 >>>
  添加获取支持的链接、GitHub 状态页面、行为准则、许可证链接。
-->

---

获取帮助：[在我们的讨论区发帖](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [查看 GitHub 状态页面](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [行为准则](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT 许可证](https://gh.io/mit)

</footer>
