# Emoji 案例：优化后的人机决策对话语料

## 使用方式
此文件不是“论文模板”，而是把长对话压缩为 **USER QUESTION → ASSISTANT CANDIDATE → EVIDENCE CHECK → DECISION → GENERAL RULE**。源段落索引用于回到 `emoji_dialogue_full_source.md` 核验。只有 `ACCEPTED` 决策可转化为规则；`REJECTED` 只用于错误回归。

---

## EP01：IIT 是否要求直接测 weight/value？
**USER**：使用 IIT 到底需不需要分别测“价值”和“权重”？  
**SOURCE**：[4] 起。

**EVIDENCE CHECK**：经典 functional measurement 确实区分 scale value 与 weight，但采用 IIT 并不自动要求增加两个自陈量表；真正问题是研究是否声称自己识别了这些参数。普通主效应/interaction 不能自然分离 w 与 s。

**DECISION — ACCEPTED**：IIT 可作为较宽的 judgment/information-integration account；当前研究不额外声称估计 functional weight/value。

**GENERAL RULE**：理论内部存在参数 ≠ 当前研究必须测参数；但只要论文声称参数变化，就必须有专门识别。

---

## EP02：三项实验“完整覆盖 IIT 参数”是否成立？
**USER/CANDIDATE**：提出 Study1=w>0、Study2=Δw、Study3=Δs，并称“三把钥匙”“完整闭环”。  
**SOURCE**：[327]；核查从 [329] 起。

**EVIDENCE CHECK**：Study 1 没估计 w；Study 2/3 的 interaction 无法区分 weight、scale value 或二者联合变化；不存在 functional measurement identification。

**DECISION — REJECTED**：整套参数化映射删除。

**ACCEPTED REPLACEMENT**：Study1 建立 meaningful cue 的行为效应；Study2/3 分别显示相对行为作用随 food category / communication frame 改变。

**GENERAL RULE**：漂亮理论故事不得先构造，再逼数据进入；interaction 只授权 relative effect conditionality，不授权具体参数。

---

## EP03：总理论能否直接给 H2/H3 方向？
**QUESTION**：IIT/食品接受框架能否直接推出某食品/文字条件下哪类 emoji 更高？

**EVIDENCE CHECK**：两个 umbrella theories 能组织条件性，但不能单独给出具体 representational/emotional 方向。

**DECISION — ACCEPTED**：总理论组织问题；食品、emoji、沟通领域文献产生方向。

**GENERAL RULE**：Prediction authority 与 theory centrality 分开。核心 theory 不等于每个方向都由它推出。

---

## EP04：“进入消费者判断”还是“影响消费者判断”？
**CANDIDATE**：食品相关视觉信息“进入”消费者对已购食品的未来重复选择。

**EVIDENCE CHECK**：研究测的是回购意愿，不是信息进入/注意/整合 admission process。

**DECISION — ACCEPTED REVISION**：“进入”→“影响”。

**GENERAL RULE**：微小动词也携带机制承诺；未测 cognitive entry 时回到实际 outcome relation。

---

## EP05：“更加一致/匹配”还是“在内容上直接对应”？
**CANDIDATE**：情绪型 emoji 与表达式文字“更加一致”。  
**SOURCE**：最终审查中明确指出“更加一致”可能被理解成 perceived congruence。

**EVIDENCE CHECK**：没有 congruence measure。

**DECISION — ACCEPTED REVISION**：改成“在内容上直接对应/直接对应相对更强”。

**GENERAL RULE**：objective stimulus-content relation ≠ perceived psychological match。

---

## EP06：食品类别还是“食品情境”？
**QUESTION**：为了理论编织，是否把实际变量都改成“食品情境/沟通情境”？

**DECISION — REJECTED**：Title、H、Methods、Results 使用实际“食品类别”“文字沟通框架”；Theory/Contribution 才允许提升到目标食品/伴随沟通信息。

**GENERAL RULE**：vertical gear shift；理论编织不能牺牲 operational precision。

---

## EP07：H1 是否必须重新塞入两个总理论？
**DECISION — KEEP**：不加。

**WHY**：H1 方向来自回购、emoji meaning、food-related meaning evidence；umbrella theories 不给该方向。强行加只制造 theory-name repetition。

**GENERAL RULE**：“不改”是正式结论；理论存在感来自正确职责，不是名字频率。

---

## EP08：Study 3 是否应该写成漂亮双向匹配？
**ACTUAL RESULT**：表达式文字下 emotional > representational；断言式下无可靠差异。

**REJECTED STORY**：assertive→representational，expressive→emotional 的完整对称。

**ACCEPTED**：保留不对称；H/Discussion 使用 relative shift，不预测/不声称 assertive 条件的反向显著优势。

**GENERAL RULE**：数据不负责替理论保持对称；n.s. 不得被 narrative symmetry 修复。

---

## EP09：5.1 是否重新念总理论？
**DECISION — KEEP RESULTS FIRST**：5.1 只回收 actual patterns 和邻近领域实证；5.2 才显式回收总理论贡献。

**GENERAL RULE**：5.1=What did we find；5.2=What does this add theoretically。

---

## EP10：5.2 能否写“多个情境共同决定/约束”？
**EVIDENCE CHECK**：Study 2 与 Study 3 分别操纵两个 moderators，没有联合模型。

**DECISION — REJECTED**：“共同决定/共同约束”改为“分别考察”，再升维到有限的 context-dependence conclusion。

**GENERAL RULE**：separate studies ≠ joint determination。

---

## EP11：Limitations 是否列 attention、semantic accessibility、参数等一长串？
**DECISION — DELETE**：删去没有进入核心理论/测量的机制清单，只保留实际 evidence boundary，如未直接测 information evaluation/integration process。

**GENERAL RULE**：Limitations 不是新理论生成器；future research 只补当前 evidence gap。

---

## EP12：最终理论强化应加多少？
**DECISION**：主要通过术语稳定、Theory Role、变量映射和 5.2 最终汇合强化；少量新增文字，同时删重复。

**GENERAL RULE**：理论密度优先通过咬合度提高，而非理论名/心理术语/篇幅堆积。
