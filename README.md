# C项目｜富恩資產管理有限公司落地页系统

## 项目标识

- 项目称呼：C项目
- 本地目录：`C:\Users\DELL\Documents\湾湾贷款\quncheng-funnel`
- GitHub 仓库：`https://github.com/guilireddin-art/quncheng-funnel`
- 正式域名：`https://ezsolut.com`
- GitHub Pages 原始地址：`https://guilireddin-art.github.io/quncheng-funnel/`
- Supabase 项目 ID：`ijzywhrnhvldkjdwfdyy`
- 品牌名称：富恩資產管理有限公司

## 来源与结构

C项目最初参考用户提供的三段式页面流程，当前已经改造成独立的多 Page 落地页及客户管理系统。

- `index.html`：品牌介绍页
- `loan.html`：贷款金额选择页
- `apply.html`：贷款评估申请页
- `admin.html`：主账号 Page 管理后台
- `leads-admin.html`：主账号全部客户后台
- `page-admin.html`：投手独立客户后台

页面链路：

`index.html?page=页面代号` → `loan.html?page=页面代号` → `apply.html?page=页面代号`

## 数据来源

C项目使用独立 Supabase 项目 `ijzywhrnhvldkjdwfdyy`。

它不连接旧“湾湾贷款”项目的数据源。不同投手的客户数据通过 `page_slug` 隔离，主账号可以查看全部 Page 数据。

## 发布方式

项目通过 GitHub 仓库 `guilireddin-art/quncheng-funnel` 的 `main` 分支发布到 GitHub Pages，并绑定正式域名 `ezsolut.com`。
