# 原始调研记录 · 2026-11-19

> 来源：两个并行调研代理（GitHub 公开 issues；HN/Reddit/V2EX 公开讨论），
> 抽查复核 3 条链接（Outline#1881 / HN#33259351 / V2EX t/1028650）均真实。
> 本文件是证据池：已建卡的条目标 ✅，未建卡的留在此处供后续批次升格。
> 已知偏差：Outline#1881 代理报 341 👍，实测 👍 275+（341 应为含其他表情的合计）。

## 已建卡条目（见 docs/problems/）

| 卡 | 工具/帖子 | 证据 |
|---|---|---|
| ✅ P-001 | Outline#1881 / Wekan#119 / Vikunja#240 | 强制 OAuth / 缺 LDAP / OpenID 配不上 |
| ✅ P-002 | Focalboard#4196 / AppFlowy#7872 / taiga-docker#39 | 升级后数据"消失"、目录错位、docker pull 炸登录 |
| ✅ P-003 | Leantime#2355 / Wekan#6480 / Wekan#6745 | 15s/点击、CPU 100%、大看板加载极慢 |
| ✅ P-004 | Outline#5716 / AppFlowy#13 | 强制 S3/Minio、无官方 Docker 镜像 |
| ✅ P-005 | Leantime#1099 | 任务只能单人指派 |
| ✅ P-006 | HN 17478253（TrevorAustin 评论） | Trello 管不了中型项目多层子任务 |
| ✅ P-007 | HN 10871076 | Basecamp 清单地狱、万事标"最高优先级" |
| ✅ P-008 | Reddit r/SaaS 1llqdo7 | 追踪散落 Slack 线程和表格（OP 带推广动机，降权） |
| ✅ P-009 | HN 37988759（Minor49er） | 干系人太忙不看工具通知 |
| ✅ P-010 | V2EX t/530449 | 钉钉封闭无 URL，内容分享不出生态 |
| ✅ P-011 | HN 33259351 + Reddit r/remotework 1ccycev | 混合办公名存实亡；摄像头政策+高频会议 |
| ✅ P-012 | HN 16197364 | 远程时"让队友知道你在做什么"最难 |
| ✅ P-013 | Reddit r/projectmanagement 1p08ttx | 跨团队卡在交接与 ownership |
| ✅ P-014 | Reddit r/agile 1g8o1pp | 站会 15 分钟实为 45 分钟+30-60 分钟恢复 |
| ✅ P-015 | HN 17478253（DanielBMarkham） | 花在工具/会议/报告上的时间让工具变障碍 |
| ✅ P-016 | HN 24050732 | 任意设定的 sprint 截止日与真实完成度脱节 |
| ✅ P-017 | V2EX t/793443 | Jira 吐槽归吐槽却找不出更强的，小团队退用在线 Excel |
| ✅ P-018 | AppFlowy#8862 / Vikunja#254 | Notion 700MB 导入报错、Todoist 迁移丢桶 |
| ✅ P-019 | Focalboard#5038 / taiga-back#111 | Focalboard 官方弃养征集维护者；Taiga 被质疑停滞 |
| ✅ P-020 | V2EX t/1028650 | 钉钉卡顿臃肿；"用户是企业老板，牛马的体验不重要"（❤️12） |
| ✅ P-021 | Reddit r/projectmanagement 169hh4d | HCL Notes 等遗留工具锁死团队，无共同线上空间 |
| ✅ P-022 | HN 37988759（solardev） | Jira 票据化把工作切碎，失去 feature 级所有权 |

## 未建卡条目（证据池，待后续批次升格）

| 来源 | 痛点 | 链接 |
|---|---|---|
| Focalboard#560 | 插件模式 UI 更新要等几秒 | https://github.com/mattermost-community/focalboard/issues/560 |
| Focalboard#4843 | 极易误创建空卡片污染看板（31 评论） | https://github.com/mattermost-community/focalboard/issues/4843 |
| Wekan#802 | 缺团队/组织层级 | https://github.com/wekan/wekan/issues/802 |
| taiga-back#54 | PostgreSQL 14 升级失败 | https://github.com/taigaio/taiga-back/issues/54 |
| taiga-back#21 | 项目导出丢用户 | https://github.com/taigaio/taiga-back/issues/21 |
| AppFlowy#8130 | 自托管云同步桌面端连不上（25 评论多平台复现） | https://github.com/AppFlowy-IO/AppFlowy/issues/8130 |
| Outline#5564 | OIDC token 刷新失败强制登出 | https://github.com/outline/outline/issues/5564 |
| Vikunja#1581 | 已删用户仍收逾期邮件 | https://github.com/go-vikunja/vikunja/issues/1581 |
| HN 37988759 | "已读不回"与"票据化"之外的其他吐槽（15 points/19 comments） | https://news.ycombinator.com/item?id=37988759 |

## 如实说明

- Linear / Asana / Trello / Notion / Slack / Jira 为闭源产品，无公开 GitHub issue
  跟踪器，本轮未取得其直接证据；Notion 痛点仅有 AppFlowy#8862 迁移故障间接佐证。
- OpenProject 官方仓库未启用 GitHub issues（has_issues=false），无可采条目。
- 知乎对调研环境返回 HTTP 403，本轮知乎无收获；V2EX t/1119489 抓取被内容过滤
  拦截，未列入。
- Reddit 各帖抓到了正文与引用，但抓取内容不含点赞/评论数，热度线索缺标注。
- r/SaaS 1llqdo7 的 OP 是工具方推广帖，痛点来自其转述，P-008 已降权标注。
- 跨工具共性观察（阶段 2 的需求假设素材）：①自托管身份认证是重灾区；
  ②升级/迁移即数据事故；③自托管性能与部署门槛；④基础协作能力缺口
  （多人指派/标签/团队层级）；⑤维护连续性风险。
