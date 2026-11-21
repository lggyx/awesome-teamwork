---
id: P-113
domain: 工具切换成本
title: 开源项目去Open化：把测试/核心移入闭源仓库，社区信任崩塌
source: community
evidence:
  - https://github.com/tldraw/tldraw/issues/8082
  - https://github.com/tldraw/tldraw/issues/7695
severity: 中
frequency: 中
existing_solutions:
  - tool: 接受现状 / fork
    gap: fork 也拿不到测试与后续开发，社区贡献价值归零
status: open
---

# P-113 开源项目去 Open 化

## 问题描述

tldraw 把 ~327 个测试文件从开源仓库移到闭源仓库（306 👍）；
贡献政策讨论（290 👍）。社区反应："being scared from the AI is no
the way to go, I suggest you go completely closed source and not be
lukewarm"——半开半闭最伤信任。与 P-030/P-096/P-106 同族：
2026 年"开源"承诺被各种方式稀释，用户越来越难判断一个工具
到底能信多久。

## 证据

- tldraw#8082（306 👍/15 评论）及 #7695（290 👍/7 评论）正文与评论，
  2026-11-22 实抓

## 可能的解决方向

对本项目的治理承诺：核心能力（含测试）永远开源，
"功能是否开源"做明确矩阵——这是对抗全行业信任赤字的差异化。
