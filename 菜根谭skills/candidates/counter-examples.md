# 反例候选池 — 《菜根谭》反例提取器产出

> extractor: counter-examples (反例/失败模式/警告/陷阱)
> 输出路径: candidates/counter-examples.md
> 数量: 18条

---

- id: ce01
  title: 依阿权势之患
  type: counter-example
  source_chapter: 栖守道德 勿依权贵
  source_quote: |
    "栖守道德者，寂寞一时；依阿权势者，凄凉万古。达人观物外之物，思身后之身，宁受一时之寂寞，毋取万古之凄凉。"
  failure_mode: |
    依附权势、趋炎附势，为一时荣华放弃道德坚守
  mechanism: |
    依附权势者虽风光于当下，但终将遗臭万年；坚守道德者虽寂寞于一时，却能名垂千古。依附权贵是把自己的命运交给他人掌控，一旦权势崩塌，人格与名誉一同陪葬。
  warning_signs:
    - 开始为了利益接近权贵
    - 为讨好权势而放弃原则
    - 只看眼前利益不顾身后名节
  bound_to:
    - "道德坚守原则"
    - "淡泊明志原则"
  tags: [counter-example, failure-mode, ambition, integrity]

- id: ce02
  title: 机械深沉之患
  type: counter-example
  source_chapter: 抱朴守拙 涉世之道
  source_quote: |
    "涉世浅，点染亦浅；历事深，机械亦深。故君子与其练达，不若朴鲁；与其曲谨，不若疏狂。"
  failure_mode: |
    饱经世故后变得世故圆滑、工于心计，以"练达"为荣
  mechanism: |
    阅历越深，奸诈之心也随之增加。世故圆滑看似聪明，实则让自己陷入无休止的算计之中，失去纯真本性，最终聪明反被聪明误。
  warning_signs:
    - 做事开始讲求"套路"
    - 对每个人都设防
    - 习惯用技巧代替真诚
  bound_to:
    - "以我转物原则"
    - "和气致祥原则"
  tags: [counter-example, failure-mode, cynicism, sophistication]

- id: ce03
  title: 快意不知回首
  type: counter-example
  source_chapter: 快意早回头 拂心莫放手
  source_quote: |
    "恩里由来生害，故快意时须早回首；败后或反成功，故拂心处莫便放手。"
  failure_mode: |
    春风得意之时不知见好就收，贪恋权位不肯急流勇退
  mechanism: |
    恩深往往生害，盛极必致衰败。得意时不知退让，树大招风，祸患随至。历史上李斯、吴王刘濞等皆因贪恋富贵、追求更大权力而身败名裂。
  warning_signs:
    - 处于巅峰时愈发贪婪
    - 不愿接受任何退让
    - 享受众人吹捧不能自拔
  bound_to:
    - "退让一步原则"
    - "宠辱不惊框架"
  tags: [counter-example, failure-mode, greed, pride]

- id: ce04
  title: 肥甘丧节
  type: counter-example
  source_chapter: 淡泊明志 肥甘丧节
  source_quote: |
    "藜口苋肠者，多冰清玉洁；衮衣玉食者，甘婢膝奴颜。盖志以淡泊明，而节从肥甘丧也。"
  failure_mode: |
    贪图物质享受，在肥甘美味中丧失气节，为求富贵而卑躬屈膝
  mechanism: |
    追求物质享受的人容易被物欲名利所诱惑，不惜用任何手段钻营，甚至卑躬屈膝也在所不惜。节操在贪图享受中丧失殆尽，见钱眼开、玩物丧志，最终触犯法律。
  warning_signs:
    - 对物质享受的追求超越了对品德的追求
    - 开始为利益放弃尊严
    - 消费水平远超合理范围
  bound_to:
    - "淡泊明志原则"
    - "道德坚守原则"
  tags: [counter-example, failure-mode, materialism, integrity]

- id: ce05
  title: 富贵忌刻
  type: counter-example
  source_chapter: 富贵宜厚 智宜敛藏
  source_quote: |
    "富贵家宜宽厚而反忌刻，是富贵而贫贱其行矣，如何能享？聪明人宜敛藏而反炫耀，是聪明而愚懵其病矣，如何不败？"
  failure_mode: |
    富贵之家反而刻薄待人；聪明人反而炫耀卖弄
  mechanism: |
    富贵之家本应接济贫穷、多行善举，刻薄挑剔则违背天道。真正有智慧的人如麦穗般谦逊低头，越炫耀自己缺知少识。聪明人故意卖弄，则愚昧可笑，终致失败。
  warning_signs:
    - 富贵后对不如自己的人态度变差
    - 取得成绩后到处炫耀
    - 对他人吝啬计较
  bound_to:
    - "和气致祥原则"
    - "谦逊低调原则"
  tags: [counter-example, failure-mode, arrogance, pride]

- id: ce06
  title: 偏激为灾
  type: counter-example
  source_chapter: 中和为福 偏激为灾
  source_quote: |
    "躁性者火炽，遇物则焚；寡恩者冰清，逢物必杀；凝滞固执者，如死水腐木，生机已绝，俱难建功业而延福祉。"
  failure_mode: |
    性格偏激：躁性、寡恩、凝滞固执
  mechanism: |
    躁性者火烈伤物，刻薄寡恩者冰冷无情，固执者死气沉沉。三者都难以建功立业、延及福祉。偏激是失败的前兆，偏执让机会流失。
  warning_signs:
    - 遇事急躁，不等准备充分就行动
    - 待人刻薄，不留情面
    - 听不进任何不同意见
  bound_to:
    - "中和处世框架"
    - "和气致祥原则"
  tags: [counter-example, failure-mode, temper, rigidity]

- id: ce07
  title: 谨言慎行不及
  type: counter-example
  source_chapter: 谨言慎行 君子之道
  source_quote: |
    "十语九中，未必称奇，一语不中，则愆尤骈集；十谋九成，未必归功，一谋不成，则訾议丛兴。君子所以宁默毋躁，宁拙无巧。"
  failure_mode: |
    浮躁多言、巧言令色，话多谋多反而更容易招祸
  mechanism: |
    话说多错多，十句对九句无人称赞，一句不中则怨尤集身；计谋亦然，十谋九成无功，一败则众议蜂起。多言多败，不如沉默持重。
  warning_signs:
    - 说话不假思索脱口而出
    - 计谋过度，患得患失
    - 总想表现自己的聪明
  bound_to:
    - "谨言慎行清单"
    - "中和处世框架"
  tags: [counter-example, failure-mode, arrogance, speech]

- id: ce08
  title: 欲情道狭
  type: counter-example
  source_chapter: 正义路广 欲情道狭
  source_quote: |
    "天理路上甚宽，稍游心，胸中便觉广大宏朗，人欲路上甚窄，才寄迹，眼前俱是荆棘泥涂。"
  failure_mode: |
    沉迷于物欲名利的追逐，患得患失，利欲熏心
  mechanism: |
    追求物欲如同走狭窄泥泞小路，步步陷阱，陷入后无力自拔。心路越走越窄，终日为功名患得患失，精神耗尽。追逐物欲是自我囚禁的开始。
  warning_signs:
    - 做事只看利益不顾其他
    - 得失心极重
    - 做事不从容，总在赶
  bound_to:
    - "淡泊明志原则"
    - "以我转物模型"
  tags: [counter-example, failure-mode, materialism, anxiety]

- id: ce09
  title: 躁性偾事
  type: counter-example
  source_chapter: 躁性偾事 和平徼福
  source_quote: |
    "性躁心粗者一事无成，心和气平者百福自集。"
  failure_mode: |
    性情急躁、粗心大意，做事急于求成
  mechanism: |
    急躁者无耐心，只求数量不求质量；粗心者无责任心，敷衍了事。这两个致命弱点决定做任何事都必然失败。急于求成反而欲速不达。
  warning_signs:
    - 做事总是很着急
    - 不愿在细节上下功夫
    - 情绪波动大
  bound_to:
    - "中和处世框架"
    - "动静皆静模型"
  tags: [counter-example, failure-mode, temper, impatience]

- id: ce10
  title: 阴恶祸深
  type: counter-example
  source_chapter: 阴恶祸深 阳善功小
  source_quote: |
    "恶忌阴，善忌阳。故恶之显者祸浅，而隐者祸深；善之显者功小，而隐者功大。"
  failure_mode: |
    做坏事怕被人知，暗中作恶；行善事急于让人知道，沽名钓誉
  mechanism: |
    暗中作恶是最深之祸根，伪善比显恶更有害。行善而自我宣扬则功小，只有默默行善功德才大。善恶皆在于心，不在于形。
  warning_signs:
    - 做见不得光的事
    - 帮助别人后到处说
    - 表面一套背后一套
  bound_to:
    - "道德坚守原则"
    - "淡泊明志原则"
  tags: [counter-example, failure-mode, hypocrisy, deception]

- id: ce11
  title: 有才无德之害
  type: counter-example
  source_chapter: 应以德御才 勿恃才败德
  source_quote: |
    "德者才之主，才者德之奴。有才无德，如家无主而奴用事矣，几何不魍魉而猖狂？"
  failure_mode: |
    有才无德，恃才傲物，以才害德
  mechanism: |
    才学若不以品德为主人，便如家中无主只有奴仆当家。没有道德引导的才能就像失去主人的奴仆肆意为恶，最终误入歧途，害人害己。
  warning_signs:
    - 认为自己有才能就可以不顾品德
    - 做事不考虑道德底线
    - 瞧不起品德高尚但才能不如自己的人
  bound_to:
    - "德主才奴原则"
    - "道德坚守原则"
  tags: [counter-example, failure-mode, integrity, talent]

- id: ce12
  title: 标节义道学之患
  type: counter-example
  source_chapter: 浑然和气 处事珍宝
  source_quote: |
    "标节义者，必以节义受谤；标道学者，常因道学招尤。故君子不近恶事，亦不立善名，只浑然和气，才是居身之珍。"
  failure_mode: |
    刻意标榜自己的节义和道学，以善名自居
  mechanism: |
    标榜节义者必为节义受毁谤，标榜道学者必因道学招非议。刻意立善名本身就是一种虚伪。真正的君子不标新立异，不求善名，只浑然和气。
  warning_signs:
    - 做了好事就希望别人知道
    - 经常强调自己多有道德
    - 看不起"俗人"
  bound_to:
    - "淡泊明志原则"
    - "和气致祥原则"
  tags: [counter-example, failure-mode, hypocrisy, vanity]

- id: ce13
  title: 轻诺多事倦终
  type: counter-example
  source_chapter: 不轻诺生嗔 不多事倦怠
  source_quote: |
    "不可乘喜而轻诺，不可因醉而生嗔，不可乘快而多事，不可因倦而鲜终。"
  failure_mode: |
    四种失败：乘喜轻诺、因醉生嗔、乘快多事、因倦鲜终（半途而废）
  mechanism: |
    得意忘形时随便许诺必难兑现；醉酒时乱发脾气；得意时恣意惹事；疲劳时放任疏懒有始无终。四者都是因一时失控而铸成大错。
  warning_signs:
    - 高兴时不加考虑地答应别人
    - 酒后才说"真话"
    - 得意时招摇过市
    - 累了就放弃
  bound_to:
    - "谨言慎行清单"
    - "律己宽人清单"
  tags: [counter-example, failure-mode, self-control, willpower]

- id: ce14
  title: 器小禄薄
  type: counter-example
  source_chapter: 量宽福厚 器小禄薄
  source_quote: |
    "仁人心地宽舒，便福厚而庆长，事事成个宽舒气象；鄙夫念头迫促，便禄薄而泽短，事事得个迫促规模。"
  failure_mode: |
    心胸狭隘、念头迫促，斤斤计较贪图眼前
  mechanism: |
    心胸狭窄者眼光短浅，斤斤计较于眼前小利，不顾他人权益，终将禄薄泽短、福尽祸至。只有心地宽舒者才能福厚庆长。
  warning_signs:
    - 处处与人计较
    - 只能占便宜不能吃亏
    - 做决定只看短期
  bound_to:
    - "和气致祥原则"
    - "退让一步原则"
  tags: [counter-example, failure-mode, selfishness, shortsightedness]

- id: ce15
  title: 以短攻短以顽济顽
  type: counter-example
  source_chapter: 毋以短攻短 毋以顽济顽
  source_quote: |
    "人之短处，要曲为弥缝，如暴而扬之，是以短攻短；人有顽固，要善为化诲，如忿而嫉之，是以顽济顽。"
  failure_mode: |
    当众揭发别人的短处；以愤怒厌恶对待别人的愚蠢固执
  mechanism: |
    当众揭人短不仅伤害别人自尊，也证明自己的无知无礼。对愚顽者忿而嫉之，只能证明自己同样愚顽。以短攻短，以顽济顽，恶性循环。
  warning_signs:
    - 喜欢揭人短处
    - 对别人缺点耿耿于怀
    - 总觉得自己比别人聪明
  bound_to:
    - "律己宽人清单"
    - "和气致祥原则"
  tags: [counter-example, failure-mode, arrogance, relationships]

- id: ce16
  title: 伪善诈善之患
  type: counter-example
  source_chapter: 明枪易躲 暗箭难防
  source_quote: |
    "君子而诈善，无异小人之肆恶；君子而改节，不及小人之自新。"
  failure_mode: |
    伪装善良的伪君子；正人君子改变节操
  mechanism: |
    伪君子比真小人更危险——满嘴仁义道德实则内心阴暗恶毒，欺骗性和危害性更大。君子改节不如小人自新，因其危害更隐蔽深远。
  warning_signs:
    - 表面一套背后一套
    - 满嘴道德实则自私
    - 为自己的堕落找借口
  bound_to:
    - "道德坚守原则"
    - "和气致祥原则"
  tags: [counter-example, failure-mode, hypocrisy, integrity]

- id: ce17
  title: 倚物役心
  type: counter-example
  source_chapter: 以我转物 逍遥自在
  source_quote: |
    "以物役我者，逆固生憎，顺亦生爱，一毛便生缠缚。"
  failure_mode: |
    被外物（名利、评价）所奴役，逆顺皆苦
  mechanism: |
    被物欲奴役的人，遭遇逆境满心怨恨，处于顺境又生恋栈之心。外物得失牵动内心，一毛小事便能使其身心困扰，失去自由。
  warning_signs:
    - 患得患失
    - 别人的评价能让自己高兴或痛苦很多天
    - 失去某样东西就觉得活不下去
  bound_to:
    - "以我转物模型"
    - "宠辱不惊框架"
  tags: [counter-example, failure-mode, materialism, attachment]

- id: ce18
  title: 飞蛾扑火 鸱鸮嗜腐
  type: counter-example
  source_chapter: 苦海茫茫 回头是岸
  source_quote: |
    "晴空朗月，何处不可翱翔？而飞蛾独投夜烛；清泉绿果，何物不可饮啄？而鸱鸮偏嗜腐鼠。噫！世之不为飞蛾鸱鸮者，几何人哉？"
  failure_mode: |
    明明有正道可行，却偏偏自取灭亡；明知不可为而偏要为之
  mechanism: |
    飞蛾有广阔晴空却偏投夜烛，鸱鸮有清泉美食却偏嗜腐鼠。世人明知某些路是死路，却偏偏执意行之，自投罗网，自取灭亡。
  warning_signs:
    - 明知不可为而强行为之
    - 贪恋危险的关系或机会
    - 重复同样的错误
  bound_to:
    - "以我转物模型"
    - "退让一步原则"
  tags: [counter-example, failure-mode, self-destruction, obsession]
