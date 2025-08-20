# Sampling Strategy – RCA-CAPA Six Sigma QA Project

## Purpose
Sampling allows us to draw statistically valid conclusions about SMT line performance without measuring every single unit. It balances cost, time, and data quality, ensuring we capture variation in a practical manner.

---

## Sampling Techniques (Overview)

### 1. Simple Random Sampling
- **Definition**: Every unit has an equal chance of selection.
- **Example**: Randomly pick 50 boards from a lot of 5,000 for inspection.

### 2. Stratified Random Sampling
- **Definition**: Divide the population into groups (strata) and sample from each.
- **Example**: Sample 20 boards from each of the 3 shifts to capture shift-level variation.

### 3. Systematic Sampling
- **Definition**: Select every *nth* unit.
- **Example**: Inspect every 25th board from the SMT line for inline monitoring.

### 4. Cluster Sampling
- **Definition**: Select entire groups (clusters) at intervals.
- **Example**: Audit all boards produced during 2:00–2:30 PM, then again at 6:00–6:30 PM.

---

## Project-Specific Approach

For this project (reducing SMT first-pass failure rate):

- **Primary Method → Stratified Random Sampling**
  - Ensures we capture process variation across **shifts, operators, and machines**.
  - Example: From each shift, randomly pick 20 boards daily (total = 60 boards/day).

- **Secondary Method → Systematic Sampling**
  - Useful for **real-time control** and spotting trends.
  - Example: Inspect every 25th board on the line.

---

## Benefits of the Chosen Strategy
- **Comprehensive coverage** of potential variation sources (shift/operator/machine).
- **Balanced workload** for inspectors.
- **Ease of execution** for inline monitoring.
- **Supports baseline performance analysis** and later Control Phase monitoring.

---

This strategy will guide both **baseline data collection (Measure phase)** and **ongoing monitoring (Control phase)**.
