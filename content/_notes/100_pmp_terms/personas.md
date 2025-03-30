---
title: Personas
draft: false
date: 2025-03-29
tags:
  - user-centered-design
  - requirements
  - stakeholder-analysis
  - product-development
---

# Personas

**Personas** are **archetypal representations of end users** created to reflect common goals, behaviors, motivations, and characteristics. They are used in **user-centered design**, product development, and requirements gathering to ensure the needs of real users are considered throughout the project.

Each persona is based on research and patterns observed across similar users and helps align design decisions with actual user expectations.

## Key Characteristics

- **Research-Based** – Derived from user interviews, surveys, and data analysis  
- **Behavior-Focused** – Includes goals, pain points, preferences, and context  
- **Representative, Not Real** – Fictional but grounded in actual user insights  
- **Communication Tool** – Helps project teams empathize with and design for users

## Example Scenarios

- A mobile banking app project defines personas like "Busy Professional," "Budget-Conscious Student," and "Retired Investor"  
- A product team designing a healthcare portal uses personas to identify accessibility needs  
- An agile team prioritizes features based on persona-specific user stories

## Mermaid Diagram: Personas and Product Relevance

```mermaid
flowchart LR
    subgraph Personas
        P1[Persona: Tech-Savvy Professional]
        P2[Persona: Budget-Conscious Student]
        P3[Persona: Retired Investor]
    end

    subgraph Goals
        G1[Fast, seamless access to data]
        G2[Affordable features and plans]
        G3[Simple, accessible UI]
    end

    subgraph Features
        F1[Biometric Login]
        F2[Student Discount Tier]
        F3[Large Text Mode]
        F4[Portfolio Summary Dashboard]
    end

    P1 --> G1
    P2 --> G2
    P3 --> G3

    G1 --> F1
    G1 --> F4
    G2 --> F2
    G3 --> F3
    G3 --> F4
```

## Why Personas Matter

- Promote Empathy – Help teams understand user needs and behaviors
- Guide Requirements – Inform design, functionality, and content decisions
- Support Alignment – Keep teams focused on user value and relevance
- Improve Outcomes – Drive solutions that better serve the intended audience

See also: [[Stakeholder Analysis]], [[User Stories]], [[Requirements Documentation]], [[Product Backlog]], [[Customer Requirements]].