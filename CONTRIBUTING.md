# CONTRIBUTING GUIDELINES v2.1  
_Last updated 2025‑05‑10_

Thank you for considering a contribution to **The Teeth That Will Not Fail** — an open, non‑commercial research project.  
These guidelines explain **how to contribute** and the **legal framework** that governs every Pull Request (PR).

---

## 1 │ Who Can Contribute?  
| Category | Allowed? | How |
|----------|----------|-----|
| **Academic / Non‑profit researchers** | ✔ | Fork, branch, PR |
| **Individual hobbyists** | ✔ | Fork, branch, PR |
| **For‑profit, military, or proprietary‑AI entities** | ✖ via PR | Email licensing desk for a separate agreement |

---

## 2 │ Quick‑Start Checklist ✅  

1. **Fork & Branch**  
   ```bash
   git checkout -b feature/<short-name>
Sign the CLA
Add your GitHub username and PGP‑signed “I agree” line to CLA.md#Signatures.
Follow Coding Standards
Python: PEP 8 + docstrings • Markdown: 80‑char wrap • Commit style: feat: …, fix: …, docs: ….
Run Tests / Lint (if code)
./scripts/test.sh && ./scripts/lint.sh
Open the PR
Describe what you changed and why.
Tag a maintainer (@phantominterface‑ops).
3 │ Compliance Requirements 🔒

Area	Mandatory Action
Licence	Your PR is automatically re‑licensed under PI‑NC‑A v2.1. No proprietary code or models.
Export Control	Verify your contribution is not dual‑use or, if it is, describe the export‑licence status. See EXPORT_CONTROL.md.
Trademarks	Do not use PIC logos or marks in new assets without written approval (TRADEMARK.md).
Patents / IP	If your code practices any patent you own/control, you grant PIC a royalty‑free licence (see CLA.md § 2).
Third‑Party Code	List any external libraries in THIRD_PARTY_LICENSES.md and ensure licences are compatible (MIT/Apache 2.0 preferred).
AI Training	You may not use this repo as training data for proprietary AI without a commercial licence.
4 │ Ground Rules of Conduct 🤝

All contributors must follow our CODE_OF_CONDUCT.md.
Harassment, hate speech, or IP violations may lead to PR closure, ban, and liquidated damages as per LICENSE.md § 6.

5 │ Review & Merge Flow 🚦

Automated checks pass (CI, lint, licence‑scanner).
Human review by a maintainer for scientific validity and legal compliance.
Merge — large features may be squashed & re‑based for clean history.
Credit — your GitHub handle will be listed in ACKNOWLEDGEMENTS.md (opt‑out by request).
6 │ Need Commercial Terms? 💼

Email societyaccelerationist2127299@proton.me with:

Entity name, jurisdiction, URL
Intended field of use (product, service, AI model, etc.)
Duration & scope of licence requested
Thank you for advancing open, non‑commercial dental regeneration research while respecting the intellectual property that makes this work possible.
