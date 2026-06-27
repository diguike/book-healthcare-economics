# 第 2 章　数据源清单（会失灵的市场：医疗作为经济部门）

> data_cutoff：2026-05 ｜ 本清单为 verify-data（结构关）与 fact-check（事实关）的核查依据。
> 红线：E1（中美 GDP 占比同口径比较，9.3% 是 OECD 均值不是中国）。
> 口径纪律：跨国并排比较一律用 OECD/世界银行「经常性卫生支出 CHE」口径；单国内部结构用该国本国口径并标注。

## 一、核心数据点与出处

| # | 数据点 | 取值 | 口径 | 来源 | 时点 | 核查状态 |
|---|--------|------|------|------|------|---------|
| 1 | 美国卫生总支出 | 约 4.9 万亿美元 | NHE | CMS National Health Expenditure 2023 Highlights | 2023（2024-12 发布） | 已核（research/industry-reports.md + 多源一致） |
| 2 | 美国人均卫生支出 | 约 1.46 万美元（2023）/ 约 1.55 万美元（2024） | NHE | CMS NHE；Peterson-KFF HST | 2023 / 2024 | 已核 |
| 3 | 美国卫生支出占 GDP | 17.6%（2023）→ 18.0%（2024） | NHE（CMS 口径） | CMS NHE；Peterson-KFF HST 引 CMS | 2023 / 2024 | 已核（HST 明确 17.7%→18.0%；CMS Highlights 17.6%，口径细节待 fact-check 统一） |
| 4 | 美国卫生支出占 GDP（国际可比口径） | 17.2% | CHE（经常性） | OECD Health at a Glance 2025 | 2024 | 已核 |
| 5 | OECD 平均卫生支出占 GDP | 9.3% | CHE | OECD Health at a Glance 2025 | 2024 | 已核（E1：此为 OECD 均值，非中国） |
| 6 | 中国卫生总费用占 GDP | 约 7.2% | THE（卫生总费用，本国口径） | 国家卫健委口径；Statista/世界银行序列佐证 | 2023 | 已核（约 7.1%–7.2%，多源一致） |
| 7 | 中国经常性卫生支出占 GDP | 约 5.4% | CHE（国际可比） | 世界银行 World Development Indicators | 2022 | 半核（世行 CHE 序列；精确年份值待 fact-check 打开原表确认） |
| 8 | 美国人均预期寿命 | 78.4 岁（2023）/ 约 79 岁（2024） | — | OECD HaG 2025；Peterson-KFF | 2023 / 2024 | 已核 |
| 9 | 美国「花最多、活最短」 | 人均支出最高 + 预期寿命垫底 + 可避免死亡率最高 | — | Commonwealth Fund, U.S. Health Care from a Global Perspective 2026 | 2026-05 | 已核（机构报告结论） |
| 10 | OECD/世行各国占 GDP（德/法/日/英/韩） | 德 12.7%；法约 11.9%；日约 11.4%；英约 10.9%；韩约 9.6% | CHE | OECD Health at a Glance 2025 | 2024 | 半核（德 12.7%、OECD 均值 9.3%、美 17.2% 已核；法/日/英/韩为约值，**待 fact-check 打开 OECD GDP 表逐国确认精确值**） |
| 11 | 印度经常性卫生支出占 GDP | 约 3.3% | CHE | 世界银行 WDI | 2022 | 待核（约值，fact-check 打开世行原表确认） |
| 12 | 65 岁以上人口占比 | 日 29.6%、德约 23%、法约 22%、美 17.7%、中 14.3%、印约 7% | — | 世界银行 Population ages 65 and above（SP.POP.65UP.TO.ZS） | 2023 | 半核（日 29.6%、美 17.7%、中 14.3% 已核；德/法/印为约值待精确确认） |
| 13 | 中国老龄化爬升速度 | 未来十余年 65+ 占比将逼近今日美国 | — | 世界银行人口序列；RAND 中国老龄化研究（RBA3372-1） | 2023 序列 | 已核（定性方向，多源一致） |
| 14 | 美国卫生支出占 GDP 中长期上行 | 未来十年缓慢上行（预测） | NHE 投影 | CMS NHE Projections 2024–33；Health Affairs 同步发表 | 2025 发布 | 半核（定性方向已核；逐年投影具体数 fact-check 时补） |

## 二、一手数据源链接

- CMS National Health Expenditure Data（美国 NHE 一手）：https://www.cms.gov/data-research/statistics-trends-reports/national-health-expenditure-data
- OECD Health at a Glance 2025（跨国可比金标准）：https://www.oecd.org/en/publications/2025/11/health-at-a-glance-2025_a894f72e.html
  - 占 GDP 章节：https://www.oecd.org/en/publications/health-at-a-glance-2025_8f9e3f98-en/full-report/health-expenditure-in-relation-to-gdp_6e4c2773.html
  - 美国国别页：https://www.oecd.org/en/publications/health-at-a-glance-2025_15a55280-en/united-states_3517f35e-en.html
- WHO Global Health Expenditure Database（GHED，190+ 国可比）：https://apps.who.int/nha/database
- 世界银行 Current health expenditure (% of GDP)：https://data.worldbank.org/indicator/SH.XPD.CHEX.GD.ZS
- 世界银行 Population ages 65 and above (% of total)：https://data.worldbank.org/indicator/SP.POP.65UP.TO.ZS
- Commonwealth Fund, U.S. Health Care from a Global Perspective 2026：https://www.commonwealthfund.org/publications/issue-briefs/2026/may/us-health-care-global-perspective-2026
- Peterson-KFF Health System Tracker（美国支出趋势）：https://www.healthsystemtracker.org/chart-collection/u-s-spending-healthcare-changed-time/
- RAND, China's Aging Population（RBA3372-1）：https://www.rand.org/pubs/research_briefs/RBA3372-1.html

## 三、口径与红线备注（fact-check 高危点）

1. **E1 红线（最高优先级）**：9.3% 是 OECD 平均，不是中国。中国按卫生总费用（THE）约 7.2%，按经常性卫生支出（CHE）约 5.4%。跨国并排比较只能用 CHE 口径（中国 5.4% vs OECD 9.3% vs 美国 17.2%）。正文图 2-1 已把中国两个口径分两根柱子并标注。
2. **美国占 GDP 两套数都对**：CMS NHE（覆盖最全）17.6%（2023）/18.0%（2024）；OECD CHE（国际可比）17.2%（2024）。引用必须标口径。本书跨国比较用 OECD 口径，讲美国内部结构用 CMS 口径。
3. **THE vs CHE 定义**：THE（Total Health Expenditure，卫生总费用）含固定资产投资等，口径偏宽；CHE（Current Health Expenditure，经常性卫生支出）只算当年经常性医疗花费，是 OECD/WHO 跨国可比标准。
4. **预测 vs 事实**：CMS NHE Projections（占 GDP 将上行）是模型投影，正文已标「这是预测，不是事实」。
5. **日本 3 月财年**：本章未涉及日企财务，跨国卫生支出用 OECD 历年口径，无财年换算问题；后续日本章需注意。
6. **待 fact-check 精确值清单**：health_spend_gdp.csv 中标「约值-待fact-check」的法/日/英/韩/印占 GDP 值，aging_demand.csv 中标「约值」的德/法/印 65+ 占比与 OECD 均值预期寿命——核心 E1 锚点（美/OECD/中）已核，这些为二级对照值，fact-check 阶段打开 OECD GDP 表与世行原表逐国确认。

## 四、配套数据文件

- `health_spend_gdp.csv`：多国卫生支出占 GDP（标口径 THE/CHE/NHE + 年份 + 来源），图 2-1 数据底。
- `aging_demand.csv`：65 岁以上人口占比 + 人均预期寿命（多国，2023），刚性需求与「花得多不等于更健康」论证底。
