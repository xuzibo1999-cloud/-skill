# P03 PROCESS / 条件过程模型官方核验协议

**绝不凭 GPT 记忆选 PROCESS Model。先理论路径，后官方模型号。**

## 动态官方事实（最后核验：2026-08-22）
- Andrew F. Hayes 官方 version history：PROCESS 5.0 于 2025 年 6 月发布；官方 download 页给出 2025-06-01。
- 官方 FAQ：numbered model templates 位于 Hayes 著作 Appendix A；网上流传的很多 templates 已过时。
- 官方 FAQ：如果不知道 model number，应先根据研究问题/理论确定要估计的模型；若无完全对应的预编程 model，考虑 custom model（Appendix B）。
- PROCESS 是 regression-based tool，不是 SEM；可处理 direct/indirect effects、parallel/serial mediation、moderation、conditional indirect effects 等，但能力边界必须按当前官方文档核验。

官方入口：
- https://www.processmacro.org/download.html
- https://www.processmacro.org/faq.html
- https://www.processmacro.org/version-history.html
- https://www.processmacro.org/index.html

> 使用时必须重新核验当前版本；“5.0”只是本 Skill 编译日快照，不永久写死。

## 强制流程
1. 不看 Model 号，恢复 X/M1/M2/W/Z/Y。
2. 明确每一条理论路径和被调节路径。
3. 判断 mediator order、parallel/serial、first/second-stage moderation。
4. 查当前 Hayes 官方文档/最新版书 Appendix A；不得使用博客、知乎、小红书、旧模板截图或 GPT 记忆。
5. 若 numbered template 不精确对应，不强套；查 custom model。
6. 输出 `templates/process_verification_card.md`。
7. 理论文本写路径关系，不写“因为 Model 7 所以……”。Model number 只属于 Methods/analysis implementation。

## 特别限制
- “一个条件 indirect 显著、另一条件不显著”不能单独证明 moderated mediation；使用当前模型适用的 index/contrast/conditional effect inferential test。
- full/partial mediation 不作为默认理论标签。
- 同时测量 mediator 时，不把统计顺序写成真实心理时间顺序。
- PROCESS 输出不能授权未测 construct。

## 来源引用
方法正文如需引用 PROCESS，应以 Hayes 当前官方书/文档为准；官方 FAQ 明确指出 2012 white paper 已过时，不应作为当前 PROCESS 的合理引用。
