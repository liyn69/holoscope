# GitHub Pages 发布说明

本目录是静态站点根目录，已包含：

- `index.html`
- `styles.css`

## 一、最简发布方式（推荐）

1. 将当前项目推送到 GitHub 仓库。
2. 打开仓库页面 -> **Settings** -> **Pages**。
3. 在 **Build and deployment** 中选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/docs`
4. 保存后等待 1~3 分钟即可访问。

## 二、访问地址格式

发布成功后地址通常为：

- `https://<你的GitHub用户名>.github.io/<仓库名>/`

## 三、如果要绑定自定义域名

可在 `docs/` 下创建 `CNAME` 文件，内容为你的域名（例如 `www.example.com`）。

> Redeploy trigger: 2026-04-10
