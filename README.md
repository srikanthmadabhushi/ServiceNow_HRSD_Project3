# ServiceNow_HRSD_Project3
# ServiceNow HRSD | Agentic AI Auto-Assignment Flow (Yokohama PDI)

## Overview
This project simulates an **Agentic AI** that analyzes HR case descriptions and automatically assigns them to the correct HR team.  
It mimics human reasoning — detecting keywords, deciding the best assignment group, and recording the AI's rationale.

## Flow Logic
1. **Trigger:** HR Case created or updated  
2. **If:** Short description contains "payroll", "benefit", "leave", or "access"  
3. **Then:** Update Assignment Group and AI Decision Notes accordingly  
4. **Else:** Assign to General HR Desk  

## Highlights
- Built in **ServiceNow Yokohama PDI** (no HR plugin needed)  
- Demonstrates **Agentic AI reasoning** using Flow Designer  
- Fully **no-code automation**  
- Explains each routing decision via **AI Decision Notes**

## Diagram
![Flow Diagram](Diagrams/Flow Diagram.png)

## Outcome
Cases are intelligently routed to the right HR teams, reducing manual effort and demonstrating how **AI-based decision logic** can transform HR operations.
