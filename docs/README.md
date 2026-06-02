# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains standardized guides for running projects from initiation through retrospective and continuous improvement. Use this README to navigate the docs and find the right process guidance for your needs.

---

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear accountability. The organization operates across five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During initiation, teams validate business needs through a lightweight One-pager that captures the problem statement, success metrics, and stakeholder alignment—serving as the decision gate to move forward. Planning then transforms approved initiatives into actionable backlogs with shippable increments, defined dependencies, and a release roadmap. This deliberate front-loading of clarity reduces rework and misalignment downstream.

Execution and tracking are grounded in clear ownership and transparency. Each project has a named Project Manager (PM) to coordinate delivery and a Product Manager (PdM) to define outcomes and measure impact. The delivery rhythm includes daily standups (15 minutes), weekly syncs between PM and PdM, twice-weekly standups for the team, and monthly stakeholder updates. Work moves through a structured project board (Backlog → Ready → In Progress → In Review → QA → Done), with small PRs (≤400 lines), automated CI/CD, required approvals, and a comprehensive quality stack: unit tests, integration tests, end-to-end smoke tests, and security scanning. Blockers are triaged at three escalation levels—team, PM/Product Lead, and sponsor—to ensure rapid resolution without bottlenecks.

Release management is standardized to reduce risk and improve observability. Pre-release gates require all acceptance criteria met, passing CI and security scans, drafted release notes, and a documented rollback plan. Deployments follow a defined checklist—staging verification, production deployment (preferably automated), post-deploy verification, and stakeholder announcement. Finally, OctoAcme embeds continuous improvement into its culture through retrospectives after each sprint, release, or milestone. These 45–75 minute sessions capture what went well and what could improve, then convert findings into prioritized action items tracked in the backlog with clear owners and due dates. Together, these practices create a repeatable, customer-focused delivery system that scales across cross-functional teams.

---

## How to Use This Space

This Copilot Space is a centralized knowledge hub for OctoAcme's project management processes. It provides role-specific guidance and process workflows to accelerate onboarding, reduce single-person dependency risk, and enable consistent project execution.

### Quick Start by Role

**New to OctoAcme or starting your first project?**
- Start with [`octoacme-project-management-overview.md`](./octoacme-project-management-overview.md) — understand our principles, core roles, and lifecycle

**Developers**
- Read [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) to understand your responsibilities
- Review [`octoacme-execution-and-tracking.md`](./octoacme-execution-and-tracking.md) for PR workflows and quality standards
- Check [`octoacme-release-and-deployment.md`](./octoacme-release-and-deployment.md) before release cycles

**Project Managers**
- Start with [`octoacme-project-initiation.md`](./octoacme-project-initiation.md) — how to validate and authorize new work
- Use [`octoacme-project-planning.md`](./octoacme-project-planning.md) to build detailed delivery plans
- Reference [`octoacme-risks-and-communication.md`](./octoacme-risks-and-communication.md) for stakeholder updates and escalations
- Review [`octoacme-retrospective-and-continuous-improvement.md`](./octoacme-retrospective-and-continuous-improvement.md) after each phase

**Product Managers**
- Begin with [`octoacme-project-initiation.md`](./octoacme-project-initiation.md) — define success metrics and outcomes
- Use [`octoacme-project-planning.md`](./octoacme-project-planning.md) to prioritize and scope work
- Reference [`octoacme-execution-and-tracking.md`](./octoacme-execution-and-tracking.md) for reporting and metrics
- Review [`octoacme-risks-and-communication.md`](./octoacme-risks-and-communication.md) for stakeholder alignment

### Common Scenarios

**I'm starting a new project. Where do I begin?**
→ Read [`octoacme-project-initiation.md`](./octoacme-project-initiation.md) and complete the Project One-pager template. Once approved, move to [`octoacme-project-planning.md`](./octoacme-project-planning.md).

**Our sprint is ending. What should we do?**
→ Review [`octoacme-execution-and-tracking.md`](./octoacme-execution-and-tracking.md) to ensure quality gates are met, then follow [`octoacme-retrospective-and-continuous-improvement.md`](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings.

**We have a blocker or risk. How do we handle it?**
→ See [`octoacme-risks-and-communication.md`](./octoacme-risks-and-communication.md) for risk assessment and escalation paths.

**We're ready to release. What's the process?**
→ Follow the checklist in [`octoacme-release-and-deployment.md`](./octoacme-release-and-deployment.md) to ensure pre-release requirements are met and deployment proceeds safely.

**I need to understand the key roles on our team.**
→ Reference [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) for role summaries, responsibilities, and communication patterns.

---

## Contributing Updates to Process Docs

These docs are living artifacts—they should evolve as the team learns and refines processes. To request updates or additions:

1. **Use the issue template**: Open a new issue using the "Add Content to Project Management Process Docs" template (stored in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`)
2. **Provide context**: Explain what's missing, why it's needed, and (if possible) propose specific wording or examples
3. **Review with stakeholders**: Ensure updates align with team practices before merging
4. **Keep it concise**: These docs are reference materials—clarity and brevity are key

---

## Document Index

| Document | Purpose | Best For |
|----------|---------|----------|
| [`octoacme-project-management-overview.md`](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and lifecycle | New team members, stakeholders |
| [`octoacme-project-initiation.md`](./octoacme-project-initiation.md) | Steps to validate, authorize, and plan new work | PMs, PdMs starting projects |
| [`octoacme-project-planning.md`](./octoacme-project-planning.md) | Turn initiatives into actionable backlogs and release plans | PMs, delivery teams during planning phase |
| [`octoacme-execution-and-tracking.md`](./octoacme-execution-and-tracking.md) | Day-to-day execution, workflows, and quality standards | Developers, PMs during delivery |
| [`octoacme-risks-and-communication.md`](./octoacme-risks-and-communication.md) | Risk management and stakeholder communication strategies | PMs, stakeholders |
| [`octoacme-release-and-deployment.md`](./octoacme-release-and-deployment.md) | Release types, pre-release requirements, and deployment checklists | PMs, release engineers, developers |
| [`octoacme-retrospective-and-continuous-improvement.md`](./octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and converting learnings into action items | PMs, delivery teams |
| [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) | Definitions of key roles, responsibilities, and communication patterns | All roles |

---

## Key Principles

OctoAcme project management is built on these core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments rather than big-bang releases
- **Clear ownership**: Every project has a named PM and PdM with defined responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and transparent escalation

---

## Questions?

- Unsure which doc to read? Start with the "Quick Start by Role" section above
- Found a gap or inaccuracy? Open an issue using the process doc update template
- Need clarification on a specific process? Reach out to your Project Manager or Product Manager
