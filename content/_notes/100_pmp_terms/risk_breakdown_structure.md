---
title: Risk Breakdown Structure
draft: false
date: 2025-04-12
tags:
  - risk-management
  - breakdown-structure
  - planning
  - analysis
---

A **Risk Breakdown Structure** is a hierarchical representation of potential sources of risk.

It categorizes risks into structured levels, enabling project teams to systematically identify, group, and analyze risks by origin or area of impact. This structure enhances risk visibility and supports more focused risk planning and response efforts.

## Key Characteristics

- **Hierarchical Format** – Organizes risks from broad categories to specific sources  
- **Supports Risk Identification** – Encourages comprehensive review of risk areas  
- **Enables Risk Grouping** – Facilitates analysis and prioritization by category  
- **Tailorable** – Can be customized to fit the context of the project or organization  

## Example Scenarios

- Categorizing risks under technical, external, and organizational domains during planning  
- Analyzing risk exposure by source area to focus mitigation strategies  
- Using the structure to assign risk ownership by category  

## Example Risk Breakdown Structure

```mermaid
flowchart TD
    A[Risk Categories]
    
    A1[Technical Risks]
    A2[External Risks]
    A3[Organizational Risks]
    A4[Project Management Risks]

    A --> A1
    A --> A2
    A --> A3
    A --> A4

    A1a[Requirements Uncertainty]
    A1b[Technology Limitations]
    A1c[Design Complexity]
    A1 --> A1a
    A1 --> A1b
    A1 --> A1c

    A2a[Regulatory Changes]
    A2b[Market Fluctuation]
    A2c[Vendor Reliability]
    A2 --> A2a
    A2 --> A2b
    A2 --> A2c

    A3a[Resource Availability]
    A3b[Skill Gaps]
    A3c[Organizational Change]
    A3 --> A3a
    A3 --> A3b
    A3 --> A3c

    A4a[Scope Creep]
    A4b[Schedule Compression]
    A4c[Communication Breakdown]
    A4 --> A4a
    A4 --> A4b
    A4 --> A4c
```

## Role in Risk Management

- **Improves Risk Coverage** – Ensures diverse sources of risk are considered  
- **Enhances Communication** – Clarifies risk origin for stakeholders  
- **Guides Response Planning** – Supports targeted strategy development per risk group  
- **Feeds Into Risk Register** – Helps organize and maintain structured risk records  

See also: [[Organizational Breakdown Structure]], [[Resource Breakdown Structure]], [[Work Breakdown Structure]], [[Risk Register]], [[Risk Category]].
