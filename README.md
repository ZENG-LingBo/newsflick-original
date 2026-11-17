# HKUST E-Fund application

Workspace for our application to the **HKUST Entrepreneurship Fund (E-Fund)**, 2026 Autumn cohort.

> **Deadline: 18 November 2026, 5:00 PM (Hong Kong time).** Submit the online application and all supporting documents on or before then.

## How to apply

- Apply online at <https://e-fund.hkust.edu.hk/>.
- HKUST members sign in with HKUST SSO. Non-members request an account through the site first.
- Read the cohort application guideline, project proposal guideline, FAQ and SAFE term sheet on the E-Fund site before writing.
- Questions: efund@ust.hk

## Checklist

- [ ] Online application form
- [ ] Business Registration Certificate
- [ ] Proof of HKUST affiliation
- [ ] Business proposal (used at the panel interview if shortlisted)
- [ ] Term sheet with any investors (if there is one)

## Layout

| Folder | Contents |
| --- | --- |
| `proposal/` | Business proposal drafts and pitch material |
| `supporting-docs/` | Non-confidential supporting material |
| `private/` | Confidential files. Git ignores this folder; see below. |

## Keep confidential files out of git

This repository is **public**. Do not commit the Business Registration Certificate, proof of HKUST affiliation, ID documents, term sheets, cap tables or financials. Put them in `private/`, which `.gitignore` excludes.
