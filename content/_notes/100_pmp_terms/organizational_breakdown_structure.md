---
title: Organizational Breakdown Structure (OBS)
draft: false
date: 2025-03-29
tags:
  - resource-management
  - organizational-structure
  - responsibility-mapping
  - project-governance
---

# Organizational Breakdown Structure (OBS)

An **Organizational Breakdown Structure (OBS)** is a **hierarchical representation of the project organization** that maps project activities to the **organizational units** responsible for performing them. It visually connects the **people or departments** in the organization to specific parts of the project work.

The OBS facilitates responsibility assignment and ensures alignment between the project structure and the organization's operational framework.

## Key Aspects of an OBS

- **Hierarchical Structure** – Shows reporting and responsibility relationships  
- **Activity Mapping** – Links work packages or activities to the performing unit  
- **Responsibility Tracking** – Used with RACI or other matrices for clarity  
- **Integration with WBS** – OBS complements WBS to show who does what

## Example Scenarios

- Assigning work packages in a large engineering project to department leads  
- Mapping project scope to regional business units for global execution  
- Creating input for a Responsibility Assignment Matrix (RAM)

## Mermaid Diagram: Example Organizational Breakdown Structure

```mermaid
flowchart LR
    ORG[Organization]
    ORG --> PMO[Project Management Office]
    ORG --> ENG[Engineering Department]
    ORG --> OPS[Operations Department]
    ENG --> ENG1[Design Team]
    ENG --> ENG2[Development Team]
    OPS --> OPS1[Logistics Team]
    OPS --> OPS2[Support Team]
    ENG1 --> WBS1[Work Package A]
    ENG2 --> WBS2[Work Package B]
    OPS1 --> WBS3[Work Package C]
    OPS2 --> WBS4[Work Package D]
```

## Why Organizational Breakdown Structure Matters

- Clarifies Accountability – Connects tasks to responsible organizational units
- Improves Oversight – Enables targeted management and resource allocation
- Supports Reporting – Facilitates communication across departments
- Enables Governance Alignment – Links project work to formal authority structures

See also: [[Resource Breakdown Structure]], [[Risk Breakdown Structure]], [[Work Breakdown Structure (WBS)]], [[Responsibility Assignment Matrix]], [[Project Governance]].