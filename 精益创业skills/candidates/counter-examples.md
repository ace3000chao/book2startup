- id: ce01
  title: 传统商业计划管理陷阱
  type: counter-example
  source_chapter: 引言
  source_quote: |
    "好的计划、可靠的战略和深入的市场分析造成的诱惑...把它们的套入创业企业中去的想法令人难以抗拒，但是此路不通。"
  failure_mode: |
    用写商业计划的方式管理新创企业，在产品还没被市场验证之前就投入大量资源执行详细计划。
  mechanism: |
    计划思维让人把"执行计划"当成进展，而非把"验证假设"当成进展。
    计划做得越详细，放弃它就越痛苦，即使数据证明它是错的。
  warning_signs:
    - 花数月写详细的商业计划书
    - 用"等计划完成就开始"作为延误借口
    - 计划中假设市场环境是稳定的
  bound_to:
    - "信念飞跃假设检验"
    - "MVP原则"
    - "用实验替代商业计划"
  tags: [counter-example, business-plan, traditional-management]

- id: ce02
  title: 忽视顾客反馈的工程师思维
  type: counter-example
  source_chapter: 第三章
  source_quote: |
    "在早期，我们并没有按他们的建议去做，仅把这些提议视为我们的产品和整体愿景的信息来源之一。"
  failure_mode: |
    把顾客反馈当"信息参考"而非"决策依据"，用工程师的骄傲过滤掉不喜欢的反馈。
  mechanism: |
    创业者（尤其是技术背景）倾向于把顾客意见当成噪音，认为"顾客不懂技术"或"他们会改变的"。
    但实际上，顾客的行为（用或不用）比他们的语言更能说明问题。
  warning_signs:
    - 对顾客说"你不懂"
    - 把差评归咎于顾客不识货
    - 花时间解释为什么顾客"错了"
  bound_to:
    - "倾听顾客但不被顾客主导"
    - "经证实的认知"
  tags: [counter-example, customer-feedback, engineer-mindset]

- id: ce03
  title: 虚荣指标陷阱
  type: counter-example
  source_chapter: 第七章
  source_quote: |
    "如果我们被这些'总顾客数量'等等的虚荣指标误导，那么创新核算就无从谈起。"
  failure_mode: |
    关注总数（如总用户、点击量、页面浏览）而非可执行的同期群指标，
    感觉在进步但实际没有方向性的认知增长。
  mechanism: |
    虚荣指标让人感觉良好，能在会议上说"我们有X万用户"很有面子。
    但总数增长可能来自自然市场变化而非产品改进，无法指导决策。
  warning_signs:
    - 会议上只报好消息（总量增长）
    - 不追踪同期群行为变化
    - 把"用户多"当成产品成功的证据
  bound_to:
    - "三个可衡量指标"
    - "同期群分析"
    - "拒绝虚荣指标"
  tags: [counter-example, vanity-metrics, metrics]

- id: ce04
  title: 成功时的"别和成功过不去"陷阱
  type: counter-example
  source_chapter: 第八章
  source_quote: |
    "在早期的时候我们对低质量MVP和实验方式颇为反对，力劝我们放慢脚步...在我们的方法被证明是正确之后，我们听到的大多数建议是主张我们保持方向，'别和成功过不去'。"
  failure_mode: |
    创业者在早期成功（找到早期用户市场）后，错误地认为这个成功可以复制到主流市场，
    忽视了增长引擎可能已经触顶，需要转型。
  mechanism: |
    成功让人产生路径依赖，相信"为什么成功"是不言自明的。
    但早期用户和主流用户需求差异巨大，早期成功是误导信号。
  warning_signs:
    - 核心指标（激活率、留存率）已经多个月没有改善
    - 增长越来越依赖营销投入，而非自然增长
    - 竞争对手用更低成本获得了更快的增长
  bound_to:
    - "增长引擎驱动"
    - "产品/市场契合"
    - "IMVU虚荣指标案例"
  tags: [counter-example, success-trap, growth]

- id: ce05
  title: 快速规模化陷阱
  type: counter-example
  source_chapter: 第五章
  source_quote: |
    "产品发布之后，如果我们没有足够顾客来证明这个假设，那就到了转型的时候。"
  failure_mode: |
    在还没验证产品/市场契合时就投入大量资源扩张规模，
    以为"只要产品够好，顾客就会来"，实际上浪费了在错误产品上的投入。
  mechanism: |
    创业者常混淆"产品发布"和"验证成功"。发布是起点，不是终点。
    在没有反馈循环的情况下规模化，只会放大错误而非创造价值。
  warning_signs:
    - 产品发布后团队就分散去做下一个项目
    - 没有建立测量和反馈机制
    - 增长依赖补贴而非产品价值
  bound_to:
    - "MVP原则"
    - "开发—测量—认知循环"
    - "价值假设先于增长假设"
  tags: [counter-example, premature-scale, mvp]

- id: ce06
  title: 把顾客需求当产品功能
  type: counter-example
  source_chapter: 第三章
  source_quote: |
    "顾客无法告诉我们他们想要什么；毕竟大多数人从未听说过三维虚拟人像。"
  failure_mode: |
    把顾客提出的具体解决方案（"我想要XX功能"）直接当成产品方向，
    而不追问顾客真正想解决的底层问题是什么。
  mechanism: |
    顾客给你的是他们能想象到的解决方案，而非他们真正的问题。
    如果直接按顾客说的做，可能解决了并不存在的需求，或错过了真正的问题。
  warning_signs:
    - 顾客要求某个功能，你立刻去开发
    - 没有追问"你为什么想要这个"
    - 顾客说"如果你们有XX功能我就付费"但实际没付费
  bound_to:
    - "倾听顾客但不被顾客主导"
    - "五个为什么"
  tags: [counter-example, customer-request, root-cause]

- id: ce07
  title: 转型犹豫症
  type: counter-example
  source_chapter: 第八章
  source_quote: |
    "很多公司难以作出转型决定。我希望我能说，每次需要转型时我都处理得不错，但这并非事实。"
  failure_mode: |
    明知需要转型但因为情感/利益/自尊原因迟迟不做决定，
    把"坚持"当成美德，实际上是在消耗资源等待失败。
  mechanism: |
    转型意味着承认之前的假设是错的，这在心理上是痛苦的。
    加上沉没成本、团队感情、外部投资人压力，决策者会找各种理由合理化"继续"。
  warning_signs:
    - 每次"转型还是坚持"会议都变成"我们再试一个月"
    - 核心指标多个月无改善但没人提转型
    - 团队开始私下寻找后路
  bound_to:
    - "转型要当机立断"
    - "创新核算三步骤"
  tags: [counter-example, pivot-failure, indecision]

- id: ce08
  title: 大批量的死亡螺旋
  type: counter-example
  source_chapter: 第九章
  source_quote: |
    "大批量的方式必须在最后阶段一次性完成所有产品...万一顾客决定不要这些产品了怎么办？"
  failure_mode: |
    把大量资源投入一个批次的产品开发，等到发布才发现顾客不想要。
    返工成本极高，因为所有东西都耦合在一起。
  mechanism: |
    大批量让人感觉"效率高"，因为可以专注做一件事。
    但实际上把反馈周期拉长到几周甚至几个月，让错误在后期才暴露，修正成本成倍增加。
  warning_signs:
    - 产品开发周期超过1个月没有用户接触
    - 团队说"等发布再看看市场反应"
    - 没有人敢在中途改变方向
  bound_to:
    - "小批量原则"
    - "速度就是一切"
  tags: [counter-example, big-batch, late-feedback]

- id: ce09
  title: 把增长引擎误判
  type: counter-example
  source_chapter: 第十章
  source_quote: |
    "要更好地理解一种转型，就要把它作为一种新的战略假设，需要用新的最小化可行产品来验证。"
  failure_mode: |
    误以为自己的产品用的是某种增长引擎（如病毒式），实际上从未测试过，
    导致增长策略失效。
  mechanism: |
    创业者常假设自己知道增长引擎，但从未设计实验验证。
    把自然增长（少数用户自发推荐）误认为病毒式，把偶然的媒体曝光误认为口碑传播。
  warning_signs:
    - 不清楚自己的顾客从哪来
    - 以为"产品好自然会传播"
    - 没有追踪推荐转化率
  bound_to:
    - "增长引擎驱动"
    - "对比测试"
  tags: [counter-example, growth-engine, misdiagnosis]

- id: ce10
  title: 用工程指标衡量创业进度
  type: counter-example
  source_chapter: 第七章
  source_quote: |
    "他们每天都在改进产品，可是在系统上线的头6个月里，他们无法让顾客做任何事。"
  failure_mode: |
    用工程进度（功能完成数、代码行数、上线时间）衡量创业进度，
    但产品没人用，这些进度全是浪费。
  mechanism: |
    工程师擅长交付功能，衡量标准自然倾向工程指标。
    但创业的核心问题是"顾客想要什么"，不是"我们能交付什么"。
  warning_signs:
    - 团队会议讨论"完成了哪些功能"而非"顾客行为有何变化"
    - 产品有100个功能但没人用超过5个
    - 没有追踪激活率、留存率
  bound_to:
    - "经证实的认知"
    - "三个可衡量指标"
  tags: [counter-example, engineering-metrics, wrong-metrics]
