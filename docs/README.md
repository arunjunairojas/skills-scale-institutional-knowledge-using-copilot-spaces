# OctoAcme Project Management Docs

This repository brings together OctoAcme’s project management and delivery guidance into a simple, searchable set of process documents. OctoAcme follows a structured lifecycle: validate the business need and define success criteria during initiation; turn approved ideas into a backlog, milestones, and release plan during planning; execute work in small, testable increments while tracking dependencies and risks; and close the loop with release verification, stakeholder communication, and retrospective learning. The goal is to keep teams aligned, decisions visible, and delivery predictable across the full project lifecycle.

Project work is organized around clear roles and shared artifacts. The Project Manager coordinates schedules, risks, dependencies, and communication. The Product Manager defines outcomes, prioritizes the backlog, and measures success. Developers build and validate software in line with acceptance criteria, QA/test roles ensure quality and release readiness, and stakeholders provide input, feedback, and approvals. These personas work together through a consistent rhythm of planning sessions, daily standups, weekly check-ins, demos, and milestone reviews so that responsibilities stay clear and teams can respond quickly to changes.

Communication is treated as a core delivery practice rather than an afterthought. OctoAcme recommends regular updates via standups, PM/Product syncs, demo reviews, and milestone-based stakeholder briefings, with a single source of truth for status in the project README or release documentation. Risks and blockers are tracked in a risk register and escalated from team-level triage to the PM, Product Lead, and sponsor when needed. This keeps issues visible early and ensures that major dependencies, business-impacting risks, and incidents are handled with clear ownership and escalation paths.

Quality and release discipline are built into each stage of delivery. New work should have clear acceptance criteria, a defined Definition of Done, and appropriate testing coverage, including unit, integration, and smoke testing for critical flows. CI should enforce linting, automated tests, and security checks before work is merged. Releases require verification of acceptance criteria, smoke tests, rollback plans, and stakeholder communication, while retrospectives capture what went well, what needs improvement, and which action items should be tracked back into the backlog. Together, these practices create a repeatable process for delivering value while continuously learning and improving.

## Process Documents

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](octoacme-roles-and-personas.md)

## Related Documents

- [Project Management Process Issue Template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
