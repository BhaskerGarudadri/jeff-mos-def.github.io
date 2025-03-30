---
title: Phase Gate
draft: false
date: 2025-03-29
tags:
  - phase-management
  - project-lifecycle
  - governance
  - decision-point
---

# Phase Gate

A **Phase Gate** is a **formal review conducted at the end of a project phase** to decide whether to **proceed to the next phase**, **modify the current plan**, or **terminate the program or project**. It acts as a **control point** that ensures alignment with business objectives, stakeholder expectations, and project feasibility before moving forward.

Phase gates are integral to stage-based project governance models and provide an opportunity for structured evaluation, validation, and authorization.

## Key Characteristics

- **Decision-Oriented** – Results in a go, no-go, or revise decision  
- **Criteria-Based** – Requires deliverables, performance metrics, and approvals  
- **Formalized** – Part of the organization’s governance and methodology  
- **Used in All Project Types** – Common in waterfall, hybrid, and gated-agile approaches

## Example Scenarios

- A project completes the planning phase and enters a gate review to authorize execution  
- After design, stakeholders review scope, budget, and technical feasibility before development  
- At the end of deployment, a gate checks readiness before initiating operations and support

## Mermaid Diagram: Gantt with Phase Gates

```mermaid
gantt
    title Project Lifecycle with Phase Gates
    dateFormat  YYYY-MM-DD
    section Initiation
    Initiation Task       :done,  a1, 2025-01-01, 10d
    Phase Gate 1          :milestone, pg1, after a1, 0d
    section Planning
    Planning Tasks        :done,  a2, after pg1, 15d
    Phase Gate 2          :milestone, pg2, after a2, 0d
    section Execution
    Execution Tasks       :active, a3, after pg2, 30d
    Phase Gate 3          :milestone, pg3, after a3, 0d
    section Closeout
    Final Tasks           :a4, after pg3, 7d
    Final Review          :milestone, pg4, after a4, 0d
```

## Why Phase Gate Matters

- Strengthens Governance – Ensures each phase meets defined criteria before proceeding
- Reduces Risk – Prevents flawed work from moving forward unchecked
- Improves Stakeholder Confidence – Reinforces transparency and accountability
- Supports Better Decisions – Allows for reevaluation and reprioritization as needed

See also: [[Project Phase]], [[Project Lifecycle]], [[Stage-Gate Process]], [[Governance]], [[Milestone]].