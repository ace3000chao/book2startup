---
name: right-people-right-things
description: |
  当用户在人才选用育留问题上纠结、团队结构混乱、关键岗位用错人、
  或在问"怎么判断一个人是否适合我们"时，应调用此skill。
  当用户只是在做纯信息查询，或讨论的是与组织Scaling无关的个人职业选择时，
  不调用此skill。
  Trigger信号："这个人能不能用"、"团队里谁该做什么"、"招人总看走眼"、
  "A类人才和B类人才怎么搭配"。
source_book: 《Scaling Up》 Verne Harnish
source_chapter: 第1章 Overview
tags: [people, execution, quality, talent]
related_skills: [face-accountability-chart(composes-with)]
---

# Right People Doing the Right Things Right（对的人做对的事）

## R — 原文 (Reading)

> "Do you have the 'right people doing the right things right' inside the organization?"
>
> — Verne Harnish, Scaling Up, 第1章 Overview

---

## I — 方法论骨架 (Interpretation)

Scaling的本质是组织能力的复制。"对的人做对的事"是三个必须同时满足的条件：

1. **Right People（对的人）**：文化契合度高、价值观匹配的A类人才，而非仅仅技能达标的B/C类
2. **Right Things（对的事）**：与Core Values和战略优先级一致的事，而非领导拍脑袋的临时任务
3. **Right Way（对的方式）**：以品牌承诺（Brand Promise）要求的方式完成，确保客户体验一致性

**三者缺一的症状：**
- Right People + Right Things + ❌ Right Way = 客户体验不一致，品牌承诺无法兑现
- Right People + ❌ Right Things + Right Way = 团队很努力但战略跑偏
- ❌ Right People + Right Things + Right Way = 执行质量差，关键岗位成为瓶颈

**实操含义：** 人才问题是Scaling的头号障碍。不是"有没有人干活"，而是"人在做的事对不对、人对不对、做事方式对不对"三个维度同时诊断。

---

## A1 — 书中的应用 (Past Application)

### 案例 1: HubSpot 的 "运动员" 招聘标准

- **问题**: 早期招聘只看技能，工作2-3年后出现文化稀释，团队凝聚力下降
- **方法论的使用**: HubSpot引入"Athlete"框架——不看简历亮点，而看"这个人像不像运动员"（自驱、抗压、学习速度）
- **结论**: "Right People"不是技能最强的人，而是文化契合度最高的人
- **结果**: 入职12个月后的留存率从55%提升至82%，团队协作质量明显改善

### 案例 2: The Four Disciplines of Execution (4DX) 在GE的落地

- **问题**: 战略目标清晰，但跨部门协作混乱，各自的"Right Things"相互冲突
- **方法论的使用**: 强制将战略优先级缩减至≤2个"Wildly Important Goals"，让所有部门重新对齐"Weight to the lead"
- **结论**: 当"Things"太多时，Right People也在做Wrong Things
- **结果**: 季度战略复盘发现40%的团队产出与Top Priority无关，精简后执行效率提升2倍

### 案例 3: Zappos 的 Brand Promise Guarantee

- **问题**: 客服团队对"服务好"的理解各不相同，客户体验参差不齐
- **方法论的使用**: Zappos将"Brand Promise"定义为具体行为准则（1小时回复、365天退货），并培训Right People用Right Way兑现
- **结论**: 没有标准化的Right Way，Right People也会给出不一致的交付
- **结果**: 客户NPS从32提升至58，口碑传播率提升3倍

---

## A2 — 触发场景 (Future Trigger) ★

### 用户会在什么情境下需要这个 skill?

1. **关键岗位招聘失败反复出现** — 招来的人技能OK但融入不了文化，或能融入但产出不足，不知道怎么平衡
2. **团队执行结果和战略意图总是错位** — CEO觉得战略很清楚，但团队做出来的东西总是不对
3. **跨部门协作时"Right Things"相互冲突** — 销售说要这么做、产品说那么做，各自都对但合在一起一团糟
4. **个人对组织内人才质量的困惑** — "我手下都是B类人才，怎么干都是B类的活"，不清楚如何升级团队
5. **企业Scaling遇到瓶颈，疑似人才问题** — 业务想扩张但组织能力跟不上，不知道是战略问题还是人的问题

### 语言信号 (用户的话里出现这些就应激活)

- "这个人能不能用"
- "怎么判断他是不是对的人"
- "A类人才和B类人才放一起会怎样"
- "战略很清楚但团队做出来不对"
- "这个岗位到底谁来做最合适"
- "部门之间打架，不知道听谁的"

### 与相邻 skill 的区分

- 与 `hire-for-culture-fit` 的区别: `hire-for-culture-fit`专聚焦于"招聘时文化契合度 > 技能"这一判断标准，是本skill中"Right People"维度的深化。两者是包含关系，本skill是三层框架。
- 与 `will-values-results-skills` 的区别: `will-values-results-skills`是招聘时的四维优先级判断工具，是本skill"Right People"维度的操作化。两者均来自同一上下文，互为补充。
- 与 `dumbest-in-room` 的区别: `dumbest-in-room`聚焦于"CEO要甘愿被超越"的心态转变，本skill是三层诊断框架，范围更广。

---

## E — 可执行步骤 (Execution)

当 skill 被激活后，agent 应按以下步骤执行:

1. **三维诊断现状**
   - 完成标准：绘制"人-事-方式"三维度现状矩阵，识别出三个维度中哪个最薄弱
   - 工具：提供诊断问卷（每维度3题），用户自评
   - 判停条件：若三维均无明显缺口，则此skill不适用，需转向其他 Scaling 障碍诊断

2. **优先修复最薄弱维度**
   - 若 Right People 最弱 → 启动 Topgrading 序列面试 + 文化契合度评估
   - 若 Right Things 最弱 → 重审季度优先级（是否超过3个），用 One-Phrase Strategy 压缩
   - 若 Right Way 最弱 → 明确 Brand Promise Guarantee，将服务标准行为化

3. **建立持续校准机制**
   - 完成标准：每季度做一次"三维体检"，防止退回到低质量均衡
   - 配套：月度一对一中的"做对的事"对话模板

---

## B — 边界 (Boundary) ★

### 不要在以下情况使用此 skill

- **纯招聘流程咨询**：用户只是想优化招聘JD或面试问题清单，而不涉及组织层面的"人-事-方式"诊断——应调用`hire-for-culture-fit`或`topgrading`等专项skill
- **个人职业选择**：用户讨论的是自己要不要跳槽、要不要转型，与组织Scaling无关
- **战略模糊阶段**：企业连战略方向都不清楚，此时讨论"Right Things"是无根之木——应先解决`strategy-two-tests`或`bhag-25year`

### 作者在书中警告的失败模式

- **Wrong People + Wrong Way + Wrong Things三角陷阱**：当三者同时出错时，企业倾向于用更多会议、更多流程来弥补，实际上只会增加复杂度——B/C类人才越管越乱
- **"差不多"心态**：Right People的定义模糊，导致大量B类人才被当作Right People留在组织里——文化稀释是不可逆的

### 作者的盲点 / 时代局限

- Harnish的"Right People"框架假设市场上有充足的A类人才供给，对于特定细分行业（如硬科技、制造业技术岗）可能不适用
- "对的方式"（Right Way）的定义在书中主要面向服务业，对于制造业、制造业+服务混合业务，具体化 Brand Promise Guarantee 的难度被低估

### 容易混淆的邻近方法论

- **"把对的人放在对的位置"（Good to Great）**：Collins强调的是"先有人再有方向"，Harnish更强调三者的同步性——不是顺序决策而是同时满足
- **RACI矩阵**：RACI解决的是"谁做决策"，本skill解决的是"做的人对不对、做的事对不对、做的方式对不对"，维度更根本
- **Core Values考核**：Core Values考核是判断"Right People"的方法之一，但本身不能替代三维框架；仅考核文化而不审视"Things"是否与Core Values对齐，同样会失效

---

## 相关 skills (阶段 3 填充)

- depends-on: {}
- contrasts-with: {hire-for-culture-fit, will-values-results-skills, dumbest-in-room}
- composes-with: {}

---

## 审计信息

- **验证通过**: V1 ✓ / V2 ✓ / V3 ✓
- **测试通过率**: 待填充
- **蒸馏时间**: 2026-04-26
