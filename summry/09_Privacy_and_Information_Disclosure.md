# Privacy and Information Disclosure
**Course:** Data and Ethics | Dr. Ali Algarni  
**Sources:** Week 4 slides | Medium article (Ian Clemence) | GDPR | SDAIA/PDPL | NDMO | DPO Role

---

## 🗺️ Big Picture

```
PRIVACY (right) → INFORMATION DISCLOSURE (risk)
        ↓
Who governs how personal data is disclosed?
  ├── Individuals       → rights (access, correct, delete, opt-out)
  ├── Organizations     → obligations (consent, security, minimization)
  └── Governments       → regulations (GDPR, PDPL, CCPA)
        ↓
Who enforces it?
  ├── SDAIA/PDPL        → Saudi Arabia
  ├── GDPR              → European Union
  ├── NDMO              → Saudi National Data Management Office
  └── DPO               → Data Privacy Officer (inside organizations)
        ↓
What happens when it fails?
  └── Data breach incidents → SDAIA 2024 cases
```

---

## 1. What is Information Disclosure?

> **Information Disclosure** = the act of making personal or sensitive data available — intentionally or unintentionally — to parties who may or may not be authorized to receive it.

### Why it's Ethically Significant

| Type | Description | Example |
|------|-------------|---------|
| **Authorized Disclosure** | Sharing data with parties who have legitimate need and consent | Hospital sharing records with treating physician |
| **Unauthorized Disclosure** | Data accessed or shared without consent | Facebook 2021 — 533M users' data leaked |
| **Contextually Inappropriate Disclosure** | Sharing in a way that violates the original context | Medical data sold to advertisers |
| **Legally Required Disclosure** | Disclosure mandated by law | Court-ordered data access |

### The Contextual Integrity Principle
> Data flows ethically when they **match the norms of the context** in which data was originally shared.

| Original Context | Appropriate flow | Inappropriate flow |
|-----------------|-----------------|-------------------|
| Medical visit | Doctor → treating specialist | Doctor → insurance company without consent |
| Job application | Employer HR team | Employer → credit bureau |
| Survey (research) | Research team | Research team → marketing firm |

---

## 2. GDPR — General Data Protection Regulation

> **Jurisdiction:** European Union  
> **In effect:** May 25, 2018  
> **Reference:** gdpr-info.eu/chapter-2

### Core Purpose
- Protect EU citizens' personal data
- Give individuals control over their own data
- Harmonize data protection laws across EU member states

### Key GDPR Rights (Individual Rights)

| Right | What it means | Article |
|-------|--------------|---------|
| **Right of Access** | You can ask any organization what data they hold on you | Art. 15 |
| **Right to Rectification** | You can correct inaccurate personal data | Art. 16 |
| **Right to Erasure** | "Right to be Forgotten" — you can request deletion | Art. 17 |
| **Right to Restriction** | You can limit how your data is processed | Art. 18 |
| **Right to Portability** | You can get your data in a machine-readable format | Art. 20 |
| **Right to Object** | You can object to processing (e.g., for marketing) | Art. 21 |
| **Right against automated decision-making** | Right to human review of automated decisions | Art. 22 |

### GDPR Key Principles (Article 5)

| Principle | Meaning |
|-----------|---------|
| **Lawfulness, fairness, transparency** | Processing must be legal, fair, and clear |
| **Purpose limitation** | Data collected for one purpose can't be used for another |
| **Data minimization** | Collect only what's necessary |
| **Accuracy** | Keep data accurate and up-to-date |
| **Storage limitation** | Don't keep data longer than needed |
| **Integrity and confidentiality** | Protect data with appropriate security |
| **Accountability** | Organizations must demonstrate compliance |

### Consent Under GDPR
- Must be **freely given, specific, informed, and unambiguous**
- Must be as easy to **withdraw** consent as to give it
- Pre-ticked boxes = NOT valid consent
- **Opt-in** is the GDPR default — not opt-out

### GDPR Breach Notification
- Organizations must notify the **supervisory authority within 72 hours** of discovering a breach
- If breach is likely to result in high risk → must also notify **affected individuals without undue delay**

---

## 3. SDAIA — Saudi Data and AI Authority

> **Saudi Arabia's national regulatory body** for data and AI governance  
> Equivalent role to the EU's data protection authorities under GDPR

### SDAIA's Key Instruments

| Instrument | Purpose |
|-----------|---------|
| **PDPL** (Personal Data Protection Law) | Saudi Arabia's primary data protection law |
| **Implementing Regulation of PDPL** | Detailed rules for how PDPL is enforced |
| **SDAIA AI Principles (2025)** | Ethical framework for AI systems (covered in Week 3) |
| **SDAIA Personal Data Breach Incidents 2024** | Published cases of real breaches and penalties |

### PDPL — Key Provisions

| Provision | Detail |
|-----------|--------|
| **Consent** | Required before collecting personal data |
| **Purpose** | Data used only for stated purpose |
| **Data Subject Rights** | Access, correction, deletion, portability |
| **Cross-border transfers** | Restrictions on sending data outside KSA |
| **Breach notification** | Must notify SDAIA and affected individuals |
| **Penalties** | Financial penalties for violations |

### SDAIA vs GDPR Comparison

| | SDAIA / PDPL | GDPR |
|--|-------------|------|
| **Jurisdiction** | Saudi Arabia | European Union |
| **Year** | 2021 (updated 2024) | 2018 |
| **Consent model** | Explicit consent | Explicit consent |
| **Right to be forgotten** | Yes | Yes (Art. 17) |
| **Breach notification** | Yes — to SDAIA | Yes — within 72 hours |
| **AI-specific rules** | Yes — separate SDAIA AI Principles | Separate EU AI Act |
| **Cultural grounding** | Islamic values + Vision 2030 | Secular European values |

---

## 4. NDMO — National Data Management Office

> **NDMO** = Saudi Arabia's office responsible for **national data management standards and governance**  
> Operates under SDAIA

### Role of NDMO
- Sets national data management standards
- Ensures data quality, security, and governance across government entities
- Manages the **National Data Governance Framework**
- Oversees **data classification** (public, restricted, confidential, secret)

### NDMO Data Classification

| Level | Description | Example |
|-------|-------------|---------|
| **Public** | Can be freely shared | Government statistics |
| **Internal** | For organizational use only | Internal reports |
| **Confidential** | Restricted access | Personnel records |
| **Secret** | Highest protection | National security data |

---

## 5. Data Privacy Officer (DPO)

> **DPO** = Data Privacy Officer  
> The designated person within an organization responsible for ensuring data privacy compliance

### When is a DPO Required?
- Under GDPR: **mandatory** for public authorities, large-scale data processors, and those handling sensitive data
- Under PDPL: organizations processing large volumes of personal data must designate a responsible person

### DPO Responsibilities

| Responsibility | Detail |
|----------------|--------|
| **Monitor compliance** | Ensure organization follows GDPR/PDPL |
| **Training** | Educate staff on data protection |
| **Data Protection Impact Assessments (DPIA)** | Assess risks before new data projects |
| **Point of contact** | For data subjects exercising their rights |
| **Liaison with regulators** | Communicate with SDAIA/GDPR authorities |
| **Advise on data processing** | Guidance on new projects and technologies |

### DPO vs. Data Controller vs. Data Processor

| Role | Definition | Example |
|------|-----------|---------|
| **Data Controller** | Decides WHY and HOW data is processed | Hospital deciding to collect patient records |
| **Data Processor** | Processes data on behalf of controller | Cloud storage company |
| **DPO** | Oversees compliance within the organization | Internal privacy compliance officer |

---

## 6. Practical Data Privacy — Techniques

### The 5 C's of Data Ethics (from Ian Clemence article)

| C | Principle | What it requires |
|---|-----------|-----------------|
| **Consent** | Explicit permission before collecting | Opt-in forms; clear checkbox |
| **Clarity** | Clear communication about use | Plain-language privacy policies |
| **Consistency** | Uniform application of policies | Same rules for all users |
| **Control** | Users control their own data | Settings to delete/export data |
| **Consequence** | Awareness of impact of data use | Risk assessments before deployment |

### Opt-in vs. Opt-out (Detailed)

| | Opt-in | Opt-out |
|--|--------|---------|
| **Default state** | User NOT sharing | User IS sharing |
| **Action required** | User must actively agree | User must actively stop |
| **Under GDPR** | ✅ Required | ❌ Not sufficient |
| **Under PDPL** | ✅ Required | ❌ Not sufficient |
| **Dark patterns** | Consent buried in fine print | Opt-out buried in settings |
| **Example** | Newsletter signup box (unchecked by default) | Tracking cookies auto-enabled |

### Technical Privacy Measures (from Ian Clemence article)

#### 1. Data Anonymization
- Remove personally identifiable information (PII)
- Even anonymized data can be re-identified if combined with other data
- **Python example from article:**
```python
from hashlib import sha256
df['email'] = df['email'].apply(lambda x: sha256(x.encode()).hexdigest())
```

#### 2. Encryption
- Secure data at rest AND in transit
- Symmetric vs. Asymmetric (covered Week 4)
- Use of Python's `cryptography` library

#### 3. Access Controls
- Strict permissions — only authorized personnel access sensitive data
- Role-based access control (RBAC)

#### 4. Regular Audits
- Periodic reviews to identify and mitigate privacy risks
- Required under GDPR and PDPL

#### 5. Compliance with Regulations
- GDPR, HIPAA (healthcare US), CCPA (California), PDPL (Saudi)

### Common Pitfalls

| Pitfall | Why it's a problem | Best Practice |
|---------|-------------------|--------------|
| **Over-collection** | More data = more risk | Data minimization |
| **Lack of transparency** | Users don't trust what they can't see | Clear privacy notices |
| **Inadequate security** | Breaches become inevitable | Encryption + access controls |
| **No breach plan** | Response is chaotic and delayed | Incident response plan in advance |

---

## 7. Real-World Breach Cases — SDAIA 2024 Context

### Why Breach Incidents Matter Ethically
- Breaches are not just technical failures — they are **ethical failures**
- They reveal: where consent was unclear, where security was inadequate, where accountability was diffuse
- SDAIA publishes breach cases to create transparency and deterrence

### Categories of Breaches in Saudi Context
| Type | Example Scenario | Ethical Violation |
|------|-----------------|------------------|
| **Unauthorized access** | Employee accesses records beyond their role | Confidentiality violation |
| **Third-party sharing** | Data sold to broker without consent | Purpose limitation violated |
| **Inadequate security** | Unencrypted database exposed online | Integrity and confidentiality violated |
| **Retention violation** | Data kept years after purpose expired | Storage limitation violated |

---

## 🔗 How Privacy & Disclosure Connects to Other Topics

| Privacy/Disclosure Concept | Connected To |
|---------------------------|-------------|
| GDPR Right to Explanation | Week 14 (Black Box — AI can't explain) |
| Opt-in/Opt-out | Week 14 (data collection challenges) |
| Data minimization | Week 14 (over-collection pitfall) |
| DPO role | Week 14 (Data Steward / Data Controller) |
| Contextual integrity | Week 2 (Relativism — norms vary by context) |
| Breach notification | Week 16 (Transparency and Disclosure in cybersecurity) |
| PDPL vs GDPR | Week 3 (SDAIA AI Principles) |
| Anonymization techniques | Week 14 (privacy-preserving techniques) |
| 5 C's of Data Ethics | Week 2 (Big Data Ethics Principles) |

---

## ✅ Expected Exam Questions

### Multiple Choice

**Q1. GDPR requires breach notification to the supervisory authority within:**
- A) 24 hours
- B) 48 hours
- C) ✅ 72 hours
- D) 7 days

**Q2. The "Right to be Forgotten" under GDPR is formally called:**
- A) Right to Restriction
- B) Right to Object
- C) ✅ Right to Erasure (Article 17)
- D) Right to Portability

**Q3. Under GDPR, which consent model is required?**
- A) Opt-out — users share unless they stop
- B) ✅ Opt-in — users must actively agree
- C) Passive consent — implied by using the service
- D) Either — depends on the country

**Q4. A DPO's primary role is:**
- A) Building secure databases
- B) Making marketing decisions about user data
- C) ✅ Overseeing data protection compliance within the organization
- D) Authorizing all data collection

**Q5. "Data collected for medical research cannot be used for advertising" is an application of:**
- A) Data minimization
- B) ✅ Purpose limitation — GDPR principle
- C) Storage limitation
- D) Right to erasure

**Q6. NDMO stands for:**
- A) National Digital Management Organization
- B) ✅ National Data Management Office (Saudi Arabia)
- C) Network Data Monitoring Operations
- D) National Data and Metrics Office

**Q7. The 5 C's of Data Ethics are:**
- A) Collection, Control, Compliance, Clarity, Consequence
- B) ✅ Consent, Clarity, Consistency, Control, Consequence
- C) Confidentiality, Compliance, Control, Clarity, Consequence
- D) Consent, Confidentiality, Control, Compliance, Clarity

**Q8. Which is NOT a GDPR principle?**
- A) Data minimization
- B) Purpose limitation
- C) ✅ Profit maximization
- D) Accountability

### Essay Questions

**Q: Explain the individual rights granted under GDPR. Which of these rights is most relevant to AI systems, and why?**  
*Hint:* Art. 22 — right against automated decision-making = most relevant to AI; Black Box problem.

**Q: What is the role of a DPO? How does it differ from a Data Controller and a Data Processor?**

**Q: Compare GDPR and SDAIA/PDPL. What do they share? What makes PDPL uniquely Saudi?**

**Q: Describe five technical measures a data scientist should use to protect data privacy. Include a code example where relevant.**

---

## ⭐ Must-Know for Exam

- **GDPR breach notification = 72 hours** to supervisory authority
- **7 GDPR rights** — especially: Access, Erasure (Right to be Forgotten), Portability, Object to Automated Decisions
- **7 GDPR principles** — especially: Purpose Limitation, Data Minimization, Accountability
- **Opt-in = GDPR/PDPL default** — pre-ticked boxes are NOT valid consent
- **5 C's:** Consent, Clarity, Consistency, Control, Consequence
- **DPO** = compliance overseer inside the organization
- **Data Controller** = decides why/how data is processed
- **Data Processor** = processes on behalf of controller
- **NDMO** = Saudi National Data Management Office (under SDAIA)
- **NDMO data classification:** Public / Internal / Confidential / Secret
- **Contextual integrity** = data should flow as appropriate to original context
- **5 technical measures:** Anonymization, Encryption, Access Controls, Audits, Regulatory Compliance
- **PDPL vs GDPR:** Both require explicit consent + breach notification + data rights
