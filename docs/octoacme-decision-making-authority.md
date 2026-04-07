# OctoAcme — Decision-Making Authority & RACI Matrix

## Purpose
Clarify who makes decisions, who must be consulted, and who should be informed across different project activities.

## Key Decisions

| Decision | Owner | Consulted | Informed |
|----------|-------|-----------|----------|
| Approve project charter & success metrics | Sponsor / Product Lead | PM, PdM | Team |
| Prioritize backlog items | Product Manager | Project Manager | Developers, QA |
| Define acceptance criteria | Product Manager | Developers, QA | Business Analyst |
| Approve design direction | Product Manager | UX/UI Designer | Developers |
| Approve release to production | Project Manager | Product Manager, QA | Support, DevOps |
| Escalate/resolve blocker | Project Manager | Sponsor | Team |
| Change scope mid-project | Sponsor | Product Manager, PM | Team |

## Decision Triggers

- **Scope Change:** Requires Sponsor approval; PM and PdM align with team
- **Timeline Slip:** PM communicates; escalates if > 2 weeks delay
- **Quality Concern:** QA Lead and PM jointly decide go/no-go for release
- **Dependency Issue:** PM coordinates; escalates if blocking multiple teams
