# CLAUDE.md — hr-projects
> AI bootstrap entry point. Read this first.
> Keep this file under 200 lines. Push details to linked docs.

## Identity
- **Project:** HR Projects — container repo for Kevin's active HR Systems project workspaces
- **Purpose:** Holds individual project folders, each with its own CLAUDE.md, docs, and working files. Also stores the live HR Systems Roadmap workbook (OneDrive-synced, read-only).
- **Owner:** Kevin Lelitte, Manager/Director HR Systems, University of Oxford
- **Status:** Active
- **Repo:** https://github.com/begb0037admin/hr-projects
- **Last updated:** 2026-06-18

## Bootstrap Order
1. This file (orientation)
2. Navigate to the relevant project subfolder and read its CLAUDE.md
3. For the roadmap: read `HR Systems Roadmap/` — the .xlsm is the live source (OneDrive-synced)

Do NOT ask Kevin for a recap. Navigate to the relevant subfolder.

## Structure
| Folder | Purpose |
|---|---|
| `HR Systems Roadmap/` | Live HR Systems Roadmap MASTER.xlsm — read-only source of truth. Synced from Kevin's OneDrive. NEVER modify. |
| `Annual Leave Carryover Rollout/` | Annual Leave rollout (Michael's workstream, Oct 2026 deadline) |
| `DTP1092 College Staff Meeting Prep/` | College staff in PeopleXD — meeting prep materials |
| `Deactivate Applicant Successfully Hired/` | Deactivation workflow project |
| `College Staff in PXD/` | College staff migration to PeopleXD |
| `DPIA PXD/` | Data Protection Impact Assessment for PeopleXD |
| `ORCID in PXD/` | ORCID integration project |

## HR Systems Roadmap — Critical Rules
- **Source of truth:** `HR Systems Roadmap/HR Systems Roadmap MASTER.xlsm`
- **Synced from:** `C:\Users\admin\OneDrive - Nexus365\HR Systems Roadmap Master\HR Systems Roadmap MASTER.xlsm`
- **NEVER modify the file** — senior management document; Kevin updates it manually
- **Read via:** openpyxl after base64-decoding the GitHub API response (binary .xlsm)
- **Key sheet:** Work Tracker. Key columns: ID(0), Activity(1), Lead(6), Team(7), Deadline(19), Progress(22), Next steps(23), Date last reviewed(24), Status(26), Status Details(27)
- **FA team filter:** Kevin, Michael, Asta, James

## Working in a Subfolder
Each project subfolder is self-contained. Navigate there and read its CLAUDE.md before doing anything. Do not mix project context across subfolders.

## Effort Level Governance
Before any task where higher effort is warranted, signal to Kevin: what the task is, why higher effort is needed, and an explicit request to raise the effort level. Wait — do not proceed until Kevin raises it. Signal when the high-effort phase is done; Kevin decides when to return to normal. Never change effort level unilaterally. See CONSTITUTION.md Section 10 (v2.0, 2026-06-27).

## Hard Rules
- Never modify the Roadmap .xlsm — read only
- Never commit credentials or raw email data
- Always update the relevant project HANDOVER.md at end of session
- GitHub is the only working surface

## Branch and Merge Protocol
Always push directly to main. If a branch must be used, merge it to main immediately upon completion — never leave files on a branch.
