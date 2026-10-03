# P3 R04：新增原文核验与候选 B 裁决状态

日期：2026-10-03（Asia/Shanghai）。本文件仅为公开状态及恢复索引；完整未发表研究非公开保存。

## 恢复及真实新增

从 426b93c3c530a2058095907ad2f2f2d780b1375a 恢复，启动与写入前 main 均未变化。全文读取 CURRENT、R01/R02/R03_STATUS、NEXT_COMMAND，实际恢复并读完 R01–R03 报告、R01 TeX 和四页证明 PDF。旧报告、证明及两份原稿的 SHA-256 与恢复记录一致，全部保留原样。原稿全篇阅读及反例完整复核沿用 R01/R02，不重复计为进展。

四篇用户新增的期刊原文全部到位并全文读完；WH24 的完整模型和证明也读完。R03 的“这五篇全文未取得”仅作为历史保留，已不代表当前状态。文件到位与指定定理核验分别记录。

## 原文文件身份

| 附件 / 简称 | 页数 | DOI | SHA-256 |
| --- | --- | --- | --- |
| 18m1197862.pdf / WHS19 | 24 | 10.1137/18M1197862 | 23330e1e34452e66919a68264d672a2d8e281b5c9bba60c07c79b53c549dc363 |
| 陈虎.pdf / CHZ26 | 24 | 10.1016/j.jde.2025.113819 | 8a431cc9d2668c84464205ae30eed7c2bdeedb42c44e265aed2657dea8bccd7c |
| s10884-022-10161-2.pdf / ZC23 | 17 | 10.1007/s10884-022-10161-2 | 20cb48d23034e39e4631d22105877ccedcc7b0f02d8cc7da09b5f102f7d6fbdf |
| 1-s2.0-S0022247X24004554-main.pdf / CZ24 | 16 | 10.1016/j.jmaa.2024.128533 | 62e442a6c2bd78b01b623fe4a2d7c46bcc65587a7714003ea7df9eaf7250ffcc |
| s10884-023-10269-z.pdf / WH24 | 21 | 10.1007/s10884-023-10269-z | f1efe9cebe2f443eb84a6cb9e7243b24398ea4d8cb1d102adf94ea3bd644a2e2 |
| 控制系统书.pdf / Kawan13 | 290 | 10.1007/978-3-319-01288-9 | c68fe56fc0c76324bcb34a5c878c13d659741bc966a81e12f62cd3fb50c957b6 |

前五项均为期刊排版 PDF，全文读完；页数是实际 PDF 页数。Kawan13 未整本阅读：只读取本轮所需的 control-set/no-return、strict spanning subadditivity、invariant covers/partitions、entropy identity、data-rate theorem 的完整相关证明及 p. 87 generator 问题，printed pp. 26–28、45–47、78–87。

ZC23 两位作者，2022-04-26 在线/VOR、2023 年 9 月卷期；WH24 2023-05-12 在线/VOR、2024 年 12 月卷期；CHZ26 2025-10-09 在线、2026 卷年。完整准确 APA 与版本记录在非公开报告，不把在线年与卷年混用。

## 指定核验结果

- WHS19：Eq. (2.1) 是 infimum。Theorem 6.4 先固定 clopen invariant partition，K 非空紧；内部 weighted content、Frostman、Billingsley 证明已读。Corollary 6.5(iii) 还要求 maximally irreducible clopen partition，不能用于无条件 sup/inf 交换或自动用于 B。
- CHZ26：Theorem 3.3 同样 fixed clopen / compact K；固定尺度参数 α，成本的临界变量为 s。指定证明中的时间归一化、参数复用等问题已对照 PDF 图像定位，完整报告给出本轮离散整数 period 范围的修正推导。未认证全篇其余定理或连续非整数 period 版本。
- ZC23 Theorem 2.10：bounded strict complexity ⇔ finite equi-invariability，证明实际给出固定有限永久安全程序覆盖。B 的假设满足它，证明中的逐点收敛子列选择已明确补足。inner、outer 与 strict 区分；Theorem 3.5 的强化需要 technical control set，B 不具备。
- CZ24 Theorem 2.3：在 compact K、closed Q、joint continuity 下适用；K=Q 给出 finite EI 和 EI 点稠密。Theorem 2.6 / Corollary 2.7 等更强结论需要 control set。未找到固定 finite-period Borel partition 达到零 itinerary entropy 的原文取到结论。
- WH24：Theorem A 要 nonsingular µ 和 µ-strong interior invariance，结论是 inf_H R(H)。编码因果，但可用完整历史、时间索引与可变 finite alphabets，不要求有限记忆或有限状态；证明只构造任意 ε 近似的 coder，不能当成 B 的固定分割零率定理。
- Kawan13：相关 strict inf identities 和 data-rate proof 已实际读完，不能把 inf 误写成 min。

WHS19 Corollary (ii)/(iii) 引用的 Huang–Zhong18 Theorems 3.1、4.1、5.1 原文未完整取得。报告给出在明确 compact/clopen 及 maximally irreducible 条件下的独立核对，不假装已读该外部原文。2013 note 的公开早期稿只实际读到前部及 strong-interior 主定理证明，期刊定稿/后部未完整核验；strict identity 的核验采用已读完整书中证明。

出版社页面和针对性勘误检查未找到可核验的目标 corrigendum；不宣称不存在勘误。Elsevier 当前页面的 403/InternalError 不影响已提供 PDF 的全文读取。没有重复四篇附件的旧失败获取；新增依赖失败的确切地址与位置在非公开报告。

## B 的覆盖、意义、分量、可行性

B 保持原目标：紧光滑 M、有限 U、C∞ 转移、非空紧 controlled invariant Q=closure(int_M Q)、全部序列 admissible；bounded strict spanning complexity 是否蕴含存在某个固定有限 period 的有限 Borel invariant partition，指数 itinerary entropy 为零。不添加 control-set、inner/outer containment、有界 itinerary 或所有尺度零要求。

覆盖：已核验原文给出有限安全程序与 dense EI，没有给出 B 的固定零熵分割；本轮未建立由它们严格推出 B 的进一步推导。不能宣布 B 已覆盖，也不能据此宣布全球未覆盖或原创。

意义：固定分割取到与既有零 entropy、不同分割的率趋零确实不同。但在文献允许完整历史和共享时钟的通信模型中，有限初始通信后永久安全且平均率零，已经由 bounded strict complexity 假设推出；它不是 B 的新增重大后果。没有证明 B 严格导出独立四大级重大数学命题，也没有把它误写成 strong interior 或有限状态控制结论。

分量：本轮有实质原文证据、指定证明范围核验及原文书写问题修正；B 的新定理、反例与决定性证明步骤为零。R03 的 finite-program compactness 论证现在明确归于 ZC23/CZ24 已发表机制，不再留原创性暗示。

可行性：永久程序尾部不保证属于原有限家族，逐 block 当前状态重选也不保证原程序接续；固定规则的全部 itinerary 次指数界尚未解决。这里是已有推导的确切停点，不是新构造的失败尝试，也不是 B 反例。光滑性、有限输入和 regular closed 条件本身不解决接口或证明重大意义。

裁决：R04_COMPLETE / NO_UPGRADE_ROUTE_APPROVED / B_PAUSED。证据门槛仍未通过，未启动新 B 核心攻击。A 的无条件目标继续停止，不改名、不加第三候选、不把润色或外围引理记作升级。

## 完整成果恢复身份

| 文件 | 字节数 | SHA-256 |
| --- | --- | --- |
| P3_R04_Research_Report.md | 46,438 | 4f887e415f5f088517d8f31eb1a5e41c94380f8d38bec218fbfb8904ff439490 |
| P3_R03_Research_Report.md | 22,852 | cc1dbc2d322de844a487c94c449b9bc4ce65c07119b63d2ba7c43e85c9d020e6 |
| P3_R02_Research_Report.md | 32,240 | b0efa60cb65f80c2642045d1a51389cd71efc71a03c4bedf17cadacb9393bd83 |
| P3_R01_Research_Report.md | 24,182 | 585516b2321ee13d53587c3b20bc05ed36ac213c447ebfeeb79d2b4f02bbb759 |
| P3_R01_Minimax_Gap.pdf | 284,603 | 03d94cece1eeef28182f854200f2f9ef0b2c94e436d5ace1ab5622898d1d015d |
| P3_R01_Minimax_Gap.tex | 12,893 | 2e4b6a98ade558f35fb7b0a7000d355f565bdfd059a7b65ba26884aab8cf4cea |

R04 完整报告已非公开保存，含实际恢复、原文身份、全部指定核验、修正推导、覆盖对照、意义的完整逻辑检查、失败与未核验项、下一入口及 APA/DOI。公开仓库未上传任何完整研究报告、证明或论文全文。原稿身份见 CURRENT，历史状态 R01–R03 保留原样。

需要补核的实际引用原文：Huang, Y., & Zhong, X. (2018). Carathéodory–Pesin structures associated with control systems. Systems & Control Letters, 112, 36–41. DOI 10.1016/j.sysconle.2017.12.009。需含完整定义、Theorems 3.1/4.1/5.1 及证明的期刊最终 PDF；有公开 corrigendum 时一并核验。补这一历史依赖不会自动解除 B 的意义暂停。

下一入口见 NEXT_COMMAND。只有会改变覆盖或重大后果裁决的新证据，才恢复 B 的核心攻击；没有新输入不重复生成轮次成果。只研究 P3，不读改 P4/P6，不安排多代理，不投稿、购买、登录或对外联系。目标保持 Annals / Inventiones / JAMS / Acta。提交后实际回读 latest main、写入文件、旧状态及公开范围。
