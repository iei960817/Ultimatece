ULTIMATE V7 Liquid Glass 网站补丁包使用说明
=============================================

压缩包内文件目录结构：
├── index.html          （Apple 液态玻璃质感前端主页面，含开场黑曜石过渡、重温开场自动跳回首页、完整大图右下角关闭按钮、手机自适应及动态加购系统）
├── data.json           （全站数据文件，已预填 PDF 加购清单并移除凉亭拱门，含你设置的 Google OAuth Client ID 与 Google Sheets 接收网址）
└── admin/config.yml    （Decap CMS 后台配置文件，支持自由新增加购分类、增删改项目与价格，且 Google 两个字段已改为非必填）

更新步骤：
1. 解压本压缩包。
2. 将 index.html、data.json 和 admin/config.yml 上传覆盖到你的 GitHub 仓库 iei960817/Ultimatece 的对应位置（注意保持 admin/config.yml 在 admin 文件夹内，不要多套一层外层目录）。
3. 推送到 main 分支后，Netlify 会自动触发重新部署。
