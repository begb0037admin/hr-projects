# Deactivate Applicant Successfully Hired — Claude Bootstrap
## Identity
- **Project:** Deactivate Applicant Successfully Hired
- **Purpose:** Deactivate the "Applicant Successfully Hired" status in PeopleXD. When used it incorrectly removes a background database retention flag. Flagged by The Access Group.
- **Owner:** Kevin Lelitte — HR Systems Manager/Director
- **Status:** Active
- **Repository:** https://github.com/begb0037admin/hr-projects/tree/main/Deactivate%20Applicant%20Successfully%20Hired
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
| Framework reference | PROJECT_OS.md |
| Agent roles | AGENT_MODEL.md |
| Rollover procedure | ROLLOVER_SOP.md |
## Conventions
- System: PeopleXD
- Vendor: The Access Group
- Departments currently using this status must be notified before deactivation
## Hard Rules
- Test in non-production PXD before applying to production
- Department communication must go out before any change
## Out of Scope
- Wider applicant status workflow redesign
- Other PXD applicant statuses
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
