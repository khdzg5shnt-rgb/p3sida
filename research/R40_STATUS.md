# P3 R40 STATUS

更新时间：2026-10-07（UTC）

## 执行与裁决

R40_COMPLETE / FINITE_INPUT_NONATTAINMENT_VERIFIED / THIRD_MAIN_RESULT_ACCEPTED / THREE_RESULT_MANUSCRIPT_CREATED / R31_UNRESOLVED_PAUSED / R16_PRESERVED / NO_AUTOMATIC_RETRY。

用户明确授权 R39 有限输入 Borel 零率非取到定理的独立贡献裁决与条件式并稿。启动及复核 main 为 1c66f698bb3ee9966bde7155353585bdb5f79e56，base tree 为 04707da1c6d1e0e837a4b31907e7ede8b64ab8c0。全文读取 CURRENT.md、research/R39_STATUS.md、NEXT_COMMAND.md、research/R16_STATUS.md、README.md，核对完整仓库树和本地适用祖先，无 AGENTS.md、无后续实质完成项。

本轮暂停 R31 原存在性，不恢复 R19、一般 R18/R17 或 FA2。R38 没有成果文件，不索取、恢复或补造。只研究 P3，原稿与全部旧版保留。

## 独立核验及贡献范围

- R39 的同一个紧连续系统、三个输入、clopen 安全集、连续安全规则严格正率趋零，以及所有固定整数 periods、所有有限 Borel invariant partitions 正率，完整证明经本次独立审查成立。
- 完整核验全部紧化端点、全初值词数、准确循环长度、可无限续接的禁词前缀、实际块内偏移、信息恢复和全部安全端点。测试族只选择初值，不改变系统；共享状态采用同一个反馈。
- 全部 Borel 结论允许利用完整当前状态及任意合法块，不局限源输出或受限 selector。正率依赖规则和 period，没有共同正下界；按真实物理时间归一化。
- 本例 strict spanning 数无界。没有两个永久程序覆盖全部初值，不是 R16 第一例全部性质的有限输入推广。
- 该给定近似族不能满足 R31 稀疏修改条件，因此不是 R31 原反例。R31 仍未解决，本轮没有修补其前提。
- 直接原文及真实引用链的有界对照支持独立增量，未发现严格覆盖。infimum identity、条件性 generators、有限永久程序、有限输入字典、overlapping cover 最小计数与实际反馈名字已分别处理。不认证全球首次，不以搜索缺失证明新颖。
- 结果可以作为第三项主贡献：有限输入与 clopen safety 仍不足以保证 Borel 零率取到。它与 R16 的 bounded spanning / infinite inputs，以及 clopen nonattainment / Borel attainment 形成互补，不是仅凭 R31 未解否定价值，也不是仅凭证明完整自动批准发表。
- 实际生成独立 R40 TeX 与17页 PDF，重写摘要、引言、主定理安排和范围比较。R16 两项证明及 scale 附录保留，已知理论准确归属。未发现需要改变 R39 构造的错误；编辑明确了反证逻辑及输出词/原子名字记号。

完整构造、证明、反馈规则及未发表稿件不刊载于本公开页。

## 四件私有成果：实际保存后恢复身份

目录：/论文提升四大级别/。四件均 version 0。

| 文件 | library_file_id | file_id |
| --- | --- | --- |
| P3_R40_Research_Report.md | libfile_5039e9af0c2481918ee62bc3376eea2e | file_00000000ab4881f680c6b054c670ca31 |
| P3_R40_Proof_Records.zip | libfile_fb8d134784f08191ad181f43d9603380 | file_0000000006d881f997a547b519f36210 |
| P3_R40_Nonattainment.tex | libfile_b6132ad3d59881918293f51d23407704 | file_00000000370c81f993c9a0d83f9c86db |
| P3_R40_Nonattainment.pdf | libfile_2a90db5a1ea0819188f8dd93ebef7322 | file_000000008fc081f5b966f51130eaf3d3 |

| 文件 | version／实际保存字节／页数 | SHA-256 |
| --- | --- | --- |
| P3_R40_Research_Report.md | 0／21,596 | e3f9dec6564225b88f31e8390ac66824f3694c0181b78d3e1772543b73872148 |
| P3_R40_Proof_Records.zip | 0／19,228 | 1d3aebfcdc560073954c057e4d1aba1b6bdcb22fdce37d9a6ee998297fd73fe0 |
| P3_R40_Nonattainment.tex | 0／61,053 | e2f17b15a5b3747b001f5ddf3292c344f10c18b5d741a7d53e541e07c555c1a8 |
| P3_R40_Nonattainment.pdf | 0／373,031／17页 | bb653494ad96148b855550792121add3c55d121e14237ef2c9799fd54a2037e5 |


保存后按以上四个固定 file_id 重新恢复；version 和身份元数据核验。报告、ZIP、TeX 逐字节一致，ZIP CRC 与八项 payload manifest 通过；实际保存 PDF 的全文与全部17页渲染逐像素和编译版本一致。

PDF 上表哈希是实际保存后 pinned 恢复字节。编译 payload 为313,725字节，SHA-256 c523a70aa2c21fb97a8db795e896a213f22dc5de886b9a4c01b9d05df3936859，仅用于区分，不能作为实际保存版本恢复哈希。最终三次 pdflatex 后无缺失引用/标签、overfull/underfull 警告；全部页视觉检查通过。

## 直接依赖和原文限度

- [R39_STATUS](R39_STATUS.md) 两件固定 version 0 成果全文恢复；字节和 SHA-256 与该索引一致，ZIP manifest/CRC 核验，完整 core/audit/source mapping 已读。
- [R16_STATUS](R16_STATUS.md) 三件固定 version 0 成果全文恢复；报告36,053字节、TeX46,157字节和实际保存13页 PDF333,004字节均按原哈希核验。未用编译 payload，也未改原版本。
- 定向读取 Kawan、Huang–Zhong、Wang–Huang–Sun、Nie–Wang–Huang、Zhong–Huang–Zou、Tomar–Kawan–Zamani、Colonius、bounded complexity 两篇的完整相关定义/定理/证明。新增 Sibai–Mallada 2026 作者预印本 §9 与出版元数据；准确版本/DOI/APA 和假设对应在私有 SOURCE_MAPPING。
- 未取得的链末端或无关部分不称为通审；没有必须补找的原文，不重复通用 Frostman/gauge/提升或十篇四大学习。

## 就绪与结束边界

修订稿可接受外部专业审阅，本轮没有未闭合的主定理证明或必需原文阻塞。尚无独立专家审阅、普遍取到结构判据或自然控制模型类上的稳健性结果；这些是更高定位的数学缺口，不是自动新任务。不选刊、不准备投稿、不保证一区/Top/四大或录用。

GitHub 仅更新 CURRENT.md、research/R40_STATUS.md、NEXT_COMMAND.md。提交后实际回读 main、文件清单及三份全文核对。完整未发表数学非公开。

无 P4/P6、多代理、旧 A/B/depth/R09 重启、购买、登录、投稿或外部联系。本轮结束无自动重试、换题或返回暂停问题。
