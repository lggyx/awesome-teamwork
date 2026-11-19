---
id: P-029
domain: 集成生态
title: 私有 Git 服务与协作工具任务无法联动，研发被迫双写
source: community
evidence:
  - https://github.com/hcengineering/platform/issues/6653
  - https://github.com/makeplane/plane/issues/1495
  - https://news.ycombinator.com/item?id=20807328
severity: 中
frequency: 高
existing_solutions:
  - tool: 手动双写（PM 工具建任务 + Git 仓建 issue）
    gap: 同一件事两个真源，状态迟早分叉
status: open
---

# P-029 私有 Git 集成缺失

## 问题描述

研发团队用自托管 GitLab/Gitea 管代码，PM 工具的任务与代码仓的 issue
无法同步：commit 关联不到任务、issue 状态回写不了看板，只能两边手动双写。
这是 Huly 和 Plane 两仓库各自热度第一的 open issue——新一代开源 PM 工具
也没解决。

## 证据

- Huly#6653（97 👍 / 44 评论，open）："We use a self-hosted Gitlab and
  Sentry instance, is it on the roadmap to integrate those into huly?"
- Plane#1495（89 👍 / 22 评论，open）："an integration with Gitea for
  syncing Issues would be nice. … Would allow gitea users to sync their
  issues."（两链接均经代理抓取，热度为 2026-11-19 读数）
- Jira 老用户（补充，60/78）："My current frustration is the Git
  integration; it only works with commits (not PRs) and is not 100%
  reliable."——老牌工具的集成同样是半吊子。
  https://news.ycombinator.com/item?id=20807328

## 现有方案为什么不够

开源 PM 工具的集成清单普遍指向 SaaS（GitHub.com、Linear 等），对
自托管 forge 的支持排在后面；而选择自托管的团队恰恰是最核心的受众。

## 可能的解决方向

自托管 Git forge（GitLab/Gitea/Forgejo）双向同步做成一等集成，
commit/PR/issue 状态自动回写任务。
