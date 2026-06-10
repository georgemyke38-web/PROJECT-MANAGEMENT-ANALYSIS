# Project Management Portfolio

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Projects](https://img.shields.io/badge/Projects-99-blue)
![Total Cost](https://img.shields.io/badge/Total%20Cost-%24411.51M-orange)
![Total Benefit](https://img.shields.io/badge/Total%20Benefit-%24873.99M-success)

---

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Dataset Schema](#dataset-schema)
- [Key Performance Indicators](#key-performance-indicators)
- [Regional Analysis](#regional-analysis)
- [Departmental Analysis](#departmental-analysis)
- [Project Manager Leaderboard](#project-manager-leaderboard)
- [Status & Phase Breakdown](#status--phase-breakdown)
- [Recommendations](#recommendations)
- [How to Contribute](#how-to-contribute)
- [Contact](#contact)

---

## Overview

This repository documents a project management portfolio of **99 projects**
spanning **2021–2025** across four regions (North, South, East, West) and
five departments. The portfolio was analysed using Power BI and presented
by **Orji George Ifeanyi** on 25th March 2026.

| Metric                  | Value          |
|-------------------------|----------------|
| Total Projects          | 99             |
| Total Project Cost      | $411.51 Million|
| Total Project Benefit   | $873.99 Million|
| Benefit-to-Cost Ratio   | 2.12x          |
| Avg Completion Rate     | 87%            |
| Unique Project Managers | 7              |
| Date Range              | 2021 – 2025    |

---

## Repository Structure

```
project-management/
├── README.md
├── data/
│   ├── Project_Management_Dataset.csv     # 99 project records, 16 columns
│   └── processed/
├── dashboards/
│   └── new_first_presentation.pbix        # Power BI dashboard
├── presentations/
│   └── First_Project_Management_Presentation.pptx
└── docs/
    ├── project_documentation.docx
    └── recommendations.md
```

---

## Dataset Schema

| Column              | Type        | Description                        |
|---------------------|-------------|------------------------------------|
| Column1             | String      | Project name / title               |
| Project Description | String      | Full project narrative             |
| Project Type        | Categorical | Income Gen / Process Imp / etc.    |
| Project Manager     | String      | Assigned PM name                   |
| Region              | Categorical | North / South / East / West        |
| Department          | Categorical | Owning business unit               |
| Project Cost        | Numeric USD | Total project spend                |
| Project Benefit     | Numeric USD | Financial return generated         |
| Complexity          | Categorical | High / Medium / Low                |
| Status              | Categorical | Completed / In-Progress / etc.     |
| Completion%         | Percentage  | Delivery progress                  |
| Phase               | Categorical | Phase 1-Explore to Phase 5-Measure |
| Year                | Integer     | Calendar year (2021–2025)          |
| Month               | Integer     | Month number (1–12)                |
| Start Date          | Date        | Project start date                 |
| End Date            | Date        | Project end date                   |

---

## Key Performance Indicators

```
┌─────────────────────────────────────────────────────────┐
│  KPI SUMMARY (Power BI Dashboard + Dataset)             │
│─────────────────────────────────────────────────────────│
│  Total Project Cost       →  $411.51 Million            │
│  Total Project Benefit    →  $873.99 Million            │
│  Total Project Managers   →  99 (7 unique PMs)          │
│  Avg Completion %         →  87%                        │
│  Benefit / Cost Ratio     →  2.12x                      │
└─────────────────────────────────────────────────────────┘
```

---

## Regional Analysis

| Region | Projects | Total Cost   | Total Benefit | Completed |
|--------|----------|--------------|---------------|-----------|
| North  | 34       | $140.68M     | $300.88M      | 11        |
| West   | 24       | $99.19M      | $212.35M      | 9         |
| South  | 21       | $87.67M      | $184.73M      | 5         |
| East   | 20       | $83.97M      | $176.03M      | 5         |

> **North** leads in all metrics. **East** flagged for low benefit output.

---

## Departmental Analysis

| Department          | Projects | Total Cost | Avg Completion |
|---------------------|----------|------------|----------------|
| Supply Chain        | 24       | $106.64M   | 87.9%          |
| Warehouse           | 23       | $89.14M    | 87.5%          |
| Admin & BI          | 18       | $81.05M    | 88.2% ✅ Best  |
| eCommerce           | 20       | $78.60M    | 85.7%          |
| Sales and Marketing | 14       | $56.09M    | 85.1% ⚠ Low   |

---

## Project Manager Leaderboard

| Rank | Project Manager  | Total Benefit | Projects | Regions           |
|------|-----------------|---------------|----------|-------------------|
| 1    | Aleena Khan      | $160.83M      | 18       | All 4 regions     |
| 2    | Kamari Norris    | $133.91M      | ~14      | S, N, E, W        |
| 3    | Brenda Chandler  | $131.70M      | ~14      | W, N, E           |
| 4    | Yael Wilcox      | $131.25M      | ~14      | N, W, S           |
| 5    | Nyasia Hunter    | $122.22M      | ~14      | All 4 regions     |
| 6    | Deacon Delacruz  | $106.47M      | ~12      | E, S, W, N ⚠     |
| 7    | Jaylyn Mckenzie  | $87.61M       | ~9       | E, W              |

> ⚠ Deacon Delacruz identified for performance improvement in presentation.

---

## Status & Phase Breakdown

### By Status

```
Completed    ████████░░░░░░░░░░░░  30 (30.3%)
Cancelled    ███████░░░░░░░░░░░░░  27 (27.3%)  ⚠ High
In-Progress  ██████░░░░░░░░░░░░░░  25 (25.3%)
On-Hold      █████░░░░░░░░░░░░░░░  17 (17.2%)
```

### By Project Type

| Type                       | Count |
|----------------------------|-------|
| Income Generation          | 27    |
| Process Improvement        | 25    |
| Working Capital Improvement| 25    |
| Cost Reduction             | 22    |

### By Complexity

| Complexity | Count | % of Portfolio |
|------------|-------|----------------|
| High       | 40    | 40.4%          |
| Low        | 30    | 30.3%          |
| Medium     | 29    | 29.3%          |

---

## Recommendations

1. **East Region** — Shift project mix toward higher-benefit types.
2. **South Region** — Increase Sales department investment and project volume.
3. **Deacon Delacruz** — Mentorship programme; assign lower-complexity projects.
4. **Sales & Marketing Dept** — Resource augmentation and PM oversight needed.
5. **Cancellation Rate (27.3%)** — Introduce Phase 2 health-check gate.
6. **On-Hold Projects (17)** — 30-day review window: reactivate or close.
7. **High-Complexity Projects** — Mandate risk register + exec sponsor pre-Phase 3.

---

## How to Contribute

1. Clone the repository
   ```bash
   git clone https://github.com/org/project-management.git
   cd project-management
   ```

2. Create a feature branch
   ```bash
   git checkout -b feature/your-update
   ```

3. Commit your changes
   ```bash
   git add .
   git commit -m "docs: describe your change"
   ```

4. Push and open a Pull Request
   ```bash
   git push origin feature/your-update
   ```

---

## Contact

| Role              | Name                  |
|-------------------|-----------------------|
| Lead Analyst      | Orji George Ifeanyi   |
| Presentation Date | 25th March 2026       |
| Tool              | Power BI (PBIX)       |
| Dataset           | 99 rows · 16 columns  |

---
