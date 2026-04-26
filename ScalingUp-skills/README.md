# Scaling Up Skills

> 从《Scaling Up》蒸馏出的44个可执行Agent Skills，帮你把企业从创业阶段规模化扩张到行业领先。

[![book2skill](https://img.shields.io/badge/powered%20by-book2skill-blue.svg)](https://github.com/kangarooking/cangjie-skill)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](../LICENSE)

---

## 🎯 这套Skills能解决什么问题？

 Scaling Up（Verne Harnish，2014）是全球最畅销的创业规模化指南，其核心理论——**四象限框架（People / Strategy / Execution / Cash）** + **4 Decisions** + **Rockefeller Habits Checklist**——帮助无数创业公司从"活下来"到"规模化"。

 但知道理论 ≠ 能执行。问题是：

- ❌ 读完全书，还是不知道从哪里下手
- ❌ 知道BHAG、7 Strata、Rockefeller Habits，但不知道怎么在具体场景里用
- ❌ 需要决策时，书里的原则没法直接拿来用

**这套Skills解决了这个问题。** 每个Skill都是一段"遇到这个情况，直接调用"的执行指南。你不再需要读完整本书（9721行英文原文），你只需要选择你现在的痛点，调用对应的Skill。

---

## 📖 蒸馏了什么

| 指标 | 数量 |
|---|---|
| Skills总数 | 44个 |
| 框架类 | 15个 |
| 原则类 | 29个 |
| 测试用例 | ~350条 |
| 覆盖四象限 | People / Strategy / Execution / Cash |

### 技能体系总览

```
ScalingUp-skills/
├── People（人才与组织）───────── 15个
│   ├── A类人才定义（Topgrading体系）
│   ├── FACe accountability chart（组织架构）
│   ├── 授权退出法则（Dumbest in the Room）
│   ├── 文化契合招聘
│   └── 正向互动比率（3:1）
│
├── Strategy（战略与愿景）──────── 10个
│   ├── BHAG宏大冒险目标
│   ├── 7 Strata七层战略护城河
│   ├── OPSP一页纸战略
│   ├── X-Factor竞争优势
│   └── 战略两测试（Gary Hamel）
│
├── Execution（执行与运营）──────── 12个
│   ├── Rockefeller Habits（执行习惯体系）
│   ├── Manager as Coach（教练式管理）
│   ├── Complexity Enemy（复杂度管理）
│   ├── Growth Paradox（增长悖论）
│   └── 每周Stop项（持续改进）
│
└── Cash（财务与增长）──────────── 7个
    ├── Power of One（财务杠杆）
    ├── Cash Conversion Cycle（现金周转）
    └── Growth Sucks Cash（增长吃现金）
```

---

## 💡 效果示例

### 示例1：团队扩张时调用 FACe

**场景：** 公司从20人扩到50人，责权不清，跨部门推诿严重。

**没有Skills时：** 翻书找"组织架构"章节，读完还是不知道怎么画图。

**有Skills时：**
```
用户：团队扩张后责任不清，总是互相推诿
→ 调用 face-accountability-chart skill
→ 得到：FACe三步法（Function/Accountability/Cross-func）
  1. 列出核心业务功能
  2. 每个功能指定唯一负责人（A点）
  3. 标注跨部门依赖关系
→ 输出：可直接使用的组织架构图框架
```

### 示例2：战略制定时调用 BHAG + 7 Strata

**场景：** 创始人在做3年战略规划，想设定一个真正激励团队的目标。

**没有Skills时：** 知道BHAG是什么，但不知道怎么设计一个符合标准的BHAG。

**有Skills时：**
```
用户：我想设定一个能让团队兴奋10年的目标
→ 调用 bhag-goal-setting skill
→ 得到：BHAG四步设定法 + 典型案例
→ 调用 7-strata-strategy skill（下一步）
→ 得到：7层战略框架，从BHAG到日常执行的路径
```

### 示例3：财务紧张时调用 Growth Sucks Cash

**场景：** 公司收入增长50%但现金流反而更紧张，创始人困惑。

**没有Skills时：** 不知道为什么增长反而让公司更难。

**有Skills时：**
```
用户：收入增长但钱越来越紧，什么原因？
→ 调用 growth-sucks-cash skill
→ 得到：增长吃现金引力定律 + Cash Runway模型
→ 诊断：增长吃现金是第一创业引力定律
→ 建议：同时监控Cash Conversion Cycle和Growth Rate
```

---

## 🔬 这些Skill是怎么生成出来的

### Book2skill流水线

本仓库的Skills来自 [cangjie-skill](https://github.com/kangarooking/cangjie-skill)方法论，一个将书籍蒸馏为可执行Agent Skills的标准化流程。

### 6阶段质量门控

```
阶段0 → 阶段1 → 阶段1.5 → 阶段2 → 阶段3 → 阶段4
整书     候选     三重     RIA++  Zettel  压力
理解     池       验证     构造   kasten  测试
```

| 阶段 | 内容 | 质量保障 |
|---|---|---|
| **阶段0** | 整书理解，写入BOOK_OVERVIEW.md | 确保读透 |
| **阶段1** | 从9721行原文中提取101个候选单元 | 5类候选：框架/原则/案例/反例/术语 |
| **阶段1.5** | 三重验证（V1跨域佐证 / V2预测力 / V3独特性） | 不合格降级为example |
| **阶段2** | RIA++结构构造SKILL.md | 6段式完整结构（触发→步骤→边界） |
| **阶段3** | Zettelkasten关系网络 | 17条核心关系边 |
| **阶段4** | 压力测试（darwin-skill兼容） | ~350条测试用例 |

### 关键技术点

- **不做Phase 1.5筛选**：候选池全量保留，质量由阶段2的A2触发场景把关
- **并发子agent批量构造**：5个sub-agent并行，每批10-12个Skills
- **零淘汰**：52个候选全部通过三重验证（Scaling Up是高质量书籍）

---

## 📁 仓库结构

```
ScalingUp-skills/
├── INDEX.md                      ← 技能索引（推荐学习顺序）
├── BOOK_OVERVIEW.md              ← 整书理解
├── README.md                     ← 本文档
│
├── {skill-slug}/                 ← 每个Skill一个文件夹
│   ├── SKILL.md                  ← 核心技能文件
│   └── test-prompts.json         ← 压力测试用例
│
├── candidates/                   ← 原始候选池（参考用）
│   ├── frameworks.md             ← 20个框架候选
│   ├── principles.md             ← 32个原则候选
│   ├── cases.md                  ← 18个案例
│   ├── counter-examples.md       ← 14个反例
│   └── glossary.md              ← 17个术语
│
└── rejected/                     ← 被淘汰的候选（标记原因）
```

### 一个Skill长什么样

```
{skill-slug}/
├── SKILL.md              ← 核心技能文件
│   ├── frontmatter       ← name/description/source_book/tags/related_skills
│   ├── R — 原文          ← 英文原文+中文翻译，≤150字
│   ├── I — 方法论骨架    ← 5-15行自述
│   ├── A1 — 书中案例     ← 2-3个真实案例
│   ├── A2 — 触发场景★   ← 5个场景+语言信号
│   ├── E — 可执行步骤   ← 1-2-3步+判停条件
│   ├── B — 边界         ← 反场景+失败模式+盲点
│   └── 审计信息          ← V1/V2/V3验证通过
│
└── test-prompts.json     ← darwin-skill兼容测试用例
    └── test_cases: [
        { id, type: should_trigger/should_not_trigger/edge_case, prompt, expected_behavior }
      ]
```

---

## 🚀 如何使用

### 方式一：在OpenClaw中使用（推荐）

1. **安装Skills到OpenClaw**
   
   将整个文件夹复制到OpenClaw的skills目录：
   ```bash
   cp -r ScalingUp-skills/ ~/.openclaw/workspace/skills/
   ```

2. **触发Skill**
   
   在对话中直接描述你的场景，AI会自动匹配对应的Skill：
   ```
   用户：团队从20人扩到50人，责权不清互相推诿
   AI：调用 face-accountability-chart skill
   → 输出FACe三步法
   ```

3. **按需调用特定Skill**
   
   直接指定：
   ```
   请用 bhag-goal-setting skill 帮我设定一个BHAG
   ```

### 方式二：在Claude Code中使用

1. **复制SKILL.md到项目**
   
   ```bash
   cp bhag-goal-setting/SKILL.md ./skills/
   ```

2. **在Claude Code中激活**
   
   ```markdown
   你可以调用这些skills：
   - bhag-goal-setting: BHAG宏大冒险目标设定
   - 7-strata-strategy: 七层战略护城河
   - rockefeller-habits: 执行习惯体系
   ```

### 方式三：用darwin-skill做自动化进化

```bash
# 安装darwin-skill（如果还没安装）
npm install -g darwin-skill

# 对ScalingUp-skills做压力测试进化
darwin evolve ./ScalingUp-skills/

# 会自动运行test-prompts.json中的所有测试用例
# 通过率<80%的skill会被打回重做
```

---

## 📚 相关Skills集

本仓库是 **book2startup** 家族的一部分。同系列还有以下Skills集：

| 书名 | 路径 | 核心框架 | Skills数 |
|---|---|---|---|
| 孙子兵法 | `../孙子兵法skills/` | 战争战略/竞争策略 | 18 |
| 庄子 | `../庄子skills/` | 道家哲学/自由境界 | 27 |
| 易经 | `../易经skills/` | 变化哲学/决策系统 | 13 |
| 精益创业 | `../精益创业skills/` | MVP/Build-Measure-Learn | 8 |
| 菜根谭 | `../菜根谭skills/` | 世俗智慧/处世哲学 | 47 |

### 各Skills集特色

- **孙子兵法Skills**：适合竞争战略、商业谈判、博弈决策场景
- **庄子Skills**：适合战略自由度、创新思维、组织文化场景
- **易经Skills**：适合复杂决策、变化管理、风控预警场景
- **精益创业Skills**：适合产品开发、市场验证、创业启动场景
- **菜根谭Skills**：适合创业指导、学生教育、日常处事场景
- **ScalingUp Skills（本仓库）**：适合企业规模化、组织管理、战略执行场景

所有Skills均遵循**book2skill**方法论，支持OpenClaw/Claude Code/darwin-skill接入。

---

## 📖 书籍来源

《Scaling Up: How a Few Companies Make It...and Why the Rest Don't》
- 作者：Verne Harnish
- 出版年份：2014
- 来源：在互联网已公开收集

---

## 🔗 资源链接

| 资源 | 链接 |
|---|---|
| Book2skill方法论（蒸馏工具） | [GitHub - kangarooking/cangjie-skill](https://github.com/kangarooking/cangjie-skill) |
| 本仓库Gitee | [https://gitee.com/zhiyao-zhongshan-g_0/book2startup](https://gitee.com/zhiyao-zhongshan-g_0/book2startup) |
| 本仓库GitHub | [https://github.com/ace3000chao/book2startup](https://github.com/ace3000chao/book2startup) |

---

## 📄 License

MIT License — 可免费使用于个人和商业项目。

如需修改或分发，请保持本README和作者署名。