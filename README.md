# Nist-800-53-Compliance-Program-Riverside
NIST 800-53 mini compliance program with control matrix and gap analysis for a healthcare clinic

# Mini Compliance Program — NIST 800-53 (Riverside Physical Therapy)

A self-directed GRC project simulating the foundational work a Governance, Risk, and Compliance (GRC) analyst performs when building a compliance program for a healthcare organization from the ground up.

## Project Summary

This project builds a mini compliance program for **Riverside Physical Therapy**, a fictional single-location outpatient clinic with approximately 20–30 staff. Using **NIST SP 800-53** as the governing framework (selected for its strong alignment with HIPAA in U.S. healthcare settings), the project walks through the full lifecycle a real compliance program follows:

1. **Scoping** — defining the organization, its systems, and what's in/out of bounds for assessment
2. **Control selection** — tailoring 18 controls across 7 relevant NIST families (Access Control, Audit & Accountability, Incident Response, Identification & Authentication, System & Communications Protection, Contingency Planning, and Configuration Management)
3. **Control matrix** — assessing each control's current status (Missing / Partial / Implemented), assigning an accountable owner, and documenting specific remediation actions
4. **Gap analysis** — prioritizing the most significant gaps using a likelihood/impact lens, and proposing a sequenced, realistic remediation roadmap

## Deliverables

| File | Description |
|---|---|
| `Riverside_Compliance_Program_Overview.pdf` | Program scope, goals, maturity assessment, and full gap analysis with 5 prioritized findings |
| `Riverside_Control_Matrix.xlsx` / `.pdf` | 18-control matrix with status, ownership, and remediation actions, plus a live summary tab |

## What I Did

- Selected and justified a compliance framework (NIST 800-53) based on the organization's regulatory environment rather than picking one arbitrarily
- Scoped a realistic environment (EHR, workstations, network/VPN, email, backups, access management) the way an analyst would before any assessment begins
- Tailored a representative 18-control sample from NIST's full catalog, rather than assessing every control indiscriminately
- Assessed each control's real-world status and assigned ownership to roles that realistically exist at a small organization (IT Support Specialist, Office Manager, Clinic Director)
- Performed a likelihood/impact-based gap analysis to prioritize 5 findings out of many possible gaps
- Built a sequenced remediation roadmap that accounts for dependencies (e.g., policy work before technical fixes, technical fixes before structural/programmatic changes)
- Identified a cross-cutting structural finding — concentration of control ownership in a single role — that wasn't tied to any one control, but emerged from looking at the matrix as a whole

## What I Learned

- **Frameworks are translation tools, not checklists.** A control like "the organization manages information system accounts" means nothing until it's mapped to a specific system, a specific owner, and a specific current state. Most of the real work in GRC is that translation step.
- **Status isn't binary.** Almost nothing is fully "done" or fully "missing" — most controls in a real organization sit in a partial state, and learning to assess *degree* of implementation (not just presence/absence) is a core analytical skill.
- **Ownership without accountability isn't ownership.** Assigning every gap to "IT" without naming a specific role creates the same failure mode auditors flag constantly: a control nobody is actually responsible for never gets fixed.
- **Prioritization is a skill, not a formality.** With 7 missing controls to choose from, picking the right 4–5 to highlight — and being able to explain *why* those and not others — was harder and more valuable than identifying the gaps in the first place.
- **The most useful findings aren't always in the matrix.** The biggest single insight from this project (ownership concentration) wasn't a control gap at all — it came from stepping back and asking a structural question about the matrix itself, rather than just reading down the rows.

## Real-World Application

This mirrors work that real GRC analysts perform constantly, particularly at small and mid-sized healthcare organizations that don't have a dedicated compliance department:

- **Pre-audit readiness** — control matrices like this one are exactly what organizations build before a HIPAA risk assessment, SOC 2 audit, or payer/insurance compliance review
- **Vendor and partner due diligence** — healthcare organizations are increasingly asked by insurers, partners, and regulators to demonstrate documented control ownership, not just technical safeguards
- **Incident and breach preparedness** — the HIPAA Breach Notification Rule findings in this project reflect a real, recurring gap at smaller healthcare providers, where IT teams handle technical security but no one owns the legal/regulatory response process
- **Resource-constrained environments** — most small organizations don't have a CISO or compliance officer; this project intentionally reflects that reality by assigning controls to roles (IT Support, Office Manager, Clinic Director) that actually exist in organizations this size, rather than assuming idealized GRC staffing

## Conclusion

This project demonstrates the foundational GRC analyst skill set: taking an abstract framework, applying it to a specific organization, identifying where reality falls short of the requirement, and building a realistic, prioritized plan to close that gap. It also reflects something important about real compliance work — the goal isn't a perfect scorecard, it's a defensible, well-reasoned path from where an organization stands today to where it needs to be, sequenced in a way that a small team can actually execute. The combination of technical assessment (the control matrix) and business communication (the program overview and gap analysis) reflects the dual nature of GRC work: it sits between IT/security execution and organizational risk decision-making, translating between the two.

---
*This is a self-directed portfolio project using a fictional organization. It does not reflect any real company's compliance posture.*
