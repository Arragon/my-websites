# my-websites

这是 Arragon 的静态网页存档，首页是自动生成的导航页。

## 目录结构

- `pages/projects/`：一般项目企划与项目文档。
- `pages/projects/RTS-game-design/`：RTS 游戏设计、概念艺术与 AI 辅助生产管线文档。
- `pages/knowledge/literature/`：文学与美学知识地图。
- `pages/knowledge/philosophy/`：哲学与思想知识地图。

## 添加新页面

将 `.html` 或 `.htm` 文件上传到 `pages/` 下对应的主题目录并推送到 `main`。导航页会递归读取目录并按子目录分组，因此通常不需要手工维护页面清单。

导航同时会检查目标页面是否已经由 GitHub Pages 实际发布。原因是 `main` 分支会先于 GitHub Pages 部署更新；GitHub 官方说明推送后站点更新可能需要数分钟。因此刚上传的新文件可能暂时显示为“等待 Pages 发布”，而不会提前生成一个会返回 404 的链接。

RTS 相关页面统一放在：

`pages/projects/RTS-game-design/`

对应公开地址形式为：

`https://arragon.github.io/my-websites/pages/projects/RTS-game-design/文件名.html`

导航首页：

`https://arragon.github.io/my-websites/`

建议使用稳定、清晰的文件名。移动或重命名页面时，应同步检查页面内部是否存在指向旧路径的相对链接。
