# 第 17 章　没有悬崖的护城河：器械的剃须刀与刀片 — 数据源清单

> 数据时点：除特别说明外，财报为最新可得财年（多数美股/A 股为日历年，Medtronic 为 4 月财年）。检索与核验时间 2026-06。
> 本清单对应 `razor_blade_economics.csv` 与 `device_valuation_multiples.csv` 中的每一条数据。

## 一、装机—耗材—服务（剃须刀-刀片）数据

### Intuitive Surgical（ISRG）FY2025（截至 2025-12-31）

| 数据点 | 值 | 口径 | 来源 | 时点 |
|--------|-----|------|------|------|
| 总收入 | 约 100.6 亿美元（+21%） | 全年 GAAP | Intuitive 2025 Q4 及全年初步业绩公告 | 2026-01 |
| I&A 收入 | 约 60.2 亿美元（+19%） | 器械与配套耗材 | 同上 | 2026-01 |
| I&A 占比 | 约 60% | 60.2/100.6 计算 | 计算 | 2026-01 |
| 达芬奇装机量 | 11,106 台（+12%，上年 9,902） | 全球累计装机 | 同上 | 2026-01 |
| Q4 I&A 收入 | 16.6 亿美元（+17%） | 单季 | 同上 | 2026-01 |
| 公司毛利率 | 约 67% | 公司整体（待核，research 口径） | research/devices-ivd.md | 2026-06 |
| 每台在装系统 I&A | 约 57 万美元/台/年 | **作者测算**（非公司口径） | 据公司披露自算 | 2026-01 |
| I&A 增速拆解 | +19% ≈ 装机存量 +12% × 单机手术强度 +6% | **作者测算**（非公司口径） | 据公司披露自算 | 2026-01 |

- 公司 IR 与 SEC 8-K：https://isrg.intuitive.com/news-releases/ ；SEC EDGAR ISRG 8-K（FY2025 Q4 earnings release）
- 核验：WebSearch（2026-06）确认 FY2025 总收入约 100.6 亿、I&A 约 60.2 亿（+19%）、装机 11,106（+12%）、Q4 I&A 16.6 亿（+17%）。
- **原创量化分析口径**：每台 I&A 与增速拆解为作者据公司一手披露（I&A、装机量、手术量增速）自行测算，非公司披露口径，正文已标「作者测算」。算术：均值装机 (9,902+11,106)/2=10,504；6.02e9÷10,504≈$573K/台；增速分解 (1.19/1.12-1)≈6.2%。

### Boston Scientific（BSX）电生理与 Farapulse PFA

| 数据点 | 值 | 口径 | 来源 | 时点 |
|--------|-----|------|------|------|
| EP 业务收入 FY2025 | 约 33 亿美元（有机 +73%） | 电生理板块全年有机增长 | BSX FY2025 业绩与财报电话会 | 2026-02-04 |
| EP Q4 2025 增长 | 约 +35%（有机） | 单季有机，增速逐季回落 | BSX 财报电话会 | 2026-02-04 |
| Farapulse FY2024 | 上市不到一年破 10 亿美元 | 单产品线 | MedTech Dive | 2025-01 |
| 美国房颤消融 PFA 占比 | 约 70% | 2025，公司管理层电话会口径 | BSX 财报电话会 | 2026-02-04 |
| 全球房颤消融 PFA 占比 | 约 50% | 2025，公司管理层电话会口径 | 同上 | 2026-02-04 |

- 来源链接（已从行业二手升级到公司一手财报电话会）：
  - 财报电话会转录（确认 EP 全年有机 +73%、Q4 +35%、美国约 70%/全球约 50% AF 消融用 PFA）：https://www.fool.com/earnings/call-transcripts/2026/02/04/boston-scientific-bsx-earnings-transcript/
  - Q4/FY2025 业绩报道：https://www.massdevice.com/boston-scientific-q4-2025-beats/ ；https://www.investing.com/news/transcripts/earnings-call-transcript-boston-scientific-beats-q4-2025-eps-stock-falls-93CH-4485070
  - Farapulse 2024 破 10 亿：https://www.medtechdive.com/news/boston-scientific-pfa-farapulse-2024/739262/
- **口径修正**：之前误用的「Q4 +172%」实为 FY2024 Q4 数据、「季度 143→96→64→37%」为早期检索聚合，均已弃用；正文与表格统一改为公司 2026-02-04 一手口径（全年有机 +73%、Q4 +35%）。EP 收入约 33 亿由 FY2024 的 1.9 亿×(1+73%)≈3.3 亿推得，与 +73% 有机一致。
- **E3 守口径**：PFA 替代严格限定在「房颤（AF）消融术式内部」，替代对象为房颤消融里的射频/冷冻；不写「取代射频」大类；图 17-2 节点 B 已改为「PFA 在房颤消融中替代射频/冷冻」。

### Medtronic（MDT）FY2025（4 月财年，截至 2025-04-25）

| 数据点 | 值 | 口径 | 来源 | 时点 |
|--------|-----|------|------|------|
| 全年营收 | 335.37 亿美元（+3.6%） | GAAP | Medtronic FY25 Q4 业绩公告 | 2025-05-21 |
| GAAP 营业利润率 | 17.8% | GAAP | 同上 | 2025-05-21 |
| 心脏消融业务 | 约 10 亿美元（Q4 同比近 +30%，PFA 拉动） | 板块 | 同上 | 2025-05-21 |

- 来源：https://news.medtronic.com/2025-05-21-Medtronic-reports-strong-finish-to-its-fiscal-year-with-its-fourth-quarter-financial-results-announces-dividend-increase
- **财年口径**：Medtronic 为 4 月财年，FY2025 截至 2025-04-25，与日历年错位，正文已标注。

### Stryker（SYK）FY2024（日历年）

| 数据点 | 值 | 口径 | 来源 | 时点 |
|--------|-----|------|------|------|
| 骨科业务收入 | 约 91 亿美元（+8.9%） | 板块 | Stryker 2024 全年业绩公告 | 2025-01-28 |
| MedSurg 与神经技术 | 约 135 亿美元（+11.1%） | 板块 | 同上 | 2025-01-28 |
| 公司整体毛利率 | 约 64% | 公司级 | Stryker 2024 业绩 / 第三方 | 2025-01 |

- 来源：https://www.globenewswire.com/news-release/2025/01/28/3016762/0/en/Stryker-reports-2024-operating-results-and-2025-outlook.html

### 迈瑞医疗（300760.SZ）/ 联影医疗（688271.SS）FY2024

| 公司 | 数据点 | 值 | 来源 | 时点 |
|------|--------|-----|------|------|
| 迈瑞 | 总营收 | 367.26 亿元（+5.14%） | 迈瑞 2024 年报 | 2025-04 |
| 迈瑞 | IVD 收入 | 137.65 亿元（+10.82%，第一大板块） | 同上 | 2025-04 |
| 迈瑞 | 归母净利 | 116.68 亿元（+0.74%） | 同上 | 2025-05 |
| 联影 | 总营收 | 约 103 亿元（-9.73%） | 联影 2024 年报 | 2025-03 |
| 联影 | 归母净利 | 约 12.62 亿元（-36.08%） | 同上 | 2025-03 |

- 来源：
  - 迈瑞：https://finance.sina.com.cn/tech/roll/2025-05-05/doc-inevpsmt1393950.shtml ；巨潮 cninfo 年报
  - 联影：https://www.yicai.com/news/102490137.html ；https://finance.sina.com.cn/stock/s/2025-03-03/doc-ineniqhu1044381.shtml

### 国产替代——具体环节 + 进口占比 + 国产市占（对应 domestic_share.csv，style-guide 要求）

**迈瑞 IVD / 化学发光（最大 IVD 细分）：**

| 数据点 | 值 | 时点 | 来源 |
|--------|-----|------|------|
| 化学发光国内市场规模 | 超 400 亿元 | 2023 | 弗若斯特沙利文 / 券商医疗器械研报 |
| 第一梯队 | 罗氏、雅培主导（"合计金额市占 >50%"为卖方研报付费数据，**待核**；正文已软化为"主导市场"，不写具体数字） | 2024 | 券商研报（付费） |
| 化学发光国产化率（金额） | 约 30% | 2023 前后 | 弗若斯特沙利文 / 券商研报 |
| 迈瑞化学发光金额份额 | 约 7.3%（起点） | 2021 | 券商研报 |
| 迈瑞化学发光国内市占排名 | **2023 超越西门子进入前四；2024 超越贝克曼库尔特升至第三**（fact-check 订正：原误作"2024 超越西门子"） | 2023–2024 | 迈瑞披露 + 第三方 IVD 统计 |

**联影影像（CT / MRI 大型设备）：**

| 数据点 | 值 | 时点 | 来源 |
|--------|-----|------|------|
| CT 外资整体份额 | 约 89% → 约 64% | 至 2024 | CT 市场洞察报告 / 券商研报 |
| 联影 CT 国内市占 | 约 29%（升至第一；GE 约 22%、西门子约 16%） | 2024 | 同上 |
| 64 排及以上高端 CT 外资合计份额 | "约 90%"为卖方研报付费数据，**待核**；正文已软化为"高端段国产渗透仍慢"，不写具体数字 | 2024 | CT 市场洞察报告（付费） |
| MRI 第一梯队份额 | 西门子约 30.4%、GE 约 25.1%、联影约 21.3%（联影落后西门子约 9pp，不写"相近"） | 2024 | 影像市场报告 / 券商研报 |
| MRI 外资整体份额 | 约 93% → 约 69% | 至 2024 | 影像市场报告 / 券商研报 |
| 医疗设备整体国产化率 | 19%（2019）→ 43%（2024） | 2019–2024 | 行业研报 |

- 来源链接：
  - 化学发光国产替代：https://bydrug.pharmcube.com/news/detail/5bbff8b9d39fff2601049380b81dd7b1 ；https://www.innomd.org/article/92a387ee0c23dfedb3878dc7342d9ee4.html ；动脉网 https://www.vbdata.cn/1518987520
  - CT/MRI 份额：腾讯新闻《2024 年度中国 CT 市场洞察》https://news.qq.com/rain/a/20241203A07BDW00 ；华创证券联影深度报告（2025-03-03）
- **口径说明**：化学发光市占为「金额口径」；CT/MRI 为「国内新增市场份额口径」；高端段（64 排及以上 CT）单列，避免把「中端替代」误读为「全段替代」。
- **fact-check 订正记录（本轮）**：①迈瑞化学发光超越对象更正——2023 超越西门子进前四、2024 超越贝克曼库尔特升第三（原误作"2024 超越西门子"）；②罗氏+雅培">50%"与高端 CT 外资"~90%"两处为卖方付费研报、无法在线核，正文已软化为定性表述、不写具体数字，本表保留并标「待核」；③联影 MRI 不写"份额相近"，改列具体份额（西门子 30.4 / GE 25.1 / 联影 21.3，落后约 9pp）。

## 二、Dexcom vs Abbott CGM 专利诉讼战（护城河-诉讼案例）

| 事件 | 时点 | 内容 | 来源 |
|------|------|------|------|
| 互诉开始 | 2021-06 起 | 两家在多法域就 CGM 产品互提专利侵权诉讼（传感器插入机构、可穿戴密封/贴片等） | Dexcom SEC 10-Q 诉讼披露 |
| 特拉华开庭 | 2024-03 | Abbott 对 Dexcom 的 "D1" 案在特拉华地院开庭；庭前一项工厂校准专利被判无效，Abbott 撤回另四项专利 | Dexcom 10-Q（dxcm-20240630） |
| 全面和解 | 2024-12-20 | 双方约定 10 年互不就**专利、商品外观（trade dress）及设计权**起诉，互授部分分析物传感专利全球非排他许可，不含特许权使用费或付款（按 Abbott 官方公告补全和解范围） | Abbott 官方公告 / MedTech Dive / FierceBiotech / Dexcom 证券披露 |
| 上诉撤销 | 2025-07-18 | 联邦巡回上诉法院相关上诉（No. 24-1326）经双方同意撤销，各自承担费用 | PatSnap / 法院文书 |

- 来源链接：
  - https://www.medtechdive.com/news/abbott-dexcom-settle-cgm-patent-lawsuits/736300/
  - https://www.fiercebiotech.com/medtech/abbott-dexcom-agree-10-year-truce-over-diabetes-sensor-patent-litigation
  - Dexcom 10-Q：https://www.sec.gov/Archives/edgar/data/0001093557/000109355724000144/dxcm-20240630.htm
  - https://www.patsnap.com/resources/blog/litigation/dexcom-v-abbott-laboratories-continuous-glucose-monitoring-patent-appeal-patsnap/

## 三、估值倍数（device_valuation_multiples.csv）

| 公司 | 类型 | EV/EBITDA | EV/Sales | 远期 P/E | 时点 | 来源 |
|------|------|-----------|----------|----------|------|------|
| Medtronic（MDT） | 成熟龙头 | 12.21 | 3.39 | 13.54 | 2026-06-26 | stockanalysis.com |
| Stryker（SYK） | 成熟+Mako | 约 22.6（10 年中位 25.8；trailing 约 20.25） | — | 22.42 | 2026-03 | GuruFocus / stockanalysis.com |
| Intuitive（ISRG） | 高成长 medtech | 44.29（2026-03-26） | 15.72（2026-04-26） | 约 40 | 2026-03~04 | ValueInvesting.io / GuruFocus / Yahoo |

- 来源链接：
  - https://valueinvesting.io/ISRG/valuation/ev_ebitda-multiples
  - https://www.gurufocus.com/term/enterprise-value-to-revenue/ISRG
  - https://stockanalysis.com/stocks/mdt/statistics/
  - https://stockanalysis.com/stocks/syk/statistics/
- **F7 守口径**：估值不过度二分。成熟龙头看 EV/EBITDA（现金流），高成长 medtech 看 EV/Sales + 管线兑现；rNPV 不适用器械，但 EV/EBITDA 也非器械万能尺。倍数随市价每日变动，正文与表格均标注「仅作框架示意」。

## 四、监管路径与商业模式（定性，来源于综合行业知识 + research）

- FDA 510(k) / PMA 两条路径、NMPA 一/二/三类、欧盟 CE/MDR：FDA、NMPA 官网制度说明；research/devices-ivd.md 第 5 点。
- 剃须刀-刀片模型、术者黏性、毛利结构差异：research/devices-ivd.md「器械/IVD 商业模式与药的核心差异」。
- 中国集采对耗材/IVD 的「集采悬崖」（高值耗材 -80~95%、化学发光试剂联盟集采平均 -53.9%）：见第 18 章 data/18-ivd/ 详表；本章只点破其对 razor-blade 模型的反噬（F7）。

## 待核 / 局限说明

- Intuitive 公司整体毛利率「约 67%」为 research 口径，未在本轮逐条 WebFetch 一手财报确认，正文以「约」标注。
- Stryker 公司毛利率「约 64%」为公司级口径，非单一板块；EV/EBITDA 区间取第三方不同时点数据。
- Medtronic 公司毛利率「约 65%」（research 口径）正文未直接引用，改用已确认的营收 335.37 亿与 GAAP 营业利润率 17.8%。
- 估值倍数为第三方数据平台口径，随市价每日变动，仅作框架示意，不作为估值结论。
