# Measurement System Analysis (MSA) – SMT Project

## Purpose
Before improving the SMT process, it is critical to ensure that the **measurement system** itself is accurate and reliable. If the system is inconsistent, the data will mislead us into thinking the process is defective when in fact the issue lies with measurement.

---

## Key Concepts

### 1. Repeatability
- Variation when the **same inspector** measures the same PCB multiple times using the same tool.
- **SMT Example:** Inspector A inspects the same PCB twice and records different defect classifications.

### 2. Reproducibility
- Variation when **different inspectors** measure the same PCB using the same tool.
- **SMT Example:** Inspector A calls it a solder bridge, Inspector B calls it a missing component.

### 3. Accuracy
- The difference between the **average observed measurement** and the **true value**.
- **SMT Example:** AOI machine consistently flags “missing components” on perfectly soldered PCBs due to calibration drift.

---

## Method – Gauge R&R Study
1. Select **10 PCBs** representing typical defect conditions (e.g., missing component, solder bridge, tombstoning).
2. Assign **3 inspectors** to inspect all 10 PCBs **twice each**.
3. Record results and compare against **AOI (Automated Optical Inspection)** machine output.
4. Calculate:
   - % Repeatability (consistency of each inspector).
   - % Reproducibility (agreement between inspectors).
   - % Accuracy (comparison to AOI/true standard).
   - % Total Measurement System Variation.

---

## Expected Outcomes
- AOI Machine: **High repeatability (>90%)** and stable accuracy if properly calibrated.
- Manual Inspectors: Some reproducibility issues (<80%) likely due to subjectivity.
- If **Measurement System Variation >10%**, corrective actions are required:
  - Recalibrate AOI machine.
  - Standardize inspection criteria.
  - Conduct inspector training.

---

## Conclusion
This MSA ensures that the **defect data collected during Measure phase is trustworthy**. Once validated, the results can be used for:
- Baseline performance calculations (FPY, DPMO, Sigma Level).
- Root cause analysis in the Analyze phase.
