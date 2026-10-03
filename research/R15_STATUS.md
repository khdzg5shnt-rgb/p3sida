# P3 R15 STATUS

更新时间：2026-10-04（Asia/Shanghai）

## 执行及裁决

R15_COMPLETE / ONE_BOUNDED_CORE_ATTEMPT / ACTUAL_OUTPUT_OBSTRUCTION_PROVED / FINITE_LOOKAHEAD_OBSTRUCTION_PROVED / SAFE_LANGUAGE_REDUCTION_PROVED / CONTINUOUS_VS_BOREL_EXAMPLE_PROVED / FINITE_AMBIGUITY_ATTAINMENT_UNRESOLVED / M2_UNRESOLVED / NO_NEW_MAIN_RESULT / R12_PRESERVED / NO_NEW_MANUSCRIPT / NO_AUTOMATIC_RETRY。

用户本轮明确授权直接攻击 FA 的 M=2，替代 R14 的停止状态。启动 main 为 fba45a9841eb0d7bade6d8fbcaae7d10df9ff94b，实际 base tree 为 4f1688b31dda3f2b22b26aaf89f572af3cc00882。全文读取 CURRENT.md、research/R14_STATUS.md、NEXT_COMMAND.md，核对递归树及适用本地祖先路径，无 AGENTS.md 或后续实质成果。未安排多代理。

本轮有实质新推导，故保存完整私有报告并更新三份必要状态；没有稿件升级。此页不刊载未发表的完整构造、反馈规则或证明。

## 本轮已完成的准确范围

- 从候选反复出现进入实际输出计数，证明一个满足 FA2 的系统中，全部仅依赖当前候选集的规则及任意固定深度的候选后继观测规则受到正率障碍。覆盖所有固定 periods；没有只否定某一个优先级。
- 该系统本身有零率分割，所以这些障碍只排除限定方法，不反驳 FA2；没有把候选集历史计数替代真正输出。
- 从 FA2 实际构造完整永久安全输入语言的 Borel 表示与紧连续实现，证明紧化仍保留两候选界，以及安全续接、全部端点和真实原子名字的回拉界。
- 在具体紧语言模型上，证明连续固定块反馈与一般 Borel 反馈存在严格差别；实际构造 Borel 分割并完成全部初值、全部长度的统一计数。这个具体结果不是一般取到定理。
- 证明一个统一有限尺度近似引理，并明确其无法直接选择同一个零率反馈的原因。完整细节、物理时间归一化与准确开放命题在私有报告 §§4–9。

**一般 FA，包括本轮唯一目标 M=2，仍未解决。** 没有排除全部固定 periods 的全部 Borel invariant partitions，没有证明一般 Borel 取到。具体模型中的单调识别结构尚未从原始假设推出，不能偷偷加入前提。

相对 R14，新纪录是规则类别层面的实际输出障碍、精确安全语言归约和具体连续/Borel 区别。旧 R06 局部机制、经典控制器回拉和零下确界不计新主贡献。辅助结果的独立发表新颖性尚未认证；本轮不足以宣称增加 R12 主贡献或提高期刊档次。

## 私有完整成果：按实际保存结果恢复

| 项目 | 值 |
| --- | --- |
| 文件 | P3_R15_Research_Report.md |
| 保存路径 | /论文提升四大级别/P3_R15_Research_Report.md |
| library_file_id | libfile_df8a8e512c8c8191879aabf7e4786376 |
| file_id | file_00000000f62881fbb96a30a514362552 |
| version | 0 |
| 实际字节 | 41,591 |
| SHA-256 | 4f40ace8f467f78aee2130ceff7dfae3c0eefa6458a348dbcdc6f1e349ac4ccb |
| 类型 | 完整研究报告；含自足构造、证明、失败尝试、文献对应及未解接口 |

这是实际保存后的身份与版本。报告没有自指哈希；恢复时必须核对本表。无新增 manuscript、PDF 或原文包。不要从本公开摘要重建证明。

## 直接依赖恢复

R14 报告已实际恢复、核对身份和全文读取：

| 项目 | 值 |
| --- | --- |
| 文件 | P3_R14_Research_Report.md |
| library_file_id | libfile_0f5825873c7481918603e8ca6e3bfe5c |
| file_id | file_0000000090c881fbb44ce4fff3f67baf |
| version／字节 | 0／35,863 |
| SHA-256 | c9eafb33e77dd179823e541ce6d1c327725b1f1a1e2fd74ffaeff37cbe3db41e |

按实际依赖回读 R13 §5 完整双覆盖论证、R12 TeX 主构造及有限输入字典障碍、R06 §5 直接相关旧证明。R13、R12、原稿身份及字节核验保留，详见各轮 STATUS 与私有报告 §2；不重新开放旧 A/B 目标。

R12 当前阶段稿依旧使用实际保存版本：
- TeX：version 0，27,254 字节，SHA-256 3a70b7b5e3ebdfc89e7edd0bb5398d08f63bf185eb0cfda1595d2fe66823d470。
- PDF：version 0，288,210 字节、八页，SHA-256 54f5dd7cc1ba2c12ee7b13c7978fb3bb1eb7eb5e72f7afad8ff16aabb97ca5f4。
- 完整持久身份以 [R12_STATUS](R12_STATUS.md) 为准，不混用编译 payload。

原稿和 R12–R14 原字节不变。没有缺失资料需要用公开状态补造证明。

## 文献范围与未完成项

旧条件 generator、infimum identity、固定分割抽象等依赖沿用 R12–R14 已核范围，不扩大成此次全部重读。沿 Tomar–Kawan–Zamani 的真实引用链新增核验：

Reissig, G., Weber, A., & Rungger, M. (2017). Feedback refinement relations for the synthesis of symbolic controllers. *IEEE Transactions on Automatic Control, 62*(4), 1781–1796. https://doi.org/10.1109/TAC.2016.2593947

实际版本为 [arXiv:1503.03715v3](https://arxiv.org/abs/1503.03715v3)，2017-01-02 接受稿、27 页；479,526 字节，SHA-256 153267b425cfa135526d078af548b6efb1e1fa4213f67af6db65d696978702f5。直接相关定义和定理完整证明已读，版本/读取范围在私有报告 §10。经典控制回拉不能替代抽象系统上的零率反馈存在。没有全球优先权宣称。

尚未完成：一般紧两候选语言族中的固定 Borel 块规则与统一次指数真实名字界；或同类中排除全部固定块 Borel 规则的反例。具体模型在 Borel 类取到，不能冒充后一种反例。没有需要用户补找的必要原文。

## 保存与执行边界

GitHub 本次仅更新 CURRENT.md、research/R15_STATUS.md、NEXT_COMMAND.md。完整未发表推导非公开保存。提交后实际回读 main、提交文件列表和三份全文核对。

本次尝试关闭，无自动 R16、候选筛选或重复审稿。未来仅在新的具体授权下继续，不自动安排重复攻击。R12 已有核心不因本轮未解而否定。

只研究 P3；不读改 P4/P6；无多代理、购买、登录、投稿或对外联系；不重启 A、B、depth mechanism 或 R09 全名字推广。
