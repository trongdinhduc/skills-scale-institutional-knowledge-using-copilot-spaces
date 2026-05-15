# OctoAcme Project Management Docs - Issue Template

**Issue Title:** [Process Doc Update]: Create README for OctoAcme Project Management Docs with Links to All Processes and Summary

**Labels:** documentation, process improvement

---

## Summary of New Content

Create a comprehensive README for the OctoAcme Project Management documentation that serves as a central hub for all process documents. The README should include:

1. A brief overview of OctoAcme's project management approach and principles
2. A table of contents or link list to all process documents in the `docs/` folder
3. Quick navigation to help teams understand which document applies to their current phase

## Why is this update needed?

- **Closes a documentation gap**: Currently, there is no single entry point for teams to discover and understand the full scope of OctoAcme's project management processes
- **Improves usability**: New team members and cross-functional stakeholders need a clear roadmap to find relevant guidance
- **Aligns with Knowledge Base Best Practices**: A README serves as the canonical index for institutional knowledge
- **Supports the purpose of Copilot Spaces**: Making scattered project management knowledge centralized and easily accessible

## Suggested Content

```markdown
# OctoAcme Project Management Processes

Welcome to the OctoAcme Project Management documentation hub. This repository contains standardized processes and guidance for how OctoAcme runs projects across all teams.

## Quick Start

New to OctoAcme project management? Start here:

1. **First time?** → Read [Project Management Overview](docs/octoacme-project-management-overview.md)
2. **Starting a new project?** → Follow [Project Initiation Guide](docs/octoacme-project-initiation.md)
3. **Planning your work?** → Use [Project Planning](docs/octoacme-project-planning.md)
4. **In delivery phase?** → Reference [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
5. **Managing risks?** → See [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
6. **Ready to release?** → Follow [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
7. **Project complete?** → Run [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)

## About OctoAcme's Approach

OctoAcme uses a **customer-first, iterative delivery** model with clear ownership, data-informed decisions, and psychological safety. Our processes are designed to:

- Deliver customer value through small, testable increments
- Ensure clear ownership and accountability across projects
- Make decisions based on data and evidence
- Foster learning and continuous improvement
- Maintain transparent communication with stakeholders

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Complete Process Documentation

| Phase | Document | Purpose |
|-------|----------|---------|
| **Overview** | [Project Management Overview](docs/octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and artifacts |
| **Initiation** | [Project Initiation Guide](docs/octoacme-project-initiation.md) | Validate and authorize work, align stakeholders, create lightweight plan |
| **Planning** | [Project Planning](docs/octoacme-project-planning.md) | Break work into shippable increments, identify dependencies and risks |
| **Execution** | [Execution & Tracking](docs/octoacme-execution-and-tracking.md) | Manage day-to-day execution, track progress toward milestones |
| **Risk & Communication** | [Risk Management & Communication](docs/octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| **Release** | [Release & Deployment Guide](docs/octoacme-release-and-deployment.md) | Standardize releases to production and reduce deployment risk |
| **Closing** | [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert into actionable improvements |
| **Reference** | [Roles & Personas](docs/octoacme-roles-and-personas.md) | Define typical roles and responsibilities (Developers, PMs, Project Managers) |

## Key Artifacts

Throughout your project lifecycle, you'll work with these key artifacts:

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- **Weekly sync** between PM + Product Manager
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## Getting Help

- Not sure which process applies? Start with the [Project Management Overview](docs/octoacme-project-management-overview.md)
- Looking for a specific template? Check the relevant process doc
- Want to suggest improvements? Use the [Add Content to Project Management Process Docs issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

## Contributing to These Docs

OctoAcme's processes are living documents. If you have suggestions, improvements, or notice gaps:

1. Use the **[Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template
2. Describe the update needed and the rationale
3. Include suggested content if available
4. Team leads will review and integrate improvements

---

**Last Updated:** 2026-05-15  
**Version:** 1.0
```

## Acceptance Criteria

- ✅ Content aligns with existing process docs
- ✅ Update improves clarity and serves as central entry point for all processes
- ✅ README structure guides users to the right process based on project lifecycle phase

---

## How to Create This Issue

To create this issue using the issue template, visit:
`https://github.com/trongdinhduc/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml`

Then fill in:
- **Which process document do you want to update?**: `<new document>` (for a new README)
- **Summary of New Content**: [Use the summary section above]
- **Why is this update needed?**: [Use the rationale section above]
- **Suggested Content**: [Use the markdown content provided above]
- **Acceptance Criteria**: Check all boxes
