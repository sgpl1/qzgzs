# Hexo 建站模板

## 使用方法

1. 在 [仓库首页](https://github.com/Dragon1573/hexo-blog) 右上角选择 [Use this template → Create new repository](https://github.com/new?template_name=hexo-blog&template_owner=Dragon1573)
2. 创建完成后，在你的仓库下修改 [`_config.yml`](./blob/main/_config.yml#L6-L10) 的第6～10行，变成你自己的自定义内容
3. 修改 [`_config.yml`](./blob/main/_config.yml#L16) 的第16行，把站点设置为你 GitHub Pages 的发布根目录
   - 如果你的仓库命名为 `<username>.github.io` ，则根目录 URL 是 `https://<username>.github.io`
   - 如果你的仓库是其他命名（比如 `hexo-blog`），则根目录 URL 是 `https://<username>.github.io/hexo-blog`
   - 如果你有属于自己的域名，则根目录就是域名本身（比如 `https://blog.example.com`）
4. 前往 [Settings → Pages](./settings/pages) ，切换 _GitHub Pages → Build and deployment → Source_ 为 _GitHub Actions_
5. 前往 [Actions](./actions) ，在左侧 [Workflows → Hexo 站点发布](./actions/workflows/hexo-deploy.yml) 选择 _Run workflow → Run workflow_
6. 访问 GitHub Pages 发布根目录，你应该能看到构建完成的站点
