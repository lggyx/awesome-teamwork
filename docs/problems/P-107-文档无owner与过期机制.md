---
id: P-107
domain: 文档知识
title: 知识库缺"页面责任人 + 过期复核"机制，文档默认腐烂
source: community
evidence:
  - https://news.ycombinator.com/item?id=30371723
severity: 高
frequency: 高
existing_solutions:
  - tool: 靠人自觉更新 wiki
    gap: 知识维护是"工作的额外一步"，几乎总被忽略；无 owner 无过期
status: open
---

# P-107 文档无 owner 与过期机制

## 问题描述

HN 187 分热帖「How do you manage your companies knowledge base?」
给出了共识解法：**每页有 owner、有过期日，到期强制复核**。
"knowledge sharing/maintenance was simply being an extra step in our
work, a mostly disregarded one, almost an after thought"；
技术写作者证实："Assigning an owner and tracking last review date is
a very effective practice"（Google go/fresh-source、微软内部有类似系统）；
有公司甚至做到"过期 30 天后只显示预览：'Only Bob Jones knows the
rest of this story. Call him at x1234'"。

## 证据

- HN 30371723（187/118）：adrianomartins / phphphphp / kaycebasques /
  bobbydreamer / deanebarker 原文（2026-11-22 实抓）
- 核心洞察（phphphphp）："知识是资产，文档是负债"——把两者分开
  记，才能管理好后者

## 可能的解决方向

每条知识带 owner + 最后复核时间 + 过期等级；到期自动进入
轻量复核队列；离职时 owner 自动转交（衔接 P-072/P-093）。
这是 P-038（知识库退化）的可执行答案。
