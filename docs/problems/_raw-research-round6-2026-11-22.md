# 原始调研记录 · 第六轮 · 2026-11-22

> 渠道：主 agent 直采。新品类：工作流编排（Airflow/Windmill/Kestra/
> Temporal/n8n）、同步（Syncthing）、凭据管理（Bitwarden）、BI（Superset）、
> V2EX 飞书多维表格话题。另含 SoduWork 两日跟踪（见
> docs/research/soduwork-assessment-2026-11-20.md 第六节）。

## 本轮产出

- 新建卡 7 张：P-128 ~ P-134
- SoduWork 评估文档追加第六节（跟踪更新）
- 本轮未扩充旧卡（新卡均为独立主题）。

## 已建卡映射

| 来源 | 卡 |
|---|---|
| Windmill#5014 公开信（value subtracted） | P-128 |
| bitwarden/clients#11611 桌面版不再自由 | P-129 |
| Syncthing#9083 选择性文件同步 | P-130 |
| Airflow#9342 权限不跟随标签 | P-131 |
| n8n#40 gaslighting 争议（269👍/403c） + Windmill#5014 | P-132 |
| Superset#19398 + SiYuan#2249 标签分组 | P-133 |
| Temporal#680 等待外部工作流 | P-134 |

## 未建卡条目（证据池）

| 来源 | 👍/评论 | 说明 |
|---|---|---|
| Airflow#11334 暗色模式 / #7843 色盲友好 | 187/44 | 无障碍 |
| Airflow#42136 task 日志 URL 无 host | 44/97 | 运维故障 |
| Airflow#13975 一个任务多 pool | 39/9 | 调度 |
| Windmill#4981 flow 步骤单测 | 7/0 | 测试能力 |
| Kestra#1400 并发限制 / #3060 JetBrains 插件 | 18/14 | — |
| Syncthing#2491 下一代 ignore 规则 / #4721 本地目录同步 / #3388 DHT 发现 / #8113 S3 后端 | 150/101/97/90 | 同步工具高级需求 |
| Syncthing#4137 用登录页替代 HTTP Basic Auth | 61/11 | 认证（→P-001） |
| Temporal#3006 工作流暂停/恢复 / #1507 优先级队列 | 69/55 | 调度 |
| Bitwarden#12286 弹窗延迟 / #8873 Firefox 反复登出 / #20172 Chrome 变慢 | 123/121/134 | 客户端性能 |
| n8n#14361 AI Agent 不记工具调用到 memory | 33/57 | 与 SoduWork #295 内循环同族 |
| Superset#10408 Dashboard 级访问 / #33215 AI Assistant | 64/60 | 权限/AI |
| V2EX t1236658/t1143342 "求类似飞书多维表格的开源项目" | 0 回复 | 需求侧信号：中文市场对开源多维表格的渴望 |
| V2EX t1203330 "飞书多维表格差点意思" | 0 回复 | — |

## 如实说明

- arex/rex、arex/chat2db、collaborators-io、standardnotes、papercms、
  multiplylabs/tableau 等仓库搜索 422（不存在或改名），本轮空手。
- V2EX 飞书多维表格相关帖多为 0 回复招聘/广告，仅 3 条需求侧信号入池，
  未建卡（证据强度不足）。
- n8n#40 作者开头是激烈控诉，但 issue  evolved 为 403 条讨论，我们只取
  原文标题段控诉内容作为"信任危机"证据，不代表对项目的整体 judgement。

## 第六轮共性观察（重要）

1. **开源信任危机形成完整证据链**：P-113（去 Open 化）+ P-096（nagware）
   + P-106（自托管二等公民）+ P-128（value subtracted）+ P-129（许可证
   变非自由）+ P-132（gaslighting）——6 张卡、跨 6 个主流工具、热度从
   28 到 306👍。这是所有主题里证据密度最高、情绪最强烈的一条。
   **阶段 2 定位必须回应：可信的开源承诺本身就是产品卖点。**
2. **标签是统一缺失层**：P-023（文档标签）+ P-131（权限按标签）+
   P-133（内容分组）指向一个统一标签体系的设计机会。
3. **SoduWork 两日 +65% 星、303 issues、#931 越权漏洞**：热度与风险
   同步膨胀，验证"理念标杆 + 反面教材双重参照"的定位。
