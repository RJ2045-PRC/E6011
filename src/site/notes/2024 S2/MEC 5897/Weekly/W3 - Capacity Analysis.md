---
{"dg-publish":true,"permalink":"/2024 S2/MEC 5897/Weekly/W3 - Capacity Analysis/"}
---


## General
- 
- 
## Weekly objectives


## Pre-class
Watch these two videos on process time and motion study
1. [PUDDING PACKAGING](https://www.youtube.com/watch?v=n4FvB-O6rYw&t=2s)
2. [Scientific Management](https://www.youtube.com/watch?v=qUgKkBhZl9c)
Do a time and motion study for the process described in the shared word 


## Lecture
### Process time & Cycle time
>- Process time: a product spends on the process
>- Cycle time: average time between 2 products form the process
>>Single (one operator and one machine working for one part): $t_{process}=t_{cycle}$
>>Parallelly: $t_{process}/N = t_{cycle}$
>>Share resource: $t_{cycle}>t_{process}$
### **Throughput (TH)**
>- Or flow rate, average of a production processing unit per unit time
>- If considered **defects**, TH is the average quantity of good ones per unit time

>[!tip]- example
>
### Capacity 
>- Upper limit on the TH of process
>- releasing work into the system at/above **capacity** causes **unstable**
### Utilisation
>- if utilisation = 1, the workstation runs full capacity
>- usually utilisation is smaller than 1
>	- Utilisation = Planned ProductionT/ All time}
>	- Utilisation = $TH/capacity$

### Lead time & Flow time
>- lead time: measures from the start until its conclusion
>-  processing time + waiting time

>[!note] unscheduled factors impact lead time 
>- lack of raw materials
>- breakdown of transportation
>- labour shortage
>- natural disasters
### Capacity analysis
[[Week3_UnderstandingFlow_2023.pdf#page=13|Week3_UnderstandingFlow_2023, p.13]]
### **Little's Law**
$$
W_{0}=TH\times T_{p}$$

$$
TH=\frac{W_{0}}{T_{p}}
$$
$W_0$ : number average WIP parts
$T_p$ : process flow time



## Summary of equations








## Learning Objectives

- **Understand** basic concepts for manufacturing process analysis.
- **Identify** the bottleneck of a given production flow.
- **Calculate** the maximum production throughput (TH), resource capacity, and resource utilization for a given production flow.
- **Understand** the relationship between Work In Progress (WIP), Throughput (TH), and Flow Time through Little’s Law.
- **Apply** Gantt charts to analyze a production line.
- **Analyze** the major limit for further improvement of production throughput.

## Outline

### Basic Concepts:
    
- **Workstation/Resources**: Collection of one or more machines performing identical functions; process-oriented vs. product-oriented layout.
- **Routing and Job**: Sequence of workstations passed by a part, from raw materials to finished goods inventory.

- **Process Time**: Time a product spends in a process.
- **Cycle Time**: Average time between two products coming from the process.

- **Throughput (TH)**: Average production processing unit per time (e.g., parts per hour).

- **Capacity**: Upper limit on the throughput of a process.
- **Utilization**: Fraction of time a machine is used; generally less than 1.
- **Lead Time/Flow Time**: Time from the start to the conclusion of a process, including waiting time.
### Capacity Analysis:
    
-  Example analysis of a skateboard production line, highlighting concepts like resource capacity, process capacity, and utilization.
#### Little’s Law:
- Relationship between WIP, TH, and Process Time.
- Key formula: WIP=TH×Flow TimeWIP = TH \times Flow\ TimeWIP=TH×Flow Time
- TH has an upper limit equal to the bottleneck rate; increasing WIP after reaching this limit only increases process time.
#### Summary of Equations:
    
- **Flow Time** = Waiting time in inventory + Σ(flow time in each resource).
- **Resource Cycle Time** = Resource Flow Time / Batch Size.
- **Resource Capacity** = 1 / Resource Cycle Time.
- **Resource Utilization** = Resource TH / Resource Capacity.
- **Maximum Process Capacity** = min(Resource Capacity).
- **Bottleneck Rate** = Process TH_max = min(Resource Capacity).
- **Little’s Law**: $WIP=Flow Time×TH$

## Example Analysis

- Analysis of a skateboard production line shows how to calculate resource capacity, process capacity, and utilization.
- **Bottleneck**: The activity with the maximum resource utilization.

## Key Takeaways

- **Understanding bottlenecks** and how they limit production throughput is crucial for improving manufacturing processes.
- **Utilization** of resources needs to be optimized to avoid bottlenecks and maximize production efficiency.
- **Little's Law** provides a fundamental relationship between WIP, throughput, and flow time, which is essential for capacity analysis.
## Post-class

#### Question:
1. 

2. 


#### Question:




## To-do Activity
**Prompt:** 
>