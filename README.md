# NIST CSF 2.0 Starter (Portfolio-Ready)

This repo is a **hands-on starter** to demonstrate how you work with the **NIST Cybersecurity Framework (CSF) 2.0** across profiling, mapping, and evidence.

> CSF 2.0 introduces six Functions (Govern, Identify, Protect, Detect, Respond, Recover) and modernizes outcomes and terminology. Use this repo to build a public artifact that shows your process and outputs.

## Structure
```
.
├── 01-profile/            # Your CSF profile (scope, priorities, target state)
├── 02-mappings/           # Crosswalks (CSF -> ISO 27001:2022, SOC 2, etc.)
├── 03-evidence/           # Pointers to policies, screenshots, tickets, runbooks
└── docs/                  # Quickstart + notes you want in the README/wiki
```

## Quickstart
1. **Define scope** in `01-profile/csf-profile.yml` (systems, data, suppliers).
2. **Pick outcomes** you’ll tackle first (start small) and set a **target state**.
3. **Map** those outcomes to ISO 27001:2022 / SOC 2 in `02-mappings/`.
4. **Plan control work** (policies, tech controls, tickets) and drop evidence links in `03-evidence/`.
5. **Document decisions** in `docs/csf-quickstart.md` and open issues for gaps.

## Functions & Categories (CSF 2.0)
- **Govern (GV)**: GV.OC, GV.RM, GV.RR, GV.PO, GV.OV, GV.SC
- **Identify (ID)**: ID.AM, ID.RA, ID.IM
- **Protect (PR)**: PR.AA, PR.AT, PR.DS, PR.PS, PR.IR
- **Detect (DE)**: DE.CM, DE.AE
- **Respond (RS)**: RS.MA, RS.AN, RS.CO, RS.MI
- **Recover (RC)**: RC.RP, RC.CO

## Notes
- The mapping files include **illustrative samples** to get you started. Expand them as you work.
- Keep this repo **evidence-driven**—link to artifacts (policy PRs, IaC diffs, SIEM rules, runbooks, Jira tickets).
- Use Issues/Projects to show backlog, in‑progress, and done.
- Not legal or audit advice.
