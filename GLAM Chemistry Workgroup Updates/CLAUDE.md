# CLAUDE.md — GLAM Chemistry Workgroup Updates

## Identity
- **Project:** GLAM / Chemistry Work Group Holiday Scheme updates — recurring PeopleXD admin task
- **Purpose:** Holds the reusable runbook for setting PeopleXD Work Group Holiday Scheme to PHFC7 ("No Public or Fixed Closure") and renaming the Description to include the scheme, for Chemistry and GLAM (Bodleian + Ashmolean) departments. Triggered on request whenever Julie Hickman (or GLAM directly) sends a new batch of work group codes — not scheduled or automatic.
- **Owner:** Kevin Lelitte, Manager/Director HR Systems, University of Oxford
- **Status:** Active — first full run complete (see below), ready for the next GLAM/Chemistry batch
- **Last updated:** 2026-10-01

## Bootstrap Order
1. This file (orientation)
2. `RUNBOOK.md` — the step-by-step PeopleXD procedure
3. `HANDOVER.md` — current state and what's done so far

## History
- **Chemistry pilot (137 work groups):** complete, 1 Oct 2026.
- **GLAM priority list (39 work groups — 28 Bodleian + 11 Ashmolean):** complete, 1 Oct 2026.
- Full source lists, prep notes, and per-code completion evidence for this
  first run live in the OneDrive project folder (not this repo, per the
  project's own working convention at the time):
  `OneDrive - Nexus365\Meetings\Meetings\38 Day Balance for Departments\`
  — see `outputs/chemistry-workgroup-completion-evidence.md` and
  `outputs/glam-workgroup-completion-evidence.md` there for the full
  code-by-code record.
- This repo entry exists so the *procedure* survives for the next request,
  independent of that OneDrive folder's lifecycle.

## When GLAM or Chemistry sends a new batch
1. Get the new code list (work group codes + target names) from Julie or
   the department directly.
2. Follow `RUNBOOK.md` exactly.
3. Log progress per-code as you go (same pattern as the first run) so an
   interrupted run can resume cleanly.
4. Update `HANDOVER.md` here with the new completion record when done.

## Hard Rules
- GitHub is the only working surface for this folder — reads and writes go
  through the GitHub API, not a local clone, per `hr-projects/AGENT_MODEL.md`.
- Never commit credentials or raw email bodies.
- This task runs **on request only** — never set up as a scheduled/cron job
  without Kevin's explicit instruction.
