# istiocn.github.io

Istio 中文文档站点（[istio.cn](https://istio.cn) / [istiocn.github.io](https://istiocn.github.io)）的静态发布内容。

## 说明

- 本仓库保存的是**已构建的静态站点**（HTML/CSS/JS 及静态资源），而非文档源文件。
- 页面由 Istio 官方文档源（[istio/istio.github.io](https://github.com/istio/istio.github.io)）结合中文翻译构建生成。
- 请勿直接编辑生成的 HTML，改动会在下次构建时被覆盖；如需修改内容，应在文档源仓库中修改后重新构建发布。

## 目录结构

| 路径 | 内容 |
| --- | --- |
| `index.html` | 站点首页 |
| `docs/` | 文档：概念、安装、任务、参考等 |
| `blog/` | 博客文章 |
| `help/` | 常见问题、运维指南、术语表 |
| `about/` | 关于、参与贡献、版本说明 |
| `en/`、`zh/` | 英文 / 中文语言入口 |
| `css/`、`js/`、`img/`、`favicons/` | 样式、脚本与图片资源 |
| `static/CNAME` | 自定义域名配置（`istio.cn`） |

## 发布

站点通过 GitHub Pages 发布。默认分支为 `master`，同时提供 `gh-pages` 分支。

## 维护者

参见 [`OWNERS`](OWNERS)。
