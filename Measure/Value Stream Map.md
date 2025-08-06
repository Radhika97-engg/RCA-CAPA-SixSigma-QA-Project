# Value Stream Map – SMT Production Line  
**Project Goal:** Reduce First Pass Failure in SMT assembly  
**Phase:** Measure  
**Tool:** Value Stream Mapping (VSM)  

---

## Step 1: Start & End Points  
- **Start Point:** Component loading on SMT machine  
- **End Point:** Final QA pass and transfer to packaging  

---

## Step 2: Process Steps + Data Boxes  

| Step No. | Process Step           | Operators | Cycle Time (C/T) | Changeover Time (C/O) | Uptime (%) | Yield (%) |
|----------|------------------------|-----------|------------------|------------------------|------------|-----------|
| 1        | Component Loading       | 1         | 5 min            | 10 min                 | 98%        | 100%      |
| 2        | Solder Paste Printing   | 1         | 3 min            | 5 min                  | 95%        | 97%       |
| 3        | Pick and Place          | 1         | 4 min            | 8 min                  | 97%        | 96%       |
| 4        | Reflow Soldering        | 1         | 6 min            | 7 min                  | 96%        | 92%       |
| 5        | Initial QA Inspection   | 2         | 7 min            | 0 min                  | 90%        | 88%       |
| 6        | Manual Mounting         | 2         | 8 min            | 5 min                  | 93%        | 95%       |
| 7        | Final QA + Testing      | 2         | 10 min           | 0 min                  | 90%        | 85%       |

---

## Step 3: Inventory and Wait Times  

| Between Steps              | WIP (Parts) | Wait Time |
|---------------------------|-------------|-----------|
| Component Load → Printing | 10          | 2 min     |
| Printing → Pick & Place   | 15          | 3 min     |
| Pick & Place → Reflow     | 12          | 2 min     |
| Reflow → Initial QA       | 20          | 5 min     |
| QA → Manual Mounting      | 8           | 2 min     |
| Mounting → Final QA       | 10          | 3 min     |

---

## Step 4: Information Flow  

- **Production Control:** Supervisor enters daily production targets on a whiteboard & ERP  
- **Manual Communication:**  
  - Daily morning checklist in paper format  
  - Real-time issues are verbally escalated  
- **Digital Communication:**  
  - Yield data logged in Excel  
  - QA results recorded manually & shared via email  

---

## Step 5: Timeline Analysis  

| Segment                    | Type                   | Time (min) |
|---------------------------|------------------------|------------|
| Component Loading         | Value Added (VA)       | 5          |
| Solder Paste Printing     | Value Added (VA)       | 3          |
| Pick and Place            | Value Added (VA)       | 4          |
| Reflow Soldering          | Value Added (VA)       | 6          |
| Initial QA                | Essential Non-VA (ENVA)| 7          |
| Manual Mounting           | Value Added (VA)       | 8          |
| Final QA + Testing        | Essential Non-VA (ENVA)| 10         |
| **Wait & Inventory Time** | Non-Value Added (NVA)  | 17         |

---

## Summary  

- **Total Cycle Time:** 60 minutes  
- **Total Value-Added Time:** 26 minutes  
- **Total Non-Value Added Time:** 17 minutes  
- **Process Cycle Efficiency (PCE):**  
  \> PCE = (VA Time / Total Cycle Time) = 26 / 60 = **43.3%**

---

> This VSM will guide us during **Root Cause Analysis (RCA)** and **Improvement Planning**, especially in areas like:  
> QA inspection delays  
> High rework loops  
> Inventory buildup after reflow

