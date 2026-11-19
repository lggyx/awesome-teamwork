---
id: P-053
domain: 集成生态
title: 开放 API 质量差：参数命名混乱、报错无细节、支持无响应
source: community
evidence:
  - https://www.v2ex.com/t/890496
severity: 中
frequency: 中
existing_solutions:
  - tool: 抓包试错 + 社区论坛求助
    gap: 集成成本被 API 质量放大，自动化协作无从谈起
status: open
---

# P-053 开放 API 质量差

## 问题描述

想给团队做集成的开发者撞上 API 烂泥：飞书三个接口同一个参数三种
命名（folder-token / folderToken / token），错误响应只有 "Bad Request"
没有任何细节，提交支持表单石沉大海。集成生态是协作工具的放大器，
API 质量差等于亲手拆掉放大器。

## 证据

- V2EX t/890496（18 回复，2022-10），楼主："屡次在响应体里看到
  'Bad Request'，但没有更多信息，根本无助于 debug；"；"那就点提交
  表单看看能否获得支持，提交了几次毫无回复；"

## 现有方案为什么不够

API 面向演示设计（能跑通 happy path）而非面向集成方设计
（错误可诊断、命名一致、文档与实现同步）。

## 可能的解决方向

API 设计规范先行：命名统一、错误带 trace 与可读原因、
开放 API 先吃自己的狗粮（官方集成全部走公共 API）。
