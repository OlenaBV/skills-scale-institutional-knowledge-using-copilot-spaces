# OctoAcme — Roles & Handoffs Checklist

## Purpose
This checklist clarifies which roles are involved in each project phase, what their expected outputs are, and how work is handed off between teams. Use this to improve accountability, reduce gaps, and ensure smooth cross-functional collaboration.

---

## Project Phase Checklists

### Phase 1: Initiation

**Roles Involved:**
- Product Manager (Lead)
- Project Manager
- UX Designer (as needed for early research)
- Data Analyst (for baseline metrics)
- Developers (for technical feasibility assessment)
- DevOps Engineer (for infrastructure considerations)

**Key Activities & Handoffs:**
- [ ] Product Manager creates Project One-pager
- [ ] Project Manager identifies stakeholders and creates communication plan
- [ ] UX Designer conducts initial user research (if applicable)
- [ ] Data Analyst establishes baseline metrics and tracking requirements
- [ ] Developers provide technical feasibility input
- [ ] DevOps Engineer reviews infrastructure and scaling needs
- [ ] Project Manager facilitates stakeholder alignment meeting
- [ ] **Handoff**: Approved One-pager → Planning phase

---

### Phase 2: Planning

**Roles Involved:**
- Project Manager (Lead)
- Product Manager
- Developers
- UX Designer
- Data Analyst
- DevOps Engineer

**Key Activities & Handoffs:**
- [ ] Project Manager facilitates kickoff meeting
- [ ] Product Manager prioritizes backlog with acceptance criteria
- [ ] UX Designer creates design specs and prototypes
- [ ] Developers estimate work and identify technical dependencies
- [ ] Data Analyst defines tracking plan and instrumentation needs
- [ ] DevOps Engineer plans CI/CD updates and infrastructure changes
- [ ] Project Manager documents Definition of Done and test plan
- [ ] All roles contribute to Risk Register
- [ ] **Handoff**: Prioritized backlog + Design specs + DoD → Execution phase

---

### Phase 3: Execution

**Roles Involved:**
- Developers (Lead)
- Project Manager
- Product Manager
- UX Designer
- Data Analyst
- DevOps Engineer

**Key Activities & Handoffs:**
- [ ] Developers implement features and write tests
- [ ] UX Designer reviews implementations for design fidelity
- [ ] Data Analyst validates analytics instrumentation
- [ ] DevOps Engineer maintains CI/CD pipeline and monitors builds
- [ ] Product Manager validates acceptance criteria are met
- [ ] Project Manager tracks progress, manages risks, facilitates standups
- [ ] All roles participate in sprint reviews and demos
- [ ] **Handoff**: Completed features + Test results + Updated metrics → Release phase

---

### Phase 4: Release & Deployment

**Roles Involved:**
- DevOps Engineer (Lead)
- Developers
- Project Manager
- Product Manager
- Data Analyst

**Key Activities & Handoffs:**
- [ ] DevOps Engineer prepares deployment pipeline and rollback plan
- [ ] Developers complete final testing and code reviews
- [ ] Data Analyst prepares dashboards for post-release monitoring
- [ ] Project Manager coordinates release communications
- [ ] Product Manager reviews release notes and stakeholder messaging
- [ ] DevOps Engineer executes deployment and monitors system health
- [ ] Data Analyst tracks launch metrics and user impact
- [ ] **Handoff**: Released features + Metrics dashboard + Release notes → Retrospective phase

---

### Phase 5: Retrospective & Continuous Improvement

**Roles Involved:**
- All team members
- Project Manager (Facilitator)

**Key Activities & Handoffs:**
- [ ] Project Manager facilitates retrospective meeting
- [ ] All roles share what went well and improvement opportunities
- [ ] Data Analyst presents outcome metrics vs. success criteria
- [ ] UX Designer shares user feedback and usability findings
- [ ] DevOps Engineer reports on reliability and performance
- [ ] Team prioritizes 2-3 actionable improvements
- [ ] Project Manager documents action items with owners and due dates
- [ ] **Handoff**: Action items → Next project cycle or backlog

---

## RACI Matrix for Key Artifacts

Use this matrix to clarify who is **Responsible** (does the work), **Accountable** (final approval), **Consulted** (provides input), and **Informed** (kept updated) for each key artifact.

| Artifact | Product Manager | Project Manager | Developer | UX Designer | Data Analyst | DevOps Engineer |
|----------|----------------|-----------------|-----------|-------------|--------------|-----------------|
| **Project One-pager** | R/A | C | C | C | C | C |
| **Prioritized Backlog** | R/A | C | C | C | I | I |
| **Design Specs** | C | I | C | R/A | C | I |
| **Definition of Done** | C | R/A | C | C | C | C |
| **Risk Register** | C | R/A | C | C | C | C |
| **Test Plan** | C | C | R/A | I | I | C |
| **Release Plan** | C | R | C | I | I | R/A |
| **Metrics Dashboard** | C | I | C | I | R/A | C |
| **Retro Action Items** | C | R/A | C | C | C | C |

### RACI Legend
- **R (Responsible)**: Does the work to complete the task
- **A (Accountable)**: Has final approval and ultimate ownership
- **C (Consulted)**: Provides input and expertise
- **I (Informed)**: Kept updated on progress

---

## Tips for Using This Checklist

1. **Review at project kickoff**: Walk through the checklist with your team to clarify expectations.
2. **Adapt as needed**: Not all phases or roles apply to every project—customize based on scope.
3. **Track handoffs**: Use the checklist to identify gaps or delays in cross-functional work.
4. **Reference in planning**: Link to specific sections from your project plan or board.
5. **Update the RACI**: If roles shift or new artifacts are introduced, update the matrix accordingly.

---

## Related Documentation
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
