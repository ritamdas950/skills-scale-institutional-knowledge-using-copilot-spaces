# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management documentation hub. This directory contains comprehensive guides for running projects at OctoAcme using our proven, iterative delivery approach.

## OctoAcme Approach Overview

OctoAcme uses a customer-focused, iterative project management framework grounded in clear ownership, data-driven decisions, and psychological safety. Our approach balances structured planning with flexibility to adapt to changing requirements and learnings.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named owners with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning from all team members

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear accountability. The process spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need and align stakeholders using a lightweight Project One-pager that captures the problem statement, objectives, success metrics, and initial resource estimates. Once stakeholder and sponsor alignment is confirmed, projects move into Planning, where work is broken into shippable increments, prioritized with acceptance criteria, and organized into a Definition of Done. This structured approach ensures that before execution begins, the team has a clear roadmap, identified dependencies, and a documented risk register.

Execution at OctoAcme is coordinated through a regular communication cadence and visible progress tracking. The team maintains a project board (GitHub Projects) with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Daily 15-minute standups focus on progress and blockers, while weekly delivery syncs and demos keep stakeholders informed. Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. Quality is embedded throughout: unit tests, integration tests, and end-to-end smoke tests are mandatory before release, along with security scanning in CI and manual QA for feature acceptance. Risks are monitored continuously and escalated through a three-level framework—team triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues.

OctoAcme operates with clearly defined personas that ensure accountability and specialized expertise. **Developers** implement features and maintain code quality through testing and design collaboration. **Product Managers** define what should be built, prioritize the backlog, and measure outcomes through success metrics. **Project Managers** coordinate delivery, manage schedules and risks, and maintain stakeholder communication and transparency. This separation of concerns enables Product Managers to focus on *what* to build and *why*, while Project Managers handle the *how* and *when*, and Developers concentrate on technical delivery.

Communication and continuous improvement are woven into every phase. Weekly status templates standardize updates on progress, next steps, risks, and decisions needed. Incident communication follows a blameless retrospective model, and at the end of each sprint or milestone, teams run structured retrospectives (45–75 minutes) to capture what went well, what could improve, and actionable next steps. This commitment to transparency, feedback loops, and iterative improvement helps OctoAcme teams deliver reliably, reduce cycle time, and adapt quickly to change while maintaining high quality and stakeholder alignment.

## Project Lifecycle at a Glance

**Initiation** → **Planning** → **Execution** → **Release** → **Retrospective**

## Documentation Guide

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** - Start here for a high-level introduction to OctoAcme roles, artifacts, and lifecycle
- **[Roles & Personas](octoacme-roles-and-personas.md)** - Understand the key roles (Project Manager, Product Manager, Developers, QA) and their responsibilities

### Project Phases

#### 1. Initiation
- **[Project Initiation Guide](octoacme-project-initiation.md)** - Define business need, align stakeholders, and decide go/no-go for planning

#### 2. Planning
- **[Project Planning](octoacme-project-planning.md)** - Break work into shippable increments, estimate scope, and create a prioritized backlog

#### 3. Execution & Tracking
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Manage day-to-day execution, use project boards, run standups, and escalate blockers
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Identify risks, maintain a risk register, and communicate status to stakeholders

#### 4. Release & Deployment
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** - Standardize releases, prepare pre-deployment checklists, and manage rollbacks

#### 5. Close & Retrospective
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings, convert insights into action items, and foster continuous improvement

## How to Use This Documentation

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the lifecycle: Initiation → Planning → Execution → Release → Retrospective
3. **Need specific guidance?** Use the phase guides above to find relevant processes and templates
4. **Adding to the docs?** Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template to propose updates
