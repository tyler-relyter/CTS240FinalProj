# HQ Build-Out: Project Management Simulation

## Overview

**Project Management Simulation** — a hands-on, scenario-based exercise designed for students learning project management fundamentals using **Microsoft Project**. Students take on the role of Lead Project Manager overseeing a full office relocation and build-out, from lease signing through move-in.

🌐 **Live Site:** [https://tyler-relyter.github.io/CTS240FinalProj/](https://tyler-relyter.github.io/CTS240FinalProj/)

---

## Scenario

Your company is relocating to a new 10,000 sq ft facility at **404 Innovation Drive**. The current lease expires **December 31st**, and the new space must be fully built out, furnished, and operational before staff return on **January 4th**.

As Lead Project Manager, you are responsible for building a complete master schedule that reflects real-world constraints: vendor lead times, resource unavailability windows, holiday calendars, and task dependencies extracted from internal email communications.

---

## Learning Objectives

- Build a **Work Breakdown Structure (WBS)** with logical phases
- Establish **task dependencies** from unstructured sources (email chains)
- Configure a **project calendar** with holidays and non-working periods
- Assign **resources** to tasks using an hourly rate / fixed-cost model
- Resolve **resource overallocation** without missing the project deadline

---

## Project Phases

| Phase | Description |
|---|---|
| **Planning** | Lease signing, vendor sourcing, order placement |
| **Construction** | Drywall, painting, electrical, HVAC |
| **IT Infrastructure** | CAT6 cabling, server rack installation, workstation deployment |
| **Move-In** | Furniture assembly, equipment setup, final sign-off |

---

## Key Constraints

- **Working Hours:** Monday–Friday, 8:00 AM – 5:00 PM (1-hour lunch)
- **Holidays:**
  - Thanksgiving Day (Nov 26)
  - Black Friday (Nov 27)
  - Company Winter Break (Dec 24 – Jan 1)
- **IT Team Blackout:** November 10–14 (mandatory off-site security training — no IT tasks may be scheduled during this window)
- **Furniture Lead Time:** 15-day delivery window after purchase order is placed; order cannot be placed until lease is signed

---

## Files Included

| File | Description |
|---|---|
| `index.html` | Main project intake portal (the simulation landing page) |
| `Canvas_Student_Guide.html` | Student survival guide with tips and instructions |
| `HQ_BuildOut_Tasks.csv` | Raw task data — durations, phases, and resource assignments |
| `HQ_BuildOut_Resources.csv` | Resource data — roles, standard hourly rates, and fixed costs |

---

## Deliverables

Students must submit a completed `.mpp` (Microsoft Project) file containing:

1. A properly indented **Work Breakdown Structure** organized into the four project phases
2. All **task durations and predecessors** correctly mapped from the email chain
3. **Project Calendar** updated with all holidays and the IT blackout window
4. **Resource Sheet** populated with all roles, standard rates, and cost/use values
5. Resources accurately **assigned to tasks** without overallocation

---

## Getting Started

1. Visit the live site: [https://tyler-relyter.github.io/CTS240FinalProj/](https://tyler-relyter.github.io/CTS240FinalProj/)
2. Read the **Student Survival Guide** for tips on navigating the simulation
3. Download `HQ_BuildOut_Tasks.csv` and `HQ_BuildOut_Resources.csv`
4. Open Microsoft Project and build your master schedule using the provided data
5. Submit your `.mpp` file per your instructor's directions

---

## Deployment

This site is hosted on **GitHub Pages** and automatically deploys on every push to the `main` branch via the included GitHub Actions workflow.
