# OctoAcme — Project Planning

## Purpose
Turn an approved initiative into an actionable plan and backlog for delivery.

## Objectives
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities

## Activities
1. **Kickoff meeting** with stakeholders and delivery team
   - **Owner**: Project Manager
   - **Attendees**: Product Manager, Tech Lead, Key Stakeholders, Delivery Team
   - **Outputs**: Shared understanding of goals, initial questions addressed
   - **Handoff**: PM shares meeting notes and action items within 24 hours

2. **Create prioritized backlog** with acceptance criteria
   - **Owner**: Product Manager (content), Project Manager (facilitation)
   - **Collaboration**: Development team for technical input
   - **Outputs**: Prioritized list of work items with clear acceptance criteria
   - **Handoff**: Product Manager reviews and approves backlog before estimation

3. **Estimate scope** (T-shirt sizing or story points)
   - **Owner**: Development team
   - **Facilitation**: Project Manager
   - **Outputs**: Effort estimates for each backlog item
   - **Handoff**: PM incorporates estimates into release plan

4. **Define Definition of Done (DoD)**
   - **Owner**: Tech Lead with team input
   - **Review**: Product Manager and QA Lead
   - **Outputs**: Clear completion criteria for all work items
   - **Handoff**: DoD documented in project repository and shared with all team members

5. **Identify dependencies and integration points**
   - **Owner**: Tech Lead
   - **Collaboration**: Project Manager, dependent teams
   - **Outputs**: Dependency map with owners and target dates
   - **Handoff**: PM communicates dependencies to affected teams and schedules coordination meetings

6. **Create release plan and milestone map**
   - **Owner**: Project Manager
   - **Review**: Product Manager, Tech Lead
   - **Outputs**: Timeline with milestones, sprint breakdown, and go-live date
   - **Handoff**: PM publishes plan to stakeholders and schedules planning checkpoint

## Backlog Item Template
- Title:
- Description:
- Acceptance criteria:
- Priority:
- Estimate:
- Owner:
- Related docs/links:

## Sprint / Iteration Planning
- Timebox planning to agreed sprint length
- Pull items that meet DoD and have clear acceptance criteria
- Ensure team capacity is respected

## Risk & Dependency Management
- Capture in Risk Register:
  - ID, Description, Impact, Probability, Owner, Mitigation
- Mark cross-team dependencies in the project board and escalate during weekly syncs

## Planning Checklist
- [ ] Project kickoff held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted
- [ ] Dependencies identified and communicated
- [ ] Stakeholders notified of plan and timeline

## Communication Handoffs

### Planning → Execution
- **What**: Approved release plan, prioritized backlog, DoD
- **Who**: PM hands off to Tech Lead and Development team
- **When**: At sprint planning or execution kickoff
- **How**: Share via project board, repository docs, and kickoff meeting
- **Validation**: Team confirms understanding of priorities and acceptance criteria

### Within Planning Phase
- **Backlog Creation**: Product Manager → Development Team (for estimation input)
- **Estimates**: Development Team → Project Manager (for schedule planning)
- **Dependencies**: Tech Lead → Project Manager → Dependent Teams
- **Timeline**: Project Manager → Product Manager → Stakeholders

### Key Communication Artifacts
- **Project kickoff notes**: Shared within 24 hours of kickoff meeting
- **Prioritized backlog**: Published in project board before estimation
- **Release plan**: Distributed to all stakeholders before execution begins
- **Risk register**: Established during planning, reviewed in weekly syncs
- **Definition of Done**: Documented in repository README or docs/

### Ensuring Effective Handoffs
- **Document decisions**: Don't rely on verbal communication alone
- **Confirm understanding**: Ask recipients to acknowledge or ask questions
- **Provide context**: Include "why" along with "what" for better clarity
- **Set response timeframes**: "Please review by [date]" prevents delays
- **Use single source of truth**: Link to canonical documents rather than duplicating information

> 📖 For ongoing communication during execution, see [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)  
> 📖 For risk escalation paths, see [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)
