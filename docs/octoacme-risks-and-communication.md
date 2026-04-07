# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

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
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

## Risk Register Template & Examples

### Basic Risk Register Fields
| ID | Description | Impact | Likelihood | Owner | Mitigation Plan | Status | Review Date |
|----|-------------|--------|------------|-------|-----------------|--------|-------------|
| R001 | Key developer unavailable | High | Medium | PM | Cross-train backup dev; document knowledge | Open | 2026-04-14 |
| R002 | Third-party API delays | Medium | High | Tech Lead | Identify fallback option; start integration early | Mitigated | 2026-04-21 |

### Risk Assessment Scale

**Impact:**
- **High:** Project delay > 2 weeks, critical feature missing, or customer-facing outage
- **Medium:** Project delay 1-2 weeks, workaround available, or degraded performance
- **Low:** Minor delay < 1 week, no customer impact

**Likelihood:**
- **High:** > 75% chance of occurrence
- **Medium:** 25-75% chance
- **Low:** < 25% chance

### Risk Prioritization

**Rank by Risk Score = Impact × Likelihood**

| Score | Priority | Action |
|-------|----------|--------|
| High (9) | Critical | Escalate; mitigate immediately |
| Medium (4-6) | High | Monitor closely; assign owner |
| Low (1-2) | Low | Track; review weekly |

