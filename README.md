# Gym Membership Management System

Software Engineering group project at **Soran University** (Faculty of Science, Department of Computer Science).

A desktop application that helps a small or medium-sized gym manage its **members, membership plans, subscriptions, payments, attendance, and reports**, replacing paper records and scattered spreadsheets.

## Team

| Member | Role |
|---|---|
| Moeen Rebar | Project leader; requirements analysis and documentation |
| Shady Jamil | System design (database and interface design) |
| Bilal Taha | Development, testing, and quality checks |

## Project Progress

| Part | Deliverable | Status | File |
|---|---|---|---|
| 1 | Project Proposal | Done | [docs/Part1_Project_Proposal.pdf](docs/Part1_Project_Proposal.pdf) |
| 2 | Requirements Engineering (SRS) | Done | [docs/Part2_Requirements_SRS.pdf](docs/Part2_Requirements_SRS.pdf) |
| 3 | System Modeling and Design | Done | [docs/Part3_Modeling_and_Design.pdf](docs/Part3_Modeling_and_Design.pdf) |
| 4 | Software Architecture and Design | To do | - |
| 5-9 | Implementation, testing, quality and security, evolution and maintenance, final presentation | To do | - |

The task list with owners is in [docs/project-plan.md](docs/project-plan.md).

## Repository Structure

```
gym-membership-management-system/
├── README.md            Project overview and progress
├── CONTRIBUTING.md     Team workflow (branches, commits, reviews)
├── CHANGELOG.md        History of versions of the documents
├── .gitignore
├── docs/               All project documents (Parts 1-3 and the project plan)
└── src/                Source code (added during implementation)
```

## How We Work Together

We use Git and GitHub for version control. Nobody commits directly to `main`: every change is made on a separate branch and merged through a pull request that another member reviews. The full rules are in [CONTRIBUTING.md](CONTRIBUTING.md).

## Scope Summary

- **Included:** login with roles (Administrator and Staff), member management, membership plans and subscriptions, payment recording with receipts, attendance check-in, and reports.
- **Not included:** online payment, mobile app, biometric or card-reader hardware, and workout or diet planning.
