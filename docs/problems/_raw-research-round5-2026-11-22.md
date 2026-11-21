# 原始调研记录 · 第五轮 · 2026-11-22

> 渠道：主 agent 直采。新品类：Git forge（Gitea）、邮件服务器（mailcow）、
> 日历/表单/身份（Nextcloud Calendar / Formbricks / Zitadel）、
> V2EX 深挖（需求管理工具）。
> 抽查：所有建卡条目均通过 gh api 抓正文/评论原文确认。

## 本轮产出

- 新建卡 8 张：P-120 ~ P-127
- 扩充旧卡 2 张：P-017 / P-048

## 已建卡映射

| 来源 | 卡 |
|---|---|
| Nextcloud Calendar#3044 团队日历变僵尸 | P-120 |
| Gitea#3217 公开仓库私有 issue | P-121 |
| Gitea#1872/#1612/#18240/#14186 子组/联邦 | P-122 / P-127 |
| Zitadel#6601/#5822/#8835 SCIM/用户组/跨组织移动 | P-123 |
| Nextcloud Calendar#2766 + Deck#2399 外部日历只读 | P-124 |
| V2EX t365438 工具积灰 | P-125 |
| mailcow#4969 + Twake#130 推送专有依赖 | P-126 |

## 未建卡条目（证据池）

| 来源 | 👍/评论 | 说明 |
|---|---|---|
| Gitea#1029 Gitea hosted Gitea（自举路线图） | 296/99 | 自托管工具自我托管 |
| Gitea#16670 Gist 型仓库 | 137/37 | 轻量知识分享载体 |
| Gitea#13539 内置 CI/CD（GitHub Actions 兼容） | 266/96 | 集成生态 |
| Gitea#23668 Actions 手动触发 | 176/23 | — |
| Gitea#21223 代理镜像仓库 | 163/21 | — |
| mailcow#2851 Outlook 投递垃圾邮件 | 89/124 | 邮件协作互操作 |
| mailcow#7533 PHP RCE 漏洞（CVE-2026） | 53/70 | 安全运维 |
| mailcow#2316 LDAP 外认证 | 38/101 | 认证（并入 P-001） |
| mailcow#1341 DMARC 报告解析 | 27/38 | — |
| Nextcloud Calendar#629 每日历默认提醒 | 99/55 | "每次加事件都要设提醒，忘了就错过" |
| Nextcloud Calendar#28 待办到期日进日历 | 89/20 | 任务与日历割裂 |
| Nextcloud Calendar#113 重复事件复制 | 37/74 | "复杂事件改两个字段要重建" |
| Formbricks#2460 问卷导入导出 | 4/11 | "for backup / share surveys / template marketplace"→ P-018 同族 |
| Zitadel#6433 User Schema（34/62）、#9810 动态客户端注册、#7900 Token Exchange | 24-34 | 身份平台细节 |
| V2EX t462191 小团队管理工具选型（21 回复） | — | 已并入 P-017 |
| V2EX t671256 高价值系统/工具（14 回复） | — | 待升格 |
| V2EX t522404 造轮子密码管理工具（37 回复） | — | 待升格 |

## 如实说明

- Forgejo / papercms / getoutline（错误路径）仓库搜索 422，本轮空手。
- Zitadel Discussions 混入垃圾帖（"5 Best Mattress Steam Cleaning…"），
  已忽略，只采用 issue 数据。
- Formbricks 整体热度低（最高 13👍 是 bug），信息量有限。

## 第五轮共性观察

1. **资源所有权模型是团队级功能缺陷的根源**（P-120）：日历/文档/项目
   绑定个人 → 离职即僵尸。与 P-081/P-072 串成完整链条。
2. **联邦/跨组织协作从"锦上添花"变成"核心诉求"**（P-122/P-127）：
   用户要的是"加外部协作者"这个具体故事，不是抽象协议。
3. **推送开放性仍是自托管的盲点**（P-126）。
