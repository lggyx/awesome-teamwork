---
id: P-109
domain: 集成生态
title: Git 作为笔记/知识库的存储后端：要版本化与可迁移，工具不支持
source: community
evidence:
  - https://github.com/laurent22/joplin/issues/753
severity: 中
frequency: 中
existing_solutions:
  - tool: 工具私有存储 + 手动导出
    gap: 用户想要"versioned notes"，把 Git 当存储 provider 又被拒
status: open
---

# P-109 知识库缺 Git 存储后端

## 问题描述

Joplin 用户要求"please implement git as storage provider. Like GitHub
or GitLab work as the storage provider for pass, that could even give
us versioned notes"——用 Git 做后端天然获得版本历史、可迁移、
可审计。工具普遍不支持，用户被锁在私有存储格式里（呼应 P-018
迁出难、P-108 无版本控制）。

## 证据

- Joplin#753（77 👍 / 38 评论，closed）：原文如上

## 可能的解决方向

知识库支持 Git 作为可选存储后端（文件或对象映射），
数据主权与版本化一次解决。
