# EXPORT CONTROL & SANCTIONS COMPLIANCE v2.0  
(Last updated 2025‑05‑10)

> **Plain‑Language Snapshot**  
> • Treat this project as a **dual‑use** technology.  
> • You must screen every recipient and destination.  
> • No transfers to embargoed countries, military end‑users, or sanctioned persons.  
> • Swiss / EU / U S authorisations may be required before any export—digital or physical.  
> • Violations = heavy fines + prison + licence termination + liquidated damages.

-----------------------------------------------------------------
## 1 Governing Export Regimes  
| Jurisdiction | Statute / Regulation | Link |
|--------------|---------------------|------|
| Switzerland | Goods Control Act (GCA SR 946.202) & Goods Control Ordinance (GCO SR 946.202.1) | <https://www.fedlex.admin.ch/eli/cc/2019/1084_1084_1084/en> |
| European Union | Dual‑Use Regulation (EU) 2021/821 | <https://eur-lex.europa.eu/eli/reg/2021/821> |
| United States | Export Administration Regulations (15 C.F.R. 730‑774) & OFAC Sanctions (31 C.F.R. Chapter V) | <https://www.ecfr.gov/current/title-15/part-730> |
| Global | Wassenaar Arrangement (Dual‑Use List Cat. 0‑9) | <https://www.wassenaar.org/> |

-----------------------------------------------------------------
## 2 Controlled Content in this Repository  
| Control Category | Examples in this Project | WA / EU Control Ref. |
|------------------|--------------------------|----------------------|
| **Technical Data** | Protocol documents, source code, CAD/STL files, ML model weights | WA Cat. 1E002 + 1D002 |
| **Biological Designs** | Dental stem‑cell CRISPR templates, growth‑factor sequences | WA Cat. 1C351 / EU Annex I 1C351 |
| **Advanced Sensors** | Biosensor PCB schematics, read‑out ASIC layouts | WA Cat. 3A001 |
| **Encryption Software** | Any code employing ≥ 128‑bit symmetric crypto | WA Cat. 5A002 / 5D002 |

> **Digital exports count.** Placing files on a server, emailing code, or granting GitHub access **is an export** under Swiss/EU law.

-----------------------------------------------------------------
## 3 Embargoed & Restricted Destinations (May 2025)  
| Region / Country | Status | Primary Legal Basis |
|------------------|--------|---------------------|
| Cuba, Iran, North Korea, Syria | **Total embargo** | Swiss GCO Art. 2, EU 2023/1529, U S OFAC |
| Russia & Belarus | **Severe dual‑use & military ban** | EU 2024/2878, Swiss Ordinance SR 946.231.176.72 |
| Mainland China (PRC) & Hong Kong | **Strict end‑use screening** (military & AI) | EU 2021/821 Art. 4, U S EAR § 744 |
| Venezuela, Myanmar, Sudan, South Sudan | **Partial arms/dual‑use embargo** | Various UN/EU regs |

> **Military End‑Users anywhere** are **prohibited** under the project licence (see `LICENSE.md § 3`).

-----------------------------------------------------------------
## 4 Authorisation Matrix  
| Destination | End‑User | Action Required |
|-------------|---------|-----------------|
| Switzerland / EU / EFTA academic | Non‑military | **No licence** (Academic Research Exception) |
| Switzerland / EU / EFTA commercial | Civilian | **SECO / EU export licence** likely required |
| U S, Canada, UK, Japan, Australia | Civilian | File No‑Licence‑Required (NLR) or ECCN 5D992 self‑classification **+** end‑use certificate |
| Any sanctioned person / entity | Anyone | **Export prohibited** |
| Any military, defence contractor, or intelligence agency | Anyone, anywhere | **Export prohibited** |

-----------------------------------------------------------------
## 5 Screening Checklist (Before Sharing)  
1. **Recipient Due Diligence**  
   - Run names against: • OFAC SDN list • EU Consolidated Sanctions list • SECO sanctions database • UN lists.  
2. **End‑Use Certificate (EUC)**  
   - Obtain written confirmation of peaceful, non‑commercial, non‑military use.  
3. **Jurisdiction Mapping**  
   - Verify ultimate destination and all transit nodes.  
4. **Licence Determination**  
   - If any doubt, consult SECO/EU DG TRADE or U S BIS for a ruling.  
5. **Record‑Keeping (10 years)**  
   - Store EUCs, screening logs, licence numbers, and correspondence.

-----------------------------------------------------------------
## 6 Downstream Liability  
You **remain liable** for further re‑exports by your recipients.  
Include this file in every redistribution and require downstream users to comply.

-----------------------------------------------------------------
## 7 Penalties for Violation  
| Jurisdiction | Civil / Admin Penalty | Criminal Penalty |
|--------------|----------------------|------------------|
| Switzerland | Up to **CHF 1 000 000** | Up to **5 years’ imprisonment** (GCA Art. 14) |
| European Union | Up to **€1 000 000** / shipment | Up to **6 years’ imprisonment** (Reg 2021/821 Art. 23) |
| United States | Up to **$1 000 000** / violation | Up to **20 years’ imprisonment** (50 U.S.C. § 4819) |

Violations also trigger **immediate licence termination** and **liquidated damages** under `LICENSE.md § 6`.

-----------------------------------------------------------------
## 8 Contact for Compliance Queries  
**PhantomInterface Collective – Export Control Desk**  
📧 societyaccelerationist2127299@proton.me  
🔑 PGP Public Key: available on request

-----------------------------------------------------------------
### 9 Hierarchy of Terms  
This notice supplements `LICENSE.md`. Where conflicts arise, **the stricter term controls**.

> **Disclaimer:** This document is provided for informational purposes only and is **not legal advice**.  
> Consult a qualified export‑control attorney or compliance officer for specific guidance.
