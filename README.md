# Spinal Cord / CPG Literature-Data Database (Chordata)

A curated literature & open-data catalog for spinal cord / motor neuron / CPG research across **11 chordate species + 1 outgroup**, built for tracing the evolution of locomotor circuit architecture.

> **📊 数据库总量：相关文章 / 数据资源 / 网站共 178 条；其中 63 条带公开数据（每条一本预填 notebook，占 35%）。**

**Two entry points / 两个入口：**

1. **[Interactive database (main page)](https://3417534739.github.io/spinal-cpg-db/)** — `index.html`：网络图 + 全部条目 + 自动评分 + DOI/PMC/数据链接
2. **[Notebooks index](notebooks/README.md)** — 每条带公开数据的条目一本预填 notebook（内含 EN 标题 / 中文摘要 / Highlights / 数据页原文）

**English / 中文双语说明见下。**

## Species covered

Outgroup: *Crayfish (Procambarus)*
Chordata (11 species):
- Cephalochordata — *Branchiostoma* (Amphioxus)
- Tunicata — *Ciona*
- Cyclostomata — *Petromyzon* (Sea lamprey)
- Actinopterygii — *Polypterus*, *Protopterus* (Lungfish)
- Amphibia — *Ambystoma* (Axolotl), *Xenopus*
- Sauropsida — *Testudines* (Turtle), *Gallus* (Chicken)
- Mammalia — *Mus* (Mouse)
- plus *Danio* (Zebrafish) as a modern CPG model

即 **12 个研究物种**（11 个脊索动物 + 鳌虾外群）。另有 16 条**跨物种方法资源**单列统计，**不计入物种**。

## Dashboard at a glance / 数据看板图览

以下四张图由最终确认数据（178 条）实时统计生成，与看板同口径。

### 1 · 年代 × 大类分布（历史趋势）

![年代×大类分布](img/chart-trend.svg)

**结论（历史趋势）**：收录条目随年代显著加速——1973–2009 合计仅 30 条，2010–15 增至 25 条，2016–23 达到峰值 74 条，2024–26 三年即 42 条，占全库近四分之一。大类构成上，功能记录（电生理/成像类）与分子组学（测序/图谱类）始终是两大主线；2016 年以后分子组学占比明显抬升，反映单细胞/空间组学技术在脊髓与运动神经元研究中的普及。

### 2 · 物种 × 大类 热力图

![物种×大类热力图](img/chart-heatmap.svg)

**结论（物种覆盖）**：七鳃鳗（27）、海鞘（25）、小鼠（21）是收录最厚的三个物种——七鳃鳗以功能记录（15）为绝对主力，配理论建模（5），体现经典 CPG 电生理+建模传统；海鞘的结构连接（7）与功能记录（8）最厚，连接组资源突出；小鼠则以功能记录（9）为主。相反，肺鱼（5）、鳌虾外群（6）、斑马鱼（7）的覆盖偏窄——肺鱼 5 条中 4 条集中于分子组学，其余类别近乎空白，是后续文献补录的优先方向。

### 3 · 近三年热点（2024–26 vs 全时期）

![近三年热点](img/chart-recent.svg)

**结论（近三年热点）**：近三年（42 条）的热点明显向**分子组学**集中——占 2024–26 新增条目的 48%（20 条），远高于其全时期基线 30%，对应大量单细胞/空间转录组 atlas 与多组学资源的爆发；功能记录类份额从 38% 回落到 21%（经典电生理产出放缓），结构连接类保持稳定略升（17% vs 15%）。理论建模近三年仅 2 条，仍是明显短板；行为和运动 4 条，其中闭环/机器人实验范式开始出现，值得追踪。

### 4 · 物种收录完备性排名

![物种收录排名](img/chart-rank.svg)

**结论（完备性）**：条目数排名为 七鳃鳗 27 > 海鞘 25 > 小鼠 21 > 文昌鱼 14 > 非洲爪蟾 / 多鳍鱼 13 > 美西螈 12 > 乌龟 10 > 家鸡 9 > 斑马鱼 7 > 鳌虾 6 > 肺鱼 5。头部三个物种贡献了全库约 41% 的条目；尾部的肺鱼、鳌虾、斑马鱼多依赖早期经典文献与少量组学资源，公开数据可得率最低——这与"进化节点越关键、数据反而越稀缺"的总体格局一致。

## What's inside

| File | Content |
|---|---|
| `index.html` | Interactive single-file database: 178 entries, force-directed network graph, word-bank auto-relevance scoring (0–6), research-object filter, DOI / PMC / data-page links per entry |
| `INVENTORY.md` | Full audit: open-data coverage per species, reasons for unavailability, corresponding-author emails, link-fix log |
| `DATABASES.md` | ~100 neuroscience / model-organism data repositories, organized by data type |
| `WORDBANK.md` | Curated domain word bank (CPG / spinal cord / cell identity / electrophysiology / …) used for auto-scoring and search |
| `data/entries.js` | All 178 entries as loadable JS |

## Data coverage (2026-11-06)

- **178 entries**（相关文章 / 数据资源 / 网站），spanning 1973–2026
- **63 entries (35%)** with direct open-data links (GEO / ArrayExpress / DANDI / CRCNS / Figshare / Zenodo / GitHub / official portals) — 每条一本预填 notebook
- Every entry has at least one working link (DOI / PMC / open PDF / data page)
- Relevance scoring is computed from an explicit keyword rule bank (object / process / evidence dimensions) — no hand-tuned stars

---
中文说明：本库汇总 **12 个研究物种**（11 个脊索动物 + 鳌虾外群；跨物种方法资源不计入物种）的脊髓/运动神经元/CPG 文献与公开数据资源，共 **178 条**，其中 **63 条**带公开数据。每条含 DOI/PMC/数据页链接、词库自动相关度评分（对象/过程/证据三维）、研究对象过滤。`INVENTORY.md` 含逐条开放数据可得性审计与通讯作者邮箱。
