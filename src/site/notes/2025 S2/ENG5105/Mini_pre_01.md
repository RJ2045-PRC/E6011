---
{"dg-publish":true,"permalink":"/2025 S2/ENG5105/Mini_pre_01/"}
---

## OBJ
- **处理对象**：二级出水（BOD 18 mg/L，TSS 25 mg/L，浊度 5 NTU，pH 7.8，电导 1400 µS/cm，NH3-N 8 mg/L，TN 15 mg/L，TP 3 mg/L）
- **产能**：10,000 m³/d；**目标回收率**：≥75%；**进水温度**：20 °C
- **Class A 再生水硬性指标**：BOD <10 mg/L；TSS <5 mg/L；浊度 <2 NTU；pH 6–9
- **健康指标（LRC/LRV）**：bacteria ≥6-log，virus ≥7-log，原生动物 ≥6-log（相对于原污水）
- **本次对比的 5 种膜**：
	- PES membrane ([Microlab Scientific](https://www.microlabscientific.com/pes-membrane-product/)) with a pore size of 0.45 um 
	- PES membrane ([Microlab Scientific](https://www.microlabscientific.com/pes-membrane-product/)) with a pore size of 0.22 um
	- Hydrophobic PVDF ([MDI- SVF](https://mdimembrane.com/product/products/transfer-membranes/svf-pvdf-membrane/)) with a pore size of 0.2 um
	- Hydrophilic PVDF ([MDI-HVF](https://mdimembrane.com/product/products/disc-filters/disc-filters-small/pvdf-membrane-disc-filter-type-hvf/)) with a pore size of 0.2 um
	- Teflon (MDI-TF2) with a pore size of 0.2 um

## Draft Design consider
- 采用**微滤/超滤作颗粒与微生物屏障**，将 TSS、浊度降至消毒可稳定达标的水平（浊度最好 ≤0.5 NTU）。
- **末端消毒（UV±余氯）******提供主要病毒/细菌/原生动物的******对数去除学分（LRC）**，满足 6/7/6 的组合要求。
- 预处理视二级出水波动设置：混凝/絮凝（可选）→ 保安过滤（0.45 µm）→ 主膜（0.2–0.22 µm）
Pre-process: 0.45 um PES (optional)
Filtrition: 0.2 um Hydrophilic PVDF
Post-process: UV/ Residual Chlorine (for **6/7/6** LRV)
## 1. PES 0.45 µm

**定位**：前置“保安”滤层，削减 TSS、胶体与大颗粒，稳定后续主膜压差与通量。
- **优点**：
    - 天然亲水、低蛋白吸附；水通量高、压降低。
    - 成本低、易更换，适合做一次性（sacrificial）前置层。
- **限制**：
    - 孔径偏大，独立使用难以保证 <2 NTU 与足够病原体去除；对病毒无有效屏障。 **建议角色**：并联/串联为**可旁路**的预滤单元；高峰期或进水波动时投用。
## 1. PES 0.22 µm

**定位**：主膜后“抛光”层或与主膜并列作为双层屏障中的第二层。
- **优点**：
    - 孔径更小，对细菌与原生动物具较高物理截留；维持低浊度出水。
    - 亲水特性带来较好的初期通量。
- **限制**：
    - 相对 PVDF，对高强度氧化清洗（NaOCl）耐受性较弱；需谨慎控制化学清洗条件。 **建议角色**：**主膜后的抛光/冗余屏障**，在高风险用途或更严苛浊度控制下启用。
## 3. PVDF 0.2 µm (**Hydrophobic** MDI‑SVF)

**定位**：材料学上更适合**气体/溶剂**过滤。若用于水相需酒精预润湿，运行维护复杂。
- **优点**：
    - PVDF 基材强度高、耐化学性佳，耐较高次氯酸钠浓度清洗。
- **限制**：
    - 疏水膜**不自润湿**，需要 IPA/乙醇预润湿和严格避免干燥再润湿流程；对污水再生不友好。 **建议角色**：不作为本项目水相主屏障；可作**通气/排气**或化学体系专用过滤。
## 4. PVDF 0.2 µm (**Hydrophilic** MDI‑HVF)

**定位**：**主力微滤屏障（首选）**，将浊度与悬浮物稳定压低，保障终端消毒可获得足够 LRC。
- **优点**：
    - 亲水改性，易润湿、起步通量稳定；PVDF 机械强、耐氧化（可承受较高 NaOCl 清洗）。
    - 工业成熟度高，市场上有大量空纤/中空纤维模块可选，便于放大与完整性监测。
- **限制**：
    - 仍对病毒**缺乏直接尺寸排阻**，需与 UV/余氯形成**多重屏障**。 **建议角色**：**一级主膜**；与 0.45 µm PES 形成“预滤 + 主滤”的低压膜组合。
## 5. Teflon 0.2 µm（MDI‑TF2）
**定位**：强疏水、耐溶剂与强腐蚀环境；典型用于**气体灭菌过滤/强腐蚀液体**。
- **优点**：
    - 极优化学稳定性（pH 1–14、溶剂耐受），适合苛刻化学场景。
- **限制**：
    - 水相同样需**预润湿**；设备与运维对水处理不经济。 **建议角色**：不作为本项目的水相主屏障；可用于**臭氧/空气**管线端的**疏水性灭菌透气**。

