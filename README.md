# hipaa-and-iam-healthcare-foundations
HIPAA and IAM — Healthcare Foundations for Identity and Access Management. How physical healthcare security experience (HMSA) maps to digital IAM: PHI, minimum necessary, least privilege, and the road to SC-900, Security+, and CHPA.
HIPAA and IAM — Healthcare Foundations for Identity and Access Management

Security, access control, and human-led technology have defined my career in Hawai'i. This project connects what I practiced for years in physical healthcare security to what I am now building in digital Identity and Access Management (IAM).

## What this project is

A study and portfolio project in three parts: the HIPAA foundations I completed in Track 1 — Workforce Foundations, the healthcare security experience I brought from HMSA, and the direct line from both to IAM work in Microsoft Entra ID and Okta.

The principle behind all of it is the same one I use at Kepani Digital: AI proposes; the human decides. In healthcare, the human decision is not optional — it is the safeguard.

## Status

Passed — November 23, 2026: I passed the HIPAA Lab Track 1 — HIPAA Workforce Foundations exam on November 23, 2026 with a score of 100%. Certificate issued November 23, 2026, valid through November 23, 2027. Certified HIPAA Privacy Associate (CHPA) and Microsoft SC-900 are in preparation, not yet earned.

## Track 1 — Workforce Foundations

### Module 1 — PHI and the 18 identifiers

Individually Identifiable Health Information (IIHI) becomes Protected Health Information (PHI) when it is transmitted or maintained in any form — electronic, paper, or spoken — by a Covered Entity or Business Associate and contains identifiers linking it to a person. Under the Safe Harbor method, 45 CFR 164.514(b)(2), all 18 identifiers must be removed for data to count as de-identified: names, addresses and ZIP codes, dates (except year), phone, fax, and email, Social Security numbers, medical record numbers, health plan and account numbers, certificate and license numbers, vehicle and device serial numbers, URLs, IP addresses, biometric identifiers, full-face photos, and any other unique identifying code. If any one identifier sits next to health data, the whole record is PHI.

### Module 2 — Covered Entities and Business Associates

Covered Entities fall into three groups under 45 CFR 160.103: healthcare providers, health plans, and healthcare clearinghouses. A Business Associate is any outside person or company that creates, receives, maintains, or transmits PHI for a Covered Entity — billing companies, cloud and IT vendors, and consultants included. Storing data counts, even if it is never viewed. Under the Omnibus Rule, Business Associates are directly liable for Privacy and Security Rule violations.

### Module 3 — Everyday compliance

- Minimum Necessary (45 CFR 164.502(b)): use, disclose, or request only the minimum PHI needed for the purpose. It does not apply to treatment, disclosures to the patient, or signed authorizations.
- Workplace safeguards: clear desk, locked cabinets, screens angled from public view, manual lock (Win + L) and automatic logoff, verified fax numbers with a confidentiality cover sheet, and VPN with multi-factor authentication (MFA) for remote work.
- Training (45 CFR 164.530(b)): training comes before access — during onboarding — then annually and whenever policies materially change.

## From HMSA to IAM

From 2019 to 2023 I worked security at HMSA, a health plan in Hawai'i, in HIPAA-related security and confidentiality environments: physical access control, identity verification, badge checks, incident documentation, and keeping patient areas private. Track 1 gave that experience its formal language — and showed how directly it maps to digital IAM.

- Minimum Necessary → Least privilege — a billing role sees billing codes, not the full chart; the same rule applied through roles in Entra ID and Okta
- Training before access → Joiner process — no system access until onboarding and training are complete
- Clear desk, locked screens → Workstation security, session lock, and automatic logoff by policy
- Pretexting defense → Never act on a verbal claim — verify by callback to a known number, use MFA, escalate to the Security Officer; the help-desk version of identity proofing
- Incidental disclosure vs. violation → Reasonable safeguards decide the line — quiet check-in overheard is incidental; a patient list left face-up is a failure of care
- Business Associate liability → Vendor and third-party access governance — anyone who stores PHI is accountable, even if they never open it

## Where this goes next

- Microsoft SC-900 + hands-on IAM: Entra ID and Okta labs, with SailPoint, CyberArk, and BeyondTrust next.
- CompTIA Security+ planned: the DoD 8570 IAT II certification. Study on Udemy alongside the Entra ID modules; exam cost covered by Good Jobs Hawai'i 2027 courses. Exam SY0-701 retires June 11, 2027.
- CHPA planned: Certified HIPAA Privacy Associate, $99, through hipaatraining.net.
- Healthcare IAM focus: IAM work where healthcare experience counts — hospitals, health plans, and their Business Associates in Hawai'i.

## Where this project lives

This project also lives on Notion, Hugging Face, Linktree, kepanidigital.org, my WordPress blog, and LinkedIn Projects.

---

Herman Kepani Jr. — IAM & Cybersecurity Analyst (In Training), Founder & CEO, Kepani Digital LLC, Honolulu, Hawaii.
