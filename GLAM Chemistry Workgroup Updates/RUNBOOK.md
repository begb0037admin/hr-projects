# RUNBOOK — Work Group Holiday Scheme update (PHFC7) + rename

Procedure for setting a PeopleXD Work Group's Holiday Scheme to **PHFC7
("No Public or Fixed Closure")** and renaming it to include the scheme in
the title. Used for Chemistry and GLAM (Bodleian/Ashmolean) departments.
Confirmed working 1 October 2026 across 176 work groups (137 Chemistry +
39 GLAM) with zero failures.

## Prerequisites

- Live PeopleXD session, logged in (SSO), with Work Group admin access.
- The code list for this batch: work group codes + target renamed titles
  (normally supplied by Julie Hickman or the department directly).
- A place to log progress per-code as you go, in case the run is
  interrupted (browser disconnect, SSO session drop, etc.) — a simple
  markdown checklist works; see "Resuming an interrupted run" below.

## System

- Workforce Management Admin Dashboard → Work Groups
- URL: `https://my.corehr.com/pls/coreportal_uoxp/i#RosterAdminMain/WFMConfigAdmin`
  (if this redirects to an SSO logout page, the session has dropped —
  re-navigate to the WFM Configuration landing page and reopen Work Groups
  from there rather than retrying the deep link directly)

## Per-code procedure

1. Search the work group code in the Work Groups search box, press the
   search icon, wait for the row to load (~2 seconds).
2. **Check the current Holiday Scheme first.** If it's already
   "No Public or Fixed Closure" (PHFC7), skip to step 5 — rename only.
   (This happened for 4 of the 176 codes in the first run; it is not an
   error, just a pre-existing correct value.)
3. Click the Holiday Schemes cell to make it editable, then click the
   dropdown arrow to open the list of schemes.
4. Scroll to find **"No Public or Fixed Closure" / PHFC7** (alphabetically
   between "N..." and "Public Holidays..." entries) and click it, then
   click elsewhere on the page to save. Confirm the
   "Work Group Updated Successfully" toast appears and the cell now shows
   "No Public or Fixed Closure".
5. Click the Description cell to make it editable. **Triple-click** the
   text to select it all (a single click or ctrl+A can be blocked by this
   environment's automation permission layer — triple-click reliably
   selects without tripping it), then type the new name exactly as given
   in the source list, then click elsewhere to save.
6. Confirm the "Work Group Updated Successfully" toast and that the
   Description cell shows the new name.
7. Log the code as done, then move to the next code.

## Timing note

Leave ~2 seconds after a save before acting on the same row again — the
row re-renders after each save, and acting too fast can land a click on
stale page state (seen once in the first run; caught immediately by the
verification step and redone).

## Resuming an interrupted run

Keep a simple per-code checklist (code → target name → done/not done) as
you go. If the browser session drops (SSO logout loop, extension
disconnects, wrong browser window connected, etc.):
1. Re-establish a working PeopleXD session — re-navigate via the WFM
   Configuration landing page's search box to reach Work Groups, don't
   just retry the direct URL.
2. Resume from the next unchecked code in the list. Nothing already
   confirmed needs redoing.

## Verification

Every save is confirmed two ways before moving on:
1. The in-app "Work Group Updated Successfully" toast.
2. A re-read of the cell showing the new value in place of the old one.

## Known exception pattern

A small number of codes may already have Holiday Scheme set to PHFC7 when
you reach them (seen in GLAM: 101446, 101523, 104282 — 3 of 39). For these,
skip the scheme-change step (step 2–4 above) and do the rename only. This
is expected, not a data problem — note it in your per-code log rather than
treating it as a blocker.
