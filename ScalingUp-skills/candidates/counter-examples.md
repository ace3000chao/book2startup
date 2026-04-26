# Scaling Up — 反例/失败模式候选池 (阶段1产出)

> 反例提取器产出 | 包含failure_mode + mechanism | 不做筛选

---

- id: ce01
  title: 成长悖论陷阱
  type: counter-example
  source_chapter: 第2章 Barriers
  source_quote: |
    "The belief that as you scale the company — and increase your dream team, prospects, and resources — things should get easier, but they don't. Things actually get harder and more complicated."
  failure_mode: |
    创始人/领导团队认为"长大了就好了"，实际上复杂度指数增长导致更累
  mechanism: |
    每增加一个员工，沟通渠道数量指数增长（2人=2条，3人=6条，4人=24条）。
    领导力、基础设施、营销三大障碍如果没有系统解决，大了反而更乱。
  warning_signs:
    - 员工数增长但效率下降
    - 领导感觉自己越来越忙但进展越来越少
    - 团队沟通成本显著上升
  bound_to:
    - "4D Framework"
    - "Rockefeller Habits"
    - "领导力三要素"
  tags: [growth-paradox, scaling, complexity]

- id: ce02
  title: B/C类人才稀释A类人才
  type: counter-example
  source_chapter: 第5章 Managers
  source_quote: |
    "Nothing is more frustrating for A Players than having to work with B and C Players who slow them down and suck their energy."
  failure_mode: |
    让B/C类人才与A类人才一起工作，导致A类人才流失
  mechanism: |
    A类人才有选择权，当他们感到被B/C类人才拖累时会选择离开。
    而B/C类人才的低效工作方式会传染整个团队。
  warning_signs:
    - A类人才抱怨团队质量
    - 产出质量下降但找不到原因
    - A类人才主动离职
  bound_to:
    - "A Player vs B/C Player"
    - "fewer people higher pay"
    - "Topgrading"
  tags: [hiring, talent, retention, a-players]

- id: ce03
  title: Core Values墙化
  type: counter-example
  source_chapter: 第6章 The Core
  source_quote: |
    "A leader must go beyond merely posting a company's Values and Purpose on the wall and handing out plastic laminated cards."
  failure_mode: |
    Core Values只停留在海报和卡片上，没有渗透到HR系统
  mechanism: |
    当Core Values不与招聘/绩效评估/奖励/晋升挂钩时，
    员工会把它们当作空洞标语而非行为准则。
  warning_signs:
    - Core Values只在入职培训时提及
    - 绩效评估与价值观无关
    - 奖励没有按价值观分类
  bound_to:
    - "Core Values落地"
    - "HR系统对齐"
  tags: [core-values, culture, alignment]

- id: ce04
  title: 战略过度复杂化
  type: counter-example
  source_chapter: 第7章 7 Strata
  source_quote: |
    "Many bits and pieces of our 4D Framework and tools have been copied by others. Several have over-simplified our work to the point that it might still be helpful but there is huge potential left on the table."
  failure_mode: |
    工具被过度简化后只剩下形式，没有实质。
    设定几个KPI和优先级不等于真正执行了Rockefeller Habits。
  mechanism: |
    过度简化的工具让领导感觉"做了"但实际效果大打折扣。
    战略执行的关键细节被省略，导致潜在价值大量流失。
  warning_signs:
    - 只设KPI但没有跟进流程
    - 有优先级但没有季度主题
    - 有会议但没有结构化议程
  bound_to:
    - "4D Framework"
    - "OPSP"
  tags: [strategy, execution, tools]

- id: ce05
  title: 过度依赖创始人/CEO
  type: counter-example
  source_chapter: 第1章 Overview
  source_quote: |
    "Every business is more valuable to the degree that it does not depend on its top leader."
  failure_mode: |
    企业价值等于CEO的价值，一旦CEO离开企业就无法运转
  mechanism: |
    当CEO成为所有决策和信息的中枢时，组织无法Scale。
    领导把所有答案都握在自己手里，组织陷入沉默。
  warning_signs:
    - 没有CEO在场就无法开会
    - 所有信息都需要CEO过滤
    - 员工不敢自己做决定
  bound_to:
    - "Dumbest in the Room"
    - "FACe"
  tags: [leadership, delegation, dependency]

- id: ce06
  title: 糟糕的入职体验
  type: counter-example
  source_chapter: 第5章 Managers
  source_quote: |
    "The first days on the job often feel more like waterboarding than onboarding: no desk, no computer, no phone, the new boss is traveling, and the first assignment is shadowing an unenthusiastic colleague."
  failure_mode: |
    新员工入职第一天体验极差，第一印象就被破坏
  mechanism: |
    新员工在"印刻期"最敏感和最愿意学习，
    但大多数公司的入职体验是混乱和冷漠。
    这导致新员工从第一天就与公司文化疏离。
  warning_signs:
    - 新员工入职当天没有工位/电脑
    - 被安排给不热心的同事带
    - 入职培训只是读政策手册
  bound_to:
    - "Onboarding即文化灌输"
    - "First Impression"
  tags: [onboarding, culture, new-hire]

- id: ce07
  title: 战略每年只做一次
  type: counter-example
  source_chapter: 第7章
  source_quote: |
    "It's not sufficient to schedule strategic thinking time once every quarter or year."
  failure_mode: |
    年度战略规划后全年执行，中途不做调整
  mechanism: |
    市场变化速度远超年度规划周期。
    一年只做一次战略让公司错失大量调整机会。
  warning_signs:
    - 战略文档在书架上积灰
    - 季度回顾从不讨论战略
    - 市场已经变化但策略不变
  bound_to:
    - "战略必须每周讨论"
    - "迭代式战略"
  tags: [strategy, cadence, agility]

- id: ce08
  title: 同时推进所有Rockefeller Habits
  type: counter-example
  source_chapter: 第1章 Overview
  source_quote: |
    "You'll drive everyone in the organization crazy if you implement all of these habits at one time."
  failure_mode: |
    试图同时改变所有10个Rockefeller Habits
  mechanism: |
    改变需要时间和消化空间。
    一次推太多习惯会让团队应接不暇，导致所有改变都浅尝辄止。
  warning_signs:
    - 团队抱怨变化太多
    - 每项习惯都在推但每项都不彻底
    - 员工开始抵触
  bound_to:
    - "习惯必须季度轮换"
    - "聚焦1-2个习惯"
  tags: [change-management, habits, overwhelm]

- id: ce09
  title: 招聘只看技能不看不匹配
  type: counter-example
  source_chapter: 第4章 The Team
  source_quote: |
    "Cultures are like immune systems and will spit out very capable people who don't align with its norms (Core Values)."
  failure_mode: |
    招聘时只看候选人的技能和经验，忽视文化契合度
  mechanism: |
    高技能但文化不契合的员工会：
    1）破坏团队协作；2）让其他员工不适；3）最终离职
    公司为这次招聘付出的成本（时间、金钱、团队士气）远超想象。
  warning_signs:
    - 新员工与团队风格格格不入
    - 其他员工开始抱怨
    - 离职时团队反而松了口气
  bound_to:
    - "Hire for culture fit"
    - "Topgrading"
  tags: [hiring, culture, values]

- id: ce10
  title: 把"忙碌"当"高效"
  type: counter-example
  source_chapter: 第9章 Priority
  source_quote: |
    "Everyone seems to be working more hours, spinning his wheels, or spending too much time fixing things that should have been done right the first time."
  failure_mode: |
    团队越来越忙但产出没有增加，问题反复出现
  mechanism: |
    没有聚焦优先事项时，所有事情都变成紧急。
    每个人都在救火但没有人做真正重要的事。
  warning_signs:
    - 团队频繁加班但任务列表不变
    - 同一问题反复出现
    - 战略优先事项永远被紧急任务打断
  bound_to:
    - "少即是多"
    - "季度主题"
  tags: [productivity, priorities, busy-trap]

- id: ce11
  title: 薪酬等于公平
  type: counter-example
  source_chapter: 第5章 Managers
  source_quote: |
    "'Fairness' does not mean 'sameness.' You need to be creative and flexible in order to keep your top talent happy."
  failure_mode: |
    对所有员工使用相同的薪酬方案，认为这才公平
  mechanism: |
    不同员工有不同的激励需求：
    有人要高底薪，有人要高提成，有人要高股权，有人要高福利。
    统一方案会失去吸引力或浪费资源。
  warning_signs:
    - 用统一模板处理所有薪酬谈判
    - 无法留住有个性化需求的顶尖人才
    - "公平"但所有人都略微不满
  bound_to:
    - "Fairness ≠ Sameness"
    - "顶尖人才个性化激励"
  tags: [compensation, fairness, talent-retention]

- id: ce12
  title: 复制别人的薪酬体系
  type: counter-example
  source_chapter: 第5章 Managers
  source_quote: |
    "Don't copy somebody else's compensation system. Look to your Core Values, your business model, and your Brand Promise."
  failure_mode: |
    直接采用行业标准薪酬方案或复制其他公司做法
  mechanism: |
    每个公司的文化、战略和品牌承诺不同，
    需要的激励结构也不同。
    复制别人的方案可能与自身战略背道而驰。
  warning_signs:
    - 薪酬方案与价值观不一致
    - 销售团队激励与品牌承诺冲突
    - 薪酬无法支撑战略执行
  bound_to:
    - "薪酬体系必须对齐战略"
    - "Core Values驱动"
  tags: [compensation, strategy, alignment]

- id: ce13
  title: 忽视Core Competency边界
  type: counter-example
  source_chapter: 第7章 7 Strata
  source_quote: |
    "Don't define Core Competencies too narrowly. But equally important is to understand what you are inherently incapable of doing."
  failure_mode: |
    公司进入能力圈外的市场或产品线
  mechanism: |
    BIC如果只把自己定义为"便宜笔"，就无法进入打火机、剃须刀市场。
    但反过来，如果进入完全不具备能力基础的市场，也会失败。
  warning_signs:
    - 新产品与现有能力毫无关联
    - 进入市场后才发现没有竞争力
    - 试图成为所有人卖给所有人
  bound_to:
    - "Core Competency定义"
    - "7 Strata"
  tags: [strategy, core-competency, focus]

- id: ce14
  title: BHAG不够大
  type: counter-example
  source_chapter: 第1章 Overview
  source_quote: |
    "In the end, it's about keeping everyone focused on the summit (BHAG) and then deciding the appropriate next step."
  failure_mode: |
    BHAG目标太小或太短期，无法激励和指引方向
  mechanism: |
    如果BHAG几年内就能实现，它就不是"BHAG"了。
    目标太小无法产生战略张力，也不够指引10-25年的方向。
  warning_signs:
    - 团队对BHAG没有兴奋感
    - BHAG在现有能力范围内就能实现
    - 讨论BHAG时团队没有挑战感
  bound_to:
    - "BHAG必须是25年不移的地标"
  tags: [vision, goal-setting, ambition]
