# 📋 Project Management & Task Management Tools

This document explains the purpose of the most popular **free** project management tools used in engineering organizations.

---

# Which Tool Should I Choose?

| Tool | Best For | Project Type |
|------|----------|--------------|
| ⭐ OpenProject | Complete engineering project management | Mechanical + Electrical + Embedded + Software |
| ⭐ Plane | Agile software development | Embedded & Software Teams |
| ⭐ Taiga | Scrum & Kanban | Small Agile Teams |
| ⭐ Redmine | Issue & Bug Tracking | Support & Maintenance |

---

# 1. OpenProject

## Purpose

OpenProject is designed to manage **entire engineering projects**.

Think of it as the **master project plan**.

It is commonly used by:

- Systems Engineers
- Project Managers
- Engineering Managers

---

## Main Features

- ✅ Gantt Charts
- ✅ Work Breakdown Structure (WBS)
- ✅ Scheduling
- ✅ Milestones
- ✅ Dependencies
- ✅ Resource Planning
- ✅ Time Tracking
- ✅ Requirements Management
- ✅ Risk Management
- ✅ Documentation
- ✅ Task Assignment

---

## Example Use Case

Project:

```
Electric Glass Transloader
```

```
Customer Requirements
        │
        ▼
System Design
        │
        ▼
Mechanical Design
Electrical Design
Embedded Software
Hydraulic Design
HMI
AI Vision
        │
        ▼
Integration
        │
        ▼
Testing
        │
        ▼
Production
```

Every department follows one master schedule.

---

## Best For

- EV Companies
- Robotics
- Industrial Machines
- Aerospace
- Manufacturing

---

# 2. Plane

## Purpose

Plane focuses on **Agile software development**.

Instead of planning the whole company, it helps software teams organize their work into short iterations (sprints).

---

## Main Features

- ✅ Sprint Planning
- ✅ Product Backlog
- ✅ User Stories
- ✅ Roadmaps
- ✅ Kanban Board
- ✅ Bug Tracking
- ✅ Release Planning

---

## Example Use Case

Sprint 15

```
□ CAN Driver
□ PWM Driver
□ BMS Communication
□ Camera Driver
□ Motor Control
□ HMI Screen
□ OTA Update
```

Developers move tasks across the workflow:

```
Backlog
   │
   ▼
To Do
   │
   ▼
In Progress
   │
   ▼
Code Review
   │
   ▼
Testing
   │
   ▼
Done
```

---

## Best For

- Embedded Software
- AI Development
- Web Applications
- Mobile Apps

---

# 3. Taiga

## Purpose

Taiga is a lightweight Agile management tool.

It is easier to learn than Jira and works well for startups.

---

## Main Features

- ✅ Scrum
- ✅ Kanban
- ✅ User Stories
- ✅ Sprint Planning
- ✅ Task Tracking
- ✅ Backlog Management

---

## Example Workflow

```
Product Backlog

↓

Sprint Planning

↓

To Do

↓

In Progress

↓

Testing

↓

Done
```

---

## Best For

- Small Teams
- Startups
- Student Projects
- MVP Development

---

# 4. Redmine

## Purpose

Redmine is primarily an **issue tracking system**.

Instead of planning projects, it focuses on recording problems, bugs, feature requests, and maintenance tasks.

---

## Main Features

- ✅ Issue Tracking
- ✅ Bug Tracking
- ✅ Feature Requests
- ✅ Wiki
- ✅ Time Logging
- ✅ Version Tracking

---

## Example Use Case

Issue #238

```
Title:
Hydraulic Pressure Sensor Failure

Priority:
High

Assigned To:
Electrical Team

Status:
In Progress

Due Date:
Tomorrow
```

---

## Best For

- Customer Support
- Maintenance Teams
- QA Teams
- Long-term Bug Tracking

---

# Feature Comparison

| Feature | OpenProject | Plane | Taiga | Redmine |
|----------|:-----------:|:-----:|:------:|:--------:|
| Project Planning | ⭐⭐⭐⭐⭐ | ⭐⭐ | ⭐ | ⭐ |
| Gantt Charts | ✅ | ❌ | ❌ | Limited |
| Milestones | ✅ | ✅ | ✅ | Limited |
| Dependencies | ✅ | ❌ | ❌ | ❌ |
| Roadmaps | ✅ | ✅ | ⭐ | ❌ |
| Requirements | ✅ | ❌ | ❌ | ❌ |
| Kanban | ✅ | ✅ | ✅ | Limited |
| Scrum | ⭐ | ✅ | ✅ | ❌ |
| Sprint Planning | ⭐ | ✅ | ✅ | ❌ |
| Bug Tracking | ⭐⭐ | ✅ | ⭐ | ✅ |
| Time Tracking | ✅ | ⭐ | ⭐ | ✅ |
| Documentation | ✅ | ⭐ | ⭐ | ✅ |
| Wiki | ✅ | ❌ | ❌ | ✅ |

---

# Which One Should You Use?

## If you build industrial machines, EVs, or robotics

Use:

- ✅ OpenProject

It can coordinate:

- Mechanical
- Electrical
- Embedded
- Software
- Manufacturing
- Testing
- Purchasing
- Quality

---

## If you have a software team

Use:

- ✅ Plane

For:

- Sprint Planning
- Firmware Development
- AI Development
- HMI Development

---

## If you're a startup

Use:

- ✅ Taiga

Simple and fast.

---

## If customer issues are your priority

Use:

- ✅ Redmine

Perfect for:

- Bug Reports
- Service Tickets
- Customer Complaints
- Maintenance

---

# Recommended Setup for an EV / Robotics Company

```
                    OpenProject
                         │
      ┌──────────────────┼──────────────────┐
      │                  │                  │
      ▼                  ▼                  ▼
 Mechanical         Electrical         Manufacturing
      │                  │                  │
      └──────────────────┼──────────────────┘
                         │
                         ▼
                     Embedded Team
                         │
                    (Plane or Taiga)
                         │
                         ▼
                     Firmware Sprints
                         │
                         ▼
                    Testing & QA
                         │
                         ▼
               Customer Bug Reports
                    (Redmine)
```

## Final Recommendation

| Company Size | Recommended Tool |
|--------------|------------------|
| Solo Developer | Plane |
| Startup (2–15 people) | OpenProject + Plane |
| Engineering Company (15–100 people) | OpenProject + Plane + Redmine |
| Large Enterprise | OpenProject (or enterprise equivalent) + Agile tool + Issue Tracker |

**Recommended stack for your industrial EV company:**

- 🏗 **OpenProject** → Master project planning, milestones, and cross-team coordination
- 💻 **Plane** → Embedded software and AI sprint management
- 🐞 **Redmine** → Service tickets, bugs, and field issue tracking
- 📚 **BookStack** → Engineering documentation
- 🔧 **Capella** → Systems Engineering (MBSE)
