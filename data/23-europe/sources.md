# Sources — 第 23 章　欧洲：为一年健康生命标价

本章为制度章（disclaimer: false）。数据采集时点 2026-05，data_cutoff 2026-05。
快速变化项（NICE 阈值上调、EU JCA 扩围、各国控费改革）每个数据点单独标时点，发布后需定期复核。

## 一手 / 权威机构来源

| 编号 | 来源 | URL / 文档 | 用于章节段落 |
|------|------|-----------|------------|
| S1 | NICE 最终草案指南：donanemab 与 lecanemab 不推荐纳入 NHS（第三次） | https://www.nice.org.uk/news/articles/the-benefits-of-alzheimers-treatments-donanemab-and-lecanemab-remain-too-small-to-justify-the-additional-costs-says-nice-in-final-draft-guidance | 钩子；投资视角（事件风险）。日期 2025-06-19，延缓进展 4-6 个月 |
| S2 | NICE 健康技术评估方法学手册 / 严重程度修正（severity modifier） | https://www.nice.org.uk/process/pmg36 | QALY/NICE 段：阈值 £20k-30k、严重程度修正 x1.2/x1.7（2022/2023） |
| S3 | 欧盟委员会：Joint Clinical Assessments（HTA 实施页 + JCA factsheet） | https://health.ec.europa.eu/health-technology-assessment/implementation-regulation-health-technology-assessment/joint-clinical-assessments_en | EU JCA 段、图23-1：Regulation 2021/2282、2025-01-12 生效、肿瘤药+ATMP、与 EMA 并行 |
| S4 | G-BA / AMNOG 官方框架（早期获益评估 §35a SGB V，报销价谈判 §130b） | https://www.g-ba.de/english/ | 德国 AMNOG 段：IQWiG 评估、G-BA 决定、GKV-SV 谈判、六档评级、Erstattungsbetrag |
| S5 | HAS：Commission de la Transparence（SMR/ASMR 评估） | https://www.has-sante.fr/ | 法国 HAS 段：SMR 定报销比例、ASMR I-V 定价筹码、CEPS |
| S6 | MHRA：lecanemab（Leqembi）英国上市许可（2024-08-22 公告） | https://www.gov.uk/government/news | 钩子：英国监管批准但 NHS 不报 |

## 二手 / 研究文献来源

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| T1 | OHE《NICE's new cost-effectiveness threshold》/ pharmaphorum：2025-12 政府宣布 2026-04 起阈值升至 £25k-35k | QALY/NICE 段 | 阈值历史值（£20k-30k）已与 NICE 方法学一手交叉；上调为政府公告，待官方文件二次确认 |
| T2 | HIQA / 欧洲支付方视角成本效果分析：lecanemab 约 €296,506/QALY、donanemab 约 €371,299/QALY，vs €45,000 阈值 | 钩子（ICER 量级） | 标为「分析」，归属已发表的欧洲卫生经济学测算，非 NICE 官方单一 ICER。fact-check 时核 HIQA/同行评审原文 |
| T3 | Cambridge Core《Ten years of German benefit assessment》/ Cencora：约 53% 评估为未证明附加获益、约 41% 有附加获益；谈判价较上市价低约 24.5% | 德国 AMNOG 段 | 二手统计，口径为非罕见病药；fact-check 核原始统计区间与年份 |
| T4 | Simon-Kucher / GKV-FinStG：自由定价窗口由 12 月压到 6 月（2022 改革） | 德国 AMNOG 段 | 法条 GKV-FinStG 为一手，待补法条编号 |
| T5 | 《Overview of external reference pricing systems in Europe》(J Mark Access Health Policy, 2015) | ERP 段、图23-3、erp_basket.csv | 学术综述；约 23 国用 ERP、英瑞除外、篮子 1-31 国、希腊等取最低几价平均 |
| T6 | Global Legal Insights《Pricing & Reimbursement Laws 2025 — France》 | 法国 HAS 段 | SMR 报销比例档位、ASMR 与 CEPS 关系 |
| T7 | Inside EU Life Sciences（2024）：德国 2024 改革引入保密报销价以阻断 ERP 引用 | ERP 段 | 二手法律评论；fact-check 核改革法案 |
| T8 | cepInput（2021）/ Pharmafootpath：平行贸易货源（希腊/西班牙）与目的国（德/瑞/丹） | 平行进口段、图23-3 | 二手 |
| T9 | Bart et al.《Parallel Trade of Pharmaceuticals》Value in Health (2008)：德国约 8.5% 药品销售为平行进口 | 平行进口段、erp_basket.csv | 该比例为 2008 数据，年份偏旧，已标注时点；如需更新值，复核近年 affordablemedicines.eu 贸易流报告 |
| T10 | Eisai 美国定价公告（2023）：Leqembi 美国列表价约每年 USD 26,500 | 钩子（美国对照价） | 二手转述，fact-check 核 Eisai 原始公告 |

## 待 fact-check 重点（事实关）

- lecanemab MHRA 批准具体日期（2024-08-22）需 WebFetch MHRA 原始公告确认
- T2 的 €296,506 / €371,299 每 QALY 数字：确认归属（HIQA 爱尔兰支付方视角 vs 其他欧洲分析），区分「NICE 官方未公布单一 ICER」与「第三方测算」
- T1 阈值上调 £25k-35k：核英国政府/NICE 官方文件原文与生效日（2026-04）
- T3 的 53% / 41% / 24.5%：核原始统计的口径（年份、样本、是否含罕见病）
- T9 德国 8.5% 平行进口为 2008 旧数据，正文已标时点；若有近年更新值优先替换

## 数据采集时点

- 最后一次更新：2026-05
- 监管/政策数据截止：2026-05（NICE 阈值上调公告 2025-12、EU JCA 2025-01 生效、德国 GKV-FinStG 2022/2024 改革）
- 行业研究文献截止：以各文献发表年为准（ERP 综述 2015、平行进口 2008，已在表中标注年份）
