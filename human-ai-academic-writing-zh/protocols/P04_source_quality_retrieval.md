# P04 文献来源质量、检索与准入协议

## 总排序
**命题匹配度 > 原始/权威性 > 来源质量 > 近期性。**
高等级期刊不能替代 proposition match；一篇高度直接的 JCR Q1/Q2 专业论文可优于与当前关系很远的 UTD24。

## 双轨检索
### Recent Lane（rolling 60 months）
用于：议题现状、最新消费现象、gap、近期 boundary、近年 contradictory evidence。Introduction 的 contemporary empirical literature 默认多数来自近五年；不机械凑比例。

### Canonical Lane（不限年份）
用于：理论原典、里程碑 construct definition、经典 effect、方法原始文献、canonical taxonomy。

框架相关：核心/原始文献优先；议题相关：近期高质量文献优先。

## 来源质量优先池
在 proposition match 相近时优先：
1. 原始理论/方法/里程碑来源；
2. UTD24 / 当前 FT50 中的同行评审学术研究 outlet；
3. AJG 4*/4；
4. AJG 3、JCR Q1；
5. 高度相关 JCR Q2 专业期刊（心理、食品、沟通、HCI 等）。

注意：FT50 是 ranking list，不自动等于“核心理论证据”；若其中存在 practitioner outlet，只用于其适合的事实/实践用途，不以榜单身份承担 H direction。

## 默认排除
- MDPI publisher pool：默认排除；
- JCR Q3/Q4：默认不进入核心证据池；
- predatory/questionable outlet；
- 普通网页、AI 摘要站、ResearchGate 页面作为来源身份；
- conference abstract 替代正式论文；
- 未经核验 working paper 支撑核心方向。

### SOURCE_EXCEPTION
只有“与命题高度特异 + 无可替代高质量来源”同时成立时，Q3/Q4 或默认排除来源才可例外：
1. 明确标记 `SOURCE_EXCEPTION`；
2. 说明无替代证据原因；
3. 不作为核心理论/方向唯一证据；
4. 尽可能用高质量来源 triangulate；
5. 不能因为“刚好支持 H”降低门槛。

## 动态核验
- UTD24：UT Dallas 官方 journal list
  https://jsom.utdallas.edu/the-utd-top-100-business-school-research-rankings/list-of-journals
- FT50：Financial Times 当前 research journal list；使用时查当年/当前版本。
- AJG：Chartered Association of Business Schools 当前 Academic Journal Guide。编译日可核验 AJG 2024 methodology；使用时查更新。
- JCR：Clarivate 当前 Journal Citation Reports；若无法访问当前分区，标 `JCR_STATUS_UNKNOWN`，禁止猜。

编译日快照：Clarivate 已于 2026-06-17 发布 JCR 2026；期刊当前 quartile 必须按使用日官方 JCR profile/可信机构数据核验。

## Full-text Verification State
- TITLE_ONLY：禁止正式引用复杂命题
- ABSTRACT_VERIFIED：只用于候选筛选/简单摘要层命题
- FULLTEXT_VERIFIED：可正式绑定具体命题
- ORIGINAL_THEORY_VERIFIED
- METHOD_DOC_VERIFIED

核心 theory、H direction、争议性 claim 尽量要求全文/原始来源核验。

## 检索输出
先建立 `Citation Evidence Matrix`，再搜。每条候选文献必须注明：Claim ID、directness、source tier、year、verification state、是否有替代。
