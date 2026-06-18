# Annual Leave Carryover Rollout — Claude Bootstrap
## Identity
- **Project:** Annual Leave Carryover Rollout
- **Purpose:** Plan, test, and roll out annual leave carryover policy including PeopleXD configuration and staff communication.
- **Owner:** Kevin Lelitte — HR Systems Manager/Director
- **Status:** Active
- **Repository:** https://github.com/begb0037admin/hr-projects/tree/main/Annual%20Leave%20Carryover%20Rollout
## Bootstrap Order
1. This file
2. docs/STATUS.md
3. docs/HANDOVER.md
## Where Things Live
| What | Where |
|---|---|
| Current state | docs/STATUS.md |
| Latest handover | docs/HANDOVER.md |
| Open questions | docs/OPEN_QUESTIONS.md |
| Risk register | docs/RISKS.md |
| Roadmap | docs/ROADMAP.md |
| Framework reference | PROJECT_OS.md |
| Agent roles | AGENT_MODEL.md |
| Rollover procedure | ROLLOVER_SOP.md |
## Conventions
- System: PeopleXD
- Full-time and part-time scenarios must both be tested
- Communication plan required before go-live
- Roadmap deadline: October 2026 (Michael's workstream, originated from Fina)
## Hard Rules
- No policy change without senior leadership sign-off
- System changes tested in non-production first
- Part-time edge cases must be explicitly documented
## Out of Scope
- Leave policy design (HR Policy team)
- Other leave types
## Failover Chain
Kevin -> Hope -> Adam -> Work -> Admin
## Last updated
2026-06-18

## Branch and Merge Protocol
Every time files are pushed to a branch, immediately ask Kevin:
> "I've pushed to a branch — are you happy with this? Shall I merge to main now?"

Recurring triggers throughout every session:
- **On every push** — ask immediately, without waiting
- **When Kevin signals satisfaction** — phrases like "good", "happy with that", "that's great", "okay", "done", "let's move on" — check if anything is on a branch and ask to merge
- **When the topic shifts** — before starting a new subject, check if anything is on a branch

Never leave files on a branch without Kevin's explicit sign-off.
