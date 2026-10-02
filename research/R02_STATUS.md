# P3 首轮复核与候选 B 继续裁决状态

日期：2026-10-03（Asia/Shanghai）。本文件为公开状态摘要，不含完整未发表证明。

## 实际完成

本轮从 e03a3f5fbeeb912a1f4d006a5a9c517412c68ca7 恢复，启动与写入前 main 均未发生后续变化。实际读取 CURRENT、R01_STATUS、NEXT_COMMAND，以及 R01 报告、四页证明 PDF 和 TeX。三份 SHA-256 与 [R01_STATUS](R01_STATUS.md) 完全一致。

逐项推演首轮反例，没有发现推翻两个量词值的错误。核对包含：任意有限 period 下每条共同 itinerary 强迫的比特数与柱集质量界；任意 Borel 概率测度的尾质量极限；局部临界值的 Borel 可测性、零质量柱集和积分；原稿联合 Lipschitz 估计及锥上任意测度的对应，特别是固定线段上的非原子测度。原稿及 R01 文件未修改。

反例确认的范围在完整报告中逐项区分：紧联合连续、欧氏联合 Lipschitz、无限输入、C¹ 限制，以及不同环境拓扑的内点条件。没有把它推广到所有 Helfter scaling，没有据此裁决 B 的有限输入、光滑流形与正则闭约束设置。

## 文献实际范围

| 原文入口 | 本轮结果 |
| --- | --- |
| Wang–Huang–Sun19 Theorem 6.4 / Corollary 6.5(iii) / Eq. (2.1) | 出版社书目、历史及第一页预览可得；完整指定结论仍未读到 |
| Chen–Huang–Zhong26 Theorem 3.3 | 官方索引可得，全文页面访问失败；指定结论仍未读到 |
| Zhong–Chen23 bounded strict complexity 附近的结论 | Springer 书目、版本与期刊目录已核实；相关定理全文仍未读到 |
| Zhong–Chen–Huang21 的公开预印本 | 实际读取 arXiv:2005.10457v1 的相关定义、Theorem 2.5 完整证明、Definition 3.1 及 Corollary 3.2 条件。邻域型 complexity 与 technical control-set 条件不能直接当作 B 的 strict 目标 |
| Chen–Zhong24 | 新增识别与 B 密切相关的近邻论文，官方预览可得，完整定理与证明仍未读到 |

书目核对与定理核验分别记录。没有以摘要或二次引述替代上述未得原文；没有购买、登录或联系作者。未取得相关勘误原文，不宣称已证明没有勘误。

近邻原文身份：

- Zhong, X.-F., Chen, Z.-J., & Huang, Y. (2021). Equi-invariability, bounded invariance complexity and L-stability for control systems. Science China Mathematics, 64(10), 2275–2294. https://doi.org/10.1007/s11425-020-1693-7 。实际读的是 2020-05-21 的 arXiv v1，未与期刊版逐项对照。
- Chen, Z., & Zhong, X. (2024). Invariance complexity and equi-invariability for control systems. Journal of Mathematical Analysis and Applications, 539(2), Article 128533. https://doi.org/10.1016/j.jmaa.2024.128533 。仅识别为 B 的近邻待查项。

三篇指定文献的准确 APA 书目、DOI、实际阅读范围与获取失败点均写入完整报告。

## 裁决

A 的一般目标继续停止，本轮未发现需撤销首轮反例的错误。

只对 R01 已记录 B 继续裁决。B 要求在紧光滑流形、有限输入、C∞ 转移和 Q 为其内点闭包的设置下，把有界 strict spanning complexity 实现为某个固定有限 period 的 Borel invariant partition 的零指数 itinerary entropy。它增加的是固定分割的零值取到，不能以已有零熵或越来越低率的一列不同分割代替。

重要性：尚未建立可严格导出的重大结构后果或公开问题联系。当前成果：反例得到复核，但没有 B 的新证明或反例。可行性：尚无把长时段 spanning 家族转为一个固定零率分割的桥梁。完整覆盖比较未完成，不能宣布 B 已被覆盖或具有新颖性。

裁决为 B_PAUSED，批准继续的四大路线仍为零。依照用户条件，没有越过证据门槛启动 B 的新长证明；不将这一步伪造为一个失败的证明尝试。目标不变，未新增第三候选、未把 A 改名重启、未以改写或外围引理充当升级。

## 完整本轮报告恢复身份

| 文件 | SHA-256 |
| --- | --- |
| P3_R02_Research_Report.md | b0efa60cb65f80c2642045d1a51389cd71efc71a03c4bedf17cadacb9393bd83 |

完整报告已非公开保存并向用户提供，含本轮完整证明复核、范围界定、实际原文阅读、失败记录、B 的三个维度裁决及下一入口。公开仓库没有上传报告全文。R01 三份完整文件的恢复身份沿用 R01_STATUS，原稿身份见 [CURRENT](../CURRENT.md)。

下一入口见 [NEXT_COMMAND](../NEXT_COMMAND.md)。提交后须回读最新 main 与所写文件，核对裁决、哈希、原稿范围及公开范围。只研究 P3，P4/P6 不动，不安排多代理，不投稿或对外联系。
