# CURRENT

更新时间：2026-10-03（Asia/Shanghai）

## 当前裁决

- 阶段：R04_COMPLETE / NO_UPGRADE_ROUTE_APPROVED / B_PAUSED。B 真伪未定，获准继续的四大路线仍为零；A 的无条件目标继续停止。
- R04 恢复点与启动 main：426b93c3c530a2058095907ad2f2f2d780b1375a。启动和写入前核对均无后续变化。原稿基线 5284f1272dcf877ec209a344ec09c9db3f55ba59 保留。
- 实际恢复并全文读取 R01–R03 完整报告、R01 TeX 及四页证明 PDF，核对恢复 SHA-256；原稿及旧成果保持原样。原稿全篇及主证明复核沿用 R01/R02，不把重复读取算作升级。
- 新增原文已到位：WHS19、CHZ26、ZC23、CZ24 四篇期刊 PDF 全文读完，指定定义、定理、证明及本轮使用的依赖已在明确范围内核对。WH24 数据率论文也全文读完，Kawan13 的相关章节及完整证明已读。文件身份、版本、DOI、SHA-256 和准确 APA 见 R04_STATUS 与非公开报告；不再标记上述五篇全文不可得。
- 新覆盖证据：ZC23 Theorem 2.10 与 CZ24 Theorem 2.3 在 B 中适用，给出有限永久安全程序覆盖、finite equi-invariability 及稠密 equi-invariant 点。更强的 control-set 定理需要额外可达性和最大性，B 未假定这些条件。
- WHS19 Eq. (2.1) / Kawan13 是分割熵的下确界；WHS19 Theorem 6.4 和 CHZ26 Theorem 3.3 先固定 clopen 分割、要求 K 紧；WHS19 Corollary 6.5(iii) 另要 maximally irreducible clopen 分割。指定证明中的时间归一化与参数书写问题已定位，报告给出本轮离散整数 period 范围的修正核对，不扩张结论。
- 覆盖仍未最终裁定：已核验原文没有给出 B 的固定零熵分割，本轮未建立由这些结果进一步严格推出 B 的证明；不能宣布 B 已覆盖，也不能据此宣布全球未覆盖或原创。
- 意义裁决更明确：在原文允许完整历史、时间索引及可变 alphabet 的通信模型中，有限初始信息后永久安全、平均通信率零，已经由 bounded strict complexity 的假设推出。不能把它当作 B 的新重大后果；strong interior、有限记忆或有限状态结论也没有可靠蕴涵。
- B 实际新增的是某个固定有限 period 的有限 Borel 分割真正取到零指数 itinerary 率。本轮未建立它严格导出独立四大级重大数学后果的完整链。数学可行性仍未知，固定规则的可重复使用及全部 itinerary 次指数界没有解决。
- 新增的是实质原文与逻辑核验；B 的新定理、反例或决定性证明步骤为零。证据门槛未通过，按要求没有启动新核心攻击，不把修正已发表证明、外围引理或润色算作升级。
- 仍未核验：B 真伪与全部已知覆盖、重大后果链、Huang–Zhong18 的实际源版本、2013 note 的期刊最终编号/后部全文、穷尽的版本差异及勘误。指定五篇已提供全文不属于缺失项。

B 保持原目标：M 紧光滑流形，U 有限，每个 f_u 为 C∞，Q 非空紧、controlled invariant 且 Q=closure(int_M Q)，全部序列 admissible；bounded strict spanning complexity 是否蕴含存在某个固定有限 period 的有限 Borel invariant partition，其指数 itinerary entropy 为零。不加 technical control-set 条件，不更换 containment 或要求有界 itinerary / 所有尺度为零。

## 原稿与保存范围

| 文件 | SHA-256 |
| --- | --- |
| P3_JDE_FINAL_STYLE.tex | 79842eba9bdf4280b361eea04b6d3191b9429c61c4467019eb6245801464b7ee |
| P3_JDE_FINAL_STYLE.pdf | 568abbeb4268cb8676f66dcd3b0d1dfff149e91f7c5e3b54d7c80dbae0ef196e |
| P3_R04_Research_Report.md | 4f887e415f5f088517d8f31eb1a5e41c94380f8d38bec218fbfb8904ff439490 |

R04 完整报告为 46,438 字节，已非公开保存。仓库仍为 public，只含必要状态及恢复索引；未上传完整研究、证明或任何论文 PDF。R01–R03 的状态和完整成果保留原样。

本轮恢复身份及阅读范围：[R04_STATUS](research/R04_STATUS.md)。历史：[R03_STATUS](research/R03_STATUS.md)、[R02_STATUS](research/R02_STATUS.md)、[R01_STATUS](research/R01_STATUS.md)。下一入口：[NEXT_COMMAND](NEXT_COMMAND.md)。

目标保持 Annals / Inventiones / JAMS / Acta，不承诺成功、不降低目标。只研究 P3，不读改 P4/P6，不安排多代理，不购买、登录取得原文、投稿或对外联系。
