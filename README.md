# RPA in Community Pharmacy — Automated Credit Document Generation in Sifarma

> Master's Dissertation | MSc Information & Business Systems  
> Universidade Aberta & Instituto Superior Técnico | 2025

---

## Overview

This project implements and tests a **Robotic Process Automation (RPA)** 
solution for community pharmacies, targeting the generation of credit 
documents for nursing home patients in **Sifarma** — the most widely used 
pharmacy management software in Portugal.

The automation was developed and validated in a simulated Sifarma 
environment using **Microsoft Power Automate**, following the 
**Design Science Research (DSR)** methodology.

---

## The Problem

Community pharmacies serving nursing homes process credit documents 
manually — a repetitive, time-consuming task prone to human error.

The manual process required staff to:
- Navigate multiple Sifarma modules sequentially
- Manually filter and select client records
- Generate and export credit documents one by one
- Handle frequent interruptions and inconsistencies

This created operational inefficiencies, delays in billing cycles, 
and unnecessary cognitive load on pharmacy staff.

---

## The Solution

An automated RPA flow built with **Microsoft Power Automate** that:

- Logs into the Sifarma simulation environment automatically
- Navigates to the accounts receivable module
- Filters records by client and date range
- Generates credit documents automatically
- Exports results without manual intervention

---

## Methodology — Design Science Research (DSR)

| Phase | Description |
|-------|-------------|
| Problem Identification | Analysis of manual process inefficiencies |
| Requirements Definition | Functional & non-functional requirements gathering |
| Design | BPMN process modelling (manual vs. automated) |
| Development | Power Automate flow implementation |
| Demonstration | Testing in Sifarma simulation environment |
| Evaluation | Performance comparison & cost-benefit analysis |

---

## Process Modelling — BPMN

Two BPMN diagrams were developed to map the transformation:

- **Manual process** — multi-step human-driven workflow
- **Automated process** — RPA-driven equivalent with reduced touchpoints

---

## Key Findings

- Automation significantly reduced processing time per credit document
- Human error rate in document generation eliminated for automated steps
- Solution validated in simulated environment with consistent results
- Identified clear path for production implementation

---

## Limitations & Future Work

- Implemented in simulation environment (Sifarma demo), not production
- Future work should integrate AI-driven document validation
- Potential for expansion to other repetitive Sifarma workflows
- Integration with hospital pharmacy systems (GHAF) identified as 
  high-value extension

---

## Stack & Tools

![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=flat&logo=microsoft&logoColor=white)
![BPMN](https://img.shields.io/badge/BPMN-FF6B35?style=flat&logoColor=white)
![DSR](https://img.shields.io/badge/Design%20Science%20Research-412991?style=flat&logoColor=white)
![Sifarma](https://img.shields.io/badge/Sifarma-005A9C?style=flat&logoColor=white)

---

## Author

**Ângelo Saraiva**  
Pharmacy Technician (TSDT) | Digital Health & Intelligent Automation  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ângelosaraiva)

---

## License

Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
Free to use for academic and educational purposes with attribution.
