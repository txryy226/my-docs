# my-docs

使用 MkDocs + GitHub Actions 自动构建并部署到 GitHub Pages 的示例文档站点。

- 文档放 `docs/`
- 站点配置 `mkdocs.yml`
- 部署工作流 `.github/workflows/deploy.yml`

推送 `main` 分支后，Actions 会自动构建并部署到 `gh-pages` 分支，站点地址为：
`https://<你的用户名>.github.io/my-docs/`
