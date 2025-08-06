# High-Level "As-Is" Process Map – SMT Production Line  
 

---

## Objective  
To capture the current-state workflow from component placement to QA inspection and defect documentation in the SMT line, highlighting inefficiencies and rework loops.

---

## Process Flow

| Step | Description                                                                 | Symbol      |
|------|-----------------------------------------------------------------------------|-------------|
| 1️⃣   | **Start** – Begin SMT production cycle                                     | ⬤ Start     |
| 2️⃣   | **Component Loading** – Feed reels into SMT machine                        | ▭ Process   |
| 3️⃣   | **Program Machine Setup** – Load appropriate profile (temperature, layout) | ▭ Process   |
| 4️⃣   | **Solder Paste Printing** – Apply solder paste to PCB                      | ▭ Process   |
| 5️⃣   | **Pick and Place** – Components placed on PCBs                             | ▭ Process   |
| 6️⃣   | **Reflow Soldering** – PCB passed through controlled heating zones         | ▭ Process   |
| 7️⃣   | **Initial QA Inspection** – Visual and AOI check after reflow              | ▭ Process   |
| 8️⃣   | **Defect Detected?**                                                       | ◆ Decision  |
| 9️⃣   | If **Yes** → Document in FPF log and isolate PCB                           | 🔁 Loop     |
| 🔟   | If **No** → Forward to manual mounting line                                 | ▭ Process   |
| 1️⃣1️⃣ | **Manual Mounting** – Insert through-hole components (if any)              | ▭ Process   |
| 1️⃣2️⃣ | **Final QA Testing** – Functionality, burn-in, and voltage check           | ▭ Process   |
| 1️⃣3️⃣ | **Defect Found in Final QA?**                                              | ◆ Decision  |
| 1️⃣4️⃣ | If **Yes** → Trigger RCA, mark for rework                                  | 🔁 Loop     |
| 1️⃣5️⃣ | If **No** → PCB marked as passed and sent for packing                      | ▭ Process   |
|       | **End** – Product ready for delivery                                        | ⬤ End       |

---

## Legend  

| Symbol    | Meaning                                |
|-----------|----------------------------------------|
| ⬤         | Start/End of Process                    |
| ▭         | Activity or Process Step                |
| ◆         | Decision Point (Yes/No)                 |
| 🔁         | Feedback/Rework Loop                   |

---

## Observations  
- Delays often occur in the **QA inspection** phase due to unclear failure codes and lack of real-time alerts.  
- Multiple rework loops affect first-pass yield.  
- Key wastes observed: **Defects, Waiting, Overprocessing, and Non-utilized skills** during RCA.  

---

> Next: Use this map as the base for your **Value Stream Map** and **Root Cause tools** like Fishbone and 5-Whys.
