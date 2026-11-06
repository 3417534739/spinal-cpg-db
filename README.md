# Spinal Cord / CPG Literature-Data Database (Chordata)

A curated literature & open-data catalog for spinal cord / motor neuron / CPG research across **11 chordate species + 1 outgroup**, built for tracing the evolution of locomotor circuit architecture.

**Three entry points / 三个入口：**

1. **[Interactive database (main page)](https://3417534739.github.io/spinal-cpg-db/)** — `index.html`：网络图 + 全部条目 + 自动评分 + DOI/PMC/数据链接
2. **[Data intelligence dashboard (final)](https://3417534739.github.io/spinal-cpg-db/dashboard.html)** — `dashboard.html`：最终确认数据的情报看板（KPI / 年代×大类 / 物种×大类热力图 / 出版源分层 / 6 域热点 / 完备性排名 / 自动结论，178 条全量数据）
3. **[Notebooks index](notebooks/README.md)** — 每条带公开数据的条目一本预填 notebook（内含 EN 标题 / 中文摘要 / Highlights / 数据页原文）

**English / 中文双语说明见下。**

## Species covered

Outgroup: *Crayfish (Procambarus)*
Chordata:
- Cephalochordata — *Branchiostoma* (Amphioxus)
- Tunicata — *Ciona*
- Cyclostomata — *Petromyzon* (Sea lamprey)
- Actinopterygii — *Polypterus*, *Protopterus* (Lungfish)
- Amphibia — *Ambystoma* (Axolotl), *Xenopus*
- Sauropsida — *Testudines* (Turtle), *Gallus* (Chicken)
- Mammalia — *Mus* (Mouse)
- plus *Danio* (Zebrafish) as a modern CPG model

## What's inside

| File | Content |
|---|---|
| `index.html` | Interactive single-file database: 178 entries, force-directed network graph, word-bank auto-relevance scoring (0–6), research-object filter, DOI / PMC / data-page links per entry |
| `INVENTORY.md` | Full audit: open-data coverage per species, reasons for unavailability, corresponding-author emails, link-fix log |
| `DATABASES.md` | ~100 neuroscience / model-organism data repositories, organized by data type |
| `WORDBANK.md` | Curated domain word bank (CPG / spinal cord / cell identity / electrophysiology / …) used for auto-scoring and search |
| `data/entries.js` | All 178 entries as loadable JS |

## Data coverage (2026-11-05)

- **178 entries**, spanning 1973–2026
- **63 entries (35%)** with direct open-data links (GEO / ArrayExpress / DANDI / CRCNS / Figshare / Zenodo / GitHub / official portals)
- Every entry has at least one working link (DOI / PMC / open PDF / data page)
- Relevance scoring is computed from an explicit keyword rule bank (object / process / evidence dimensions) — no hand-tuned stars

## Update workflow

1. Edit `index.html` (the `const D=[...]` array) — sorting, badges and the network graph update automatically.
2. Sync `data/entries.js`.
3. Commit & push; GitHub Pages (if enabled) serves `index.html` at `https://<user>.github.io/<repo>/`.

---
中文说明：本库汇总 12 个类群的脊髓/运动神经元/CPG 文献与公开数据资源，每条含 DOI/PMC/数据页链接、词库自动相关度评分（对象/过程/证据三维）、研究对象过滤。`INVENTORY.md` 含逐条开放数据可得性审计与通讯作者邮箱。更新流程：改 `index.html` 的 D 数组 → 同步 `data/entries.js` → push。
