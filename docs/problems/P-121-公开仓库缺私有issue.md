---
id: P-121
domain: 安全与隐私
title: 公开仓库无法开私有 issue：安全漏洞协调披露无载体
source: community
evidence:
  - https://github.com/go-gitea/gitea/issues/3217
severity: 中
frequency: 中
existing_solutions:
  - tool: 私下邮件/私密渠道
    gap: 讨论脱离项目上下文，披露时间线无法管理
status: open
---

# P-121 公开仓库缺私有 issue

## 问题描述

"allow confidential issues on public repositories"——开源项目处理
安全漏洞时，需要在"早期披露"到"完全披露"之间有个私密讨论空间，
之后再公开。工具不支持，协调披露只能靠邮件/私聊，脱离项目上下文。

## 证据

- Gitea#3217（227 👍/44 评论）：原文如上，明确引用 GitLab 的
  confidential issues 做参照

## 可能的解决方向

issue/任务支持可见性级别（公开/私密/定时公开），
支撑安全披露与敏感协作（衔接 P-101 内外可见性分层）。
