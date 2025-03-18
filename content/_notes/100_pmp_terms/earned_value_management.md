---
title: Earned Value Management (EVM)
draft: false
tags:
  - project-management
  - pmp
  - earned-value-management
  - cost-management
  - performance-measurement
---

**Earned Value Management (EVM)** is a **methodology that integrates scope, schedule, cost, and resource measurements** to **assess project performance and progress**. It provides a structured approach to tracking project health using quantitative data.

## **Key Aspects of Earned Value Management**
- **Combines Scope, Schedule, and Cost** – Ensures all aspects of project performance are evaluated together.
- **Uses Key Performance Metrics** – Analyzes project efficiency through Earned Value (EV), Actual Cost (AC), and Planned Value (PV).
- **Enables Forecasting** – Helps predict cost overruns and schedule delays.
- **Supports Proactive Decision-Making** – Identifies deviations early for corrective actions.

## **Core EVM Metrics**
| **Metric**  | **Formula** | **Description** |
|------------|--------------------------------|------------------------------------------------|
| **Earned Value (EV)** | % Work Completed × BAC | Value of work performed based on budgeted cost. |
| **Planned Value (PV)** | Planned % of BAC | Budgeted cost for work scheduled at a given point. |
| **Actual Cost (AC)** | Sum of all incurred costs | Total cost spent on completed work. |
| **Cost Performance Index (CPI)** | EV ÷ AC | Measures cost efficiency (CPI > 1 is under budget). |
| **Schedule Performance Index (SPI)** | EV ÷ PV | Measures schedule efficiency (SPI > 1 is ahead of schedule). |

## **Mermaid Diagram: EVM Workflow**
```mermaid
graph LR;
    A["Project Plan"] -->|Planned Value (PV)| B["Work Scheduled"]
    B -->|Earned Value (EV)| C["Work Completed"]
    C -->|Actual Cost (AC)| D["Cost Incurred"]
    D --> E["Performance & Forecasting"]
```

## **Example Scenarios**

### **Software Development**
A project with a **BAC of \$500,000** is **40% complete** but has an **AC of \$250,000**.

- **EV = \$200,000**, **CPI = 0.8** (Over budget)
- **SPI = 1.0** (On schedule)

### **Construction Project**
A **bridge project planned for 6 months** is at **50% completion**, but only **40% of budgeted funds have been used**.

- **CPI = 1.25** (Under budget)
- **SPI = 0.8** (Behind schedule)

### **Marketing Campaign**
A **company planned to launch a campaign in 3 months** with a **budget of \$100,000**.  
At **month 2, 70% of the work is complete**, but **80% of the budget is spent**.

- **CPI = 0.875** (Over budget)
- **SPI = 1.16** (Ahead of schedule)

## **Why Earned Value Management Matters**
- **Provides Objective Performance Measurement** – Tracks real project progress.
- **Identifies Budget & Schedule Variances Early** – Helps avoid cost overruns.
- **Supports Forecasting & Risk Management** – Predicts future project trends.
- **Improves Stakeholder Confidence** – Offers data-driven insights.

See also: [[Earned Value (EV)]], [[Planned Value (PV)]], [[[[actual_cost|Actual Cost (AC)]], [[Cost Performance Index (CPI)]], [[Schedule Performance Index (SPI)]], [[Budget at Completion (BAC)]].
