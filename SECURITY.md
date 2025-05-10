# SECURITY POLICY v2.0  
_Last updated 2025‑05‑10_

---

## 1 │ Scope

This policy covers **all files and artifacts** in the repository  
**“The Teeth That Will Not Fail.”**  
Out‑of‑scope findings (e.g., third‑party hosting issues, social‑engineering  
vectors against maintainers) may be closed without action.

---

## 2 │ How to Report a Vulnerability

1. **Encrypt & Email**  
   - 📧 societyaccelerationist2127299@proton.me  
   - 🔑 Request our PGP key; unencrypted reports will be deleted.  
2. **Subject Line**  
3. **Mandatory Content**  
- Affected file(s) and code line(s) or protocol step(s)  
- Proof‑of‑Concept (PoC): minimal code, screenshot, or demo video  
- Impact assessment (RCE, data corruption, malicious misuse, etc.)  
- Your contact alias & preferred key (anonymous / extortionate reports ignored)

---

## 3 │ Disclosure Timeline

| Phase | Time Limit | Action |
|-------|-----------|--------|
| **Acknowledgement** | ≤ 7 calendar days | We confirm receipt & assign a CVE‑style ID. |
| **Triage** | ≤ 14 days | We evaluate severity and contact you with next steps. |
| **Fix Window** | ≤ 30 days (critical) / 90 days (non‑critical) | Patch merges to `main`; release notes published. |
| **Public Advisory** | ≤ 7 days after fix | Coordinated disclosure with credit (if desired). |

*We may accelerate timelines for actively exploited vulnerabilities.*

---

## 4 │ Researcher Safe Harbor

Good‑faith security research that **respects this policy** will **not** trigger
civil or criminal action under Swiss Unfair Competition Act (UCA Art. 6),
Computer Crime statutes (SCC Art. 143‑144bis), or DMCA § 1201 equivalents,
**provided that**:

1. No data is exfiltrated, modified, or destroyed.  
2. Testing is limited to non‑production forks; no attacks on upstream servers.  
3. You do **not** weaponize, sell, or publicly disclose the issue before the
coordinated‑disclosure date we agree upon.  

Violations void safe harbor and may result in **injunctive relief, liquidated
damages, and criminal referral**.

---

## 5 │ Out‑of‑Scope Reports

- Automated “dependency X is outdated” messages with no exploit path  
- Social‑engineering or phishing attempts  
- Denial‑of‑service tests that degrade availability  
- Issues already documented in `KNOWN_ISSUES.md` (if present)  

These may be closed without acknowledgment.

---

## 6 │ Credit & Recognition

Ethical reporters may choose:

- **Public acknowledgement** in `SECURITY.md` + release notes  
- **Private thanks** (no public name)  
- **No credit** (default if unspecified)  

We currently **do not** offer monetary bounties.

---

## 7 │ Legal & Export Notice

Security testing and disclosure **must** comply with:

- [`LICENSE.md`](./LICENSE.md) — non‑commercial terms  
- [`EXPORT_CONTROL.md`](./EXPORT_CONTROL.md) — Swiss/EU/US export laws  
- Swiss Federal Act on Data Protection (FADP)  

Any exploit code or technical data you send is automatically re‑licensed back
to us under PI‑NC‑A 2.1 for remediation purposes.

---

## 8 │ Contact Fingerprint

PhantomInterface Export‑Security Desk
societyaccelerationist2127299@proton.me
PGP‑fingerprint: 8E44 92F1 7FC0 4A77 1B88 652C 1AB3 4421 0D2F C4B8


*For urgent matters, include “SEV‑CRITICAL” in the email subject.*

---

_Your responsible disclosure helps strengthen open research.  
Thank you for keeping **The Teeth That Will Not Fail** secure._  
