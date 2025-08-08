# Data Collection Plan – SMT Process Optimization

## Objective
To capture accurate, representative, and stratified data on defects and process parameters in the SMT production line, enabling baseline performance measurement, root cause identification, and validation of improvement actions.

---

## 1. Why Are We Capturing This Data?
- Establish the baseline **First Pass Yield (FPY)** and defect rates.
- Identify the **most common and costly defects** in SMT PCB assemblies.
- Link defect patterns to specific **machines, processes, shifts, operators, or materials**.
- Ensure improvement actions in the **Improve phase** can be validated with before/after data.

---

## 2. What Data Will Be Captured?

### Performance Measures
- **Primary Output Metric:** First Pass Yield (FPY) = (Units Passed without Rework) / (Total Units Produced)
- **Defect Metrics:** Defects per million opportunities (DPMO), % defect rate per board, defect type frequency.
- **Process Metrics:** Placement accuracy, solder paste deposition volume, reflow oven profile parameters.

---

## 3. Operational Definitions

| Metric               | Definition                                                                 | Measurement Method                                           |
|----------------------|-----------------------------------------------------------------------------|--------------------------------------------------------------|
| First Pass Yield (FPY) | % of boards passing all quality checks without rework                      | Count good boards at final inspection / total boards produced |
| Defect Type          | Category of fault observed (e.g., missing component, tombstoning, solder bridge) | Inspector classification following defect code SOP           |
| Solder Paste Volume  | Volume in mm³ deposited per pad                                             | 3D SPI measurement                                           |
| Placement Accuracy   | Deviation in µm from nominal pad center                                     | Pick-and-place machine vision system logs                    |

---

## 4. Stratification Factors

| Factor  | Breakdown |
|---------|-----------|
| **What**  | Defect type (missing component, solder bridge, tombstoning, etc.) |
| **When**  | Shift (Morning, Afternoon, Night), Day of Week |
| **Where** | SMT Line #, Reflow Oven Zone, Placement Machine ID |
| **Who**   | Operator ID, QC Inspector ID |

---

## 5. Data Source & Location
- **Defect Data:** AOI (Automated Optical Inspection) logs, manual inspection logs.
- **Process Data:** SPI machine logs, pick-and-place logs, reflow oven temperature profile logs.
- **Location:** Local server database, QA department records.

---

## 6. How Will the Data Be Collected?
- **Defect Data:** Extract AOI & manual inspection results into Excel.
- **Process Parameters:** Export machine logs in CSV format.
- **Check Sheets:** Use standardized defect check sheets for manual entries.
- **Automation:** Prefer automated extraction where possible to reduce manual errors.

---

## 7. Who Will Collect the Data?
- **Primary:** QA inspectors (for visual/manual inspection logs).
- **Secondary:** Process engineers (for machine parameter logs).
- **Oversight:** Six Sigma project lead to ensure definitions are followed consistently.

---

## 8. When Will the Data Be Collected?
- **Defect Data:** At the end of each production shift.
- **Process Parameters:** At machine setup and hourly intervals.
- **Sampling Size:** 100% inspection for defect type logging during baseline study period (first 2 weeks).

---

## Sample Size & Duration
- **Sampling Plan:** Continuous sampling for 2 weeks to ensure sufficient defect occurrence for Pareto analysis.
- **Estimated Data Points:** ~500–800 boards/day × 14 days = ~7,000–11,000 records.

---

**Next Step:** Prepare the Excel Data Collection Sheet with pre-filled defect categories, stratification factor dropdowns, and automatic FPY & DPMO calculation.
