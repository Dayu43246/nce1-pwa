# 新概念英语一 · 跟课打卡（PWA）

按 B 站「胶学」新概念第一册课程推进的 144 课学习工具：任意选课、一键跳分 P 视频、熟读成诵、作业清单、造句练习、分环节计时与饼图统计。

## 部署

本仓库用于 GitHub Pages 托管。把以下文件放在仓库根目录：

- index.html
- manifest.webmanifest
- sw.js
- icons/icon-180.png、icon-192.png、icon-512.png
- 讲义.pdf（可选）

然后在 Settings → Pages 里选择 Deploy from a branch，分支 main、目录 / (root)。

## 进度数据

学习进度存在浏览器 localStorage（nce1_pwa_v1），可用「导出/导入 JSON」或 GitHub Gist 在手机与电脑之间同步，不经过本仓库。
