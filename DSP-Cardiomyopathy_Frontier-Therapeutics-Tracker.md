# DSP 心肌病 / 致心律失常性心肌病（ACM）治疗前沿追踪

> **整理说明**
> - 本文档由《未来可以持续关注的有 3.pdf》（16 条追踪条目）规范化整理而成
> - 新增整合 *Advanced Science* (2026) 关于 **POSTN–CCL3 前馈信号环** 的最新研究成果，作为独立重点章节
> - 影响因子（IF）以 2024 年度 JCR 为准，个别 2025 年度有更新的已并列标注；JCR 分区取该刊主学科最高分区
> - 整理日期：2026 年 10 月 6 日

---

## 一、总览表

| # | 方向 | 核心靶点 | 候选药物 / 手段 | 当前阶段 | 证据级别 | 参考文献 |
|---|---|---|---|---|---|---|
| ★ | **POSTN–CCL3 前馈环（新加入）** | POSTN / integrin–JNK / CCL3–CCR5 | Maraviroc（CCR5，已获批）、SP600125（JNK） | 临床前体内药效 | **C+** | [1] |
| 1 | 抗纤维化双重靶向 | SRC + TGFβ | Saracatinib、Pirfenidone | 临床前 | C | [3] |
| 2 | GSK3 抑制 | GSK3β | Tideglusib（已获批阿尔茨海默适应证） | **II 期临床 NCT06174220** | **B** | [4] |
| 3 | CAR-T 逆转纤维化 | FAP | 靶向 FAP 的工程化 T 细胞 | 临床前 | C | [5] |
| 4 | sEH–EET 轴 | 可溶性环氧化物水解酶（sEH） | sEH 抑制剂（±COX-2 抑制剂 / ω-3 PUFA） | 临床前 | C | [6] |
| 5 | PDE4 抑制增强桥粒黏附 | PDE4 | Apremilast（阿普米斯特，已获批） | 临床前（体外 + 体内） | C | [7] |
| 6 | 基因治疗（DSP 相关通路） | FGF21 / Cx43 | RJB-0402（AAV8-FGF21）、AAV-Cx43 | 临床前 / IND 申报中 | C | [8][9] |
| 6a | PKP2 基因治疗（已独立建档） | PKP2 | LX2021 | 待追踪 | — | [10] |
| 7 | 炎症小体（焦亡） | NLRP3 炎症小体 / NEK7 | MRT-810（NEK7 分子胶降解剂） | **I 期临床** | C | [11] |
| 8 | 抗纤维化转录因子 | PKNOX2 | 尚未成药（靶点发现阶段） | 靶点发现 | D | [12] |
| 9 | EGFR 抑制促 DSP 膜转位 | EGFR | 厄洛替尼等已获批 EGFRi | **I/IIa 期 NCT06545695**（皮肤病适应证） | C | [13][14] |
| 10 | cGAS–STING 通路 | cGAS | VENT-03、IMSB301 | **II 期（红斑狼疮）** | C | [15][16] |
| 11 | DSP-AS1 反义 lncRNA | DSP-AS1 | GapmeR / LNA2（ASO） | 体外概念验证 | D | [17][18][19] |
| 12 | IL-1 通路 | IL-1α/β、NLRP3 | Rilonacept、Canakinumab（均已获批） | 病例报告 + 体内机制 | **B** | [20][21] |
| 13 | NF-κB / CCR2⁺ 巨噬细胞 | CCR2⁺ 巨噬细胞、NF-κB | 尚无专用药物（抗炎策略） | 临床前机制 | C | [2] |
| 14 | VIM–BECN1 / p38 | VIM、BECN1、p38 | 未开发 | 机制验证 | D | [22] |
| 15 | GLP-1 | GLP-1R | — | **已暂移出主动追踪**（检索未见 DSP/ACM 特异性文献） | — | [23] |

**证据级别**：A＝人体随机对照 / B＝人体病例或队列＋体内机制 / C＝动物体内药效 / D＝体外或机制验证

---

## 二、重点新增：POSTN–CCL3 前馈信号环 ★

### 2.1 文献信息

**Periostin-CCL3 Feedforward Signaling Loop Promotes Cardiac Fibrosis and Cardiomyocyte Necroptosis in Arrhythmogenic Cardiomyopathy**
***Advanced Science*, 2026** [(PDF)](https://doi.org/10.1002/advs.77670) (IF **14.3** / 2025 年度 **14.1**，JCR **Q1**)

- **文章号 / DOI**：e77670 · 10.1002/advs.77670
- **共同第一作者**：Tiantian Wu（吴甜甜）、Ruotong Li、Xiaoyue Zhang
- **通讯作者**：吴甜甜（wutiantian@xmu.edu.cn，厦门大学）、崔丹（广州国家实验室）、**宋江平**（fwsongjiangping@126.com，中国医学科学院阜外医院）、欧阳高亮（厦门大学）
- **单位**：厦门大学（生命科学学院 / 医学院 / 附属晋江医院常见病研究所）、中国医学科学院阜外医院心血管疾病国家重点实验室、广州国家实验室
- **时间线**：Received 2025-12-19 → Revised 2026-08-24 → Accepted 2026-09-02
- **资助**：国家自然科学基金 82273416、82172932、82573223 等

> **追踪提示**：本研究的通讯作者宋江平教授，正是总览表第 3 条「FAP CAR-T 逆转心肌炎纤维化」的团队负责人（阜外医院）。同一团队在一年内沿着**细胞治疗**（清除肌成纤维细胞）与**小分子打断细胞间对话**（POSTN–CCL3）两条路线并行推进，值得作为一条独立线索持续跟进。

### 2.2 核心机制：心肌细胞 ↔ 成纤维细胞的正反馈环

```
        ┌───────────────── 心脏肌成纤维细胞 ─────────────────┐
        │                                                    │
        │   POSTN ──→ integrin αvβ3 / αvβ5                   │
        │                    │                               │
        │                    ├─→ JNK ─→ RIP3 → MLKL ─→ 坏死性凋亡（心肌细胞死亡）
        │                    │                               │
        │                    └─→ JNK ─→ ETS2 ─→ CCL3 ↑       │
        │                                   │                │
        │                                   ↓                │
        │                        CCL3 ─→ CCR5 ─→ NF-κB       │
        │                        (ILK / p-P65)               │
        │                                   │                │
        │                                   ├─→ 肌成纤维细胞活化（α-SMA↑）
        │                                   └─→ POSTN 表达 ↑ ──┘  ← 闭合正反馈
        └────────────────────────────────────────────────────┘
```

**关键细胞定位**
- **POSTN**：主要来源于心脏**肌成纤维细胞**（Vimentin⁺），而非心肌细胞、脂肪细胞、巨噬细胞或内皮细胞
- **CCL3**：主要来源于 **cTNT⁺ 心肌细胞**（RNA-FISH 与免疫荧光双验证，小鼠与患者样本一致）
- **CCR5**：CCL3 的受体；POSTN 缺失后心肌 *Ccr5* 显著下降，而 *Ccr1*、*Ccr3* 无变化 → 受体选择性明确

### 2.3 动物模型

采用 **心脏特异性 DSP 条件性敲低小鼠**（α-MHC-Cre × DSP^flox，即 `CreDSP^f/+`，由 Ali J. Marian 教授实验室提供），是 DSP 单倍剂量不足的经典 ACM 模型。实验分组：
`DSP^f/+ Postn^+/+`、`DSP^f/+ Postn^-/-`、`CreDSP^f/+ Postn^+/+`、`CreDSP^f/+ Postn^-/-`

另用 **AAV9-Tcf21-Cre**（1.5×10¹¹ vg/只，尾静脉单次注射，4 周龄）实现**心脏成纤维细胞特异性 Postn 敲除**，验证细胞来源特异性。

### 2.4 主要结果

**① POSTN 缺失改善心功能与生存**
- 心衰标志物 *Nppa*、*Nppb* 显著下降（n=5）
- 心室扩张减轻，EF%、FS% 改善（n=4）
- ACM 相关 T 波倒置消失
- 跑步时间延长，心脏重量/胫骨长度比（HW/TL）下降（n=6）
- **生存率显著提高**（Kaplan-Meier，n=20）
- 成纤维细胞特异性敲除可完整复现上述保护效应

**② POSTN 缺失减轻纤维化与炎症**
- Masson / Sirius Red 染色：胶原沉积显著减少
- α-SMA、Col1a1 蛋白与 *Acta2*、*Col1a1*、*Col3a1*、*Tgf-β3* mRNA 下调（n=6~8）
- 炎症基因 *CD68*、*F4/80*、*Tnf-α*、*IL-6*、*IL-1β*、*IL-17* 下调；CD68⁺ 巨噬细胞浸润减少；血清 IL-6 降低

**③ POSTN 经 integrin–JNK–RIP3–MLKL 驱动心肌细胞坏死性凋亡**
- 血清 LDH 活性下降，p-RIP3、p-MLKL 降低
- 体外：新生小鼠心肌细胞（NMCM）+ si*Dsp* + rmPOSTN；人心肌细胞系 AC16 + si*DSP* + rhPOSTN → 坏死率（PI 染色）升高
- **整合素 αvβ3/αvβ5 中和抗体**或 si*Itgβ3/β5* 可阻断 JNK、RIP3、MLKL 磷酸化
- **PD98059**（MAPKK 抑制剂）、**SP600125**（JNK 抑制剂）、**Necrostatin-1**（坏死性凋亡抑制剂）均可在体外逆转

**④ CCL3 经 CCR5–NF-κB 活化成纤维细胞并诱导 POSTN**
- rmCCL3 刺激新生小鼠心脏成纤维细胞（NMCF）：*Acta2*、*Postn* 呈时间-剂量依赖性上调
- **Maraviroc**（CCR5 拮抗剂）可完全逆转 rmCCL3 或与 ACM 心肌细胞共培养诱导的成纤维细胞活化
- **BAY-11-7082**（NF-κB 抑制剂）同样阻断 α-SMA 与 POSTN 上调
- 体内：POSTN 缺失后 ILK、p-P65 显著下降

**⑤ 患者样本验证（阜外医院，伦理批件 2013-496）**
- ACM 患者心肌 POSTN 显著高于正常对照
- POSTN 上调程度与**纤维脂肪替代严重度**、**心肌细胞坏死性凋亡（p-MLKL）**正相关
- POSTN 与 CCL3 在患者心肌中共定位

### 2.5 药理干预（最具转化价值的部分）

| 药物 | 靶点 | 给药方案 | 主要结果 |
|---|---|---|---|
| **Maraviroc** | CCR5 | 5 月龄 ACM 小鼠，**50 mg/kg/日，口服 × 3 个月** | 减轻心脏重构；*Nppa*/*Nppb* 下降；胶原沉积、POSTN、α-SMA 减少；血清 LDH 下降；p-RIP3、p-MLKL 下降；JNK–ETS2–CCL3 轴受抑（n=8） |
| **SP600125** | JNK | 5 月龄 ACM 小鼠，**25 mg/kg 腹腔注射，每周 3 次 × 3 个月** | 与 Maraviroc 保护效果相当 |

> **Maraviroc 是 FDA 已批准的 CCR5 拮抗剂（抗 HIV 药物，商品名 Selzentry）**，安全性与药代数据完备，是本项目中最具备"老药新用"快速转化条件的候选。相比之下 **SP600125 仅为科研工具化合物**，不具备直接成药性，其价值在于验证 JNK 这一靶点。

### 2.6 必须注意的四条限定（决定如何理解这条线索）

1. **它是"放大环"而非"启动因子"**：4 月龄小鼠各实验组在心脏形态、心衰标志物、纤维化、坏死性凋亡及 JNK–ETS2–CCL3 轴上**均无差异**；到 8 月龄才出现显著分离。→ 该轴不启动 ACM，而是在疾病进展中被激活并放大损伤。**定位是"减速"，不是"根治"。**
2. **不修复桥粒本身**：透射电镜显示，POSTN 缺失后**桥粒超微结构缺陷并未完全恢复**。→ 与基因替代、DSP-AS1 抑制等"补 DSP"路线是互补关系，而非替代关系。
3. **DSP 特异性未确立**：作者明确说明，所用模型为 DSP 条件性敲低；这些改变是 DSP 缺陷特有，还是桥粒心肌病的共性特征，**仍是开放问题**。
4. **功能必要性待补**：CCL3 主要来自心肌细胞，但尚需**心肌细胞特异性 *Ccl3* 敲除**来确立心肌源 CCL3 的功能必要性。

---

## 三、其余追踪方向详述

### 3.1 抗纤维化双重靶向（SRC + TGFβ）〔3〕

斯坦福大学医学院心血管研究所 **Joseph C. Wu（吴庆明）** 教授团队，*Nature*（2025 年 3 月）。

- **策略**：SRC 抑制联合 TGFβ 通路阻断的"双靶点联合干预"
- **转化药物**：**Saracatinib**（原抗癌药，SRC 抑制剂）+ **Pirfenidone**（吡非尼酮，已获批特发性肺纤维化）
- **团队背景**：Stanford Cardiovascular Institute 主任、Simon H. Stertzer 医学与放射学教授，专注心血管基因组学与 iPSC 疾病建模、药物发现与精准医疗，曾任 AHA 主席
- **联系方式**：joewu@stanford.edu

### 3.2 GSK3 抑制剂〔4〕

加拿大心血管遗传学研究中心（**Dr. Jason D. Roberts**、**Dr. Andrew D. Krahn** 团队）

- **试验**：**NCT06174220**
- **药物**：**Tideglusib**（GSK3 抑制剂，原阿尔茨海默病适应证）
- **时间**：2025 年 3 月启动，**2027 年 3 月出结果**
- **联系方式**：andrew.krahn@ubc.ca
- **注**：GSK3β 抑制（SB216763、BIO）在 PKP2 / Dsg2 模型中已有充分证据，可同时逆转电生理异常与细胞损伤表型；但 **DSP 特异数据薄弱**，本试验是重要的验证窗口。

### 3.3 FAP 靶向 CAR-T 逆转心肌炎纤维化〔5〕

阜外医院**宋江平**团队，*Theranostics*（2025 年 12 月）

- 在模拟**自身免疫性**与**病毒性**两种病因的心肌炎小鼠模型中，输注靶向 **FAP**（成纤维细胞活化蛋白）的 CAR-T 细胞
- **心脏纤维化面积减少 55%–65%**，心功能明显改善
- **与第 2 章 POSTN–CCL3 研究为同一通讯作者团队**，建议合并追踪

### 3.4 sEH–EET 轴〔6〕

美国科罗拉多大学安舒茨医学院心血管研究所 **Dr. Luisa Mestroni**（心血管遗传学项目负责人 / 教授）

- 发表于 *JACC: Basic to Translational Science*（2025）
- 首次系统阐明 **sEH–EET 轴**在 ACM 发病中的作用，为 ACM 提供首个具转化潜力的**炎症靶向**治疗方案
- **联合策略建议**：COX-2 抑制剂或饮食干预（补充 **ω-3 PUFA**）以增强疗效
- **联系方式**：luisa.mestroni@cuanschutz.edu

### 3.5 Apremilast（PDE4 抑制剂）增强桥粒黏附〔7〕

*Apremilast improves cardiomyocyte cohesion and arrhythmia in different models for arrhythmogenic cardiomyopathy*，*Stem Cell Research & Therapy*（2025）

- 通过增强桥粒功能和心肌细胞黏附，改善 ACM 模型中的细胞结构与电生理稳定性
- **作者（Jens Waschke 教授）2025-12-10 邮件回复要点**：
  - 该药最初由其团队提出用于**天疱疮**（同为桥粒病，Sigmund et al., *Nat Commun* 2023），天疱疮方向已有系列病例报告支持
  - **剂量建议**：参照天疱疮病例报告，严重副作用与心律失常问题不突出
  - **试验现状**：欧洲与美国**均无计划中的试验**；慕尼黑曾有意启动但未推进（团队为基础科学家，无患者资源）
  - **关键告诫**：**心律失常是核心风险**；治疗必须有 ACM 治疗经验的心脏科医生监督；未植入 ICD 的患者能否用药是关键问题
  - 作者明确表示：若有心脏科医生监督，可直接用药并发表病例报告，**不必等待 III 期试验**

### 3.6 基因治疗〔8〕〔9〕

**核心瓶颈**：DSP 编码序列约 8.6 kb，远超 AAV 约 4.7 kb 的包装上限，必须依赖双载体（overlapping / trans-splicing）或截短体。因此现有策略多为"间接法"或靶向共同通路。

| 项目 | 载体 | 机制 | 阶段 |
|---|---|---|---|
| **RJB-0402**（Rejuvenate Bio） | AAV8，肝脏特异性表达 **FGF21** | 同时靶向脂肪生成、炎症、纤维化 | 获 **CIRM 400 万美元**资助推进 IND 前研究，拟进入首次人体试验 |
| **AAV-Cx43**（Sheikh 团队） | AAV | 恢复缝隙连接蛋白 Cx43，间接促进桥粒蛋白重新定位到细胞连接 | 2026 年 1 月发表；*Dsp* 缺失与 PKP2 突变小鼠均获益，延长寿命；**突变类型无关** |

> **注**：LX2021 为 Lexeo 的 **PKP2** 基因治疗项目，与上表 Cx43 / FGF21 路线机制不同，已拆分为独立条目（见 3.6a 及总览表第 6a 条）分别追踪。

### 3.6a PKP2 基因治疗：LX2021〔10〕（独立建档）

- **项目**：LX2021（Lexeo Therapeutics）
- **靶基因**：**PKP2**（桥粒斑蛋白 2，非 DSP），适应证为 PKP2 突变相关 ACM
- **载体与机制**：信息待核实，暂列「待追踪」
- **追踪定位**：PKP2 基因序列远小于 DSP（约 8.6 kb），不受 AAV 包装上限约束，与第 3.6 节 DSP 间接法面临的瓶颈性质不同，故分开建档

### 3.7 炎症小体 / NEK7〔11〕

**背景机制**：美国 NIH 资助项目（F30HL162454，至 2026 年 2 月）探索 DSP 截断如何通过**细胞焦亡**激活炎症小体。
- 用 siRNA 敲低新生大鼠心室肌细胞 DSP 后进行 RNA-seq：**免疫趋化通路显著升高**，多个**焦亡相关基因**尤为突出
- 假说：桥粒斑蛋白减少 → 炎症小体过度活化 → 钙处理异常 → 致心律失常性异质性细胞连接
- **干预靶点聚焦 NEK7**（炎症小体组件，心衰中表达有差异），手段包括 siRNA、小分子抑制剂、表观遗传调控
- 项目地址：https://taggs.hhs.gov/Detail/AwardDetail?arg_AwardNum=F30HL162454

**药物进展**：
- **MRT-810**（Monte Rosa Therapeutics）：全球首款进入临床的 **NEK7 靶向分子胶降解剂**，口服，通过降解 NEK 蛋白从上游阻断 NLRP3 炎症小体活化，抑制细胞焦亡与多种促炎因子释放
- 2025 年 11 月 AHA 年会公布临床前数据：药效优于现有 NLRP3 抑制剂，改善动脉粥样硬化与心包炎相关炎症；小鼠与食蟹猴显示强效持久抗炎，安全窗口高
- **I 期临床进行中，预计 2026 年上半年公布初步数据**
- 机制区别于传统抗 IL-1 / IL-6 药物，为全新抗炎方向

### 3.8 PKNOX2〔12〕

中国医学科学院阜外医院**胡盛寿 / 陈亮**团队，*Signal Transduction and Targeted Therapy*（2024-04-22）

- 利用优化的单细胞核 RNA 测序解析人类心脏细胞组成与转录调控网络
- 在成纤维细胞亚群中发现新的心脏纤维化相关转录调节因子 **PKNOX2**
- 体内外过表达与敲减实验确立：**PKNOX2 是一种新的抑制纤维化的转录因子**
- 为心衰及心肌纤维化治疗提供新角度与潜在靶点（**尚未成药**）

### 3.9 EGFR 抑制剂促 DSP 膜转位〔13〕〔14〕

*Experimental Dermatology* 2024, 33: e15046（DOI: 10.1111/exd.15046），荷兰格罗宁根大学医学中心心脏科/皮肤科联合研究，通讯作者 **Maria C. Bolling**（m.c.bolling@umcg.nl）

- **关键机制**：EGFR 抑制剂 **AG-1478** 处理患者原代角质形成细胞，可促进**胞质内 DSP 向细胞膜易位**、增加细胞膜处桥粒数量
- **注意**：该效应**不增加 DSP 总蛋白合成**，而是改变**亚细胞定位** —— 这对 DSP **单倍剂量不足**尤其有意义
- 首次在患者原代细胞中证实对 DSP 突变相关皮肤病的表型纠正
- **临床转化优势**：已有临床获批的 EGFR 抑制剂（如厄洛替尼）为该发现的快速转化奠定基础

**临床试验 NCT06545695**（*Epidermal Growth Factor Receptor Inhibition for Keratinopathies*）
- 2025 年 8 月启动，**多中心 1/2a 期**，验证**低剂量厄洛替尼**对掌跖角化症、先天性厚甲、表皮松解性鱼鳞病的安全性与疗效
- 牵头：美国西北大学，合作：耶鲁大学
- 周期：预计 2026 年 12 月至 2030 年 6 月 30 日
- **注意**：当前适应证为**皮肤角化病**，非心脏适应证

### 3.10 cGAS–STING 通路〔15〕〔16〕

**Ali J. Marian** 团队（UTHealth 休斯顿，分子医学研究所心血管遗传学中心），*JCI Insight* 2025, 10(16): e192283（2025-07-03）

- **机制**：DSP 缺陷心肌细胞的胞质中出现本应位于细胞核或线粒体的**自身 DNA**（核 DNA + 线粒体 DNA）→ 被 cGAS 识别 → 激活 **STING1 / TBK1** → 打开 **IRF3 与 NF-κB** 促炎基因开关
- **干预证据**：DSP 敲除小鼠中**基因敲除 cGAS** 可延长生存、改善心功能、减少纤维化

**在研 cGAS 抑制剂**
- **VENT-03**（Ventus Therapeutics）：临床开发中最先进的**口服小分子 cGAS 抑制剂**，首个完成 I 期并启动 II 期的 cGAS 抑制剂；II 期用于伴活动性皮肤病红斑狼疮，多中心随机双盲安慰剂对照 + 开放标签扩展；**28 天安慰剂对照顶线数据预计 2026 年下半年发布**
- **IMSB301**：另一领跑者
- 试验设计已纳入心脏健康与衰老相关生物标志物，为心血管适应证拓展留出接口

### 3.11 DSP-AS1 反义 lncRNA〔17〕〔18〕〔19〕

**这是目前证据链最完整的"内源性 DSP 表达调控因子"**，也是绕开 AAV 包装限制的聪明路线。

- **人群遗传学证据**（Luisa Foco 等，意大利 Eurac Research 等多机构，*Human Genetics* 2025）：CHRIS 队列 N=4342，DSP 常见变异 **rs2744389** 与 **QRS 间期**相关（P = 3.5×10⁻⁶），在 MICROS 研究（n=636，P=0.010）中重复
- **关键点**：该变异关联的是 **DSP-AS1**（反义 lncRNA）表达，而非 DSP 本身
- **孟德尔随机化**：支持 **DSP-AS1 → DSP 表达**的因果效应（P = 6.33×10⁻⁵；共定位后验概率 = 0.91）
- **功能验证**：hiPSC-CM 中用特异性 **GapmeR** 敲低 DSP-AS1 → DSP mRNA 与蛋白双双上调
- **意义**：DSP-AS1 有望成为 DSP 缺乏相关疾病（ACM、DCM、心皮综合征及部分癌症）的治疗靶点

**后续项目（DESMOJOINT）**：Eurac Research（意大利）联合 Cardiocentro Ticino（瑞士）、帕多瓦大学（意大利）、根特大学（比利时）
- 用 **LNA2**（GapmeR）在携带 DSP 无义突变（单倍剂量不足）的 hiPSC-CM 及其同基因型对照中下调 DSP-AS1
- 2026 年最新进展：LNA2 处理 10 天后，ddPCR 显示 DSP-AS1 显著下降且 **DSP 转录本回升**；DSP-AS1/DSP 调控轴在心肌细胞与心脏成纤维细胞中活跃，内皮细胞中较弱
- 已构建多细胞微组织（MT）与工程化心脏组织（EHT）用于验证电生理表型
- 探索**细胞外囊泡**递送该分子
- 项目周期：2025 年 1 月 – 2027 年 12 月

### 3.12 IL-1 通路〔20〕〔21〕

#### 12.1 突破性病例：IL-1 抑制剂成功治疗激素耐药复发性 DSP 心肌心包炎

- **25 岁女性**，携带致病性 DSP 变异，反复发作心肌心包炎
- 泼尼松 40 mg/d 联合秋水仙碱治疗 3 个月**无效**，hs-TnI 持续升高至 145 ng/L（正常 < 17 ng/L）
- 改用**利纳西普（Rilonacept，IL-1α/β 双抑制剂）**：320 mg 负荷剂量皮下注射，随后 160 mg 每周一次
- **疗效**：3 个月后胸痛完全缓解，hs-TnI 降至 44 ng/L，成功停用泼尼松；9 个月后无症状，hs-TnI 恢复正常（8 ng/L），心功能稳定
- **意义**：首次在人体证实 IL-1 通路阻断对 DSP 相关难治性炎症发作的有效性

#### 12.2 机制突破：IL-1β 是桥粒蛋白心肌病"炎症–纤维化"恶性循环的核心驱动因子

- 通过**单核 RNA 测序**与**空间转录组学**分析 ACM 患者心肌，发现疾病区域存在"炎症–纤维化"空间生态位，其中巨噬细胞高表达 **NLRP3** 和 **IL-1β**
- 在 **Dsg2 突变小鼠**模型中，抗 IL-1β 中和抗体显著减轻心肌纤维化、降低炎症因子、改善收缩功能、减少心律失常
- 为已上市的 IL-1 抑制剂（**利纳西普、卡那单抗**）用于桥粒蛋白心肌病提供机制基础，支持开展更大规模临床试验

### 3.13 NF-κB / CCR2⁺ 巨噬细胞〔2〕

详见参考文献 [2]。该研究在 ACM 临床前模型中确立 **NF-κB 信号经 CCR2⁺ 巨噬细胞驱动心肌损伤**，与第 3.10（cGAS-STING）、3.12（IL-1β）共同构成 ACM 的**先天免疫轴**，也解释了为何抗炎策略在 DSP 心肌病"hot phase"中反复显示获益。

### 3.14 VIM–BECN1 / p38〔22〕

*Circulation Research*（2026 年 8 月）：*Deficient Desmoplakin Drives Excessive Cardiac Fibrosis via VIM-Mediated Sequestration of BECN1 in Cardiac Mesenchymal Stromal Cells*

DSP 缺陷 → 波形蛋白（VIM）扣押 Beclin-1（BECN1）→ 自噬与胞吞功能受损 → 心脏间充质基质细胞过度纤维化。

**三个理论干预点（均停留在机制验证层面）**

| 干预点 | 逻辑 | 风险 |
|---|---|---|
| 抑制 **VIM** | 降低 VIM 即减少对 Beclin-1 的扣押，间接恢复抗纤维化通路 | VIM 为人体广泛表达的骨架蛋白，全身抑制存在未知安全风险 |
| 补充 **BECN1** | 直接过表达，抵消被扣押造成的功能不足 | Beclin-1 参与凋亡、肿瘤调控等多条通路，全身过表达风险高；心脏靶向递送是难点 |
| **p38 抑制剂** | TGF-β 下游促纤维化执行通路，DSP 缺陷时 p38 持续异常激活 | 广谱抗纤维化靶点，非 DSP 特异；仅停留于理论机制层面 |

### 3.15 GLP-1〔23〕

**原文档仅有标题，无具体内容。**

**检索说明（2026-10-06）**：未检索到 GLP-1 / GLP-1RA 针对 DSP 心肌病或 ACM 的特异性研究文献；仅有泛心血管获益证据（CVOT 中 MACE 下降）及间接机制研究（如利拉鲁肽减轻自身免疫性心肌炎，*Sci Rep* 2025）。按勘误表建议，本条**暂移出主动追踪列表**，保留占位；若后续出现 DSP/ACM 特异性数据再行恢复。

---

## 四、机制通路整合视图

DSP 单倍剂量不足后的病理级联，可分为四条相对独立的"可打击轴线"：

```
                        DSP 单倍剂量不足（桥粒机械缺陷）
                                    │
        ┌───────────────┬───────────┼───────────────┬──────────────┐
        ↓               ↓           ↓               ↓              ↓
   【轴 A】        【轴 B】      【轴 C】        【轴 D】       【轴 E】
   机械/结构       先天免疫     纤维化放大      桥粒蛋白补充     代谢/线粒体
        │               │           │               │              │
   Src / PKC      cGAS-STING   POSTN ⇄ CCL3     DSP-AS1 抑制    EPAS1/HIF-2α
   → 肌节缩短      → IRF3/NF-κB  (前馈环) ★      (GapmeR/LNA2)   → 线粒体应激
        │          NLRP3/NEK7        │           EGFR 促膜转位    → ROS → 凋亡
   GSK3β/Wnt       → IL-1β      TGFβ / SRC       Apremilast           │
        │          CCR2⁺ 巨噬    PKNOX2          基因替代          FGF21
        │               │        p38 / VIM-BECN1 (AAV-DSP/Cx43)       │
   Saracatinib    Rilonacept     Maraviroc        RJB-0402      代谢干预
   Tideglusib     MRT-810       Pirfenidone      （GLP-1 已暂移出追踪）
   Dasatinib      VENT-03       FAP CAR-T
```

**组合逻辑提示**
- **轴 E 与轴 A 是"源头"，其余多为"下游放大器"**。POSTN–CCL3、IL-1β、cGAS 均属下游，单用可减速但难根治。
- **轴 D 是唯一能真正"补 DSP"的路线**，但受限于 AAV 包装容量（DSP-AS1 抑制是最优解）或皮肤/体外证据阶段（EGFR 抑制剂）。
- **LX2021（PKP2）不列入轴 D**，独立建档于总览表第 6a 条 / 3.6a 节：其靶基因为 PKP2 而非 DSP，不受 DSP 包装瓶颈约束，追踪逻辑不同。
- **Maraviroc 与 Rilonacept 是转化门槛最低的两个候选**（均已获批，安全性数据完备），且分别命中纤维化放大环与炎症轴，理论上可联合。

---

## 五、优先级建议（供追踪资源分配参考）

| 优先级 | 方向 | 理由 |
|---|---|---|
| **P0** | IL-1 通路（Rilonacept） | 已有人体病例成功，药物已获批，机制刚被阐明，最可能快速落地 |
| **P0** | POSTN–CCL3 / Maraviroc ★ | 药物已获批，体内药效数据完整，靶点位于纤维化与细胞死亡的交叉点 |
| **P1** | DSP-AS1 / LNA2 | 唯一能上调内源性野生型 DSP 等位基因的路线，天然绕开 AAV 包装限制；已有 MR + 功能验证的完整证据链 |
| **P1** | GSK3 抑制剂 Tideglusib | 唯一进行中的 ACM 靶向临床试验（NCT06174220），2027 年 3 月出结果 |
| **P1** | cGAS 抑制剂 VENT-03 | II 期 2026 年下半年出数据，且试验已纳入心脏生物标志物 |
| **P2** | Apremilast | 作者明确表示可在心脏科医生监督下直接用药并发表病例报告，无需等待试验；但心律失常风险需严格评估 |
| **P2** | EGFR 抑制剂（厄洛替尼） | 老药，机制上"促膜转位"对单倍剂量不足特别对口，但当前试验仅覆盖皮肤病适应证 |
| **P2** | NEK7 / MRT-810 | I 期数据 2026 年上半年公布，机制新颖 |
| **P3** | PKNOX2、VIM-BECN1、p38 | 靶点发现或机制阶段，成药路径长 |

---

## 六、参考文献

[1] Periostin-CCL3 Feedforward Signaling Loop Promotes Cardiac Fibrosis and Cardiomyocyte Necroptosis in Arrhythmogenic Cardiomyopathy. **Advanced Science, 2026** [(PDF)](https://doi.org/10.1002/advs.77670) (IF **14.3**，JCR **Q1**)

[2] NFκB signaling drives myocardial injury via CCR2+ macrophages in a preclinical model of arrhythmogenic cardiomyopathy. **The Journal of Clinical Investigation, 2024** [(PDF)](https://365.kdocs.cn/l/cus0nAqjtewa) (IF **13.6**, JCR **Q1**)

[3] Selective inhibition of stromal mechanosensing suppresses cardiac fibrosis. **Nature, 2025** (IF **50.5**，JCR **Q1**)〔DOI 待补〕

[4] GSK3 抑制剂 Tideglusib 治疗 ACM 临床试验. **ClinicalTrials.gov NCT06174220, 2025**（2027 年 3 月出结果）

[5] Engineered T cell therapy for the treatment of cardiac fibrosis during chronic phase of myocarditis. **Theranostics, 2025** (IF **13.3**，JCR **Q1**)〔DOI 待补〕

[6] 可溶性环氧化物水解酶（sEH）抑制剂在致心律失常性心肌病（ACM）中的作用. **JACC: Basic to Translational Science, 2025** (IF **7.2**，JCR **Q1**)〔DOI 待补〕

[7] Apremilast improves cardiomyocyte cohesion and arrhythmia in different models for arrhythmogenic cardiomyopathy. **Stem Cell Research & Therapy, 2025** (IF **7.3**，JCR **Q1**)〔DOI 待补〕

[8] RJB-0402：AAV8 载体表达 FGF21 治疗 DSP 心肌病. **Rejuvenate Bio, 2026**（IND 前研究阶段，CIRM 资助 400 万美元）

[9] Connexin-43 Restoration Alleviates Desmosomal Arrhythmogenic Cardiomyopathy. **Circulation: Heart Failure, 2026** (IF 待补，JCR **Q1**)〔DOI 待补〕

[10] LX2021（Lexeo Therapeutics）. **PKP2 基因治疗**〔信息待核实〕

[11] MRT-810：全球首款进入临床的 NEK7 靶向分子胶降解剂. **Monte Rosa Therapeutics, 2025**（AHA 年会公布临床前数据；I 期进行中）

[12] PBX/Knotted 1 homeobox-2 (PKNOX2) is a novel regulator of myocardial fibrosis. **Signal Transduction and Targeted Therapy, 2024** (IF **52.7**，JCR **Q1**)〔DOI 待补〕

[13] EGFR 抑制剂促进 DSP 向细胞膜易位修复桥粒功能. **Experimental Dermatology, 2024** [(PDF)](https://doi.org/10.1111/exd.15046) (IF **3.1**，JCR **Q1**)

[14] Epidermal Growth Factor Receptor Inhibition for Keratinopathies. **ClinicalTrials.gov NCT06545695, 2025**（多中心 1/2a 期，西北大学牵头）

[15] Cardiomyocyte cytosolic nuclear self-DNA contributes to the pathogenesis of desmoplakin cardiomyopathy. **JCI Insight, 2025** [(PDF)](https://doi.org/10.1172/jci.insight.192283) (IF **6.1**，JCR **Q1**)

[16] VENT-03：口服小分子 cGAS 抑制剂 II 期临床试验. **Ventus Therapeutics, 2026**（红斑狼疮适应证；顶线数据预计 2026 年下半年）

[17] Genomic and molecular evidence that the lncRNA DSP-AS1 modulates desmoplakin expression. **Human Genetics, 2025** [(PDF)](https://doi.org/10.1007/s00439-025-02761-x) (IF 待补)

[18] Targeting an Antisense lncRNA of the Desmoplakin Gene for Treating Arrhythmogenic Cardiomyopathy in Human Cellular Model（DESMOJOINT）. **Eurac Research / Cardiocentro Ticino, 2025–2027**（在研项目）

[19] DSP-AS1 lncRNA as a promising target for treating desmoplakin cardiomyopathy. **Cardiovascular Research, 2026**（122 Suppl 1: i134；LNA2 在 hiPSC-CM 中回升 DSP 转录本）

[20] Desmoplakin Cardiomyopathy Presenting With Recurrent Myopericarditis Responsive to Interleukin-1 Blockade. **JACC: Case Reports, 2025** [(PDF)](https://doi.org/10.1016/j.jaccas.2025.104039) (IF **0.67**，JCR **Q3**)

[21] Interleukin-1β Drives Disease Progression in Arrhythmogenic Cardiomyopathy. **JACC: Basic to Translational Science, 2026** [(PDF)](https://doi.org/10.1016/j.jacbts.2026.101542) (IF **7.2**，JCR **Q1**)

[22] Deficient Desmoplakin Drives Excessive Cardiac Fibrosis via VIM-Mediated Sequestration of BECN1 in Cardiac Mesenchymal Stromal Cells. **Circulation Research, 2026** (IF **16.2**，JCR **Q1**)〔DOI 待补〕

[23] GLP-1 相关方向. **待补充**〔原文档仅有标题；2026-10-06 检索未见 DSP/ACM 特异性文献，暂移出主动追踪〕

---

*本文档为研究追踪用途，内容均来自公开文献与企业公告，不构成任何诊疗建议。*
