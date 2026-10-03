# P3 R05：原文依赖补核与候选 B 再裁决

日期：2026-10-03（Asia/Shanghai）。仅公开状态和恢复索引；完整未发表研究非公开保存。

## 恢复与实际新增

恢复点及启动 main：999d546d22eb4cdb6b244725b809b88c3c801913，无需接续的后续实质成果。全文读取 CURRENT、R01–R04_STATUS、NEXT_COMMAND；实际恢复并读完 R01–R04 报告、R01 TeX 和四页证明 PDF，SHA-256 均匹配。原稿和旧成果保留原样，未重新宣称全稿所有定理无误。

新增 Huang–Zhong18 附件此前只有身份/首页核对。本轮才真正读完六页正文、全部证明和参考文献，逐页图像对照；重点逐行审查 Theorems 3.1、4.1、5.1 的定义、条件、量词、证明及实际依赖。不再记为全文不可得。

## 新原文身份

- 文件：1-s2.0-S0167691117302281-main.pdf
- 页数：6（printed pp. 36–41）；字节数：398,097。
- SHA-256：f89791e5e96b00c5ff3fbeb521a304a45856ac3b030cf0225bca913d631e8fe8。
- 版本：期刊最终排版 PDF；收稿 2017-07-28，修订/接受 2017-12-22，在线 2018-01-12。PDF 创建日不替代发表日。
- 准确 APA：Huang, Y., & Zhong, X. (2018). Carathéodory–Pesin structures associated with control systems. Systems & Control Letters, 112, 36–41. https://doi.org/10.1016/j.sysconle.2017.12.009

文件匹配、全文读取、三个指定定理核验均已完成；“核验”包含定位证明问题，不等于全部印刷式子通过，也不等于认证全篇其他定理。

## 核验及旧判断调整

- Theorem 3.1 比较控制/给定 cover 结构的容量与相应 entropy，没有 generator 的存在量词。分割的 block 长度和实际时间必须明确；2018 印刷成本与按 period 归一化的 entropy 不能未经修正直接对齐，WHS19 使用了显式实际时间成本。
- Theorem 4.1 要 K=Q，strict/fixed-cover 项采用 finite collections；inner 项另要 strong invariance，不能替换 strict。完整报告核对了 finite-cover 拼接计数，并修正印刷中的中间式问题。有限覆盖等式不保证某个固定零熵分割存在。
- Theorem 5.1 的 2018 定义与 WHS19 Definition 4.9 并不相同，2019 明写了 assigned-word 单射性。完整报告给出遗漏条件的检验、指出证明失败位置，并区分控制词定义域与状态安全端点。没有将修正写成已发表勘误。
- R04 独立推导实际使用 WHS19 的强条件及正确时间成本。经复核，其原来明确限定的 compact/clopen identity 与 conditional generator 推导保留；不能把它记成 2018 印刷证明无条件通过，也不能从 B 的假设推断存在这种强分割。
- 定向回查 WHS19 Corollary 3.2、Theorem 4.13、Corollary 6.5(ii)/(iii) 的完整引用链，以及所需 Kawan13 Propositions 2.3、2.22。R04 已读原文只在相关完整部分回查，不重复算新增。
- Theorem 6.4 的 fixed clopen/compact 范围、CHZ26 3.3 的 fixed-scale 范围及 R04 时间成本修正继续保留，不作无条件 sup/inf 交换或任意 Borel 的扩张。
- HZ18 的已读全文不再缺失；其他版本、所有勘误及未用于本轮的其他定理未穷尽认证。定向公开检索没有取得相应勘误原文，不宣称不存在；出版社页面 403 仅影响在线版本检查，不影响附件全文已读。

诊断及完整数学推导留在非公开报告，本公开文件不发布完整研究或证明。

## B 的再裁决

原目标不变：紧光滑 M、有限 U、C∞ 转移、非空紧 controlled invariant Q=closure(int_M Q)、全部序列 admissible；bounded strict spanning complexity 是否蕴含某个固定有限 period 的 finite Borel invariant partition，其指数 itinerary entropy 为零。不增加 control-set、inner/outer、有界 itinerary 或全尺度零要求。

覆盖：已逐项组合新旧结论，缺口仍是固定零熵分割的存在量词。ZC23/CZ24 给有限永久程序、finite EI/dense EI；WHS19/Kawan 给 inf identity；HZ18 的结构比较和修正后的条件 generator 都没有从 B 导出所需存在性。不能宣布 B 已覆盖，也不能宣布全部前人未覆盖或原创。

重要性：B 若成立会得到这一个限定零熵类的 fixed generator attainment；新原文没有补上通向独立重大数学命题的完整链。已有零 entropy、不同分割率趋零、有限初始索引后永久严格安全以及完整历史/共享时钟零率不作为新增重大后果。有限记忆、有限状态、强内点任务未被严格推出。

当前分量：完成了新增原文的实质证明审查、依赖归属修正和数学诊断；B 的新定理、B 反例、新决定性步骤仍为零。不能把文献补核当成四大突破。

可行性：永久程序尾部与当前状态重新选择未自动形成同一可重复规则；全部 itinerary 次指数增长尚未解决。真伪及证明可行性未知，不由困难推断重大意义。

裁决：R05_COMPLETE / NO_UPGRADE_ROUTE_APPROVED / B_PAUSED。证据门槛未通过，未启动新的 B 核心攻击，也未伪造失败构造。A 的无条件目标继续停止，不改名、不增加第三候选。

## 完整成果恢复身份

| 文件 | 字节数 | SHA-256 |
| --- | --- | --- |
| P3_R05_Research_Report.md | 33,055 | c01adea2d0d01caa8999e071c982760978047ec7887db40f1a292d2f11b6639b |
| P3_R04_Research_Report.md | 46,438 | 4f887e415f5f088517d8f31eb1a5e41c94380f8d38bec218fbfb8904ff439490 |
| P3_R03_Research_Report.md | 22,852 | cc1dbc2d322de844a487c94c449b9bc4ce65c07119b63d2ba7c43e85c9d020e6 |
| P3_R02_Research_Report.md | 32,240 | b0efa60cb65f80c2642045d1a51389cd71efc71a03c4bedf17cadacb9393bd83 |
| P3_R01_Research_Report.md | 24,182 | 585516b2321ee13d53587c3b20bc05ed36ac213c447ebfeeb79d2b4f02bbb759 |
| P3_R01_Minimax_Gap.pdf | 284,603 | 03d94cece1eeef28182f854200f2f9ef0b2c94e436d5ace1ab5622898d1d015d |
| P3_R01_Minimax_Gap.tex | 12,893 | 2e4b6a98ade558f35fb7b0a7000d355f565bdfd059a7b65ba26884aab8cf4cea |
| P3_JDE_FINAL_STYLE.tex | 143,115 | 79842eba9bdf4280b361eea04b6d3191b9429c61c4467019eb6245801464b7ee |
| P3_JDE_FINAL_STYLE.pdf | 553,697 | 568abbeb4268cb8676f66dcd3b0d1dfff149e91f7c5e3b54d7c80dbae0ef196e |

R05 完整报告已非公开保存，含全部恢复、三个指定 theorem 的完整核对、诊断与修正、真实引用链、覆盖组合断点、重大意义检查、未核验与失败记录、APA/DOI 和下一入口。公开 GitHub 只存必要状态及恢复索引；历史 R01–R04 保留原样。

下一入口见 NEXT_COMMAND。只在改变覆盖或重大后果门槛的新证据出现时继续核心 B；不再让用户重复找已补齐 HZ18。本轮没有新的必要补找文献。以后确需补找，最终回复必须单独列准确题名、作者、DOI 和版本。

目标保持 Annals / Inventiones / JAMS / Acta，不承诺成功、不降低目标。只研究 P3，不读改 P4/P6，不安排多代理，不购买、登录、投稿或联系作者。提交后实际回读 main、写入文件、历史 blob 及公开范围。
