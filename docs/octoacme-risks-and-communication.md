# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- **ID**: Unique identifier (e.g., RISK-001)
- **Description**: Clear description of the risk
- **Impact** (High/Med/Low): Severity if risk occurs
- **Likelihood** (High/Med/Low): Probability of occurrence
- **Owner**: Person accountable for monitoring and mitigation
- **Mitigation plan**: Specific actions to reduce likelihood or impact
- **Status**: Active / Mitigated / Accepted / Occurred
- **Last updated**: Date of most recent review

### Risk Assessment Matrix

| Impact / Likelihood | High Likelihood | Medium Likelihood | Low Likelihood |
|---------------------|-----------------|-------------------|----------------|
| **High Impact**     | Critical (Immediate escalation) | High (Escalate within 24hrs) | Medium (Monitor closely) |
| **Medium Impact**   | High (Escalate within 24hrs) | Medium (Track weekly) | Low (Document only) |
| **Low Impact**      | Medium (Track weekly) | Low (Document only) | Low (Document only) |

### Example Risk Register Entry

```
ID: RISK-003
Description: Key developer on leave during critical sprint may delay release
Impact: Medium (could delay release by 1-2 weeks)
Likelihood: High (leave is confirmed)
Owner: Project Manager
Mitigation: 
  1. Knowledge transfer sessions scheduled week before leave
  2. Backup developer identified and briefed
  3. Scope adjusted to complete critical items before leave
Status: Active (mitigation in progress)
Last updated: 2026-01-05
```

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Use the [Stakeholder Engagement Log](stakeholder-engagement-log.md) to track all interactions
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

> 📖 For detailed stakeholder tracking, see [Stakeholder Engagement Log Template](stakeholder-engagement-log.md)  
> 📖 For communication during planning, see [OctoAcme Project Planning](octoacme-project-planning.md)

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- **Level 1: Team** → Discuss in daily standup or as soon as identified
- **Level 2: PM** → Escalate within 1-2 business days if team cannot resolve
- **Level 3: Product Lead** → Escalate within 1 business day if PM cannot resolve or risk impacts multiple teams
- **Level 4: Sponsor** → Escalate immediately for business-critical or customer-impacting issues

### Escalation Timelines by Risk Level

**Critical/High Impact Risks:**
- **Initial identification** → Team discussion: Same day
- **Team → PM**: Within 4 hours if team cannot mitigate
- **PM → Product Lead**: Within 24 hours if unresolved
- **Product Lead → Sponsor**: Immediately for critical business impact

**Medium Impact Risks:**
- **Initial identification** → Team discussion: Within 1 business day
- **Team → PM**: Within 2 business days if team cannot mitigate
- **PM → Product Lead**: Within 1 week if trend worsening
- **Product Lead → Sponsor**: As needed for strategic decisions

**Low Impact Risks:**
- **Initial identification** → Document in risk register
- **Team → PM**: In next weekly sync
- **PM → Product Lead**: In next monthly review if persistent
- **Escalation beyond Product Lead**: Typically not required unless pattern indicates larger issue

### When to Escalate
- **Immediately**: Security incidents, data breaches, critical production outages
- **Same day**: High-impact risks with imminent deadline or customer impact
- **Within 1-2 days**: Medium risks that team cannot resolve with available resources
- **Weekly**: Low risks or status updates on known risks
- **Monthly**: Risk register review and trend analysis

### Security Escalations
For security incidents, follow the security incident runbook and notify Security on-call immediately. Do not wait for standard escalation timelines.
