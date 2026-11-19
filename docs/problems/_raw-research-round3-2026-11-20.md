# 原始调研记录 · 第三轮 · 2026-11-20

> 执行方式：主 agent 直接采集（应用商店子代理交付 30 条后，其余子代理
> 按用户要求全部关闭，改由主 agent 用 gh api / WebFetch 亲自扫）。
> 抽查复核 3 条（Mattermost#34271 / HN 18874707 / V2EX t1071370）属实。
> 抽查复核本轮新增 3 条（Mattermost#34271 实测 110👍+188👍评论、
> HN 18874707 实测 102/76、V2EX t1071370 实测 33 回复）。

## 本轮产出

- 新建卡 28 张：P-079~P-106（含应用商店 10 张、HN 深挖 12 张、
  中文 5 张、Reddit 2 张、GitHub 扫描 4 张、需求侧 2 张等）
- 扩充既有卡 20+ 张（证据并入，见各卡"补充"条目）

## 已建卡映射（本轮证据 → 卡）

- Jitsi#4758/5550/5295/5252/8128/5830、Element#29891/3546、SiYuan#2024、
  BBB#1969/9152/4882 → P-084；Element#2320 → P-085；SiYuan#2829/8873/
  10414、Docmost#78 → P-086；SiYuan#2828、HedgeDoc#2879/657 → P-087；
  Rocket#1112/4489、Zulip#1555、Element#2349 → P-092；Zulip#10643、
  Element#1358 → P-098；Rocket#23638 → P-099；BookStack#569、
  Outline#2201、Huly#5555、Cal#8904 → P-100；Plane#4087 → P-101；
  Cal#28086、Wiki.js#2523 → P-102；Reddit sxjjiq → P-095；
  Reddit 13z5xr4 → P-096；HN OKR/工时 → P-097/P-103；Wekan#109/2698、
  Leantime#249 → P-104；AppFlowy-Cloud#943/803/565/1402、AFFiNE#6920/
  6872 → P-105；AFFiNE#7097/8716/6641/2646、AppFlowy-Cloud#1570/680/
  1039 → P-106；V2EX 879876 → P-090；V2EX 724850/196843/505106 → P-091；
  V2EX 168072 → P-094；HN 28642916/43676734 → P-093；HN 40969693 深挖 →
  P-059/P-060；SE SharePoint/SCRUM/USB/文档张力 → P-007/P-069/P-048/
  P-057；Outline#859/1160/962/1172/743、Zoom/Miro 评论文本 →
  待并入对应卡（见下"待并入"）

## 未建卡条目（证据池 · 待升格或并入，按仓库枚举）

### Element（element-hq/element-web）
| issue | 👍 | 说明 |
|---|---|---|
| #5891 自定义铃声/通知音 | 150 | open |
| #5993 对讲（push-to-talk） | 88 | open |
| #30844 房间列表缩放被移除 | 80 | closed |

### SiYuan（siyuan-note/siyuan）
| #5086 插件系统 | 50 | closed |
| #17674 CLI | 20 | closed |
| #3718 云端收集箱 | 19 | closed |

### Logseq（logseq/logseq）
| #3462 配置迁移 XDG 规范 | 80 | open |
| #3150 允许修改历史 | 41 | open |
| #9403 Android 选 Nextcloud 目录 | 36 | open |
| #4592 自托管建议汇总 | 33 | closed |

### HedgeDoc
| #2877 离线支持 | 26 | open |

### Docmost
| #590 读写模式分离 | 32 | closed |
| #240 自定义图标 | 32 | open |
| #93 链接增强 | 31 | closed |
| #95 目录/子页树 | 31 | closed |
| #734 每空间自定义 Logo | 29 | closed |
| #63 手动建成员 | 28 | closed |
| #551 日历 | 26 | closed |
| #1468 AI/LLM 集成 | 25 | closed |
| #342 链接页面 | 24 | closed |

### Kimai
| #403 默认客户/项目 | 25 | closed |
| #4292 日历视图日合计 | 21 | closed |
| #699 默认活动 | 20 | closed |
| #963 暂停按钮 | 19 | closed |
| #351 支出追踪 | 15 | closed |
| #4723 HHmm 格式 | 12 | closed |
| #1407 webhooks | 12 | closed |
| #617 收藏组合 | 11 | closed |
| #1810 邮件通知 | 10 | closed |

### Jitsi
| #6390 播视频不静音 | 35 | closed |
| #2829 RTMP 直播 | 30 | closed |
| #21059(LiveKit)、#5860 虚拟背景、#7601 Peertube、#5439 Firefox 警告 | 32/27/26/26 | — |

### BBB
| #9046 每人音量单独调节 | 83 | open |
| #8474 Ubuntu 版本支持 | 45 | closed |
| #21059 LiveKit 集成 | 32 | open |
| #5836 自定义 CSS/JS | 30 | open |
| #9131 摄像头虚拟背景 | 28 | closed |
| #2045 对讲按钮 | 27 | closed |

### CryptPad
| #681 仅评论视图 | 14 | closed |
| #2415 撤回版本发布 | 14 | closed |
| #704 匿名权限控制 | 11 | open |
| #1047 邮件通知 | 10 | open |
| #1311 passkey | 10 | open |
| #143 屏侧评论 | 11 | closed |

### Flarum
| #283 用户列表 | 34 | closed |
| #3360 无障碍 mega-issue | 8 | open |

### Outline（补充面）
| #859 文件附件 | 116 | closed |
| #457 文档评论 | 89 | closed |
| #1160 集合公开分享 | 60 | closed |
| #2831 diagrams.net 集成 | 52 | closed |
| #1177 认证与 docker 安装 | 46 | closed |
| #4271 Mattermost 集成 | 38 | closed |
| #2916 自定义主题 | 31 | closed |
| #2929/@889 文档内 @提及 | 31/27 | closed |
| #962 GitLab/GitHub SSO | 29 | closed |
| #3132 协同编辑下的编辑按钮 | 29 | closed |
| #1172 批量导入 markdown（含 Notion） | 26 | closed |
| #1141 分享整个文档树 | 25 | closed |
| #883 Gmail 个人号登录 | 24 | closed |
| #11113 MCP Server | 24 | closed |
| #1038 MathJax | 23 | closed |
| #743 订阅文档变更 | 22 | closed |

### Mattermost（补充面）
| #15975 主题随 OS 切换 | 72 | open |
| #2355 删除聊天历史 | 48 | closed |
| #6405 用户级深浅色 | 47 | closed |
| #37221 图片加载后滚动位置漂移 | 20 | closed |
| #1982 关闭表情渲染 | 19 | closed |
| #31193 easyjson 供应链 | 21 | open |

### Cal.com（补充面）
| #5756 Proton Calendar 集成 | 36 | closed |
| #27401/#28077/#28085 round-robin 成员级规则 | 23/19/21 | open/closed |
| #1985 BBB 集成 | 20 | closed |
| #12201 部署域名配置 | 19 | closed |

### Vikunja（补充面）
| #115 轻松改任务所在列表 | 19 | closed |
| #114 批量编辑 | 12 | open |
| #1529 显示子项目任务 | 11 | open |
| #1364 总览周/月日历 | 11 | open |
| #474 清理已完成 | 10 | open |
| #2023 项目级标签 | 8 | open |

### AFFiNE（补充面）
| #5069 自托管版本进展 | 71 | closed |
| #5491 本地存储加密 | 25 | open |
| #1602 Private Cloud | 26 | closed |
| #5807 LaTeX | 23 | closed |
| #8966 RTL | 22 | open |
| #12819 Android 无 SSO | 23 | closed |
| #6517 移动版 | 22 | closed |
| #12983 复制为 markdown | 29 | closed |

### Nextcloud server（补充面）
| #16726 PHP→Go 重写呼吁 | 209 | closed |
| #65754 PHP CVE 部署告警 | 153 | closed |
| #4917 应用顺序可配置 | 134 | closed |
| #1600/#1497 订阅日历共享/暴露 | 113/103 | open/closed |
| #22509/#24380/#25607 升级兼容故障 | 93/93/91 | closed |

### Rocket.Chat（补充面）
| #3582 频道头像 | 296 | closed |
| #1723 自定义 emoji | 124 | closed |
| #1209 显示名与用户名分离 | 69 | closed |
| #1887 每用户主题 | 59 | closed |
| #2355 删除聊天历史 | 48 | closed |
| #6405 用户级深浅色 | 47 | closed |

### Wekan（补充面）
| #687 ownCloud/Nextcloud 集成 | 52 | closed |
| #480 移动应用 | 26 | closed |
| #808 日历视图 | 25 | closed |
| #298 清单 | 23 | closed |
| #486 看板背景 | 18 | closed |
| #252 公开看板列表 | 16 | closed |

### Leantime（补充面）
| #2309/#146/#3212 PostgreSQL 支持 | 14/13/7 | closed |
| #371 OAuth2/OIDC | 13 | closed |
| #958 SAML | 9 | closed |
| #398 模块开关 | 9 | open |
| #1690 SQLite compose | 9 | open |
| #268 里程碑多依赖 | 9 | open |
| #778 非 root 运行 | 7 | closed |
| #180 跨项目移动任务 | 6 | closed |

### Kanboard（补充面）
| #85 任务多用户 | 40 | closed（→P-005 已并） |
| #2087 设计改进 | 14 | closed |
| #1472 过滤 NOT 运算 | 9 | closed |
| #2650 任务打印/PDF | 8 | closed |
| #3142/#1456 批量操作 | 8/6 | closed |
| #2562 任务模板 | 7 | closed |
| #4119 反代子路径 | 8 | open |
| #5308 登出崩溃 | 8 | closed（→P-024 已并） |
| #3932 tooltip 不消失 | 6 | closed |
| #530/#2831 泳道列组 | 6/6 | closed |
| #2433 已完成可见 | 6 | closed |
| #2068 子任务计时 | 6 | closed |

### Taiga（补充面）
| #127 项目前缀自定义 | 6 | open |
| #157 媒体上传 S3 | 5 | open |
| #55 Matrix 集成 | 4 | open |
| #95 无法删用户 | 2 | open |
| #129 ActivityPub | 2 | open |
| #140 按 id 直达票据 | 2 | open |

### HN / SE / V2EX / 商店（未并入部分）
| 来源 | 说明 |
|---|---|
| HN 31860489 | "大家都恨但没人敢说"（50/48） |
| HN 31860489 内 | UX 退化清单（点击多/延迟） |
| HN 46053293 | "为什么 Jira/Confluence 是默认 PM 工具"（2026，2/4） |
| HN 19554550 等 | 已并入 P-063 |
| V2EX t538474 | 求半天可上手的超轻量代码评审工具（28） |
| V2EX t843526 | 代码规范引入心得（31） |
| V2EX t922133 | "大部分公司没有单元测试和代码评审" |
| V2EX t604753 | 临时通知周末值班（15） |
| SE | 客户/工程师文化错配（11）；企业门户失望史（17） |
| Zoom 商店 | 三重 passcode 摩擦；周期会议日程同步错乱 |
| Miro 商店 | 编辑交互（点击区域小/误判）；工具栏消失 |

## 如实说明

- GitLab 官方仓库（gitlab-org/gitlab）尝试经 GitLab API 按 upvotes 拉
  issues，该端点不支持 upvotes 排序（422），本轮放弃，未采。
- TriliumNext/Notes 几乎无高热 issue（迁移期）；planka 仓库已迁移
  （旧路径 422），本轮未取；Discourse issues 无 reactions 数据，
  无可用痛点，如实放弃。
- Reddit 直连 403，经 redlib 镜像（red.artemislena.eu）读取，卡片存
  规范 URL。
- HN/Element/SiYuan 等扫描用 `gh api search/issues?sort=reactions`
  一次性拉列表；卡片引用以标题原文+热度为准（标题为页面原文），
  正文引文仅在深入抓取的条目上使用。
- 已知命名修正：Huly=hcengineering/platform、Cal.com=calcom/cal.diy、
  Twake=linagora/twake-legacy、Trilium→TriliumNext/Notes。

## 第三轮共性观察

1. **自托管信任正在被同行透支**（P-030/P-096/P-106/P-105 四连）——
   "开源/自托管"承诺与实际功能墙的落差是 2026 年最尖锐的用户情绪。
2. **AI 是新的锁定层**：内置 AI 不可关、端点不可换（P-105）。
3. **会议/IM 的协作配套**（白板/分组/群私信/线程）是长期欠账（P-084/
   P-092）。
4. **需求侧信号明确**：Notion/Jira/Miro 平替呼声（P-095）+
   中文两头难（P-056）= 本项目生态位。
