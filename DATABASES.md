# 神经科学数据库总表（v2 尽可能全 · 供词库检索用）

> 2026-11-05 汇编，来源：OpenNeuroscience、NIH BRAIN 数据档案网络、多伦多大学图书馆指南、awesome-vem-datasets、模式生物库目录。★ = 对 10 物种脊髓/MN/CPG 数据缺口直接有用。

## A. 序列 / 单细胞 / 空间组学

| 数据库 | 入口 | 说明 |
|---|---|---|
| GEO | ncbi.nlm.nih.gov/geo | ★ 最大通用组学库 |
| SRA / BioProject | ncbi.nlm.nih.gov/sra | ★ 原始测序 |
| ENA | ebi.ac.uk/ena | ★ 欧洲镜像（PRJEB 号） |
| DDBJ | ddbj.nig.ac.jp | ★ 日本镜像（Ciona 团队） |
| NGDC（OMIX/GSA/HRA） | ngdc.cncb.ac.cn | ★ 国内库（毛炳宇 OMIX003801） |
| ArrayExpress / BioStudies | ebi.ac.uk/arrayexpress | ★ E-MTAB 号 |
| NeMO Archive | nemoarchive.org | BRAIN 计划多组学档案 |
| Broad Single Cell Portal | singlecell.broadinstitute.org | ★ Cao 2019 = SCP454 |
| CZ CELLxGENE | cellxgene.cziscience.com | 鼠脊髓 atlas 多份 |
| OmicsDI | omicsdi.org | 跨组学库元检索 |
| Single Cell Expression Atlas | ebi.ac.uk/gxa/sc | EBI 单细胞 |
| HCA Data Coordination Platform | data.humancellatlas.org | 人类+比较 |

## B. 结构连接 / EM / 形态

| 数据库 | 入口 | 说明 |
|---|---|---|
| EMPIAR | empiar.org | ★ 原始 EM 数据（含 vEM） |
| BossDB | bossdb.org | ★ 皮级 EM/X 射线体积（MICrONS/FANC/BANC） |
| Open Connectome Project / NeuroData | neurodata.io | ★ EM 连接组开放档案 |
| EBRAINS Knowledge Graph | ebrains.eu | ★ 欧洲脑研究设施（图谱+EM+模型） |
| NeuroMorpho.org | neuromorpho.org | ★ 3D 神经元重建（含鱼/两栖） |
| neuPrint / FlyWire / CATMAID / webKnossos | 各官网 | 连接组浏览/注释平台（无脊椎为主，方法可借鉴） |
| OpenOrganelle | openorganelle.janelia.org | Janelia FIB-SEM |
| awesome-vem-datasets | github.com/JackieZhai/awesome-vem-datasets | ★ vEM 数据集总目录 |
| NeuroVault | neurovault.org | 统计图谱（人类的，参考） |

## C. 电生理 / 神经活动（核心缺口层）

| 数据库 | 入口 | 说明 |
|---|---|---|
| CRCNS | crcns.org | ★ 精选电生理数据集（locomotion/spinal） |
| DANDI | dandiarchive.org | ★ NWB 格式电生理+钙成像（>20 物种） |
| NeuroElectro | neuroelectro.org | ★ 文献挖掘的神经元电生理参数（可直接查七鳃鳗/鱼 MN） |
| G-Node | g-node.org | 欧洲电生理数据（NIX 格式） |
| NEMAR | nemar.org | 人类 EEG/MEG/iEEG |
| DABI | dabi.loni.usc.edu | 人类颅内电生理（BRAIN 计划） |
| EMBER (BBQS) | brain-bbqs.org | ★ 同步神经-行为多模态数据 |
| Brain Image Library | brainimagelibrary.org | ★ 大规模显微/光片（已用于 cor-assBVIN78） |
| braincircuits.io | braincircuits.io/resources | 神经回路数据集导航 |

## D. 行为 / 运动

| 数据库 | 入口 | 说明 |
|---|---|---|
| Dryad | datadryad.org | ★ 行为学大户（运动学/视频） |
| Zenodo / Figshare / OSF | zenodo.org 等 | ★ 通用兜底（DOI 数据集） |
| Mendeley Data | data.mendeley.com | Elsevier 系随附 |
| Harvard Dataverse | dataverse.harvard.edu | JEB/生态系 |
| EMBER | brain-bbqs.org | 同步行为-神经 |
| Movebank | movebank.org | 动物追踪（不适用，排除） |

## E. 计算模型

| 数据库 | 入口 | 说明 |
|---|---|---|
| ModelDB | senselab.med.yale.edu/modeldb | ★ Ekeberg/CPG/oscillator 模型源码 |
| Open Source Brain | opensourcebrain.org | ★ 开源神经模型（NeuroML） |
| NeuroML.org | neuruml.org | 模型格式标准 |
| CRCNS（模型部分） | crcns.org | 数据+模型配套 |

## F. 模式生物门户（物种专属层）

| 数据库 | 物种 | 入口 |
|---|---|---|
| **ANISEED（Tunicate Portal）** | ★ 海鞘 | aniseed.fr |
| **AmphioxusDB 系** | ★ 文昌鱼 | 各镜像 |
| Xenbase | ★ Xenopus | xenbase.org |
| ZFIN | ★ 斑马鱼 | zfin.org |
| GEISHA | ★ 家鸡表达 | geisha.arizona.edu |
| NARF（National Avian Research Facility） | 家鸡/禽类 | narf.ac.uk |
| SAL-SITE | ★ 美西螈（Ambystoma） | ambystoma.org |
| AxoBase | 美西螈 | axobase 专线 |
| MGI / EMAGE / eMouseAtlas | 鼠发育 | informatics.jax.org |
| RGD | 大鼠（比较用） | rgd.mcw.edu |
| WORMBASE / FlyBase | 无脊椎对照 | 常规 |
| Echinobase | 棘皮（外群参考） | echinobase.org |

## G. 比较基因组 / 直系同源（marker 跨物种映射）

| 数据库 | 入口 |
|---|---|
| OMA / OrthoDB / EggNOG / TreeFam / Genomicus / DIOPT / EnsemblCompara | 各官网 |
| Bgee | bgee.org（跨物种表达） |
| UniProt / KEGG | 常规 |

## H. 元检索 / 目录（找库的库）

| 名称 | 入口 | 用途 |
|---|---|---|
| **NIF（Neuroscience Information Framework）** | neuroinformatics.org | ★ 最大神经科学数据目录 |
| **FAIRsharing** | fairsharing.org | ★ 按学科/标准查库 |
| **re3data** | re3data.org | ★ 全球研究数据库注册 |
| CONP | portal.conp.ca | 加拿大神经开放平台 |
| NITRC | nitrc.org | 工具+数据 |
| NIH BRAIN 数据档案网络 | nih.gov/brain | 官方档案索引 |
| The Node resources | thenode.biologists.com | 发育生物资源 |

---

## 检索执行顺序（对照 115 条无数据缺口）

1. **NeuroElectro**：species=lamprey/xenopus/axolotl → 直接得到已发表神经元的 R_in/发放/突触参数（虽非原始数据，可量化补缺）
2. **CRCNS + DANDI**：关键词 `locomotion, spinal, fictive, swimming, lamprey, zebrafish, axolotl`
3. **ModelDB + OSB**：`lamprey CPG, Ekeberg, spinal oscillator, salamander`——把理论建模空类填掉
4. **DDBJ + ANISEED**：Ciona 团队历史数据；`Ciona motor ganglion / nervous system`
5. **NGDC-OMIX + GEISHA + SAL-SITE**：国内文昌鱼、鸡胚表达、蝾螈
6. **Dryad/Zenodo/Figshare 全量扫**：词库组 1/4/6 关键词 + 10 物种名
7. **EMPIAR/BossDB**：`ascidian / amphioxus / lamprey EM`——碰运气看有无未发表连接组

---

## I. 物种专属深挖（来源：文献综述/社区资源页/博客，2026-11-05 网络挖掘）

### 海鞘——官方"四库分工"体系（Genetics 2012 综述记载，国际被囊动物信息系统协定）
| 数据库 | 分工 | 入口 |
|---|---|---|
| **GHOST**（京都大学） | 基因组/EST/KH gene models/表达图谱 | ghost.zool.kyoto-u.ac.jp |
| **CIPRO** | 蛋白/2D-PAGE/质谱/表达 | cipro.ibio.jp |
| **ANISEED** | 发育遗传学/原位/解剖（覆盖 Phallusia、Halocynthia） | aniseed.cnrs.fr |
| **FABA（4D Ascidian Body Atlas）** | **4D 细胞谱系/解剖**（庆应 Hotta lab）——对 MN 谱系追踪直接有用 | chordate.bpni.bio.keio.ac.jp/faba |
| VISTA browser | Cioin2 物种间比对（enhancer 搜索） | pipeline.lbl.gov |

### 文昌鱼
| 数据库 | 说明 | 入口 |
|---|---|---|
| **LanceletDB** | 基因组+转录组+比较工具合集 | 搜索 LanceletDB |
| **中研院 amphioxus EST/cDNA 库** | 31.9 万条 EST、可 BLAST、可索取 cDNA 克隆 | amphioxus.icob.sinica.edu.tw |
| OMIX003801（毛炳宇） | 胚胎 scRNA/snRNA+ATAC | ngdc.cncb.ac.cn/omix |

### 美西螈——社区资源全家桶（Murawala lab 资源页 + AxoBase）
| 资源 | 说明 | 入口 |
|---|---|---|
| **AxoBase** | 社区维护总门户（实验室/转基因系/抗体） | axobase.org |
| **Axolotl-omics** | Tanaka lab：BLAST+UCSC+HiGlass 一站式 | axolotl-omics.org |
| Axolotl Transcriptomics Portal | Bryant 2017 Cell Reports 转录组 | 链接在 AxoBase |
| Axologl | Voss lab/AGSC 原位杂交图像库 | 链接在 AxoBase |
| Sal-site | NIH P40 股票中心+基因组 | ambystoma.uky.edu |
| UCSC 浏览器 | 2019/2021/2024 三代组装 | genome.ucsc.edu |
| Salamander Slack | 社区直接问人（要数据的最快路径） | 联系 Murawala lab |

### 七鳃鳗
| 数据库 | 说明 | 入口 |
|---|---|---|
| **SIMRbase**（Stowers，Smith lab） | ★ 种系基因组浏览器（kPetmar1/gPmar100）+BLAST+基因搜索；另含太平洋七鳃鳗、西方溪七鳃鳗浏览器 | simrbase.stowers.org/sealamprey |
| UCSC VGP hub | 2025 新组装 UKy_Petmar_22M1（GCA_048934315.1） | hgdownload.gi.ucsc.edu/hubs/VGP |
| Kaessmann lab | 脑 atlas（E-MTAB-11085/11087） | kaessmannlab.org |

### 龟
| 数据库 | 说明 | 入口 |
|---|---|---|
| KEGG pss | 中华鳖 2025 染色体级组装（Sci Data） | kegg.jp/kegg-bin/show_organism?org=pss |
| GigaDB 100085 | 绿海龟 2013 Nat Genet 基因组 | gigadb.org |
| VGP GenomeArk rCheMyd1 | 绿海龟 curated 组装（pri+alt） | genomeark.org |
| Ensembl archive | PelSin_1.0 | ensembl.org |
| genomes.jbrowse.org | VGP 各龟种一键浏览（含 2025 新种） | genomes.jbrowse.org |

### 肺鱼 / 多鳍鱼
| 数据库 | 说明 | 入口 |
|---|---|---|
| VGP hub | 西非肺鱼 Protopterus annectens GCA_040939525.1（2024）UCSC 浏览器 | hgdownload.gi.ucsc.edu/hubs/VGP |
| figshare | 非洲肺鱼 GFF/CDS/PEP（已收 Nat Comms 2023） | 已在主清单 |
| Polypterus senegalus | 基因组见 2021 论文数据（无专库） | 查论文 suppl |

### 中文博客/教程发现（方法论）
- 吴田振博客：ncbi-genome-download 批量下载 10 物种基因组的实操教程（wu-tz.github.io）
- DANDI 中文实操教程：dandi CLI 搜索/下载/断点续传（coreui.cn 等）
- ZFIN wiki "Other Databases"：鱼类库大全（cBARBEL/Fugu/SalmonDB/CarpBase——辐鳍鱼比较备胎）
- SFBD（法国发育生物学会）模式生物库列表、The Node resources 页、genenames.org useful links

### 社区直接问人通道（要数据最快路径）
- Salamander Slack（蝾螈社区）｜CionaLab GitHub｜Stowers SIMRbase 联系｜AGSC/Voss lab｜Tanaka lab wiki
