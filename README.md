# 📋 University Assignment Lifecycle — BPMN Process Improvement Project

> **Mapping, analysing, and redesigning a university's end-to-end assignment management process using BPMN 2.0**

---

## 📌 Project Overview

This project applies **Business Process Model and Notation (BPMN 2.0)** to map, analyse, and improve the full assignment lifecycle at a university — from assignment creation through to final grade appeal resolution.

The project delivers two complete sets of process diagrams:

- **AS-IS** — the current state process, documenting how the system actually operates across all stakeholders
- **TO-BE** — a redesigned future state introducing **AI-assisted automation** and **resource optimisation** to reduce bottlenecks and improve process efficiency

Both versions were developed independently, presented to academic staff, and received formal evaluation.

---

## 🗂️ Processes Mapped (5 Diagrams per Version)

| # | Process | Stakeholders Involved |
|---|---------|----------------------|
| 1 | Assignment Submission & Marking Lifecycle | Students, Canvas, Marker, School Admin |
| 2 | Extension Request & Evidence Assessment | Student, School Admin, AI (TO-BE) |
| 3 | Extension Decision & Outcome | Student, School Admin, Unit Coordinator, Canvas |
| 4 | Marking Process & Late Submission Handling | Marker, Canvas, PhD Students (TO-BE) |
| 5 | Grade Review, Formal Appeal & Investigation | Student, Marker, Canvas, School Admin, Investigation Officer, AI (TO-BE) |

---

## 🔄 AS-IS vs TO-BE: Key Improvements Designed

### Process 2 — Extension Assessment
| AS-IS | TO-BE |
|-------|-------|
| School Admin manually reviews every extension request and supporting evidence | **AI layer introduced** to pre-screen extension requests and assess evidence before escalating to School Admin — reducing manual review load |

### Process 4 — Marking Process
| AS-IS | TO-BE |
|-------|-------|
| Marking handled exclusively by contracted Markers | **PhD Students introduced** as an additional marking resource via a structured job offer / accept / reject workflow — reducing bottleneck and improving scalability |

### Process 5 — Grade Review & Appeals
| AS-IS | TO-BE |
|-------|-------|
| Investigation Officer manually reviews all formal appeal documents | **AI layer added** to assist investigation document analysis — supporting faster, more consistent formal appeal outcomes |

---

## 🛠️ Tools Used

- **Lucidchart** — primary diagram design and collaboration
- **Microsoft Visio** — diagram refinement and formatting
- **BPMN 2.0 notation** — pools, lanes, gateways (exclusive, parallel, inclusive), subprocesses, intermediate timer events, message flows

---

## 📁 Repository Contents

```
📂 AS-IS/
   └── AS_IS_v1_0.pdf         # Current state — all 5 process diagrams

📂 TO-BE/
   └── TO_BE_v0_1.pdf         # Future state — all 5 redesigned process diagrams

📄 README.md
```

---

## 💡 BPMN Concepts Demonstrated

- **Swimlane diagrams** across multiple stakeholder pools (up to 6 concurrent lanes)
- **Exclusive gateways (X)** for decision branching — e.g. extension approve/deny, late submission check, satisfied/unsatisfied student
- **Parallel gateways (+)** for concurrent process flows — e.g. simultaneous notifications to multiple stakeholders
- **Subprocess markers** for collapsed process references (extension process, marking process)
- **Intermediate timer events** — e.g. marking triggered "after due date," results released "after 2 weeks from due date"
- **Message flows** between stakeholder lanes — e.g. email notifications, form submissions
- **End states** — multiple named termination points per process (results accepted, extension complete, formal appeal dismissed, formal appeal complete)

---

## 🎯 Business Analysis Skills Demonstrated

- **AS-IS process documentation** — accurately capturing real-world workflows across multiple stakeholders without simplification
- **Gap analysis** — identifying bottlenecks (manual extension screening, marking resource constraints, lengthy appeals)
- **TO-BE process redesign** — proposing practical, technology-augmented improvements with clear rationale
- **Stakeholder mapping** — managing process flows across 6 concurrent stakeholder types
- **AI integration planning** — identifying where AI automation creates measurable process value without removing human decision authority
- **Structured presentation** — diagrams developed and presented to academic staff for formal evaluation

---

## 📖 Background

This project was completed as part of the **Master of Business Analytics** program at **Edith Cowan University, Perth (2024–2025)**. The assignment lifecycle was selected as the process domain due to its complexity, multi-stakeholder nature, and clear opportunities for efficiency improvement — characteristics common in real-world BA engagements.

---

## 👩‍💼 Author

**Yashasvi Sharma**
Master of Business Analytics — Edith Cowan University (2025)
[LinkedIn](https://www.linkedin.com/in/yashasha) · [GitHub](https://github.com/Yashisha)

