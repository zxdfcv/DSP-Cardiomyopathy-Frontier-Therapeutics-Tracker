# DSP Cardiomyopathy: Frontier Therapeutics Tracker

> DSP 心肌病 / 致心律失常性心肌病（ACM）治疗前沿追踪
>
> **DSP Cardiomyopathy: Frontier Therapeutics Tracker — From Desmoplakin Deficiency to Emerging Treatments**

## 项目简介

本仓库持续追踪 **DSP（桥粒斑蛋白）基因缺陷相关心肌病**的治疗前沿，覆盖从病理机制到临床转化的完整证据链。主文档为 [`DSP-Cardiomyopathy_Frontier-Therapeutics-Tracker.md`](./DSP-Cardiomyopathy_Frontier-Therapeutics-Tracker.md)，由原始追踪记录（16 条条目）规范化整理而成，并整合 *Advanced Science* (2026) POSTN–CCL3 前馈信号环研究作为独立重点章节；**2026-10-23 增补糖皮质激素与吗替麦考酚酯两条，以 *Circulation* (2025) DSP-ERADOS n=1014 多中心队列为核心依据**。

## 内容结构

| 章节 | 内容 |
|---|---|
| 一、总览表 | 18 条追踪方向（按证据等级 B → C+ → C → D 降序；17/18 为 2026-10-23 增补，置于表末但证据级别同为 B）：核心靶点、候选药物、当前阶段、证据级别 |
| 二、追踪方向详述 | 按证据等级降序：IL-1、**2.1a 糖皮质激素**、**2.1b 吗替麦考酚酯**、GSK3、POSTN–CCL3、抗纤维化、CAR-T、sEH–EET、Apremilast、基因治疗、NEK7、EGFR、cGAS–STING、NF-κB、PKNOX2、DSP-AS1、VIM–BECN1、GLP-1 |
| 三、机制通路整合视图 | DSP 单倍剂量不足后的五条「可打击轴线」（A 机械结构 / B 先天免疫 / C 纤维化放大 / D 桥粒蛋白补充 / E 代谢线粒体） |
| 四、优先级建议 | P0–P3 追踪资源分配参考（P0 新增：17 糖皮质激素 / 18 吗替麦考酚酯） |
| 五、参考文献 | [1]–[28]，含 IF / JCR 分区标注（[24]–[28] 为 2026-10-23 增补） |

## 证据级别定义

| 级别 | 含义 |
|---|---|
| A | 人体随机对照 |
| B | 人体病例或队列 + 体内机制 |
| C | 动物体内药效 |
| D | 体外或机制验证 |

## 版本管理

采用语义化版本号（SemVer）：

```
v1.0.0
 │ │ └─ 修订号（Patch）：勘误、错别字、数值修正
 │ └─── 次版本号（Minor）：新增追踪条目、补充文献内容
 └───── 主版本号（Major）：文档框架重组等结构性变更
```

当前版本：**v2.1.0** — 增补糖皮质激素（17 / 2.1a）与吗替麦考酚酯（18 / 2.1b）两条 B 级条目，含 DSP-ERADOS n=1014 队列证据

## 更新日志

| 日期 | 版本 | 提交 | 说明 |
|---|---|---|---|
| 2026-10-06 | v1.0.0 | `065870a` | 初始版本：16 条追踪条目 + POSTN–CCL3 新章节 + 勘误表 6 项执行 |
| 2026-10-06 | — | `13e3a5f` | 文件重命名为英文名 `DSP-Cardiomyopathy_Frontier-Therapeutics-Tracker.md` |
| 2026-10-06 | — | `f03443f` | 移除「数据勘误与待核实项」章节：6 项勘误已全部执行并固化于正文，勘误历史可查阅 git 标签 `v1.0.0` |
| 2026-10-06 | — | `dd2ad93` | POSTN–CCL3 独立章节并入正式详述（2.3 节）；总览表与详述章节按证据等级（B → C+ → C → D → 未定级）降序重排 |
| 2026-10-06 | **v2.0.0** | 本次提交 | 删除全部条目新增标志「★」（5 处）；结构性变更，打 v2.0.0 标签 |
| 2026-10-23 | **v2.1.0** | 本次提交 | 增补条目 17 糖皮质激素 / 18 吗替麦考酚酯（详述 2.1a / 2.1b）；核心证据为 *Circulation* (2025) DSP-ERADOS n=1014 队列〔24〕；新增参考文献 [24]–[28]；机制视图、优先级表同步更新 |

## 待跟进事项

- [ ] GLP-1：检索未见 DSP/ACM 特异性文献，已暂移出主动追踪（占位保留）
- [ ] **DSP-ERADOS 队列〔24〕未披露 63 例免疫抑制者的具体方案构成**（激素单用 / MMF 单用 / 联合）、剂量与疗程 —— 这是 17、18 两条最关键的证据缺口
- [ ] 参考文献 [3][5][6][7][8][9][10][11][12][16][22] 的 DOI 待补充
- [ ] 检索是否存在「免疫抑制 vs 观察等待」的前瞻性注册登记（2026 年后）
- [ ] IL-1 阻断与广谱免疫抑制的**头对头**证据（目前为零）
- [ ] Coderre 摘要〔28〕是否扩展为 Mayo 病例系列（Ackerman / Giudicessi 团队）
- [ ] 获取 ESC CardioGenomics Insights Vol.15《How to: treat patients with DSP-cardiomyopathy and hot myocarditis phases》全文（本次检索站点超时）
- [ ] LX2021（PKP2 基因治疗）载体与机制信息待核实（独立建档，见 2.8a 节）
- [ ] VENT-03 II 期顶线数据（预计 2026 年下半年）
- [ ] MRT-810 I 期初步数据（预计 2026 年上半年）
- [ ] Tideglusib NCT06174220 结果（预计 2027 年 3 月）

## 免责声明

本文档仅供研究追踪用途，内容均来自公开文献与企业公告，不构成任何诊疗建议。

---

*DSP Cardiomyopathy: Frontier Therapeutics Tracker · 从桥粒斑蛋白缺陷到新兴疗法*
