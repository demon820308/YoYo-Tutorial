# AI 创作教程站

四门提示词写作课的合集站，部署到 Cloudflare Pages（Git 绑定，push 到 main 即自动重新部署）。

- `index.html` — 门户首页
- `minimax-h3/` — 《MiniMax H3 教程：学会写 MiniMax H3 提示词》
- `higgsfield/` — 《Higgsfield 提示词教程：把想法，写成镜头》
- `midjourney/` — 《Midjourney 教程：从第一张图到稳定出好图》
- `cinedance-lira-acting/` — 《CineDance × LIRA × 表演系统教程：从出图、导镜头到演人物》

四套教程各自是单文件 HTML（由 Muse 网页教程导出后加了全站顶栏），内容更新时替换对应文件并 push 即可。

部署：Cloudflare Pages 项目 `yoyo-tutorial`（yoyo-tutorial.pages.dev），Git 绑定本仓库 main 分支，push 即自动部署；无构建命令，输出目录为仓库根目录。
