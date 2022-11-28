## 备份 Alberthua Blog 的原始文件

- `blog-origin` 分支用于备份 Alberthua Blog 的原始文件

- 🔗 可使用 https://alberthua-perl.github.io 访问博客

- 使用以下步骤更新内容至 `main` 分支：

  ```bash
  $ git checkout blog-origin
  # 切换至 blog-origin 分支
  $ hexo generate
  # 将 blog 的 markdown 文件装换为静态网页文件
  $ hexo deploy
  # 将 blog-origin 分支中更新的文件推送至 main 分支中并触发 GitHub Action 自动执行发布 GitHub Pages 网站
  ```