# Chang Jin — CV

这是用于在线展示个人简历 PDF 的静态网站。

## 发布到 GitHub Pages

1. 将本仓库的更改推送到 `main` 分支。
2. 在 GitHub 仓库打开 **Settings → Pages**。
3. 在 **Build and deployment → Source** 中选择 **GitHub Actions**。
4. 打开 **Actions** 页面，等待 **Deploy CV to GitHub Pages** 工作流完成。

发布地址：<https://jinchang1223.github.io/cv/>

以后更新简历时，只需替换 `Chang_Jin_CV.pdf` 并推送到 `main`；网页会自动重新部署。

## 本地预览

在仓库目录运行：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。
