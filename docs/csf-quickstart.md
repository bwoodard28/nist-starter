# CSF 2.0 Quickstart (How to Use This Repo)

## 1) Frame the Profile
- Define **scope** (systems, data, suppliers).
- Choose **3–5 CSF outcomes** for an initial sprint (see `prioritized_outcomes` in the YAML).

## 2) Map to Other Frameworks
- Open `02-mappings/csf-iso-soc2.csv` and extend rows for each CSF outcome you tackle.
- Keep mapping **many-to-many** (CSF outcome ↔ multiple ISO/SOC2 items).

## 3) Plan & Execute Controls
- Create policy PRs, IaC changes, SIEM rules, runbooks.
- Link **evidence** (URLs, screenshots, ticket IDs) in `03-evidence/` and the mapping file.

## 4) Show Your Work
- Commit early and often. Use Issues/Projects to show backlog → done.
- Update `01-profile/csf-profile.yml` scores monthly under `measurement`.
