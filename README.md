# HIPAA Compliance Checklist

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Last Updated](https://img.shields.io/badge/Updated-April_2026-blue.svg)](https://github.com/PetronellaTech/hipaa-compliance-checklist)
[![Stars](https://img.shields.io/github/stars/PetronellaTech/hipaa-compliance-checklist?style=social)](https://github.com/PetronellaTech/hipaa-compliance-checklist)

> A complete HIPAA compliance checklist for healthcare organizations and business associates covering the Privacy Rule, Security Rule, and Breach Notification Rule with practical implementation guidance.

---

## Table of Contents

- [Overview](#overview)
- [Who Must Comply with HIPAA](#who-must-comply-with-hipaa)
- [HIPAA Rules at a Glance](#hipaa-rules-at-a-glance)
- [Privacy Rule Checklist](#privacy-rule-checklist)
- [Security Rule Checklist](#security-rule-checklist)
- [Breach Notification Rule Checklist](#breach-notification-rule-checklist)
- [Business Associate Requirements](#business-associate-requirements)
- [Risk Assessment Guide](#risk-assessment-guide)
- [Penalties and Enforcement](#penalties-and-enforcement)
- [2025-2026 Updates](#2025-2026-updates)
- [Common Compliance Gaps](#common-compliance-gaps)
- [Additional Resources](#additional-resources)
- [About Petronella Technology Group](#about-petronella-technology-group)

---

## Overview

The **Health Insurance Portability and Accountability Act (HIPAA)** establishes national standards for protecting the privacy and security of individually identifiable health information, known as **Protected Health Information (PHI)**. This HIPAA compliance checklist covers all three major rules that organizations must follow: the Privacy Rule, the Security Rule, and the Breach Notification Rule.

Whether you are a hospital, medical practice, health insurance company, pharmacy, or a business associate that handles PHI on behalf of a covered entity, this checklist provides a systematic approach to evaluating and improving your HIPAA compliance posture.

## Who Must Comply with HIPAA

### Covered Entities

- [ ] **Health Plans** - Health insurance companies, HMOs, employer-sponsored health plans, government health programs (Medicare, Medicaid)
- [ ] **Healthcare Providers** - Any provider that transmits health information electronically: doctors, hospitals, clinics, pharmacies, dentists, chiropractors, nursing homes, psychologists
- [ ] **Healthcare Clearinghouses** - Entities that process nonstandard health information into standard formats

### Business Associates

- [ ] **Any organization** that creates, receives, maintains, or transmits PHI on behalf of a covered entity
- [ ] Examples: IT service providers, cloud hosting providers, EHR vendors, billing companies, shredding companies, lawyers, accountants, consultants with PHI access

> **Key point**: Since the 2013 HIPAA Omnibus Rule, business associates are **directly liable** for compliance with the Security Rule and breach notification requirements.

## HIPAA Rules at a Glance

| Rule | Statute | Scope | Key Requirement |
|------|---------|-------|----------------|
| **Privacy Rule** | 45 CFR Parts 160, 164 (Subparts A, E) | Use and disclosure of PHI | Minimum Necessary standard, patient rights, Notice of Privacy Practices |
| **Security Rule** | 45 CFR Parts 160, 164 (Subpart C) | Electronic PHI (ePHI) | Administrative, physical, and technical safeguards |
| **Breach Notification Rule** | 45 CFR Parts 160, 164 (Subpart D) | Notification after breach | 60-day notification to individuals, HHS, and media (if 500+ affected) |
| **Enforcement Rule** | 45 CFR Part 160 (Subparts C-E) | Penalties and investigations | Tiered penalties up to $2.1M per violation category per year |

---

## Privacy Rule Checklist

The Privacy Rule governs how PHI is used and disclosed, and establishes patient rights regarding their health information.

### Administrative Requirements

- [ ] **Designate a Privacy Officer** responsible for developing and implementing privacy policies and procedures
- [ ] **Develop written privacy policies and procedures** that comply with the Privacy Rule
- [ ] **Distribute a Notice of Privacy Practices (NPP)** to all patients at first service encounter
- [ ] **Obtain signed acknowledgment** of receipt of the NPP from patients (make good-faith effort)
- [ ] **Train all workforce members** on privacy policies within a reasonable time of hiring and periodically thereafter
- [ ] **Apply appropriate sanctions** against workforce members who violate privacy policies
- [ ] **Establish a complaint process** for patients to file privacy-related complaints
- [ ] **Document all privacy policies, procedures, and actions** and retain for at least 6 years from creation or last effective date
- [ ] **Mitigate any harmful effects** of a use or disclosure that violates policies

### Minimum Necessary Standard

- [ ] **Identify roles** that need access to PHI and the categories of PHI each role requires
- [ ] **Limit PHI access** to the minimum necessary to accomplish the intended purpose for each use, disclosure, and request
- [ ] **Implement policies for routine disclosures** that limit the PHI disclosed to standard, pre-approved sets
- [ ] **Develop criteria for non-routine disclosures** that require case-by-case review
- [ ] **Establish reasonable reliance standards** for requests from other covered entities, public officials, and researchers

### Patient Rights

- [ ] **Right of Access** - Provide patients access to their PHI within 30 days of request (one 30-day extension permitted). Fees limited to reasonable cost-based amounts per HHS guidance ($6.50 flat fee safe harbor or actual costs)
- [ ] **Right to Amend** - Allow patients to request amendments to their PHI. Respond within 60 days. May deny but must provide written reason
- [ ] **Right to Accounting of Disclosures** - Provide an accounting of disclosures made in the prior 6 years (excluding treatment, payment, operations, and other exceptions)
- [ ] **Right to Request Restrictions** - Accept requests to restrict use/disclosure of PHI. Not required to agree, EXCEPT for disclosures to health plans for services paid in full out of pocket
- [ ] **Right to Confidential Communications** - Accommodate reasonable requests to receive communications by alternative means or at alternative locations
- [ ] **Right to a Paper Copy of NPP** - Provide a paper copy of the Notice of Privacy Practices upon request

### Permitted Uses and Disclosures

- [ ] **Treatment, Payment, and Healthcare Operations (TPO)** - PHI may be used/disclosed without authorization for TPO
- [ ] **Authorization required** for uses beyond TPO: marketing, sale of PHI, psychotherapy notes, and most research
- [ ] **Authorizations must include**: description of PHI, who may use/disclose, purpose, expiration date, right to revoke, signature
- [ ] **Public interest exceptions documented**: required by law, public health, abuse/neglect reporting, health oversight, judicial proceedings, law enforcement, decedents, organ donation, research, serious threats, workers' compensation, government functions

### De-identification

- [ ] **Expert Determination method** or **Safe Harbor method** used when de-identifying PHI
- [ ] **Safe Harbor**: Remove all 18 identifiers (names, dates, geographic data smaller than state, phone numbers, emails, SSNs, MRNs, health plan numbers, account numbers, certificate/license numbers, vehicle identifiers, device identifiers, URLs, IP addresses, biometric identifiers, full-face photos, any other unique number/code)
- [ ] **No actual knowledge** that remaining information could identify an individual

---

## Security Rule Checklist

The Security Rule requires covered entities and business associates to implement safeguards to protect the confidentiality, integrity, and availability of **electronic PHI (ePHI)**. Safeguards are categorized as Required (R) or Addressable (A).

### Administrative Safeguards (45 CFR 164.308)

- [ ] **(R) Security Management Process** (164.308(a)(1))
  - [ ] Conduct a thorough **risk analysis** to identify threats and vulnerabilities to ePHI
  - [ ] Implement a **risk management** program to reduce risks to a reasonable and appropriate level
  - [ ] Apply a **sanction policy** for workforce members who violate security policies
  - [ ] Implement procedures to regularly review **information system activity** (audit logs, access reports, security incident tracking)

- [ ] **(R) Assigned Security Responsibility** (164.308(a)(2))
  - [ ] Designate a **Security Officer** responsible for developing and implementing security policies

- [ ] **(A) Workforce Security** (164.308(a)(3))
  - [ ] Implement procedures for **authorization and/or supervision** of workforce members who access ePHI
  - [ ] Implement procedures to determine that access is **appropriate based on role**
  - [ ] Implement procedures for **terminating access** when employment ends or role changes

- [ ] **(A) Information Access Management** (164.308(a)(4))
  - [ ] Implement policies and procedures for **authorizing access** to ePHI consistent with Privacy Rule minimum necessary
  - [ ] Implement policies for **granting access** to ePHI (e.g., provisioning workstation, account, and application access)
  - [ ] Implement policies for **modifying access** based on role changes

- [ ] **(R) Security Awareness and Training** (164.308(a)(5))
  - [ ] Provide **security reminders** (periodic awareness updates)
  - [ ] Train on procedures for **guarding against malicious software**
  - [ ] Train on procedures for **login monitoring** (recognizing unauthorized access)
  - [ ] Train on procedures for **password management**

- [ ] **(R) Security Incident Procedures** (164.308(a)(6))
  - [ ] Implement policies to **identify and respond to** suspected or known security incidents
  - [ ] **Mitigate harmful effects** of security incidents to the extent practicable
  - [ ] **Document** security incidents and their outcomes

- [ ] **(R) Contingency Plan** (164.308(a)(7))
  - [ ] Establish a **data backup plan** for creating and maintaining retrievable exact copies of ePHI
  - [ ] Establish a **disaster recovery plan** for restoring lost data
  - [ ] Establish an **emergency mode operations plan** to enable continuation of critical processes during an emergency
  - [ ] Implement procedures for periodic **testing and revision** of contingency plans
  - [ ] Assess the **criticality of applications and data** to determine recovery priorities

- [ ] **(R) Evaluation** (164.308(a)(8))
  - [ ] Perform periodic **technical and nontechnical evaluations** in response to environmental or operational changes

- [ ] **(R) Business Associate Contracts** (164.308(b)(1))
  - [ ] Obtain **satisfactory assurances** from each business associate that they will appropriately safeguard ePHI (i.e., sign a BAA)

### Physical Safeguards (45 CFR 164.310)

- [ ] **(A) Facility Access Controls** (164.310(a)(1))
  - [ ] Establish a **contingency operations** procedure for allowing facility access to restore lost data
  - [ ] Implement a **facility security plan** to safeguard the facility and equipment from unauthorized physical access
  - [ ] Implement **access control and validation** procedures to control and validate a person's access to facilities
  - [ ] Document **maintenance records** of physical security repairs and modifications

- [ ] **(R) Workstation Use** (164.310(b))
  - [ ] Implement policies specifying **proper functions, manner of use, and physical environment** for workstations accessing ePHI

- [ ] **(R) Workstation Security** (164.310(c))
  - [ ] Implement **physical safeguards** that restrict access to workstations to authorized users only

- [ ] **(A) Device and Media Controls** (164.310(d)(1))
  - [ ] Implement policies for **disposal** of ePHI and hardware/media containing it
  - [ ] Implement procedures for **media re-use** to ensure ePHI is removed before re-use
  - [ ] Maintain **accountability** records for hardware and media movements
  - [ ] Create **data backups** of ePHI before equipment is moved

### Technical Safeguards (45 CFR 164.312)

- [ ] **(R) Access Control** (164.312(a)(1))
  - [ ] Assign **unique user identification** (unique username/number) to each user
  - [ ] Establish an **emergency access procedure** for obtaining ePHI during an emergency
  - [ ] Implement **automatic logoff** after a predetermined period of inactivity
  - [ ] Implement **encryption and decryption** of ePHI (addressable but strongly recommended)

- [ ] **(R) Audit Controls** (164.312(b))
  - [ ] Implement hardware, software, and/or procedural mechanisms to **record and examine activity** in systems containing ePHI

- [ ] **(R) Integrity** (164.312(c)(1))
  - [ ] Implement policies and procedures to **protect ePHI from improper alteration or destruction**
  - [ ] Implement electronic mechanisms to **corroborate that ePHI has not been altered or destroyed** in an unauthorized manner

- [ ] **(R) Person or Entity Authentication** (164.312(d))
  - [ ] Implement procedures to **verify that a person or entity seeking access** to ePHI is the one claimed

- [ ] **(R) Transmission Security** (164.312(e)(1))
  - [ ] Implement security measures to ensure **integrity of ePHI during transmission** (guard against unauthorized modification)
  - [ ] Implement **encryption** for ePHI transmitted over electronic networks (addressable but strongly recommended for email and internet-based transmission)

---

## Breach Notification Rule Checklist

### Breach Definition and Risk Assessment

A **breach** is the acquisition, access, use, or disclosure of unsecured PHI in a manner not permitted by the Privacy Rule that compromises the security or privacy of the PHI.

- [ ] **Conduct a four-factor risk assessment** for each suspected breach:
  1. The nature and extent of PHI involved (types of identifiers, likelihood of re-identification)
  2. The unauthorized person who used the PHI or to whom the disclosure was made
  3. Whether the PHI was actually acquired or viewed
  4. The extent to which the risk to the PHI has been mitigated

- [ ] **Document the risk assessment** and determination for each incident

### Notification Requirements

- [ ] **Individual notification**: Notify affected individuals without unreasonable delay, and no later than **60 days** after discovery of the breach
- [ ] **Written notice by first-class mail** (or email if the individual has agreed) including:
  - [ ] Description of the breach (what happened, date of breach, date of discovery)
  - [ ] Types of PHI involved
  - [ ] Steps the individual should take to protect themselves
  - [ ] What the organization is doing to investigate, mitigate, and prevent future breaches
  - [ ] Contact information for questions (toll-free phone number, email, postal address)
- [ ] **Substitute notice** if contact information is insufficient for 10+ individuals: conspicuous posting on website for 90 days or notice in major media
- [ ] **HHS notification**: Report to the Secretary of HHS
  - [ ] **500+ individuals affected**: Notify HHS and prominent media outlets simultaneously with individual notification (within 60 days)
  - [ ] **Fewer than 500**: Notify HHS within 60 days of the end of the calendar year in which the breach was discovered (via the HHS Breach Portal)
- [ ] **Media notification**: If 500+ individuals in a state or jurisdiction are affected, notify prominent media outlets in that area within 60 days

### Exceptions to Breach Definition

- [ ] **Unintentional access** by a workforce member acting under the authority of the covered entity or business associate, in good faith and within the scope of authority, with no further use or disclosure
- [ ] **Inadvertent disclosure** between authorized persons at the same covered entity, business associate, or organized health care arrangement, with no further use or disclosure
- [ ] **Good faith belief** that the unauthorized person to whom the disclosure was made would not reasonably have been able to retain the PHI

---

## Business Associate Requirements

### Business Associate Agreement (BAA) Essentials

Every BAA must include:

- [ ] **Description of permitted uses and disclosures** of PHI by the BA
- [ ] **Prohibition on further use or disclosure** beyond what is permitted or required by the contract or law
- [ ] **Requirement to implement appropriate safeguards** to prevent unauthorized use or disclosure
- [ ] **Requirement to report** any use or disclosure not provided for, including breaches of unsecured PHI
- [ ] **Requirement that BA ensure any subcontractors** agree to the same restrictions (downstream BAAs)
- [ ] **Requirement to make PHI available** to covered entity to fulfill patient access rights
- [ ] **Requirement to make PHI available for amendment** and incorporate amendments
- [ ] **Requirement to make information available for accounting** of disclosures
- [ ] **Requirement to make internal practices available to HHS** for compliance determination
- [ ] **Requirement to return or destroy PHI** at termination of the agreement (where feasible)
- [ ] **Authorization for termination** if the BA violates a material term of the agreement

### Common Business Associate Categories

| Category | Examples | Key PHI Risk |
|----------|----------|-------------|
| **IT/MSP** | Managed IT providers, cloud hosting, backup services | Full ePHI access, infrastructure control |
| **EHR Vendors** | Epic, Cerner, athenahealth, eClinicalWorks | Complete clinical record access |
| **Billing/Coding** | Medical billing companies, clearinghouses | Diagnosis codes, insurance information |
| **Legal/Consulting** | Healthcare attorneys, compliance consultants | PHI in legal files and consulting records |
| **Shredding/Disposal** | Document destruction, e-waste companies | PHI on discarded media |
| **Communication** | Answering services, patient portals, secure messaging | Real-time PHI in communications |

---

## Risk Assessment Guide

The HIPAA Security Rule **requires** a thorough risk analysis. Here is a step-by-step approach:

### Step 1: Scope the Assessment

- [ ] Identify all systems that create, receive, maintain, or transmit ePHI
- [ ] Include all physical locations, remote workers, cloud services, and mobile devices
- [ ] Identify all workforce members with access to ePHI

### Step 2: Identify Threats and Vulnerabilities

| Threat Category | Examples |
|----------------|---------|
| **Natural** | Floods, earthquakes, storms, power outages |
| **Human (intentional)** | Hackers, ransomware, disgruntled employees, social engineering |
| **Human (unintentional)** | Misdirected emails, lost devices, misconfigured systems |
| **Environmental** | HVAC failure, power surges, water leaks |

### Step 3: Assess Current Controls

- [ ] Document existing administrative safeguards (policies, training)
- [ ] Document existing physical safeguards (locks, cameras, device management)
- [ ] Document existing technical safeguards (encryption, access controls, logging)

### Step 4: Determine Likelihood and Impact

- [ ] Rate each threat-vulnerability pair on likelihood (Low/Medium/High)
- [ ] Rate potential impact to confidentiality, integrity, and availability (Low/Medium/High)
- [ ] Calculate risk level (Likelihood x Impact)

### Step 5: Document and Remediate

- [ ] Document all findings in a **Risk Assessment Report**
- [ ] Create a **Risk Management Plan** prioritizing high-risk items
- [ ] Implement controls to reduce risk to reasonable and appropriate levels
- [ ] Establish a schedule for periodic reassessment (annually recommended)

---

## Penalties and Enforcement

### HIPAA Penalty Tiers (as adjusted for inflation, 2026)

| Tier | Knowledge Level | Per Violation | Annual Maximum |
|------|----------------|---------------|----------------|
| **Tier 1** | Did not know and could not have known | $137 - $68,928 | $2,067,813 |
| **Tier 2** | Reasonable cause, not willful neglect | $1,379 - $68,928 | $2,067,813 |
| **Tier 3** | Willful neglect, corrected within 30 days | $13,785 - $68,928 | $2,067,813 |
| **Tier 4** | Willful neglect, not corrected | $68,928 - $2,067,813 | $2,067,813 |

> **Note**: Criminal penalties can reach up to $250,000 and 10 years imprisonment for offenses committed with intent to sell or use PHI for personal gain.

### Recent Notable Settlements

- HHS has been active in enforcing right-of-access violations (settlements ranging from $15,000 to $240,000)
- Ransomware-related investigations are increasing, with settlements often exceeding $1 million
- State attorneys general can also enforce HIPAA, with separate penalties

---

## 2025-2026 Updates

### HIPAA Security Rule NPRM (2024-2025)

HHS proposed significant updates to the Security Rule in late 2024. While the final rule is pending, organizations should prepare for:

- [ ] **Mandatory encryption** of ePHI at rest and in transit (removing addressable status)
- [ ] **Mandatory MFA** for all systems containing ePHI
- [ ] **72-hour notification to covered entity** from business associates after a breach (reduced from "unreasonable delay")
- [ ] **Annual security risk assessments** (codifying current best practice)
- [ ] **Network segmentation** requirements for systems containing ePHI
- [ ] **Vulnerability scanning every 6 months** and penetration testing annually
- [ ] **12-month maximum for PHI data retention** review cycles
- [ ] **Technology asset inventory** requirements with 24-hour update mandate for changes

> **Important**: These are proposed changes. Monitor the Federal Register for the final rule. Start preparing now, as compliance timelines will likely be 180 days to 1 year after final publication.

---

## Common Compliance Gaps

1. **Incomplete BAAs**: Many organizations have vendors with PHI access but no BAA in place. Audit all vendor relationships.
2. **No documented risk assessment**: The single most common finding in HHS investigations. Must be documented, not just "understood."
3. **Lack of encryption**: Encryption is addressable (not required under current rules), but unencrypted ePHI on stolen/lost devices is automatically a breach.
4. **Insufficient access controls**: Shared logins, excessive access privileges, and no role-based access.
5. **Missing audit logs**: Systems must log access to ePHI, and logs must be reviewed regularly.
6. **No contingency plan testing**: Having a plan is not enough. It must be tested and updated.
7. **Workforce training gaps**: Training must be role-specific and documented with dates and content.
8. **Ignoring mobile devices**: Smartphones and tablets that access ePHI must be covered by security policies, MDM, and encryption.
9. **Email PHI without encryption**: Sending unencrypted ePHI via email is a common source of breaches.
10. **No incident response plan**: Many organizations cannot articulate how they would detect, contain, and report a breach.

---

## Additional Resources

- [HHS HIPAA Home Page](https://www.hhs.gov/hipaa/index.html) - Official HIPAA guidance
- [NIST Cybersecurity Framework and HIPAA Crosswalk](https://www.hhs.gov/hipaa/for-professionals/security/nist-security-hipaa-crosswalk/index.html) - Mapping NIST CSF to HIPAA
- [HHS Breach Portal (Wall of Shame)](https://ocrportal.hhs.gov/ocr/breach/breach_report.jsf) - Reported breaches of 500+ records
- [HHS Security Risk Assessment Tool (SRA)](https://www.healthit.gov/topic/privacy-security-and-hipaa/security-risk-assessment-tool) - Free risk assessment tool from HHS/ONC
- [OCR Guidance on Ransomware](https://www.hhs.gov/hipaa/for-professionals/security/guidance/cybersecurity/index.html) - Ransomware-specific guidance
- [45 CFR Parts 160 and 164](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164) - Full regulatory text

---

## Professional Compliance Services

Need help implementing these controls? **Petronella Technology Group** provides comprehensive compliance consulting:

- [HIPAA Compliance Services](https://petronellatech.com/compliance/hipaa-compliance/) - Healthcare security assessments
- [Cybersecurity Services](https://petronellatech.com/cybersecurity/) - Managed security and assessments
- [CMMC Compliance Guide](https://petronellatech.com/compliance/cmmc-compliance-guide/) - Full CMMC Level 2 preparation
- [AI-Powered Security](https://petronellatech.com/ai/ai-services/) - AI infrastructure with compliance built in

**Petronella Technology Group** is a CMMC-RP certified cybersecurity firm headquartered in Raleigh, NC. Our entire team holds CMMC Registered Practitioner credentials. [Contact us](https://petronellatech.com/contact-us/) or call (919) 348-4912.

## About Petronella Technology Group

[Petronella Technology Group (PTG)](https://petronellatech.com) has provided cybersecurity, compliance, and managed IT services from Raleigh, NC since 2002. Our entire team holds **CMMC-RP (Registered Practitioner)** certification, and we have deep expertise in healthcare IT security:

- **Craig Petronella** (Founder) - CMMC-RP, CCNA, CWNE, DFE #604180
- **Blake Rea** - CMMC-RP
- **Justin Summers** - CMMC-RP
- **Jonathan Wood** - CMMC-RP

We serve healthcare organizations including medical practices, dental offices, behavioral health providers, and their business associates across the Southeast.

### Get Professional Help

PTG offers comprehensive HIPAA compliance services:

- **HIPAA Risk Assessments** - Thorough technical and administrative assessments meeting HHS requirements
- **HIPAA Policies and Procedures** - Complete documentation packages customized to your organization
- **Technical Remediation** - Encryption, access controls, logging, backup, and disaster recovery implementation
- **Ongoing Compliance Monitoring** - Managed security services with HIPAA-specific reporting
- **Breach Response Support** - Incident investigation, notification assistance, and HHS reporting guidance

[Schedule a Free Consultation](https://petronellatech.com/contact/) | Call **(919) 422-2607**

Visit [petronellatech.com/hipaa-compliance/](https://petronellatech.com/hipaa-compliance/) for more HIPAA resources.

---

*Maintained by [Petronella Technology Group](https://petronellatech.com) | 5540 Centerview Dr, Suite 200, Raleigh, NC 27606 | (919) 422-2607 | Founded 2002*

*This checklist is provided for informational purposes. It is not legal advice. Consult with a qualified HIPAA compliance professional for formal guidance.*
