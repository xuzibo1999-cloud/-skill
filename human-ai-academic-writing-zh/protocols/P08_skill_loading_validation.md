# P08 Skill 完整加载与防伪验证

## 新会话 FULL LOAD
必须读取 MANIFEST、SKILL、全部 core、P01–P08、templates、required corpus。对 `emoji_dialogue_full_source.md` 至少读取 canonical ranges；需要案例全文复盘时加载全文。

## 输出 `SKILL_LOAD_REPORT`
必须包含：
- Skill name/version
- Core loaded count
- Protocol loaded count
- Template loaded count
- Corpus states
- 8 条关键原则校验
- canonical rejected→accepted case
- Ready mode

模板见 `templates/skill_load_report.md`。

## FULL 防伪条件
准确给出至少一个 corpus conversion：
1. Study1=w>0 / Study2=Δw / Study3=Δs → REJECTED；accepted ceiling = relative behavioral effect/context dependence；或
2. “进入判断” → “影响判断”；或
3. “更加一致/匹配” → “在内容上直接对应”；或
4. Study3 假对称 → expressive 单侧优势 + assertive n.s. 原样保留。

如果不能：`SKILL_LOAD_INCOMPLETE`。

## Same-session
已经 FULL 后可报告 `SESSION_VERIFIED`，不必每轮重新读取全部 corpus，但若用户要求回放某案例或长时间上下文发生漂移，应重载相关文件。

## 禁止
不得用“我已经理解全部要求”替代可验证 report；不得把当前会话中的临时候选规则写成永久 skill，除非状态为 ADOPTED。
