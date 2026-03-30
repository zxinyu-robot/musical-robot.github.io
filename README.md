# zxinyu-robot.github.io

个人主页（GitHub Pages）Hugo 模板。

## 本地预览

需要安装 `hugo`：

```bash
cd zxinyu-robot.github.io
hugo server -D
```

然后打开 `http://localhost:1313`。

## 部署

该仓库使用 GitHub Actions 自动构建并发布到 `gh-pages` 分支。

你需要：
1. 在 GitHub 新建仓库：`zxinyu-robot.github.io`
2. 把本地代码推送到该仓库的默认分支（workflow 默认监听 `main`）
3. 在 GitHub 仓库设置里确认 Pages 使用 GitHub Actions 部署

## 内容结构

- 主线分章节目录：
  - `/about/`
  - `/experience/`
  - `/education/`
  - `/contact/`
- 支线代表项目：
  - `/projects/slam-runtime-architecture/`
  - `/projects/placeholder-project/`

