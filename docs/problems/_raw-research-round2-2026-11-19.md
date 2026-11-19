# 原始调研记录 · 第二轮 · 2026-11-19

> 来源：三个并行调研代理——A（GitHub 第二轮：Plane/Huly/AFFiNE/Zulip/
> Mattermost/Rocket.Chat/Nextcloud Deck/Kanboard/BookStack/Wiki.js/Cal.com/
> Twake）、B（英文社区：HN/Reddit/PM StackExchange）、C（中文社区：
> V2EX 深挖/少数派/Gitee）。
> 抽查复核 3 条（Mattermost#34271 / HN 18874707 / V2EX t/1071370）均属实；
> Mattermost#34271 实测热度（110 👍 + 单条 188 👍）强于代理报告。

## 本轮产出

- 新建卡 28 张：P-029 ~ P-056
- 扩充既有卡证据 9 张：P-002/P-004/P-008/P-014/P-015/P-017/P-018/
  P-019/P-026
- 首轮补漏 6 张（同日早些时候）：P-023 ~ P-028，及 P-001/P-002/P-003
  证据补充

## 新增问题域

第二轮新增两个域（收集过程中涌现）：
**集成生态**（P-029/P-053/P-054）、**安全与隐私**（P-034/P-035）。

## 未建卡条目（证据池，待后续升格）

| 来源 | 痛点 | 链接 |
|---|---|---|
| Zulip#1555 | 私信不支持 topics（36 👍/11 评论） | https://github.com/zulip/zulip/issues/1555 |
| Zulip#10643 | 不支持语音消息（33 👍/66 评论） | https://github.com/zulip/zulip/issues/10643 |
| Zulip#10385 | 无法按日期跳转历史消息（11 👍，衍生#25436 15👍） | https://github.com/zulip/zulip/issues/10385 |
| Rocket.Chat#23638 | HEIC 图片桌面/网页端无法预览（19 👍/55 评论） | https://github.com/RocketChat/Rocket.Chat/issues/23638 |
| BookStack#569 | 多语言版本互不关联（83 👍/80 评论，closed 未实现） | https://github.com/BookStackApp/BookStack/issues/569 |
| Plane#8147 | Markdown 里 Mermaid 图渲染为纯文本（26 👍/9 评论） | https://github.com/makeplane/plane/issues/8147 |
| Plane#4087 | 无内部评论，Viewer（外包/客户）看到全部技术讨论（10 👍） | https://github.com/makeplane/plane/issues/4087 |
| Mattermost#15975 | 深浅色主题不随 OS 切换（72 👍/62 评论） | https://github.com/mattermost/mattermost/issues/15975 |
| Cal.com#28086 | AM/PM 不醒目，跨时区预订误订凌晨（17 👍） | https://github.com/calcom/cal.diy/issues/28086 |
| Cal.com#8904 | 预订页无法指定语言（28 👍/20 评论） | https://github.com/calcom/cal.diy/issues/8904 |
| Kanboard#5501 | 权限粒度粗，无法"只见自己的卡"（已并入 P-034） | https://github.com/kanboard/kanboard/issues/5501 |
| Wiki.js#2523 | 新用户默认时区锁死 America/New_York（11 👍/10 评论） | https://github.com/requarks/wiki/issues/2523 |
| Huly#5555 | 无 RTL（右到左文字）支持（11 👍/3 评论） | https://github.com/hcengineering/platform/issues/5555 |
| AFFiNE#8399 | 只支持手动导出备份（12 👍） | https://github.com/toeverything/AFFiNE/issues/8399 |
| AFFiNE#13447 | Android 删除文字触发成倍复制（11 👍/19 评论） | https://github.com/toeverything/AFFiNE/issues/13447 |
| V2EX t/640601 | 远程办公落地难（居家干扰/孤独，偏人的问题非工具问题） | https://www.v2ex.com/t/640601 |
| sspai 82179 | 印象笔记会员复杂广告泛滥 / All in One 幻觉 | https://sspai.com/post/82179 |
| Gitee ShowDoc#IC8W96 | 项目分组无法过滤（4 评论） | https://gitee.com/star7th/showdoc/issues/IC8W96 |
| HN 31813957 | "I f***ing hate Jira"（971 分/526 评论，抱怨卡顿臃肿，与已收主题相邻） | https://news.ycombinator.com/item?id=31813957 |
| HN 26709951 | "The Daily Standup Is a Waste of Time"（102 分，与 P-014 相邻） | https://news.ycombinator.com/item?id=26709951 |

## 如实说明（渠道障碍）

- Reddit 直连（www/old）403，正文经 redlib 镜像（red.artemislena.eu）
  读取；卡片证据用规范 Reddit URL，镜像 URL 未入卡。
- G2 被 Cloudflare 拦（403），Capterra/Slashdot 未再试——评测站本轮无收获。
- 知乎 403（首轮已知）；电鸭社区被验证码+JS 拦截，仅 RSS 读到一条相关
  帖标题（eleduck.com/posts/3EfRx5），正文读不到，未列入。
- Lobste.rs 搜到 "JIRA is an antipattern" 串但评论多为元评论，无可用
  痛点；dev.to tag=jira 只有厂商 SEO 文。
- 仓库路径修正：Huly 实际为 hcengineering/platform；Cal.com 已改名
  calcom/cal.diy；Twake 实际为 linagora/twake-legacy（TwakeApp/Twake
  已不存在）。
- 中文代理无 WebSearch 工具，V2EX 站内搜索不生效，改用 SoV2EX API
  发现帖子后逐帖抓取 www.v2ex.com/t/数字（均成功）。
- BookStack/Wiki.js 高热 feature request 多为 closed 未实现状态
  （BookStack 2026-04-28 批量关闭 94-102 👍 请求）——痛点成立，
  状态已在对应卡片标注。

## 跨工具共性观察（第二轮，阶段 2 需求假设素材）

1. **集成生态是真空带**：Git forge 联动（P-029）、API 质量（P-053）、
   标准协议双向（P-054）三面缺口，新一代工具也没补上。
2. **"治理"是知识库的死亡原因**：不是没功能，是没人维护（P-038）、
   发布无审核（P-037）、搜索找不到（P-033）。
3. **汇报/可见性的结构矛盾**：重复汇报层烧人（P-043）× 影子系统
   （P-046）× 维护工作不可见（P-044）——信息聚合全部人肉。
4. **对开源厂商的商业信任危机**：回头加墙（P-030）+ 砍授权（P-031）
   + 席位计费（P-032）——"自托管=可控"的承诺正在被同行透支。
5. **中文语境独有缺口**：本土化两难（P-056）+ 中文搜索（P-033 子问题）
   ——本项目的潜在生态位。
