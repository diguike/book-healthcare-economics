# Sources — 第 27 章　给创新定价：rNPV、SOTP 与估值工具箱

> 采集时点：2026-06-27（write 阶段 WebSearch + WebFetch 核查）。data_cutoff 基准 2026-05；公司市值 / 并购溢价另标具体时点。
> 本章是方法论章，所有 rNPV / SOTP / reverse-DCF 算例均为「演示框架」，输入为显式假设；进入正文的「事实型」数字（成功率、IRR、并购价、分部收入）逐条登记于下，fact-check 阶段需逐条 WebFetch 一手复核标 ⚠️ 者。
> 核心口径纪律：
> - PoS / LOA 必须分层，正文严禁套全行业整体 7.9% 到具体管线；分阶段转化率为 BIO/Informa 历史统计「事实」，分层后取值（10%/20% 等）为「分析判断」，峰值销售为「预测」，三者在正文已区分。
> - 德勤 IRR（5.9% / 剔 GLP-1 3.8%）= 单一机构、特定 top-20 样本、预测值，正文已标口径 + 反方，不得当事实。
> - 并购价区分股权价值 vs 企业价值（EV）；溢价标明相对哪个「未受影响交易日」。
> - 销售额口径区分总收入 vs 净产品销售；强生分部为公司报告口径。

## 一手来源（财报 / 监管 / 公告 / 行业研究原文）

| 编号 | 来源 | URL / 文档 | 用于段落 | 口径要点 |
|------|------|-----------|---------|---------|
| S1 | BIO / Informa《Clinical Development Success Rates and Contributing Factors 2011–2020》 | https://www.bio.org/clinical-development-success-rates-and-contributing-factors-2011-2020 | rNPV 的 PoS 分层、分阶段转化率 | 12,728 次阶段转化；整体 Phase 1 LOA 7.9%；肿瘤 5.1%（最低）；生物药 9.1% vs 小分子 NME 5.7%；疫苗 9.7% |
| S2 | BIO 新闻稿《BIO Releases Largest Study Ever on Clinical Development Success Rates》 | https://www.bio.org/press-release/bio-releases-largest-study-ever-clinical-development-success-rates | 同上，研究规模与口径 | 史上最大样本；分阶段口径 |
| S3 | Deloitte《Measuring the return from pharmaceutical innovation 2024》（第 15 期） | https://www.deloitte.com/us/en/Industries/life-sciences-health-care/articles/measuring-return-from-pharmaceutical-innovation.html | ROI 压力测试段 | top-20 cohort；IRR 2019 谷底 1.5%→2024 5.9%；剔 GLP-1 降到 3.8%；峰值/资产 $510M→$370M；上市成本 $2.229B |
| S4 | 辉瑞 8-K / 收购 Seagen 公告（SEC EDGAR） | https://www.sec.gov/Archives/edgar/data/0000078003/000119312523068538/d408093dex991.htm | reverse-DCF + takeout 段 | 每股 $229；EV 约 $43B；溢价 33%（vs 2023-03-10）/ 42%（vs 未受影响 2023-02-24）；2023-12 交割 |
| S5 | Seagen 8-K / 收购公告（SEC EDGAR） | https://www.sec.gov/Archives/edgar/data/0001060736/000119312523068474/d467472dex991.htm | reverse-DCF 段 | Seagen 侧交易条款 |
| S6 | Seagen FY2022 业绩公告（BusinessWire） | https://www.businesswire.com/news/home/20230215005723/en/Seagen-Reports-Fourth-Quarter-and-Full-Year-2022-Financial-Results | reverse-DCF 段 Seagen 收入 | 2022 总收入约 $2.0B；净产品销售 $1.7B（Padcev $451M、Tukysa $353M、Adcetris、Tivdak） |
| S7 | 安进 8-K / 收购 Horizon 公告（SEC EDGAR） | https://www.sec.gov/Archives/edgar/data/0000318154/000119312522302256/d346985dex991.htm | takeout premium 段 | 每股 $116.50；股权价值约 $27.8B；EV 约 $28.3B；溢价 48%（vs 未受影响 2022-11-29 收盘 $78.76）；2023-10 交割 |
| S8 | Horizon 8-K / 收购公告（SEC EDGAR） | https://www.sec.gov/Archives/edgar/data/0001492426/000119312522302262/d362658dex991.htm | takeout premium 段 | Horizon 侧条款 |
| S9 | 强生 Q4 & 全年 2025 业绩公告（SEC 8-K / JNJ IR） | https://www.sec.gov/Archives/edgar/data/0000200406/000020040625000201/a2025q3exhibit991.htm | SOTP 算例 | FY2025 总收入 $94.19B；Innovative Medicine $60.40B；MedTech $33.79B；净利 $26.80B ⚠️ 核 Q4 全年终稿 8-K |
| S10 | Citeline / Norstella 成功率更新（2014–2023 口径） | https://www.norstella.com/insight/why-are-clinical-development-success-rates-falling/ | PoS 段「成功率仍在下行」 | 整体 Phase 1 LOA 降到约 6.7%；Ph1 47%/Ph2 28%/Ph3 55%/申报 92% |

## 二手来源（行业统计 / 媒体转述，做线索与交叉）

| 编号 | 来源 | URL | 用于段落 | 是否已回溯一手 |
|------|------|-----|---------|--------------|
| T1 | Kybora《Biotech Companies with Negative Enterprise Values》 | https://kybora.com/biotech-companies-with-negative-enterprise-values/ | 开篇跌破现金 | 否；⚠️ 232 家（2023H2）/139 家（2024-06）口径与样本待核一手 |
| T2 | Medicine to Market《Biotechs Trading Below Enterprise Value》 | https://medicinetomarket.com/biotechs-trading-below-enterprise-value-zombies-comebacks-and-caution-ahead/ | 开篇跌破现金 | 否；行业博客，量级佐证 |
| T3 | BioSpace《More Than One-Third of Biotechs Have Under a Year of Cash Left, EY Finds》 | https://www.biospace.com/business/more-than-one-third-of-biotechs-have-under-a-year-of-cash-left-ey-finds | 开篇现金跑道 | 部分；EY 口径 39%（2024），转述 |
| T4 | drugdiscoverytrends《From 1.5% to 5.9%: Deloitte digs into…R&D IRR climb》 | https://www.drugdiscoverytrends.com/from-1-5-to-5-9-deloitte-digs-into-whats-fueling-big-pharmas-rd-irr-climb/ | ROI 段 | 是，已与德勤报告交叉 |
| T5 | drugdiscoverytrends《Deloitte report showed pharma returns rising…GLP-1s did most of the work》 | https://www.drugdiscoverytrends.com/deloitte-report-showed-pharma-returns-rising-to-7-glp-1s-did-most-of-the-work/ | ROI 段剔 GLP-1 | 是 |
| T6 | FiercePharma《Done deal: Pfizer completes $43B acquisition of Seagen》 | https://www.fiercepharma.com/pharma/done-deal-pfizer-completes-43b-acquisition-seagen | reverse-DCF 段辉瑞 2030 指引 | 是；辉瑞指引 Seagen 2030 贡献 >$10B 风险调整后收入（$8B 已上市 + $2B+ 管线） |
| T7 | CPHI Online《Biologic products advance…higher success rate》 | https://www.cphi-online.com/news/clinical-development-success-rates-and-contributing-factors-2011-2020-new-report/ | PoS 段生物药 vs 小分子 | 是，BIO 报告转述 |
| T8 | Bullfincher — JNJ 分部收入 | https://bullfincher.io/companies/johnson-johnson/revenue-by-segment | SOTP 段分部收入交叉 | 部分；与 8-K 交叉，量级一致 |

## 关键数据点与口径（写入正文的「事实型」数字逐条登记）

| 正文数字 | 值 | 时点 | 口径 | 来源 | fact-check 状态 |
|---------|-----|------|------|------|----------------|
| 整体 Phase 1 LOA | 7.9% | 2011–2020 | 全行业全适应症混合，BIO/Informa | S1, S2 | 已核 |
| 分阶段转化率 | Ph1→2 52% / Ph2→3 28.9% / Ph3→申报 57.8% / 申报→获批 90.6% | 2011–2020 | 连乘≈7.9%（算术自洽已验） | S1 | 已核（连乘=7.87%） |
| 肿瘤 Phase 1 LOA | 5.1%（14 领域最低） | 2011–2020 | 疾病领域口径 | S1 | 已核 |
| 生物药 / 小分子 NME LOA | 9.1% / 5.7%；疫苗 9.7% | 2011–2020 | 模态口径 | S1, S7 | 已核 |
| 成功率更新（下行） | Phase 1 LOA 约 6.7% | 2014–2023 | Citeline 口径 | S10 | 已核 |
| 德勤 top-20 IRR | 2019 谷底 1.5% → 2024 5.9% | 2024 报告 | 预测 IRR，单一机构 | S3, T4 | 已核 |
| 剔 GLP-1 后 IRR | 3.8%；峰值/资产 $510M→$370M | 2024 | 同上，特定样本 + 反方已写 | S3, T5 | 已核 |
| 资产上市平均成本 | ≈$2.229B | 2024 | 德勤口径 | S3 | 已核 |
| 辉瑞收购 Seagen | $229/股；EV≈$43B；溢价 33%/42% | 2023-03 宣布，2023-12 交割 | 企业价值口径 | S4, S5 | 已核 |
| Seagen 2022 收入 | 总收入≈$2.0B；净产品销售≈$1.7B | FY2022 | 区分总收入 vs 净产品销售 | S6 | 已核 |
| 辉瑞对 Seagen 2030 指引 | >$10B 风险调整后收入（$8B 已上市 + $2B+ 管线） | 2023 交易材料 | 公司指引（预测） | T6 | 已核 |
| 安进收购 Horizon | $116.50/股；股权≈$27.8B；EV≈$28.3B；溢价 48%（vs $78.76, 2022-11-29） | 2022-12 宣布，2023-10 交割 | 区分股权价值 vs EV | S7, S8 | 已核 |
| 强生 FY2025 收入 | 总 $94.19B；创新药 $60.40B；器械 $33.79B；净利 $26.80B | FY2025 | 公司报告分部口径 | S9, T8 | 已核（⚠️ 复核全年终稿 8-K） |
| 负 EV 生命科学公司数 | ≈232 家（2023H2）→ ≈139 家（2024-06） | 2023–2024 | 行业统计，口径待核 | T1, T2 | ⚠️ unverifiable 倾向，正文已标「待核」 |
| 现金<12 月的 biotech 占比 | ≈39% | 2024 | EY 口径 | T3 | 已核（转述） |

## reverse-DCF 倒推算术备查

- 辉瑞 EV $43B ÷ 约 4.3× 峰值销售 ≈ 隐含峰值 $100 亿；与辉瑞自报 2030 贡献 >$100 亿交叉对齐（4–5× 峰值销售为成熟专科肿瘤经验区间，非精确取数）。

## 数据采集时点

- 最后一次更新：2026-06-27
- 财报数据截止：强生 FY2025（2026-01 公告）；Seagen FY2022；并购价为公告当时
- 行业报告截止：BIO/Informa 2011–2020；Citeline 2014–2023；德勤 2024（第 15 期）
</content>
