---
title: Finish-to-Start (FS)
draft: false
tags:
  
  
  - schedule-management
  - dependencies
  - logical-relationships
---

**Finish-to-Start (FS)** is a **logical relationship** in which a **successor activity cannot start until a predecessor activity has finished**. This is the most common dependency type in project scheduling.

## **Key Aspects of Finish-to-Start**
- **Successor Activity Cannot Begin Until the Predecessor Is Complete** – Ensures sequential task execution.
- **Most Common Logical Relationship** – Frequently used in project planning and scheduling.
- **Helps Define Project Workflows** – Critical for scheduling dependencies and determining task order.

## **Finish-to-Start vs. Other Logical Relationships**
| **Dependency Type** | **Definition** | **Example** |
|--------------------|------------------------------------------------|--------------------------------|
| **Finish-to-Start (FS)** | Successor cannot start until predecessor finishes. | Construction painting cannot begin until wall installation is complete. |
| **Finish-to-Finish (FF)** | Successor cannot finish until predecessor finishes. | Proofreading cannot finish until writing is complete. |
| **Start-to-Start (SS)** | Successor cannot start until predecessor starts. | Framing a house cannot start until foundation pouring begins. |
| **Start-to-Finish (SF)** | Successor cannot finish until predecessor starts. | The night shift cannot finish until the next shift starts. |

## **Example Scenarios**

### **Software Development**
A **testing phase** cannot start until **development is fully completed**.

### **Construction Project**
A **roofing team** cannot start work until the **building structure is fully assembled**.

### **Marketing Campaign**
A **social media campaign** cannot begin until the **graphic design team completes the ad creatives**.

## **Mermaid Diagram: Finish-to-Start Dependency**
```mermaid
graph LR;
    A["Task A: Write Report"] -->|Must Finish Before| B["Task B: Submit Report"]
    B -->|Can Only Start After Task A is Done| C["Task C: Publish Report"]
```
## Why Finish-to-Start Matters

- Ensures Logical Task Progression – Maintains correct order of operations.
- Prevents Premature Execution of Tasks – Ensures dependencies are respected.
- Improves Project Scheduling – Helps define clear relationships between tasks.
- Essential for Critical Path Analysis – Used to determine the project’s longest path.

See also: [[Finish-to-Finish (FF)]], [[Start-to-Finish (SF)]], [[Start-to-Start (SS)]], [[Logical Relationship]], [[Schedule Network Diagram]].
