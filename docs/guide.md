# 使用指南

1. 修改 docs 目录中的 Markdown 文件。
2. 在本地预览并检查页面及链接。
3. 提交修改并推送到 main 分支。
4. 在 Actions 页面查看构建与部署状态。
5. 打开网站检查内容是否更新。

## 常用命令

- `python -m mkdocs serve`：本地预览。
- `python -m mkdocs build --strict`：构建网站并严格检查警告。

## 注意事项

- 本地预览时修改文件会实时刷新浏览器，方便调试。
- 构建时使用 `--strict` 参数会将警告视为错误，有助于发现死链接等问题。
- 推送到 main 分支后，GitHub Actions 会自动触发部署，无需手动操作。
