# DTP1092 — ORCIDs in PeopleXD / Onboarding
## Meeting Notes & Speaker Prep | 14 April 2026

---

## 📋 One-Line Summary

The project aims to surface ORCID identifiers through PeopleXD (onboarding + self-service), but the scope has narrowed to a **"pointing" approach** — linking staff to IT Registration rather than capturing data directly in PXD. Several decisions remain unmade and a governance paper is still outstanding.

---

## 🗂 Background in 60 Seconds

- **What:** Add ORCID capture/prompting into PeopleXD at two points — new starter onboarding and employee self-service
- **Why:** ORCIDs are already collected via IT Registration (register.it.ox.ac.uk). The goal is to push the value into the Data Warehouse alongside SSO for research/reporting — more staff prompted = better coverage
- **Where it stands:** The original spec (pre-populate from CUD, validate via orcid.org) was scaled back. Current agreed direction is PXD points to IT Registration — **no data collected in PXD itself in this phase**
- **Risk flag:** Simon has raised that modifying PXD onboarding software previously caused a major incident (data loss). He wants a robust benefit justification before proceeding

---

## ✅ What Has Been Agreed

- Onboarding prompt: selected staff groups only, non-mandatory
- Self-service tile: open to all staff
- Both touchpoints **link out** to IT Registration — PXD does not store ORCID directly
- Pre-population from CUD: not in scope (integration doesn't exist)
- Validation via orcid.org: not in scope (not supported in PXD)

---

## ❓ Open Questions — Expect These to Come Up

| Question | Status | Owner (likely) |
|---|---|---|
| Which staff groups see the onboarding ORCID prompt? | Not decided | HR Policy / IT Services |
| Governance paper to RPC/RIC (mandate? single system?) | Not drafted | Unassigned |
| How significant is the onboarding software change technically? | Unclear | IT Services / HR Systems |
| Has adding the ORCID link to onboarding already improved uptake? | No analysis done | IT Services |
| Is the data quality risk (unverifiable entries) formally accepted? | Not closed | Needs decision |

---

## 🎯 Your Ask Going Into This Meeting

You don't have a formal deliverable to present, but there are likely **decisions or assignments** that will land on you. Be ready for:

- Being asked to **confirm which PXD onboarding change is actually needed** (is it a small config, or a module change?)
- Being asked whether HR Systems will **own the onboarding staff group configuration**
- The question of whether your **data quality concern is still a blocker** — have a clear answer: either it's accepted risk (and who accepts it) or it needs to be resolved first
- A possible ask to **share PXD screenshots** of where the ORCID entry/edit points would appear — Crispin asked for these on 27 March and it's not confirmed you sent them

---

## ⚠️ Watch Out For

- **Simon may push back strongly.** He has twice flagged the risk of amending onboarding software and hasn't had his concerns formally addressed. Don't be caught off guard — acknowledge the risk is real, and ask for clarity on what the actual technical change involves before committing to anything.
- **The "is this just what we already have?" confusion.** Simon asked on 7 April whether this is simply the current solution. Anne clarified partly but it may come up again. Be ready to explain clearly: the current self-service is available only to selected groups — the proposal broadens it and adds an onboarding prompt.
- **Scope creep risk.** The project has already been descoped once. If anyone proposes adding data collection back in (direct ORCID storage in PXD), that brings the validation problem back with it — don't let that pass without flagging it.

---

## 🗣 Speaker Notes

**If asked to introduce your position:**
> "From the HR Systems side, we've confirmed PeopleXD can support an ORCID prompt at onboarding and through self-service, pointing staff to IT Registration. What we can't do — without significant new integration work — is pre-populate from CUD or validate the ORCID against orcid.org. So the current direction, which I think is the right one for now, is a linking approach rather than data collection in PXD itself."

**If Simon raises the onboarding risk:**
> "Simon's concern is valid — the onboarding module is sensitive and we know changes carry risk. Before we commit to any config work, I'd want to understand exactly what the change involves technically, and whether it's a configuration change or a software amendment. That will determine the level of change governance we need."

**If asked about the data quality risk:**
> "If we're only linking out to IT Registration and not collecting ORCID in PXD, the validation concern I raised is largely mitigated for this phase. If the scope ever extends to direct capture in PXD, that risk comes back and would need to be formally accepted."

**If asked about staff groups:**
> "We need a decision on which staff groups see the onboarding prompt — that's not something HR Systems can determine alone. I'd suggest that sits with HR Policy with input from IT Services on who currently has access to the self-service tile."

**If asked about the governance paper:**
> "My understanding is that a paper to RPC or RIC was identified as a prerequisite — covering whether ORCID should be mandated and the single vs. multiple system question. That needs to be assigned and progressed before we move to delivery. Happy to contribute to it but I'd need a lead author and timeline."

**If the meeting tries to move to delivery without resolving the above:**
> "Before we agree a delivery timeline, I'd want to make sure we have: staff group decisions confirmed, the governance paper in progress, and clarity on the technical scope of the onboarding change. Otherwise we risk starting work before we've got the key sign-offs in place."

---

## 📌 Your Pre-Meeting Checklist

- [ ] Check your calendar — is there a meeting with Crispin/Eugenio that was set up after 27 March?
- [ ] Recall whether you sent Crispin the PXD screenshots he asked for (27 March) — if not, offer them in the meeting
- [ ] Decide your position on the data quality risk — is it an accepted risk for the "pointing" approach, or still live?
- [ ] Know your answer on which staff groups HR Systems currently has configured for self-service access

---

*Prepared by AI Inbox & Calendar Assistant | Based on DTP1092 email thread 10 March – 9 April 2026*
