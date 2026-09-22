# 意大利旅行手册

单文件静态网页，入口为 index.html。无需安装依赖或构建。

## GitHub + Vercel

在 Vercel 新建项目，导入本仓库，Framework Preset 选择 Other，Root Directory 保持仓库根目录。vercel.json 已配置为直接发布静态页面。

生产分支使用 main，发布后 main 分支的新提交会自动触发部署。生产网址应允许访客直接访问；若出现登录要求，检查项目的 Deployment Protection 设置。

## 离线与行李清单

下载 index.html 即可离线查看。地图导航与外部网站需要网络。

当前行李新增保存在访问者自己的浏览器；多人共享同步尚未接入数据库，不会自动共享给其他设备。

订单二维码、证件号、确认号和 PIN 不包含在网页中。
