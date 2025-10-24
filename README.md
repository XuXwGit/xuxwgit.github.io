# xuxw.github.io

静态个人主页，将通过 GitHub Pages 部署到 https://xuxw.github.io。

## 自定义内容
- 在 `index.html` 的“关于我”部分替换为你的真实简介。
- 在“项目”部分更新项目名称、描述和 GitHub 链接。
- 在“联系我”部分填写常用邮箱并根据需要调整社交链接。
- 若需增加更多项目或信息，可复制现有卡片结构或新增段落。

## 部署 GitHub Pages
1. 确认仓库名称为 `xuxw.github.io` 并保持公开（Public）。
2. 将最新内容推送到默认分支（通常为 `main`）。
3. 在 GitHub 仓库页面中打开 **Settings → Pages**，将 **Source** 设置为 `Deploy from a branch`，并选择 `main` 分支与 `/ (root)` 目录，保存设置。
4. 等待几分钟，让 GitHub Pages 完成首次构建与发布，可在 **Actions** 页面查看进度。
5. 发布完成后访问 https://xuxw.github.io 验证页面是否正常展示。

### 常见问题：访问 404
- 如果出现 “There isn't a GitHub Pages site here” 提示，通常表示 Pages 未成功发布。请再次确认以上设置是否保存，并确认仓库包含 `index.html` 文件且位于根目录。
- 第一次启用 Pages 后需要数分钟才会生效，稍等片刻后刷新页面。
- 如仍然报错，可在仓库的 **Settings → Pages** 页面下方查看 Build logs，或在 **Actions** 里排查部署流程是否失败。
