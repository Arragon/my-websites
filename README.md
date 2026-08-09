# my-web

这是 Arragon 的静态网页存档，首页是自动生成的导航页。

## 添加新页面

将任意 `.html` 或 `.htm` 文件上传到 [`pages/`](./pages/) 下对应的主题目录并推送到 `main`。主页会递归读取这些目录、按主题分组展示，因此不需要再编辑 `index.html` 或维护页面清单。

当前主题目录为：`pages/projects/`（项目企划）、`pages/knowledge/literature/`（文学与美学）和 `pages/knowledge/philosophy/`（哲学与思想）。新增主题时可直接创建新的子目录，导航会以目录名作为分组标题；如需更友好的中文标题，再为其补充导航映射即可。

页面地址为：`https://arragon.github.io/my-websites/pages/文件名.html`。启用 GitHub Pages 后，导航首页地址为：`https://arragon.github.io/my-websites/`。

建议使用清晰的英文、中文或下划线文件名；导航会自动把下划线和连字符显示为空格。
personal webs
