# XY Matrix – SMT Production Line Project

## Objective
To identify the most critical input variables (X’s) affecting first-pass yield and inspection defect rates in the SMT line.

---

## Output Variables (Y's) and Importance

| No. | Output Variable                            | Importance (1–10) |
|-----|---------------------------------------------|-------------------|
| 1   | First Pass Yield > 95%                      | 10                |
| 2   | Component Placement Accuracy > 98%          | 9                 |
| 3   | Inspection Defects per Lot < 2              | 8                 |

---

## Input Variables (X's)

| No. | Input Variable                                                                 |
|-----|---------------------------------------------------------------------------------|
| 1   | Solder paste application quality (alignment, thickness)                        |
| 2   | PCB loading orientation                                                        |
| 3   | Pick and place machine calibration accuracy                                    |
| 4   | Stencil cleanliness and maintenance                                            |
| 5   | Operator training level (SMT setup)                                            |
| 6   | Reflow oven temperature profile consistency                                    |
| 7   | Incoming component quality (as per IQC reports)                                |
| 8   | AOI inspection program alignment with latest BOM/ECN changes                   |

---

## XY Matrix Scoring Table

| No. | X Variable                                      | FPY > 95% (10) | Accuracy > 98% (9) | Defects < 2 (8) | Total | % Impact |
|-----|--------------------------------------------------|----------------|---------------------|------------------|--------|----------|
| 1   | Solder paste application                         |       9        |          9          |        9         | 252    |   17%    |
| 2   | PCB loading orientation                          |       9        |          9          |        3         | 219    |   15%    |
| 3   | Pick & place calibration                         |       9        |          9          |        9         | 252    |   17%    |
| 4   | Stencil maintenance                              |       9        |          6          |        6         | 210    |   14%    |
| 5   | Operator training                                |       6        |          6          |        6         | 174    |   12%    |
| 6   | Reflow oven profile consistency                  |       6        |          6          |        6         | 174    |   12%    |
| 7   | Incoming component quality                       |       6        |          6          |        6         | 174    |   12%    |
| 8   | AOI program alignment                            |       3        |          6          |        6         | 138    |    9%    |

**Total Weighted Score: 1593**

---

## Insight

- **Top 3 X’s to investigate in Measure phase**:
  1. Solder paste application
  2. Pick & place calibration
  3. PCB loading orientation

These inputs will guide **data collection, capability analysis, and RCA** steps.

