# Sources — 第 3 章　十年、十亿、九死一生：一款新药是怎么造出来的

> data_cutoff：2026-05　｜　最后核对：2026-06-27（WebFetch / WebSearch 逐条核）
> 口径红线：E4（Eroom 定义=每10亿美元 R&D 产出新药数约每9年减半，非"成本每9年翻倍"）；F5（ROI 标 Deloitte 单一机构 + 特定样本 + 预测值 + 反方）；F8（临床成功率按适应症/模态分层，不用单一整体值套 rNPV）。

## 一手 / 权威机构来源

| 编号 | 来源 | URL / 文档 | 用于段落 | 口径要点 |
|------|------|-----------|---------|---------|
| S1 | Scannell, Blanckley, Boldon, Warrington, "Diagnosing the decline in pharmaceutical R&D efficiency", Nature Reviews Drug Discovery 11, 191–200 (2012) | doi:10.1038/nrd3681 | Eroom 定律定义与曲线（图3-2） | **E4**：每10亿美元 R&D（通胀调整）产出新药数约每9年减半；1950→2010 约下降80倍（部分表述约百倍）。**是"产出效率减半"，不是"成本翻倍"** |
| S2 | BIO / Informa Pharma Intelligence (Biomedtracker) / QLS Advisors, "Clinical Development Success Rates and Contributing Factors 2011–2020"（2021-02-17 发布） | https://go.bio.org/rs/490-EHZ-999/images/ClinicalDevelopmentSuccessRates2011_2020.pdf ；概览 https://www.bio.org/clinical-development-success-rates-and-contributing-factors-2011-2020 | 漏斗各期成功率（图3-1）、PoS 分层 | Phase I→II 52%；II→III 28.9%；III→申报 57.8%；申报→获批 90.6%；自一期总 LOA 7.9%。分层：肿瘤 5.3%、小分子NME 5.7%、生物药 9.1%、疫苗 9.7%。样本：9,704 个项目、12,728 次相位转换 |
| S3 | PhRMA / IFPMA "the pharmaceutical innovation journey" | https://www.ifpma.org/initiatives/alwaysinnovating-the-pharmaceutical-innovation-journey/ ；https://phrma.org/policy-issues/research-development/clinical-trials | 漏斗发现端（5000→250→5→1）、10–15年、<12%获批 | 每 5,000–10,000 个被筛化合物约 1 个上市；全程 10–15 年；进入一期者最终<12%获批 |
| S4 | DiMasi, Grabowski, Hansen, "Innovation in the pharmaceutical industry: new estimates of R&D costs", Journal of Health Economics 47:20-33 (2016)（Tufts CSDD） | https://pubmed.ncbi.nlm.nih.gov/26928437/ ；https://www.globenewswire.com/news-release/2016/03/10/1187518 | 单药研发成本锚点 | 资本化后 $2,558M（2013 美元，资本化率10.5%）；自付成本 $1,395M；常被引为"约26亿美元"。样本：10家药企106个药、1995–2007 首次人体试验 |
| S5 | Deloitte, "Measuring the return from pharmaceutical innovation 2024"（第15版年度报告，2025-04 前后发布） | https://www.deloitte.com/uk/en/about/press-room/global-pharma-rd-returns-rise-as-one-glp-drugs-help-drive-forecast-growth.html ；https://www.prnewswire.com/news-releases/deloittes-15th-annual-pharmaceutical-innovation-report-pharma-rd-returns-continue-upward-for-second-consecutive-year-302410138.html | 反共识洞察（剔除GLP-1后ROI） | Top20 IRR 2024=5.9%（2023≈4.x%、2019谷底1.5%、2010首期约10%）；**剔除 GLP-1 后 IRR 降至3.8%**；预测单药峰值销售 $510M→剔除GLP-1 $370M（2023为$353M）；单药平均研发成本 $2.23B；2024 新增29个"重磅资产"入管线 |
| S6 | Deloitte, "Measuring the return from pharmaceutical innovation 2025"（第16版，2026-05 前后发布） | https://www.drugdiscoverytrends.com/deloitte-report-showed-pharma-returns-rising-to-7-glp-1s-did-most-of-the-work/ ；https://www.deloitte.com/us/en/industries/life-sciences-health-care/research/measuring-the-return-from-pharmaceutical-innovation.html | 最新一期 ROI（data_cutoff 内） | IRR 2025=7.0%（连续第二年回升）；**剔除 GLP-1/GIP 后降至2.9%**（16年报告史上单一药类影响最大）；单药平均研发成本 $2.67B |
| S7 | fiercebiotech，"Drug development cost pharma $2.2B per asset in 2024…: Deloitte" | https://www.fiercebiotech.com/biotech/drug-development-cost-pharma-22b-asset-2024-plus-how-glp-1s-impact-roi-deloitte | 交叉核 S5 | $2.2B/资产、5.9%、剔除GLP-1后3.8%（二手转引 Deloitte，已交叉一手新闻稿） |
| S8 | drugdiscoverytrends，"From 1.5% to 5.9%: …IRR climb" | https://www.drugdiscoverytrends.com/from-1-5-to-5-9-deloitte-digs-into-whats-fueling-big-pharmas-rd-irr-climb/ | 谷底/回升口径交叉 | 2019谷底1.5%；逐年回升路径 |

## AI 制药案例来源（议题6，承接 research/disputes-frontier.md）

| 编号 | 来源 | 用于段落 | 口径要点 |
|------|------|---------|---------|
| S9 | Insilico Medicine IR / NEJM·相关报道（见 research/disputes-frontier.md 议题6） | AI 压缩发现端 | rentosertib（ISM001-055，TNIK 抑制剂，靶点+化合物全 AI 设计）：立项到临床候选约2.5年；特发性肺纤维化2期a，60mg组 FVC +98.4mL vs 安慰剂 −20.3mL，**n=71、12周、全中国、2期a、非注册性3期** |
| S10 | Exscientia / Recursion 公开披露（见 disputes-frontier.md 议题6） | AI 压缩发现端 | 某资产约12个月进入1期（常规4–5年）；所有里程碑集中在临床前到1/2期，**无 AI 药物已通过3期** |

## 二手 / 背景

| 编号 | 来源 | 用于段落 | 是否已回溯一手 |
|------|------|---------|--------------|
| S11 | OECD, "Eroom's Law and the decline in the productivity of biopharmaceutical R&D"（AI in Science 章节） | Eroom 背景 | 是（回溯 Scannell 2012 = S1） |
| S12 | Ringel et al., "Breaking Eroom's Law", Nature Reviews Drug Discovery 19, 833-834 (2020) | eroom_curve.csv 后续更新点 | 是（原文，提出生产率改善迹象，未成共识） |

## 数据采集时点

- 最后一次更新：2026-06-27
- 财报 / 报告数据截止：Deloitte 2025 报告（2026-05 前后）为最新一期；BIO 数据窗口 2011–2020；Scannell 1950–2010；Tufts 1995–2007 入组
- 待 fact-check 复核项：BIO 申报→获批率 90.6% 当前由总 LOA 与三段推进率算术反推一致（0.52×0.289×0.578×0.906≈0.0786≈7.9%），原文表格未直接 WebFetch 到（PDF 二进制未解析），fact-check 阶段需取 PDF 原表确认；Deloitte 2023 IRR 同时见 4.1%/4.3% 两个口径（年度修订），正文用"约4%"
