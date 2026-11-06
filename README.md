# Spinal Cord / CPG Literature-Data Database (Chordata)

A curated literature & open-data catalog for **spinal cord, brain, motor neuron / CPG** research across **11 chordate species + 1 outgroup**, built for tracing the evolution of locomotor circuit architecture. 32 of 178 entries are brain atlases / maps (whole-brain connectomes, brain single-cell & spatial atlases), included for cross-comparison with spinal cord data.

> **📊 数据库总量：相关文章 / 数据资源 / 网站共 178 条；其中 63 条带公开数据（每个数据项附有相关研究的文章 / 数据详情，占 35%）。**

**Two entry points / 两个入口：**

1. **[Interactive database (main page)](https://3417534739.github.io/spinal-cpg-db/)** — `index.html`：网络图 + 全部条目 + 自动评分 + DOI/PMC/数据链接
2. **[Notebooks index](notebooks/README.md)** — 每个带公开数据的数据项附有对应研究的详情 notebook（内含 EN 标题 / 中文摘要 / Highlights / 数据页原文）

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

## 组学技术生态（数据来自 PubMed 官方检索计数）

![组学技术发文量](img/chart-omics.svg)

> 注：横轴为四年合计的对数刻度，条内四色为各年度占比（2026 年截至 11 月）；数据来自 PubMed 官方 E-utilities 检索计数（2026-11-06 查询），检索式与影响因子数据见下方表注。

文献计量分析表明，单细胞RNA测序（single-cell RNA sequencing, scRNA-seq）发文量呈持续增长态势：近四年累计发文40,464篇，2026年前11个月已达12,933篇；空间转录组（13,627篇）与单细胞多组学（RNA+ATAC配对，8,095篇）处于第二梯队，年发文量增速显著；空间增强分辨转录组测序（Stereo-seq）近四年累计发文185篇，呈逐年递增趋势（年度发文量依次为17、41、57、70篇）；单细胞CUT&Tag（204篇）与捕获转录组表位测序（CITE-seq，296篇）发文量呈稳步上升趋势；Patch-seq近四年累计发文73篇，2023年后发文量有所回落，技术发展进入成熟整合阶段。每行的红色圆点代表对应技术在脊髓/CPG领域的四年累计应用发文量：scRNA-seq已有388篇应用文献，空间转录组应用文献为125篇，scHi-C、DNA甲基化技术的应用文献数量为0（图中以虚线圈标注），Patch-seq仅4篇应用文献。技术总发文量与领域实际应用量之间的差距，即为本研究数据库拟填补的研究空白。

**技术分层总览**（分子组学按"读出层"金字塔逐层叠加读出维度）：

- **转录组主线**：bulk RNA-seq · scRNA-seq · snRNA-seq · Smart-seq2（全长）· 空间转录组（Stereo-seq / Visium / MERFISH）
- **活动依赖转录组**：TRAP-seq · FosTRAP——只读"正在放电/被激活"的神经元，是 CPG 招募研究的直接武器
- **+ 开放染色质**：10x Multiome · SHARE-seq · SNARE-seq · sci-CAR → 同时获得 RNA + 染色质可及性 + TF motif + 基因调控网络
- **+ 组蛋白修饰**：scCUT&Tag · Paired-Tag · nano-CUT&Tag（H3K27ac=活性 enhancer，H3K4me3=活跃启动子，H3K27me3=抑制性，H3K4me1=poised enhancer）
- **+ 蛋白**：CITE-seq · REAP-seq · Feature Barcode；**RNA+ATAC+蛋白**：TEA-seq · DOGMA-seq · ASAP-seq
- **+ DNA 甲基化**：scM&T-seq · scNMT-seq · scTrio-seq；**三维基因组**：scHi-C · enhancer–promoter contact / TAD 分析
- **代谢组**：bulk / 单细胞 / 空间代谢组（LC-MS/MS、质谱成像）——神经递质与能量代谢
- **功能配对**：Patch-seq（电生理+形态+转录组三合一）

| 技术 | PubMed 2023 / 24 / 25 / 26* | 四年合计 | 脊髓/CPG 领域应用量 | 众数期刊（发文最多）· IF | 顶刊最高 IF | 对 CPG / 运动神经回路 / 脊髓演化研究的价值 |
|---|---|---|---|---|---|---|
| scRNA-seq | 6,365 / 8,751 / 12,415 / 12,933 | **40,464** | **388** | Nat Commun · 15.7 | Nature · 48.5 | 跨物种脊髓细胞类型同源比对的底座——把海鞘、七鳃鳗、小鼠的运动神经元放上同一棵演化树 |
| 空间转录组 | 2,206 / 2,524 / 3,781 / 5,116 | **13,627** | **125** | Nat Commun · 15.7 | Nat Methods · 32.1 | 保住背腹轴与节段坐标——CPG 神经元的位置信息正是解离数据丢掉的部分 |
| 单细胞多组学（RNA+ATAC） | 741 / 1,115 / 2,456 / 3,783 | **8,095** | **60** | Nat Commun · 15.7 | Nature · 48.5 | 同一细胞 RNA+ATAC 配对；非模式物种参考基因组弱时尤其有用 |
| 空间代谢组（质谱成像） | 534 / 578 / 717 / 761 | **2,590** | **29** | 未单列 | — | 神经递质与能量代谢的空间分布——CPG 连续放电的代谢代价与恢复 |
| snRNA-seq | 228 / 317 / 561 / 667 | **1,773** | **46** | 未单列 | — | 对冷冻 / 致密组织友好，成体脊髓 atlas 的主力方案 |
| Visium | 75 / 105 / 191 / 252 | **623** | **5** | Nat Commun · 15.7 | Nat Methods · 32.1 | 低门槛平台，适合物种间脊髓切片的快速空间对照 |
| scATAC-seq | 129 / 149 / 171 / 159 | **608** | **5** | Nat Commun · 15.7 | Nat Methods · 32.1 | 顺式调控演化——运动神经元表型的"接线改动"大多写在增强子里 |
| CITE-seq（RNA+蛋白） | 62 / 63 / 85 / 86 | **296** | **1** | 未单列 | — | marker mRNA 与蛋白丰度解耦的校准层，避免"有转录无翻译"的误判 |
| MERFISH | 35 / 33 / 82 / 72 | **222** | **5** | Nat Commun · 15.7 | Cell · 42.5 | 靶基因 panel 单分子定位，可逐个验证 CPG 基因表达的空间梯度 |
| CUT&Tag（组蛋白修饰，单细胞） | 21 / 30 / 53 / 100 | **204** | **15** | 未单列 | — | 区分"marker 表达"与"调控程序真正开启"——H3K27ac/H3K4me3 才是 enhancer/启动子工作的证据 |
| Stereo-seq | 17 / 41 / 57 / 70 | **185**（官方累计 463） | **0** ⚠️ | Nat Commun · 15.7 | Cell · 42.5 | cm 级视场 + 亚细胞分辨率，可整段脊髓连续切片做 3D 重建，非模式物种大图谱利器 |
| Smart-seq2（全长） | 33 / 38 / 53 / 55 | **179** | **3** | 未单列 | — | 全长覆盖+高灵敏度，非模式物种（无参考注释）从头注释的优选 |
| scHi-C（三维基因组） | 21 / 24 / 33 / 24 | **102** | **0** ⚠️ | 未单列 | — | enhancer–promoter 物理接触与 TAD 结构——调控演化从"序列"到"空间构象" |
| 活动依赖转录组（TRAP/Fos，神经限定） | 26 / 19 / 27 / 23 | **95** | **7** | 未单列 | — | **只读运动时实际被招募的神经元**——游泳/爬行前后 CPG 招募图谱的直接手段 |
| Patch-seq | 19 / 17 / 13 / 24 | **73** | **4** | Neuron · 17.0 | Nature · 48.5 | **电生理 + 形态 + 转录组三合一**，把离子通道表达谱直接锚到 CPG 节律 / 突触属性上——"基因 → 细胞功能"的最短路径 |
| scM&T / scNMT（DNA 甲基化） | 8 / 0 / 3 / 5 | **16** | **0** ⚠️ | 未单列 | — | 甲基化+转录组同细胞配对，细胞状态的表观遗传"记忆"层 |

表注：发文量 = PubMed 官方 E-utilities 检索计数（2026-11-06 查询；*2026 年数据截至 11 月）。记数规则：各技术的检索相互独立，一篇论文同时使用或提及多种组学时，会在其命中的每种技术下各计 1 次，因此各行合计大于去重后的文献总数；脊髓/CPG 领域应用量为该技术检索式与领域限定词（spinal / spinal cord / central pattern generator / locomotor / locomotion，标题+摘要）的交叉计数。众数期刊 = 2023–25 该技术论文发表最多的期刊（在 14 本高影响力期刊范围内检索），其影响因子为 2024 JIF（2025-06 发布：Nature 48.5、Science 45.8、Cell 42.5、Nat Biotechnol 41.7、Nat Methods 32.1、Nat Commun 15.7、Cell Res 25.9、Nat Neurosci 20.0、Neuron 17.0、Cell Discov 12.5、Genome Biol 9.4、Dev Cell 8.7、Cell Rep 6.9）；顶刊最高 IF = 该技术在同范围检索下发文 ≥2 篇的期刊中影响因子最高者。Stereo-seq 官方发布数据（STOmics，截至 2025-12-31）累计 463 篇、IF>20 的占 20%，蝾螈端脑再生（Science 封面）、猕猴皮层与屏状核 3D 图谱（Cell 封面）、跨物种小脑比较（Science）等脑科学/演化标杆工作均出自该平台。

针对Patch-seq等神经元研究专用技术的专项分析：Patch-seq是目前唯一可在同一单细胞水平实现电生理表型、细胞形态特征与转录组图谱三维关联的技术，对神经运动回路研究的支撑作用最为直接。中枢模式发生器（central pattern generator, CPG）的节律发生机制与突触整合特性（如中间神经元的电耦合效应、运动神经元的输入电阻参数），只有借助该多模态配对技术才能建立其与基因组调控层面的关联。尽管该技术累计发文量较低（近四年共73篇，2026年回升至24篇），但高影响力期刊占比突出（《Nature》《Science》各发表2篇），主要刊载期刊为《Neuron》（影响因子17.0）与《Nature Communications》；其当前核心应用价值体现在与神经元图谱（atlas）项目的整合，Allen研究所构建的高保真电生理、形态与转录组规模化联合分析管线即为典型代表，相关条目已纳入本数据库。同属“神经元功能-分子关联”研究路径的技术还包括活动依赖性转录组分析技术（TRAP/Fos）及基于单细胞电生理筛选的转录组分型方法（如七鳃鳗网状脊髓细胞分型研究），这类技术可作为本数据库中“功能记录”类数据与“分子组学”类数据的天然衔接桥梁。

**本数据库已收录组学数据及研究缺口分析：**

当前数据库最核心的短板并非全技术平台的覆盖度不足，而是缺乏可关联分子身份、空间定位特征与中枢模式发生器（CPG）功能的多模态配对证据。现有数据集已涵盖部分空间转录组、空间增强分辨转录组测序（Stereo-seq）、独立单细胞ATAC测序（scATAC-seq）及小鼠Patch-seq相关内容，但七鳃鳗、非洲爪蟾（Xenopus）与龟胚胎的CPG脊髓仍缺乏细胞水平的功能-分子配对数据。

第一类核心缺口为CPG神经元的功能表型与分子身份配对研究，涵盖Patch-seq、膜片钳记录联合形态重建、细胞捕获RNA测序及RNAscope多模态联合分析方案。第二类核心缺口为运动过程中CPG神经元的活动招募解析，需结合功能性游泳或在体运动观测，联合钙成像、腹根/神经束电生理记录、肌电图（EMG）检测，以及Fos/Arc、CaMPARI、TRAP等活动依赖标记后的单细胞测序技术开展研究。第三类核心缺口为CPG脊髓的空间定位分析，应优先采用RNAscope或小型化MERFISH标志物检测体系，Visium可作为候选目标区域明确后的扩展验证方案。第四类核心缺口为基因调控程序的功能验证，优先采用RNA+ATAC多组学联合测序、H3K27ac/H3K27me3修饰的CUT&Tag检测技术。

CITE-seq、Hi-C、广谱代谢组及Smart-seq2全长转录组测序暂不列为全物种普适性的数据补充目标。上述技术分别适用于表面蛋白检测、特异性三维调控机制解析、变态或再生过程的代谢特征分析，以及稀有细胞类群与转录本异构体鉴定。独立scATAC-seq仅作为候选调控元件的佐证数据，而非独立的数据库覆盖目标。

---
中文说明：本库汇总 **12 个研究物种**（11 个脊索动物 + 鳌虾外群；跨物种方法资源不计入物种）的脊髓、脑、运动神经元/CPG 文献与公开数据资源，共 **178 条**（其中脑图谱/脑数据 32 条，供脊髓数据跨比较），其中 **63 条**带公开数据。每条含 DOI/PMC/数据页链接、词库自动相关度评分（对象/过程/证据三维）、研究对象过滤。`INVENTORY.md` 含逐条开放数据可得性审计与通讯作者邮箱。
