# 脊索动物神经/CPG 领域词库（v1.0）

> 构建方法：语料 = 158 条收录条目的标题/模态/说明 + 30 篇本地 PDF 前 3 页（含摘要）。
> 第一遍：正则切词（英文 uni/bi/tri-gram，中文 2–4 字 n-gram），统计总频与文档频。
> 第二遍过滤（本版）：剔除期刊排版噪音（karolinska/department/copyright/accepted/e-mail/doi/org 等）、
> 通用学术词（study/results/methods/data/analysis）、残缺 n-gram 碎片（"tion""经元""动神""觉反馈"等）、
> 与领域无关的一般词；保留 rel=1.0 且语义完整的词，按主题归类。
> 每个词条标注文档频（df，出现在多少篇文献中）。用途：相关性评分、文献检索式、查全查自检。

## 1. CPG 与节律生成（核心）
central pattern generator / CPG / CPGs（df 32+9+7）｜pattern generator｜节律生成 / rhythm generation（df 3）｜rhythm / 节律（df 16）｜rhythmic output｜locomotor rhythmicity｜oscillator / oscillation / 振荡 / 振荡器（df 6）｜NMDA-induced TTX-resistant oscillations｜burst / bursting / 爆发｜burst frequency｜节律爆发｜fictive locomotion / 假想运动（df 4）｜locomotor activity｜节段 / segmental / segmental network｜节段振荡器 / segmental oscillators｜hemisegment / 半节段 / 半脊髓 / hemicord / hemispinal cord｜unit burst generator（UBG）｜half-center / 半中心｜reciprocal inhibition / 交互抑制｜coupled oscillator / 耦合振荡器｜left-right alternation / 左右交替｜phase lag / 相位滞后｜phase resetting / 相位重置｜entrainment / 牵引｜rostrocaudal propagation｜speed / locomotor speed｜slow and fast locomotor burst

## 2. 脊髓 / 神经索 / 解剖结构
spinal cord / 脊髓（df 41）｜nerve cord / 神经索（df 4）｜caudal nerve cord / 尾部神经索｜motor ganglion / MG｜spinal network｜spinal interneurons（df 4）｜spinal neurons｜ventral neurons｜neural tube / 神经管｜floor plate / 底板｜notochord / 脊索｜ventral root / 腹根｜dorsal root｜neuromuscular junction / NMJ / 神经肌肉连接 / 终板｜myotome / 肌节｜axial muscles / 轴向肌｜muscle band｜edge cells（df 5）｜dorsal cells｜commissural neurons（df 5）｜coordinating neurons｜command neurons｜lateral interneurons｜EIN / excitatory interneurons（df 5）｜CC / inhibitory interneurons｜Renshaw cells / Ia inhibitory interneuron｜Mauthner cell｜reticulospinal neurons / 网状脊髓（df 7）｜Müller cells｜V0 / V1 / V2a / V3 / Shox2｜dIN / cIN｜LPN / IPN / CN / MP / PPN2s｜MLR / mesencephalic locomotor region（df 7）｜DLR / diencephalic locomotor region｜brainstem / hindbrain / 脑干（df 6）｜rhombencephalon｜basal ganglia（df 4）｜striatal / D1/D2 neurons｜cerebellum（df 3）｜frontal eye（df 4）｜cerebral vesicle｜sensory vesicle / 感泡｜antenna cells｜coronet cells

## 3. 细胞类型与神经元身份
motor neurons / motoneurons / MNs / 运动神经元（df 7+7）｜interneurons（df 8）｜neuron subtype / 神经元亚型｜cell type / cell-type-specific｜terminal selector｜effector genes｜MN pool / motoneuron pool｜LMC / MMC / HMC｜Hox / Pax / Nkx / Olig / Shh / Neurogenin / Ebf / Onecut / Nkx6 / Dkk3 / Agrin｜progenitor / 祖细胞｜neurogenesis / 神经发生｜proliferation / 增殖｜lineage / 谱系｜clonal barcoding / LARRY｜cell lineage｜ependymoglial cells｜astroglia / 星形胶质｜oligodendrocyte｜gliosis｜phenotype

## 4. 突触与电生理
synapse / synaptic / 突触（df 6）｜chemical synapse / 化学突触｜electrical synapse / gap junction / 电突触｜synaptic pattern｜excitatory / inhibitory / 兴奋性 / 抑制性｜inhibition / 抑制（df 5）｜reciprocal｜post-inhibitory rebound / PIR｜plateau potential / 钙平台｜NMDA（df 6）/ AMPA / kainate｜T-type Ca²⁺ / CaV1.3 / L-type Ca²⁺｜KCa / KCa2 / late AHP / afterhyperpolarization｜5-HT / serotonin / 血清素｜dopamine / 多巴胺（df 3）｜D1 / D2 receptors｜cholinergic / 胆碱能（df 4）｜GABAergic / GABA｜glycinergic / 甘氨酸（df 4）｜glutamatergic / 谷氨酸（df 4）｜glycine receptor / 甘氨酸受体｜strychnine / 士的宁｜picrotoxin｜neuromodulation / 神经调制（df 3）｜intracellular recording / 胞内记录｜sharp electrode｜whole-cell｜patch-clamp / Patch-seq｜calcium imaging / GCaMP / 钙成像（df 6）｜voltage imaging / ASAP｜EMG / 肌电｜ventral root recording｜fictive locomotion｜electrical stimulation / 电刺激（df 2）｜pharmacology / 药理（df 3）｜ablation / 消融（df 5）｜laser ablation｜miniSOG｜microstimulation｜confocal imaging

## 5. 发育与构建
development / 发育（df 5）｜developmental｜patterning / 图式化｜circuit assembly（df 3）｜circuit development｜spontaneous activity / 自发活动｜spontaneous rhythmic bursting｜motor axon pathfinding / 轴突寻路｜D-V pathfinding｜pool-specific fasciculation｜embryonic / 胚胎（df 11）｜postnatal day｜larva / larval / 幼虫 / 幼体｜tadpole / 蝌蚪（df 4）｜metamorphosis / 变态（df 5）｜ontogeny｜organizational continuity

## 6. 行为与运动输出
locomotion / locomotor（df 21+）｜motor control / 运动控制（df 6）｜motor output / 运动输出｜motor behaviors / motor actions｜swimming / 游泳（df 14+20）｜forward/reverse swimming｜undulatory swimming｜walking / 行走｜stepping｜crawling / 爬行｜terrestrial locomotion / 陆生运动｜amphibious / 两栖（df 3）｜burrowing / 钻沙｜tail flick｜escape / startle response｜phototaxis / 趋光｜avoidance / 避光｜dimming response｜gait / 步态｜tripod gait｜kinematics / 运动学｜posture / 姿态｜eigenciona｜swimmeret（df 5）｜limb movements｜fin-body coordination｜motor repertoire｜behavioral repertoire｜terrestrial crawling

## 7. 组学与数据资源
single-cell RNA-seq / scRNA-seq｜snRNA-seq｜scATAC-seq / ATAC｜multiome / RNA+ATAC｜spatial transcriptomics / Stereo-seq / Visium｜in situ sequencing / ISS｜smRNA-FISH｜atlas（df 9）｜cell browser｜connectome / ssEM / serial-section EM（df 5）｜synaptome｜transcriptome / 转录组｜RNA velocity｜developmental trajectory｜genome / 基因组｜barcoding｜FACS sorting｜peripheral nerve mapping｜ultrastructural map｜open dataset / 公开数据集

## 8. 理论与建模
computational model（df 3）｜Hodgkin-Huxley model｜multi-compartment model｜86 compartments / 12 ionic currents｜ionic current｜coupled oscillator model｜nearest-neighbor coupling｜descending drive / 驱动信号｜proprioceptive feedback / 本体感觉反馈｜sensory feedback / 感觉反馈（df 7）｜robot / robotics / 机器人｜neuromechanical model｜virtual muscles｜simulation / 仿真｜model validation｜CPG controller｜distributed controller

## 9. 演化与比较
evolution / 演化（df 9）｜vertebrate / 脊椎动物（df 10）｜vertebrate evolution｜chordate / 脊索动物｜ancestral / 祖先｜homolog / homology / 同源｜comparative｜deep homology｜circuit elements evolution｜evolutionary origin｜invertebrate chordate｜proto-vertebrate｜water-to-land transition｜terrestrialization｜jawed / jawless vertebrates｜cyclostome｜gnathostome

## 10. 物种与专属名词
lamprey / 七鳃鳗（df 8）｜Petromyzon｜ammocoete｜amphioxus / Branchiostoma / 文昌鱼｜Ciona / Ciona intestinalis / robusta｜swimmeret system / crayfish（df 5）｜Pacifastacus / Procambarus｜zebrafish / Danio rerio / 斑马鱼（df 5）｜larval zebrafish｜axolotl / Ambystoma / 美西螈｜salamander / Pleurodeles / 蝾螈（df 6）｜Xenopus laevis / tropicalis｜turtle / Trachemys｜Gallus gallus / chick embryo｜Mus musculus｜Polypterus senegalus｜lungfish / Protopterus｜tunicate / 尾索动物｜urochordate｜cephalochordate｜Oikopleura｜Dendrodoa｜Halicryptus?（无）｜Drosophila（无）

## 11. 二次过滤中剔除的代表项（示例，供追溯）
karolinska institutet / stockholm / sweden / department / university（机构地址）｜copyright / creative commons / open access / accepted / received / published online（出版流程）｜e-mail / gmail / http / www / doi / org / pmc（链接与元数据）｜the spinal / from the / and the / has been / this review（句法碎片）｜tion / tem / bec / identi（PDF 切词残片）｜经元 / 动神 / 觉反馈 / 髓运 / 索腹侧（中文 n-gram 跨词残片）｜study / results / analysis / data（通用学术词）｜january / february / september / october（月份）

---

# v1.1 扩充（基于拓展检索 9 篇新文献 + PDF 深挖 6 页重切）

> 扩充语料：v1.0 语料 + 拓展库新增 9 条（文昌鱼神经化学图谱、七鳃鳗 Vglut2 光遗传、Xenopus Ih/Na 泵/aIN、小鼠 V3 光遗传/limb CPG/MN 亚型演化）+ PDF 提取加深至前 6 页。
> 与 v1.0 求差后得到新候选 EN 1,019 / CN 6,956，二次过滤（剔期刊名/月份/试剂成分 NaCl·CaCl·MgCl·glucose·sigma、作者名、图注残留 scale bar/dorsal view、 accession 编号）后收录如下。

## 12. CPG 与节律生成（扩充）
limb CPG / 肢体运动 CPG（df 3）｜tail CPG→limb CPG switch / 尾 CPG→肢 CPG 转换｜locomotor rhythmicity（df 4）｜cell-type-specific origins of rhythmicity｜rhythm generation / 节律生成｜burst termination / 爆发终止｜burst frequency｜frequency adaptation｜swim episode / 游泳 episode 时长｜inter-swim interval｜speed-dependent gait / 速度依赖步态｜locomotor speed｜module / modular organization / 模块化组织｜distributed rhythm generation / 分布式节律生成｜flexor–extensor alternation / 屈伸交替

## 13. 脊髓 / 神经索解剖（扩充）
commissural interneuron / CIN / 连合中间神经元｜V0ᴰ / V0ᵛ / V3 CIN｜primary motor center / PMC / 初级运动中心｜cerebral vesicle / 脑泡｜frontal eye complex / 额眼复合体｜lamellar body / 板状体｜infundibular organ / 漏斗器｜Hesse organs｜tectal zone / 顶盖区｜MHB-like / ZLI-like boundary｜somite / 体节（df 3）｜limb bud / 肢芽｜crural plexus｜lumbosacral cord / 腰髓｜hemienlargement / 半侧扩大部｜cervical / thoracic / lumbar 颈/胸/腰段｜dorsal–ventral pathfinding

## 14. 细胞类型与身份（扩充）
V2a (Chx10⁺)｜Shox2⁺｜V1 (En1⁺)｜V2b (Gata2⁺)｜V3 (Sim1⁺)｜V0 (Dbx1-derived)｜Foxp1｜Hoxa6/c6 / Hoxc9 / Hox10｜PEA3 / ER81｜MMC / LMC / HMC / PGC / CT（column of Terni）｜motor pool / 运动神经元池｜Renshaw homolog｜engrailed⁺ IN｜switch neurons｜Rohon-Beard cells｜D1/D2-MSN｜neurochemical map / 神经化学图谱｜vGlut / VGAT / VAChT / ChAT｜serotonergic / dopaminergic

## 15. 突触与电生理（扩充）
Ih current / ZD7288（HCN 阻断）｜myomodulin｜Na⁺/K⁺ pump / 钠钾泵｜usAHP / ultraslow afterhyperpolarization / 超慢后超极化｜graded synaptic currents｜electrical coupling / 电耦联｜suction electrode｜paired whole-cell｜piriform?（无）｜rhythm frequency｜TTX-resistant oscillation｜dendritic Ca²⁺｜nimodipine / Bay K 8644｜picrotoxin｜sarcosine（GlyT1）｜dpERK｜microdissection｜micro-aspiration

## 16. 行为与运动输出（扩充）
five motor behaviors / 五种运动行为（swim/struggle/forward–backward stepping）｜gait transition / 步态转换｜turning / directionality / 转向｜stopping locomotion / 运动终止｜locomotor start / 运动发起｜V2a stop neurons / 停止神经元｜gaze-controlling neurons｜visual selection commands｜shadow response（df 2）｜startle-like maneuver｜struggling / 挣扎

## 17. 理论与建模（扩充）
two-layer rhythm generator (RG)｜half-center vs unit-burst 之争｜distributed CPG controller｜virtual muscles / 虚拟肌肉｜local proprioceptive feedback loop｜hydrodynamic simulation｜salamander robot / 蝾螈机器人｜Nengo / spiking simulation｜neuromechanical simulation｜model validation against pharmacology

## 18. 演化与比较（扩充）
Foxp1-loss = ancestral state / 祖先态｜HMC-like precursor｜agnathan / 无颌类｜Hox network co-option / Hox 网络征用｜cis-regulatory evolution｜common ancestor / 共同祖先｜million years ago（MYA）｜evolutionary transition water→land｜cross-species projection / 跨物种 cell-type 映射｜orthology mapping（df 2）

## 19. 数据资源专名（扩充，供检索式使用）
ARTISTA｜LBSPA｜AmphioxusAtlas｜CNP0000891 / OMIX003801 / CRA010773 / GSE131155 / GSE121807 / GSE255742 / GSE183759 / GSE312424 / GSE317755 / GSE122939 / GSE106269 / E-MTAB-8839 / E-MTAB-11085/11087｜CRCNS ci-1｜MARS-seq｜10x Visium / Chromium｜PacBio HiFi｜LARRY barcoding｜DeepLabCut / SLEAP｜SeqSeek｜BICCN｜Xenbase｜X treme?（无）

## 20. 中文扩充
连合中间神经元｜屈伸交替｜节律生成网络｜半节段｜初级运动中心｜脑泡｜额眼复合体｜板状体｜神经化学图谱｜自发节律活动｜轴突路径选择｜运动神经元池｜运动柱｜超慢后超极化｜钠钾泵｜短时记忆｜光遗传｜下行驱动｜本体感觉反馈｜分布式节律生成｜步态转换｜运动终止｜速度模块｜细胞类型起源｜分子蓝图｜超微结构图谱｜外周神经映射｜跨物种比较｜祖先态
