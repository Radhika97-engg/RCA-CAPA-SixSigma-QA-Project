# SIPOC Diagram – SMT First Pass Yield Improvement Project

The SIPOC diagram provides a high-level overview of the SMT line quality inspection and correction workflow targeted in this project. It maps out the critical flow from supplier to customer.

---

## Title: Reduce First-Pass Failure Rate in SMT Line from 14% to < 5% within 60 Days

---

### Process Start and End:
- **Start:** Start of SMT production (first piece inspection)
- **End:** Final quality clearance before delivery

---

## SIPOC Table

| **S - Supplier**            | **I - Inputs**                                 | **P - Process Steps**                                                                 | **O - Outputs**                                 | **C - Customer**               |
|-----------------------------|------------------------------------------------|----------------------------------------------------------------------------------------|--------------------------------------------------|--------------------------------|
| R&D Team                    | PCB Design Documents                           | Verify first piece (visual & schematic check)                                          | First-pass inspected board                      | Internal QA Team               |
| SMT Machine Operator        | SMT Machine Temperature Logs                   | Cross-check machine temp/program before run                                           | Inspection records of SMT output                | Production Supervisor          |
| Quality Inspector (PQC)     | Circuit Diagrams, Part Placement Sheets        | Inspect solder placement and component alignment                                      | List of defective boards                         | Final QC Team                  |
| Production Supervisor       | Component Datasheets                           | Report issues to R&D, change components if needed                                     | Escalation record / Change request               | Management / OEM Partner       |
| ESD Monitor System          | Line Voltage/Current Stability Logs            | Approve/correct component insertions by labor                                         | Approved/Rejected mount log                      | Client (Panasonic, Havells)    |

---

### Notes:
- This SIPOC diagram is part of the **Define Phase** of DMAIC.
- Outputs feed into next steps: **Root Cause Analysis**, **Pareto Analysis**, and **FMEA.**

---

