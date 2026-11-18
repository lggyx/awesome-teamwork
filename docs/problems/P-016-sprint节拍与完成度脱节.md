---
id: P-016
domain: 流程适配
title: 硬性 sprint 节拍与真实完成度脱节，"按剧本走"浪费大量时间
source: community
evidence:
  - https://news.ycombinator.com/item?id=24050732
severity: 中
frequency: 高
existing_solutions:
  - tool: 固定节奏 Scrum
    gap: 截止日是任意设定的，工作完成却不能交付，流程沦为表演
status: open
---

# P-016 硬性 sprint 节拍与真实完成度脱节

## 问题描述

固定 sprint 的截止日与工作真实完成度无关：事情做完了也要等下个仪式节点，
"To C"组织的敏捷实践被开发者体验为表演——"It is horrible, so much wasted
time trying to play by the book on this."

## 证据

- HN「Ask HN: What was the best project management style you have been a
  part of?」（50 points / 19 comments），AlexanderNull："It is horrible, so
  much wasted time trying to play by the book on this. ... Things get done
  when they're done, not when an arbitrary sprint end day has occurred."
  https://news.ycombinator.com/item?id=24050732

## 现有方案为什么不足

工具把"节奏"固化成日历硬约束，而不是跟随真实流转的软节奏。

## 可能的解决方向

工具支持"完成即交付"的流式节奏，仪式按需触发而非按日历触发。
