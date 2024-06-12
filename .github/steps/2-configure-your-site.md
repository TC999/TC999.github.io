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
7. 等待大约 20 秒，然后刷新此页面（您正在按照说明操作的页面）。[GitHub Actions](https://docs.github.com/en/actions) 将自动更新到下一步。 