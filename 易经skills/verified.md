# 易经 · 三重验证通过清单（阶段1.5产出）
> book2skill 流水线阶段1.5 · 2026-04-21

## 验证结果汇总

| 类型 | 候选总数 | 通过数 | 通过率 |
|------|----------|--------|--------|
| Frameworks | 20 | 10 | 50% |
| Principles | 15 | 3 | 20% |
| Counter-examples | 10 | 10 | 100% |
| Cases | 10 | 10 | 100% |
| Glossary | 10 | 10 | 100% |
| **合计** | **65** | **43** | **66%** |

---

## ✅ 通过验证的方法论（进入阶段2）

### Frameworks（10条）

```yaml
- id: f04
  title: 德位匹配论
  type: framework
  source_chapter: 乾卦·文言传·坤卦
  V1_cross_domain:
    passed: true
    evidence:
      - 乾卦文言传："贵而无位，高而无民，贤人在下位无辅"
      - 坤卦文言传："阴疑于阳必战"
      - 系辞传：臣弑其君，子弑其父，非一朝一夕之故
  V2_predictive_power:
    passed: true
    novel_question: "如何判断一个人是否'德不配位'？"
    derived_answer: "三信号：① 有头衔却无实权（贵而无位）② 有名无实无人追随（高而无民）③ 真正的人才在下面无法进入核心（贤人在下位无辅）。出现任意一种，组织必然生变。"
  V3_exclusivity:
    passed: true
    why_not_common: "德位相配是常见概念，但'贵而无位/高而无民/贤人在下位无辅'这三层具体诊断机制是爻辞中的独特表述，非普通常识。"
  → 进入阶段2

- id: f05
  title: 时机等待法
  type: framework
  source_chapter: 需卦
  V1_cross_domain:
    passed: true
    evidence:
      - 需卦：需于郊→需于沙→需于泥→需于血→饮食（五个层次）
      - 彖传：刚健而不陷，其义不困穷
  V2_predictive_power:
    passed: true
    novel_question: "如何判断'等待'是智慧还是拖延？"
    derived_answer: "看客观条件：① 郊（安全区）→耐心蛰伏 ② 沙（开始有杂音）→坚守 ③ 泥（危险临近）→谨慎应对 ④ 血（陷入险境）→冷静脱身。不是所有等待都正确，时机未到贸然行动=陷险，时机到了不行动=错失。"
  V3_exclusivity:
    passed: true
    why_not_common: "'等待'是常识，但需卦五层次提供了具体的判断框架，且'有准备的等待'vs'盲目等待'的区分有独特性。"
  → 进入阶段2

- id: f06
  title: 变革创新论
  type: framework
  source_chapter: 革卦·鼎卦
  V1_cross_domain:
    passed: true
    evidence:
      - 革卦：己日乃孚，元亨利贞，悔亡
      - 鼎卦：圣人亨以享上帝，大亨以养圣贤
      - 系辞传：穷则变，变则通，通则久
  V2_predictive_power:
    passed: true
    novel_question: "为什么很多改革失败后迅速反弹？"
    derived_answer: "缺少'鼎'——变革（革）后必须有固化机制（鼎）来定格成果。改革三宗罪：① 时机未到（孚不足）② 准备不足 ③ 后续巩固缺失。改革前问'孚了吗？'改革后问'鼎了吗？'"
  V3_exclusivity:
    passed: true
    why_not_common: "'变革'是常识，但'己日乃孚'（时机成熟才取信）+'鼎'（固化成果）的组合机制有独特性，非泛泛谈变革。"
  → 进入阶段2

- id: f07
  title: 反省复盘法
  type: framework
  source_chapter: 复卦·无妄卦
  V1_cross_domain:
    passed: true
    evidence:
      - 复卦：出入无疾，朋来无咎；七日来复
      - 无妄卦：其匪正有眚，不利有攸往
      - 坤卦文言：不远复，无祗悔，元吉
  V2_predictive_power:
    passed: true
    novel_question: "复盘应该多久进行一次？"
    derived_answer: "'七日来复'——周期性自检机制。错误→复盘→修正→进步是必然规律。复盘三问：① 做对了什么？② 做错了什么？③ 下一步怎么改？'不远复'——越早发现问题越容易纠正。"
  V3_exclusivity:
    passed: true
    why_not_common: "'反省'是常识，但'七日来复'的7天具体周期 + '不远复'的越早越好的精确时机 + 螺旋上升机制，有独特性。"
  → 进入阶段2

- id: f10
  title: 守成戒贪法
  type: framework
  source_chapter: 乾卦·节卦
  V1_cross_domain:
    passed: true
    evidence:
      - 乾卦上九：亢龙有悔
      - 节卦：亨，苦节不可贞
      - 节卦彖传：天地节而四时成，节以制度，不伤财，不害民
  V2_predictive_power:
    passed: true
    novel_question: "什么时候'节俭'反而是病？"
    derived_answer: "'苦节不可贞'——过度的节制（不舍得花钱/不舍得投人）反而是另一种极端。守成三原则：① 设定边界（当位以节）② 控制节奏（不伤财不害民）③ 警惕'苦节'（过度节约同样是病）"
  V3_exclusivity:
    passed: true
    why_not_common: "'戒贪'是常识，但节卦的'有度的慷慨'vs'苦节'的具体区分 + '不伤财不害民'的标准，有独特性。"
  → 进入阶段2

- id: f11
  title: 顺势而为法
  type: framework
  source_chapter: 豫卦·随卦
  V1_cross_domain:
    passed: true
    evidence:
      - 豫卦：豫，顺以动，圣人以顺动
      - 随卦：随，元亨利贞，无咎
      - 象传：泽中有雷，随，君子以向晦入宴息
  V2_predictive_power:
    passed: true
    novel_question: "'顺势'和'跟风'的区别是什么？"
    derived_answer: "辨势→借势→不逆势三层。顺势是看清规律后主动配合；跟风是盲目模仿他人。随卦的'随'不是盲从，而是'元亨利贞'——有原则的跟随；豫卦的'顺以动'——顺规律而动，非顺情绪而动。"
  V3_exclusivity:
    passed: true
    why_not_common: "'顺势而为'是常见成语，但豫随辩证框架（顺规律vs顺情绪）+ 三层辨势框架有独特性。"
  → 进入阶段2

- id: f12
  title: 刚柔并济法
  type: framework
  source_chapter: 大壮卦·遯卦
  V1_cross_domain:
    passed: true
    evidence:
      - 大壮：利贞，大壮者贞也
      - 遯：亨，遯，小利贞
      - 系辞传：刚柔者，立本者也
  V2_predictive_power:
    passed: true
    novel_question: "什么时候该'刚'，什么时候该'柔'？"
    derived_answer: "大壮（过于强壮）时需要'柔'来平衡；遯（需要退避）时需要'刚'来果断。核心：刚过则折，柔过则弱。刚柔的辩证转换——不是非此即彼，而是动态平衡。"
  V3_exclusivity:
    passed: true
    why_not_common: "'刚柔并济'是常见概念，但大壮/遯的辩证框架 + 动态平衡的判断标准有独特性。"
  → 进入阶段2

- id: f14
  title: 厚积薄发法
  type: framework
  source_chapter: 大畜卦·无妄卦
  V1_cross_domain:
    passed: true
    evidence:
      - 大畜：刚健笃实，辉光日新
      - 无妄：其匪正有眚，不利有攸往
      - 大畜彖传：能正在家用度之道，乃应天
  V2_predictive_power:
    passed: true
    novel_question: "什么时候该全力投入，什么时候该蛰伏积累？"
    derived_answer: "'不家食吉'——当你还在消耗资源（家食）阶段，说明还没准备好，应该继续蛰伏积累。积累期三问：① 自身准备是否充分？② 辉光是否日新？③ 资源是否支撑到临界点？"
  V3_exclusivity:
    passed: true
    why_not_common: "'厚积薄发'是常见概念，但'不家食'作为临界点判断 + '辉光日新'的积累标准有独特性。"
  → 进入阶段2

- id: f15
  title: 破局解困法
  type: framework
  source_chapter: 解卦·蹇卦
  V1_cross_domain:
    passed: true
    evidence:
      - 解卦：利西南，无攸往
      - 蹇卦：利西南，不利东北
      - 彖传：蹇，难也，見险而能止
  V2_predictive_power:
    passed: true
    novel_question: "困境中该进还是该退？"
    derived_answer: "辩证判断：'无所往，其来复吉；有攸往，夙吉'——如果没有明确方向，原地恢复（如休息/蛰伏）更吉祥；如果有明确方向，尽早行动（夙）更吉祥。见险而能止——困境中不是所有行动都是好的，有时候'止'比'动'更有智慧。"
  V3_exclusivity:
    passed: true
    why_not_common: "'解困'是常见概念，但蹇/解的辩证判断（无所往vs有攸往）+ '见险而能止'的时机选择有独特性。"
  → 进入阶段2

- id: f19
  title: 盈亏警示法
  type: framework
  source_chapter: 泰卦·否卦·丰卦
  V1_cross_domain:
    passed: true
    evidence:
      - 泰卦：小往大来，吉亨
      - 否卦：否之匪人，不利君子贞
      - 丰卦：亨，王假之，勿忧，宜日中
  V2_predictive_power:
    passed: true
    novel_question: "如何判断一个组织/市场的拐点？"
    derived_answer: "'丰顶即衰'——当最盛时（丰卦，日中）恰恰是衰落的起点。拐点信号：① 决策速度明显加快（过度自信）② 听不进不同意见 ③ 资源消耗速度远超往常。泰否循环——极泰→否；极否→泰。阴阳转换处即是预警点。"
  V3_exclusivity:
    passed: true
    why_not_common: "'物极必反'是常识，但'日中见斗'（丰卦意象）+ '决策加速=拐点信号'的具体诊断 + 泰否循环框架有独特性。"
  → 进入阶段2
```

### Principles（3条）

```yaml
- id: p04
  title: 用九，见群龙无首，吉
  type: principle
  source_chapter: 乾卦·用九
  V1_cross_domain:
    passed: true
    evidence:
      - 乾卦用九：见群龙无首，吉
      - 乾卦文言：乾元用九，天下治也
  V2_predictive_power:
    passed: true
    novel_question: "集体决策时，如何避免'一言堂'？"
    derived_answer: "用九原则——对集体计划保持'观察、理解'，不强行主导。不出头告发（无首）= 不做绝对权威，让各方力量自然发挥作用。反而'吉'——这是民主决策的古老智慧。"
  V3_exclusivity:
    passed: true
    why_not_common: "'集思广益'是常识，但'见群龙无首'作为集体决策的独特表述 + '无首'（不出头告发=不独断）的具体机制有独特性。"
  → 进入阶段2

- id: p06
  title: 或跃在渊，进无咎
  type: principle
  source_chapter: 乾卦·九四
  V1_cross_domain:
    passed: true
    evidence:
      - 乾卦九四：或跃在渊，无咎
      - 乾卦文言：知至至之，可与言几也
  V2_predictive_power:
    passed: true
    novel_question: "进阶时机如何判断是否成熟？"
    derived_answer: "'在渊'——在深渊中蓄势（准备期）；'跃'——起跳（行动期）。判断标准：① 谋划是否充分？② 时机是否合宜？③ 是否有Plan B？三者具备才'进无咎'——盲目冒进=有咎。"
  V3_exclusivity:
    passed: true
    why_not_common: "'谨慎行动'是常识，但'渊'（蓄势）+ '跃'（起跳）的辩证 + '知至至之'的时机精准判断有独特性。"
  → 进入阶段2

- id: p13
  title: 穷则变，变则通，通则久
  type: principle
  source_chapter: 系辞下·第二章
  V1_cross_domain:
    passed: true
    evidence:
      - 系辞下：穷则变，变则通，通则久
      - 革卦：己日乃孚，元亨利贞，悔亡
      - 鼎卦：元吉，亨
  V2_predictive_power:
    passed: true
    novel_question: "为什么很多变革'变'了但不'通'？"
    derived_answer: "缺条件：'己日乃孚'——变革前必须有信任积累；'悔亡'——变革后必须消除隐患。变而不通=变得太早（孚不足）或变后无巩固（无鼎）。通则久=通之后要有固化机制。"
  V3_exclusivity:
    passed: true
    why_not_common: "'穷则变'已是成语，但附带的'己日乃孚'时机条件 + '鼎'的巩固机制组合，使这一原则超越了一般成语解读。"
  → 进入阶段2
```

### Counter-examples（10条）— 默认通过V1/V2

```yaml
counter_examples:
  - id: ce01
    title: 亢龙有悔——极端冒进的下场
    bound_to: [限制"敢为天下先"的滥用, 限制"快速扩张"类策略]
  - id: ce02
    title: 盛极而衰——巅峰状态后继续激进导致下滑
    bound_to: [限制"规模经济"在鼎盛期的过度应用]
  - id: ce03
    title: 商纣沉湎于酒——放纵导致亡国
    bound_to: [限制"功成不居"原则的滥用]
  - id: ce04
    title: 积不善之余殃——恶行长期积累最终爆发
    bound_to: [限制"快速成功"类策略]
  - id: ce05
    title: 履霜坚冰至——忽视初期微弱预警信号
    bound_to: [限制"时机等待法"的消极应用]
  - id: ce06
    title: 小人勿用必乱邦——关键岗位用人失当
    bound_to: [限制"中庸和谐法"的过度包容]
  - id: ce07
    title: 穷之灾——路径封闭后强行继续推进
    bound_to: [限制"变革创新论"的冒进]
  - id: ce08
    title: 明入地中——逆势在不友善环境中硬冲
    bound_to: [限制"刚柔并济法"的过度刚]
  - id: ce09
    title: 否之匪人——策略与闭塞环境完全不匹配
    bound_to: [限制"顺势而为法"的盲目跟从]
  - id: ce10
    title: 山附于地剥——基础逐步侵蚀最终整体崩溃
    bound_to: [限制"德位匹配论"的过度自信]
```

### Cases（10条）— 默认通过V1/V2

```yaml
cases:
  - id: yi_case_01
    title: 周公测日影迁都洛邑
    bound_to: [科学决策方法, 迁都战略]
  - id: yi_case_02
    title: 商纣沉湎于酒亡国
    bound_to: [危机意识, 功成不居]
  - id: yi_case_03
    title: 武王伐纣改朝换代
    bound_to: [变革决策, 宽恕与安定]
  - id: yi_case_04
    title: 古公亶父迁徙岐山
    bound_to: [战略迁徙, 顺应时势]
  - id: yi_case_05
    title: 立太子之慎重
    bound_to: [嫡长继承制, 政权传承]
  - id: yi_case_06
    title: 帝乙归妹——和亲政策
    bound_to: [和亲外交, 战略缓和]
  - id: yi_case_07
    title: 周公摄政与"不事王侯"
    bound_to: [忠臣之道, 功成身退]
  - id: yi_case_08
    title: 高宗伐鬼方——三年克之
    bound_to: [持久战风险, 用人原则]
  - id: yi_case_09
    title: 周文王积善行仁天下归心
    bound_to: [仁德治国, 积善累德]
  - id: yi_case_10
    title: 东邻杀牛不如西邻夏祭
    bound_to: [与时偕行, 天时地利]
```

### Glossary（10条）— 全部通过

```yaml
glossary:
  - {id: g01, term: 乾, key_distinction: "≠天 → 规划未来"}
  - {id: g02, term: 坤, key_distinction: "≠地 → 厚德处事"}
  - {id: g03, term: 龙, key_distinction: "≠神兽 → 计划"}
  - {id: g04, term: 元, key_distinction: "≠起始 → 使之周全"}
  - {id: g05, term: 亨, key_distinction: "≠通顺 → 有利于取得成功"}
  - {id: g06, term: 贞, key_distinction: "≠占卜 → 坚定不移"}
  - {id: g07, term: 彖, key_distinction: "≠断裂 → 孔子对卦辞的判断"}
  - {id: g08, term: 象, key_distinction: "≠符号 → 通过卦象模拟万物规律"}
  - {id: g09, term: 道, key_distinction: "≠道德/道路 → 《周易》治国法则"}
  - {id: g10, term: 太极, key_distinction: "≠终极真理 → 阴阳未分的宇宙原始状态"}
```

---

## ❌ 未通过验证（rejected/目录）

### Frameworks未通过（10条）

| ID | 标题 | 失败原因 |
|----|------|----------|
| f01 | 乾坤纲领法 | V3失败：乾坤体系在中华文化中已是高度常识，"天行健""地势坤"几乎人人皆知，缺乏独特解读角度 |
| f02 | 进退存亡抉择法 | V3失败："亢龙有悔""知进退"是常见成语，缺乏独特洞见 |
| f03 | 周期循环观 | V3失败："物极必反""盛极必衰"是常见成语，独特性不足 |
| f08 | 中庸和谐法 | V3失败："中庸"已是文化常识，"保合太和"的独特性未能在V2中充分证明 |
| f16 | 祸福转化法 | V3失败："祸福相依"在中华文化中是常识 |
| f17 | 止于至善法 | V1失败：仅来自艮卦一个语境，跨域证据不足 |
| f18 | 创业起步法 | V1失败：仅来自屯卦一个语境，跨域证据不足 |
| f20 | 修身齐家法 | V3失败："各安其位""正家而天下定"是文化常识 |
| f09 | 居安思危法 | V3失败："安而不忘危"已是常见成语 |
| f13 | 诚信立业法 | V1失败：仅来自中孚卦一个语境，V3的独特性未救V1 |

### Principles未通过（12条）

p01天行健、p02地势坤、p03亢龙有悔、p07飞龙在天、p08积善之家、p09履霜坚冰至、p10直方大、p11一阴一阳之谓道、p12形而上者谓之道、p14安而不忘危、p15善不积不足以成名——以上均因V3失败（常识性过高）被拒。

---

## 质量门检查

- [x] V1跨域验证：frameworks通过10/20（50%）
- [x] V2预测力：全部通过的frameworks均能推导新问题
- [x] V3独特性：未通过条目均有明确失败原因记录
- [x] counter-examples/cases/glossary按规则默认通过
- [x] 未通过条目已记录原因（审计价值）

**通过率66%**，符合方法论密集书籍的预期范围（30%-70%）
