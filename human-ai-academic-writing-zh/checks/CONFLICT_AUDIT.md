# Module / Protocol Conflict Audit

版本检查结论：主结构保留，不新增 M13+；新增要求作为横向 protocols/templates/corpus infrastructure。

| 可能重叠 | 最终边界 | 结论 |
|---|---|---|
| M02 vs M08 | M02 决定能说什么；M08 把已授权命题正式化为可检验 H | KEEP BOTH |
| M03 vs M06 | M03 理论资格/分工；M06 共享理论骨架的正文写法 | KEEP BOTH |
| M04 vs M05 | M04 全文 architecture；M05 Introduction 实际论证与写作 | KEEP BOTH |
| M07 vs M08 | M07 论证 WHY；M08 formalize WHAT TO TEST | KEEP BOTH |
| M09 vs M10A | M09 5.1 回收 findings；M10A 计算 theoretical delta | KEEP BOTH |
| M11 vs M12 | M11 控制修改流程；M12 控制中文生成式病理 | KEEP BOTH |
| P04 vs P05 | P04 决定文献是否准入/优先级；P05 决定 claim 如何绑定 citation 与 APA7 | KEEP BOTH |
| P03 vs M07B | M07B 决定理论路径；P03 动态核验 PROCESS implementation | KEEP BOTH |

## 新增缺口已补齐
1. M04 一页式排兵布阵：已补。
2. Theory Role Card：已补。
3. PROCESS 不能凭记忆选模型：P03 已补，强制官方动态核验。
4. 文献准入/UTD24/FT50/AJG/JCR/MDPI/Q3：P04 已补。
5. Claim–Citation placement 与 APA7：P05 已补。
6. 触发式写作流程：P06 已补。
7. emoji 正负语料 + 完整源序列 + 最终正文：corpus 已补。
8. Skill FULL LOAD 防伪报告：P08 + template 已补。

## 需要持续动态处理而非写死的内容
- PROCESS current version/model templates
- FT50 current list
- UTD24 current list
- AJG current edition
- JCR current quartile/category
- 目标期刊 author guidelines

## Gold corpus 边界
最终正文是“最后已形成版本”的正向语料，但 citation placement 等新增规范可对其继续做回归审计；error corpus/decision log 对 canonical rejected cases 优先级高于 Gold。
