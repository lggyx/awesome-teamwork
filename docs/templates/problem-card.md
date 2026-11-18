---
id: P-NNN              # 全局唯一，从 P-001 递增；文件名与此 id 一致
domain: 沟通对齐        # 沟通对齐/任务管理/文档知识/会议/进度可见性/跨团队协作/远程异步/工具切换成本
title: 一句话说清问题   # 主语 + 痛点，不用"如何…"句式
source: self           # self | community | competitor
evidence:              # source 为 self 时写背景一句话；否则放真实链接
  - "亲历记录：<背景，如'上一项目跨 3 个时区协作时的实际情况'>"
severity: 高           # 高/中/低——痛感强度
frequency: 高          # 高/中/低——发生频率
existing_solutions:    # 现有解法及不足；没有就写"无"
  - tool: <工具或方法名>
    gap: <为什么不够>
status: open           # open | merged（并卡时指向保留卡）| parked
---

# P-NNN <问题标题>

## 问题描述

<具体场景：什么角色、在什么时刻、遇到什么阻碍。写事实，不写口号。>

## 现有方案为什么不够

<逐条对应 existing_solutions 展开；引用外部证据时给链接。>

## 可能的解决方向（可选）

<阶段 1 只记录灵感，不做方案论证；阶段 2 再收敛。>
