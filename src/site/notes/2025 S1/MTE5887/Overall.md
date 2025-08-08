---
{"dg-publish":true,"permalink":"/2025 S1/MTE5887/Overall/"}
---

[[1 FDM\|1 FDM]]
[[2 SLA\|2 SLA]]
[[2 SLS\|2 SLS]]
## Outline
#### **Polymers**
[[2025 S1/MTE5887/Notes/Polymers-mock\|Polymers-mock]]
#### Material extrusion w2 w3
[[2025 S1/MTE5887/Notes/FDM-1\|FDM-1]]
[[2025 S1/MTE5887/Notes/FDM-2\|FDM-2]]
[[2025 S1/MTE5887/Notes/FDM-3\|FDM-3]]
[[2025 S1/MTE5887/Notes/Large Scale FDM\|Large Scale FDM]]
##### Summary: Extrusion based systems
**Advantages**
- FDM is the most **accessible** AM process **容易**
- Constantly increasing number of thermoplastic materials and some composites **热塑材料众多**
- Stiffness and strength comparable to injection molding **与传统注塑强度相当**
- Attractive for large-scale manufacturing **适合大规模部署**
**Disadvantages**
- Require post-processing due to **rough surface finish** **需要后处理**
- **Low build speed** compared to SLA and SLM **构建速度慢**
- Resolution **分辨率低**
- Accuracy **精度低**
#### Introduction to polymers w4
[[Polymer-intro\|Polymer-intro]]
[[PE\|PE]] - 聚乙烯
#### Thermoplastics used in FDM w5
[[2025 S1/MTE5887/Notes/Craze\|Craze]]
[[2025 S1/MTE5887/Notes/应力弛豫+蠕变\|应力弛豫+蠕变]]

[[ABS  HIPS\|ABS  HIPS]]
[[PLA, Nylon  TPE\|PLA, Nylon  TPE]]
[[W5 Q&A\|W5 Q&A]]
####  Stereolithography (SLA)
Polymers for Stereolithography (SLA) w6
W6 Q&A
SLA Process w7
#### Selective Laser Sintering w7
##### [[2025 S1/MTE5887/Notes/SLS Process 1\|SLS Process 1]] w7
1. **Process**
2. 所用材料的**Physical properties** + **Thermal properties**
##### [[2025 S1/MTE5887/SLS Process 2\|SLS Process 2]] w7
1. 与LPBF类似
W7 Q&A
Process Control and Design for Selective Laser Sintering w9
#### Bio & Composites Printing w8
3d Bioprinting
3d Composites Printing
#### Ink-Jetting Printing w10
[[2025 S1/MTE5887/Notes/Material Jetting\|Material Jetting]]
[[2025 S1/MTE5887/Notes/Binder Jetting\|Binder Jetting]]
1. Ink-Jetting 原理
2. Ink-Jetting 打印头 (种类和原理)
3. Material Jetting (材料，应用)

4. BJ 流程-后处理过程-材料-应用
#### Muti-Material Printing
![Pasted image 20250611004834.png|316](/img/user/Attachments/ScreenShot/Pasted%20image%2020250611004834.png)

[[2025 S1/MTE5887/Notes/Muti-material 3d-printing\|Muti-material 3d-printing]]

#### 4D Printing w11
[[2025 S1/MTE5887/Notes/4D-Printing\|4D-Printing]]
1. 智能材料概述
2. **形状记忆合金**SMA+**形状记忆聚合物**SMP
3. 多材料4d打印
4. 4D打印方式：直接打印和间接打印
5. 局限性和机遇

#### DfAM: Design for AM w11
[[2025 S1/MTE5887/Notes/Value Propositions and Design for AM\|Value Propositions and Design for AM]]
1. 实用主义优化
2. 限制主义优化


## 7种 AM 选择
[[2025 S1/MTE5887/Notes/7种 主要AM工艺\|7种 主要AM工艺]] - 选择树
## Decision Table

| Process过程                        | Materials材料                   | Typical Applications典型应用            | Post-processing后处理                          | Advantages优势                          | Disadvantages弊                          |
| -------------------------------- | ----------------------------- | ----------------------------------- | ------------------------------------------- | ------------------------------------- | --------------------------------------- |
| Vat Photopolymerization还原光聚合     | Photopolymer resin光敏树脂        | Prototypes, dental, jewelry原型、牙科、珠宝 | Wash, UV cure, support removal洗涤、UV 固化、去除支撑 | High detail, smooth高细节，流畅             | Brittle, limited function脆性，功能受限        |
| Material Jetting材料喷射             | Photopolymer, wax光敏聚合物、蜡      | Prototypes, medical models原型、医疗模型   | Support removal, cure支撑物去除、固化               | Multi-material/color, detail多材质/颜色、细节 | Cost, fragile, post-process成本、易碎、后处理    |
| Binder Jetting粘结剂喷射              | Metal, ceramic, sand金属、陶瓷、沙子  | Metal parts, molds, color金属零件、模具、颜色 | Debinding, sinter, cure脱脂、烧结、固化             | Fast, large, cheap, color快速、大、便宜、彩色   | Weak green parts, post-process薄弱的生坯，后处理 |
| Material Extrusion材料挤出           | Thermoplastics热塑性 塑料          | Functional parts, jigs功能部件、夹具       | Support removal, finish支撑移除、整理              | Cheap, easy, robust便宜、简单、坚固           | Layer lines, anisotropy图层线、各向异性         |
| Sheet Lamination片材层压             | Paper, polymer, metal纸、聚合物、金属 | Models, casting patterns模型、铸造模型     | Trimming, finish修剪、整理                       | Fast, low cost, big parts快速、低成本、大型零件  | Low detail, adhesive limits低细节，胶粘剂极限    |
| Powder Bed Fusion粉末床熔融           | Metal, polymer金属、聚合物          | Aerospace, medical, tools航空航天、医疗、工具 | Powder removal, finish除粉、表面处理               | Strong, dense, complex坚固、致密、复杂        | Expensive, rough, post-process昂贵、粗糙、后处理 |
| Directed Energy Deposition定向能量沉积 | Metal wire/powder金属丝/粉末       | Repair, large structures维修，大型结构     | Machining, finish机加工、精加工                    | Big, repair, graded大、修复、分级            | Low detail, rough, costly细节少、粗糙、成本高     |
