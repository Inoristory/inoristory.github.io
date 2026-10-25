# inoristory.github.io

两个站，同一套 [anzhiyu](https://github.com/anzhiyu-c/hexo-theme-anzhiyu) 主题：

| 路径 | 内容 |
| --- | --- |
| `/` | [Misaka Home](https://misaka.sakurakoi.top/) 的本地静态复刻（161 篇文章、追番、友链、归档等全量页面） |
| `/inori/` | 我的博客 —— 由 [inoristory.top](http://inoristory.top/)（Halo 2 + fuwari 主题）迁移而来，16 篇文章 |

## 本地预览

站点用的是根绝对路径（`/css/...`、`/img/...`），必须通过 HTTP 访问，直接双击 `index.html` 会掉样式。

```bash
# 任选一个静态服务器
npx serve .          # 或 python -m http.server 8000
```

## 说明

- 所有第三方 CDN 资源（样式、脚本、字体、图片）都已镜像到 `_vendor/<域名>/` 下，断网也能正常渲染。
- 少数资源在原站本身就是坏的（追番封面 `bangumi.tv`、部分友链头像域名失效），此处保持原状。
- 博客部分 `/inori/` 的图片在 `inori/upload/`，已统一转成 webp。
- 完整复刻/迁移过程与校验报告见本地项目的 `README.md`。
