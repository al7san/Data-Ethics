# Exam Focus Guide — Data and Ethics
**Priority reference for final exam preparation**

---

## 🗺️ What This Exam Tests

This exam prioritizes **understanding and application over memorization.**  
Every topic below can appear as MCQ, T/F, Short Answer, or Case Study.  
For Case Studies: be precise, one concept per point, no more than ⅓ of a page per case.

---

## Topic 1 — Morality, Ethics, Law & Society

### The Four Concepts

Understanding each concept individually AND how they relate to each other is essential — especially how they influence written regulations like GDPR and PDPL.

| Concept | Definition | Source | Scope |
|---------|-----------|--------|-------|
| **Morality** | Personal, internal compass of right and wrong | Individual | Subjective — varies person to person |
| **Ethics** | Systematic, external study of morality — recognized by a social group | Society / Profession | Group-based, independent of religion |
| **Law** | Formal rules decreed by authority, enforceable by punishment | Government | Binding — derived from moral codes |
| **Society** | A group of people sharing values, norms, and institutions | Community | Context for all of the above |

### How They Relate — The Chain

```
Individual Morality
      ↓
Shared Ethics (social norms, professional codes)
      ↓
Formal Law (regulations, legislation)
      ↓
Regulations like PDPL, GDPR, NCA Cybersecurity Framework
```

> **Key insight:** Law is derived from moral codes — not the other way around. When lawmakers write data protection regulations, they are translating ethical principles (privacy is a value) into enforceable rules.

### Applying This to Real Regulations

| Regulation | Ethical Basis | Moral Root |
|-----------|--------------|-----------|
| **PDPL (Saudi)** | Privacy is an ethical obligation | Human dignity is a personal moral value |
| **GDPR (EU)** | Individuals have the right to control their data | Autonomy and self-determination |
| **NCA Cybersecurity Framework** | Organizations have a duty to protect society | Trust and responsibility |

### Common Exam Trap
> Ethics ≠ Morality. Ethics is **social and external** (comes from groups, professions, society). Morality is **personal and internal** (comes from the individual).

---

## Topic 2 — Ethical Theories

### Why Six Theories Matter
No single theory answers every ethical question. Real-world decisions require applying multiple frameworks and recognizing the tension between them.

---

### The Six Theories — Deep Understanding

#### 1. Consequentialism
**Core:** Judge the action by its outcomes — not by rules or intent.

| Subtype | Who benefits? | Data Science Application |
|---------|--------------|--------------------------|
| **Egoism** | The individual/actor only | Company collects data to maximize its own profit, ignoring user harm |
| **Utilitarianism** | The majority — greatest good for the greatest number | Deploy a healthcare AI that helps millions even if a few are misclassified |
| **Altruism** | Everyone except the actor | Researcher shares a dataset publicly at personal career risk |

**The key question:** Does this action produce more benefit than harm overall?

---

#### 2. Deontology (Duty Theory)
**Core:** Judge the action by the intent and method — not the outcome.

| Condition | Judgment |
|-----------|---------|
| Wrong goal + wrong method | Unethical |
| Good goal + wrong method | Still unethical |
| Good goal + good method + legitimate duty | Ethical |

**Canonical example — Ethical Hacking:**

| Scenario | Deontological Verdict | Reason |
|---------|----------------------|--------|
| Hacking into a system to steal data | ❌ Unethical | Wrong intent, no legitimate duty |
| Hacking into a system you are hired to test | ✅ Ethical | Correct intent + authorized method = proper duty |
| Hacking "for a good cause" without authorization | ❌ Unethical | Good goal but method not sanctioned |

> **Exam tip:** Under Deontology, the moment the method or intent is wrong, the action is unethical — regardless of the outcome.

---

#### 3. Human Nature Theory
**Core:** Judge the action by the capabilities and rational capacity of the actor.

The theory holds that humans have unique rational capabilities, and moral responsibility depends on whether the actor was capable of understanding what they were doing.

| Actor Condition | Moral Responsibility |
|----------------|---------------------|
| Full adult with normal capability | Full responsibility |
| Elderly person, child, coerced individual | Reduced or no responsibility |
| Technical expert making uninformed decision | Ethically problematic — capability without care |
| Non-technical manager making data decisions | Problematic — lacks capability to assess impact |

**Data science application:**
A product manager with no technical background deploys a biased ML model. Under Human Nature theory, the question is: did they have the capability to understand the harm? If they had access to expertise and ignored it — culpable. If genuinely incapable — reduced responsibility.

---

#### 4. Relativism
**Core:** Right and wrong are relative to the culture, society, and time period — no universal norms.

**Two dimensions:**
- **Cultural Relativism:** What's acceptable in one culture may not be in another
- **Temporal Relativism:** What was acceptable in the past may not be today

| Example | Relativist Interpretation |
|---------|--------------------------|
| Accessing children's data in KSA vs. US | Different legal and cultural standards — neither is universally "right" |
| Collecting location data in 2005 vs. 2025 | The same practice that was acceptable is now considered a violation |
| Surveillance in authoritarian vs. democratic states | Standards differ based on political culture |

**Why it matters for data ethics:** Data crosses borders. A data practice legal in one jurisdiction may violate another's laws. Relativism explains — but does not justify — these differences.

---

#### 5. Hedonism
**Core:** Pleasure is the only intrinsic good. Ethical actions are those that maximize pleasure and minimize pain.

**Application:**
- Designing systems that maximize user satisfaction = ethically good under Hedonism
- Using dark patterns that frustrate users = ethically bad (causes displeasure)
- The "pleasure" can be extended to wellbeing broadly — which connects to user-centered design

---

#### 6. Emotivism
**Core:** Ethical statements are not objectively true or false — they express emotional reactions.

**Key insight:** "That data collection practice is wrong" really means "that practice makes me feel violated." Under Emotivism, this emotional response is itself ethically significant.

| Real example | Emotivist reading |
|-------------|------------------|
| Elderly patients made nervous by automated bank systems | Their discomfort is morally relevant — the system creates fear |
| Users feeling surveilled by smart home devices | The feeling of violation = an ethical signal |
| Survey respondents feeling used | Emotional discomfort is a legitimate ethical concern |

---

### Applying ALL Theories to One Case

**Case: Ethical Hacking**

| Theory | How it applies | Verdict |
|--------|---------------|---------|
| **Consequentialism** | The outcome is protection of the system — benefits outweigh harms | ✅ Ethical |
| **Deontology** | Done as a duty, with authorization, correct method and intent | ✅ Ethical |
| **Human Nature** | The hacker has the technical capability and is acting with informed judgment | ✅ Ethical (if authorized) |
| **Relativism** | Legal in most jurisdictions when authorized — cultural context matters | ✅ Generally ethical |
| **Hedonism** | Results in security and peace of mind for users | ✅ Ethical |
| **Emotivism** | Users feel protected; the hacker feels professional fulfillment | ✅ Ethical |

> Notice: All six theories converge on the same answer here — because the case is designed well. In harder cases, theories will disagree, which is precisely why you need all six.

---

### Theory Comparison Table

| Theory | Judges by | Key Question | Weakness |
|--------|----------|-------------|----------|
| Consequentialism | Outcomes | Did it produce more good than harm? | Justifies wrongs for "good outcomes" |
| Deontology | Intent + Method | Was it the right duty, done the right way? | Rules can conflict |
| Human Nature | Actor's capability | Was the actor capable of knowing better? | Hard to assess capability |
| Relativism | Cultural/temporal context | Right by whose standards, when? | No universal baseline |
| Hedonism | Pleasure produced | Does it maximize wellbeing? | Narrow definition of good |
| Emotivism | Emotional response | How does it make people feel? | No rational basis for claims |

---

## Topic 3 — Code of Ethics vs Code of Conduct

### The Core Distinction

> Code of Ethics **governs decision-making** and is rooted in ethical theories.  
> Code of Conduct **governs actions** and provides specific rules derived from those principles.

The relationship is directional:
```
Ethical Theories
      ↓ (inform and shape)
Code of Ethics  (principles and values)
      ↓ (translates into)
Code of Conduct (specific rules, procedures, disciplinary actions)
```

### Side-by-Side Comparison

| Dimension | Code of Ethics | Code of Conduct |
|-----------|---------------|-----------------|
| **Governs** | Decision-making and judgment | Specific actions and behaviors |
| **Nature** | Broad principles tied to theories | Concrete rules and procedures |
| **Audience** | Professionals and institutions | Employees and members |
| **Enforcement** | Advisory and inspirational | Often mandatory with consequences |
| **Contains** | "Be honest," "Do no harm," "Protect privacy" | "Do not share user data with third parties without written consent" |
| **Changes with** | Evolving societal values | Policy updates and legal requirements |

### Real-World Examples

| Code of Ethics | Code of Conduct |
|---------------|-----------------|
| DASCA Code of Ethics (data scientists globally) | Company data handling policy |
| SDAIA AI Principles (Saudi AI framework) | KKU Academic Integrity Policy |
| ACM Code of Ethics (24 imperatives, 1992) | Employee social media policy |

### Five Objectives of a Code of Ethics

| Objective | What it does |
|-----------|-------------|
| **Disciplinary** | Ensures professionalism and integrity |
| **Advisory** | Offers guidance and tips |
| **Educational** | Teaching tool for new members |
| **Inspirational** | Motivates members toward "the good" |
| **Publicity** | Builds client trust and public confidence |

---

## Topic 4 — CIA Triad + Encryption

### CIA Triad — The Three Pillars of Security

| Element | Protects Against | Violated By | Real Example |
|---------|-----------------|-------------|-------------|
| **Confidentiality** | Unauthorized disclosure | Data breach, eavesdropping | Facebook 2021 — 533M users exposed |
| **Integrity** | Unauthorized modification | Data tampering, record alteration | Hacker modifies medical dosage records |
| **Availability** | Unauthorized withholding | DDoS attack, ransomware | Hospital system taken offline |

### Critical Distinction — Frequently Tested

> **Authentication ≠ Integrity**
> - **Authentication** = verifying the identity of a user ("Who are you?") → belongs to Access Control
> - **Integrity** = ensuring data has not been tampered with ("Is this data unchanged?") → CIA element
>
> Statement: *"Authentication ensures data integrity in the CIA triad"* → **FALSE**

### Encryption — Three Types

| Type | Mechanism | Strength | Weakness | Use Case |
|------|-----------|---------|---------|---------|
| **Symmetric** | One shared key for both encryption and decryption | Fast | Key distribution problem — how to share the key securely? | Encrypting large volumes of data |
| **Asymmetric** | Two keys: Public (anyone can see) + Private (only owner) | More secure | Slower | Digital signatures, key exchange |
| **Hash Function** | One-way transformation → fixed-size digest | Cannot be reversed | Not used for encryption — only verification | Password storage, digital signatures |

### Digital Signature

A digital signature uses **Asymmetric encryption** to guarantee:
1. **Authenticity** — the message came from the stated sender (uses Private Key)
2. **Integrity** — the message was not altered in transit (uses Hash)

```
Sender:   [Message] + [Private Key] → [Signed Message]
Receiver: [Signed Message] + [Public Key] → Verified ✅
```

---

## Topic 5 — Privacy, Information Disclosure & Anonymity

### Privacy — Full Definition

> Privacy = a human attribute consisting of **four elements**:

```
PRIVACY
├── Control of External Influences
│   ├── Solitude      → the right to be ALONE without disturbance
│   ├── Anonymity     → the right to have NO public personal identity
│   └── Intimacy      → the right NOT to be monitored
└── Control of Personal Information
    └── Reserve       → the right to CONTROL personal information and its dissemination
```

### Three Types of Privacy

| Type | What it protects | Example |
|------|----------------|---------|
| **Personal** | Physical and behavioral attributes of an individual | Health condition, phone number, personal address |
| **Informational** | Data about a person from unauthorized access | Email content, browser history, medical records |
| **Institutional** | Confidential data belonging to an organization | Company source code, budget reports, trade secrets |

> **Exam trap:** A company's hacked budget report = **Institutional Privacy** violation — not Personal Privacy.

### Privacy vs Information/Data Disclosure

| | Privacy | Information Disclosure | Data Disclosure |
|--|---------|----------------------|-----------------|
| **Focus** | The right | The act of revealing info | The act of revealing raw data |
| **Governed by** | PDPL, GDPR | US Privacy Act 2020 | SDAIA Cases 2024 |
| **When permitted** | Default: not without consent | 12 exceptions (US) | 4 cases (SDAIA) |

### Anonymity — Types, Benefits, Risks

**Two types:**

| Type | Description | Commonality |
|------|-------------|------------|
| **Pseudo Identity** | Known by a pseudonym, username, or code number | Most common |
| **Untraceable Identity** | No identity of any kind — including pseudo names | Rare |

**When anonymity is beneficial:**
- Internal whistleblowing — exposing unethical organizational practices
- National security operations
- Protecting sensitive relationships and identities

**When anonymity is harmful:**
- Criminals exploit it, especially on social media platforms
- Accountability becomes impossible — no one can be held responsible
- Enables harassment, fraud, and misinformation without consequence

> Important: No anonymity type is 100% — someone with basic networking knowledge can trace misuse.

---

## Topic 6 — Data Controller ⭐ (High Priority)

### Definition

> **Data Controller** = the entity (person or organization) that determines **WHY** and **HOW** personal data is processed.

This is one of the most important concepts in modern data governance — especially in Saudi Arabia under PDPL.

### Data Controller vs Data Owner vs Data Processor

| Role | Decides | Responsible For | Example |
|------|---------|----------------|---------|
| **Data Owner** | Grants permission to use data | Their own personal data | The individual whose data is collected |
| **Data Controller** | Purpose and method of processing | Legal compliance, protection | Hospital deciding to collect patient records |
| **Data Processor** | Nothing — executes instructions | Processing on behalf of controller | Cloud storage company hosting the data |

### Responsibilities of the Data Controller

| Responsibility | Detail |
|----------------|--------|
| **Lawfulness** | Ensure a legal basis exists for every data processing activity |
| **Transparency** | Inform data subjects about what is collected and why |
| **Data Minimization** | Collect only what is necessary for the stated purpose |
| **Security** | Implement appropriate technical and organizational measures |
| **Breach Response** | Notify regulators (within 72 hours under GDPR) and affected individuals |
| **Disclosure Decisions** | Evaluate and authorize any request to share personal data with third parties |

### Data Controller in Disclosure Scenarios

When a disclosure request is received, the Data Controller must:

```
1. VERIFY   → Is this request legally justified? (Which of the 4 SDAIA cases applies?)
2. MINIMIZE → What is the minimum data needed? (Data Minimization principle)
3. DOCUMENT → Record what was shared, when, with whom, and why
4. NOTIFY   → Inform relevant parties if required by law
```

### Who Acts as Data Controller in an Organization?

- **Executives and Senior Officials** — ultimate accountability
- **Privacy Officers / DPO** — day-to-day compliance oversight
- **IT Department** — technical implementation of controls

---

## Topic 7 — Seven Sources of Harm in ML

### Framework Overview

These seven sources map where bias and harm enter throughout the ML pipeline. Each requires different mitigation strategies.

---

### Stage 1: Data Generation (3 Sources)

#### Historical Bias
- **What:** Training data encodes past societal prejudices — even when collected correctly
- **Why it's insidious:** The data can be perfectly accurate and still be biased
- **Example:** Word embeddings trained on historical text associate "doctor" with "he" and "nurse" with "she"
- **Mitigation:** Audit training data for historical patterns; use debiasing techniques

#### Representation Bias
- **What:** The sample used for training doesn't represent the real-world population that will use the model
- **Example:** A facial recognition system trained on 80% light-skinned faces performs poorly on dark-skinned faces
- **Quiz 2 connection:** "A hiring dataset mostly includes candidates from one demographic → the model favors that demographic" = Representation Bias
- **Mitigation:** Stratified sampling; actively seek diverse data sources

#### Measurement Bias
- **What:** The features chosen to measure a concept are unfair to certain groups
- **Example:** Using "prior arrests" as a proxy for criminal risk — this variable reflects policing patterns, not actual criminality; it systematically disadvantages minorities who are policed more heavily
- **Mitigation:** Critically evaluate proxy variables; consider what they actually measure

---

### Stage 2: Model Building (2 Sources)

#### Aggregation Bias
- **What:** Building one model for a diverse population as if all subgroups are identical
- **Example:** A diabetes risk model trained on combined data performs poorly for specific ethnic groups because the disease manifests differently
- **Mitigation:** Build separate sub-models or use multi-task learning for different groups

#### Learning Bias
- **What:** The optimization process itself amplifies disparities — the model learns to perform well on the majority at the expense of minorities
- **Example:** Pruning a model to improve overall accuracy disproportionately hurts underrepresented groups
- **Mitigation:** Use fairness-aware loss functions; evaluate performance across groups during training

---

### Stage 3: Evaluation and Deployment (2 Sources)

#### Evaluation Bias
- **What:** The benchmark dataset used to evaluate the model doesn't represent the actual user population
- **Example:** Commercial facial analysis tools benchmarked on datasets that are 80%+ light-skinned — the tools appear to perform well overall but fail badly on darker skin tones
- **Mitigation:** Use diverse, representative evaluation datasets; conduct subgroup analysis

#### Deployment Bias
- **What:** The model is used in a context or manner different from how it was designed and evaluated
- **Example:** A recidivism risk assessment tool designed to *inform* a judge's decision starts being used to *make* the decision automatically — the model was never validated for that level of authority
- **Mitigation:** Monitor actual use post-deployment; set clear scope boundaries; continuous auditing

---

### All Seven — Summary

| # | Source | Stage | One-Line Definition |
|---|--------|-------|-------------------|
| 1 | **Historical** | Data Generation | Past prejudice embedded in the data itself |
| 2 | **Representation** | Data Generation | Sample doesn't represent the real population |
| 3 | **Measurement** | Data Generation | Proxy features are unfair to certain groups |
| 4 | **Aggregation** | Model Building | One model treats all subgroups as identical |
| 5 | **Learning** | Model Building | Training optimization favors the majority |
| 6 | **Evaluation** | Evaluation | Benchmark doesn't match the use population |
| 7 | **Deployment** | Deployment | Model used beyond its intended scope |

---

## Topic 8 — Data Ethics Issues + Cybersecurity Issues

### Data Ethics Issues (Week 14-15)

| Issue | What it means | Example |
|-------|--------------|---------|
| **Over-collection** | Collecting more data than the purpose justifies | An app requesting microphone access just to send messages |
| **Purpose violation** | Using data for something other than its original purpose | Medical research data sold to advertisers |
| **Lack of meaningful consent** | Terms of service designed to be unread | 50-page privacy policy with opt-out buried on page 47 |
| **Black Box decisions** | AI systems that cannot explain their own outputs | A loan denial by deep learning with no explanation |
| **Problem of Many Hands** | Responsibility is distributed across so many people that no one is accountable | A biased model built by a team of 20 — no single person "caused" the bias |

### Cybersecurity Ethics Issues

#### Transparency and Disclosure — In Detail

This is a central ethical tension in cybersecurity: when you discover a vulnerability or breach, when and how do you disclose it?

| Scenario | Ethical Assessment | Reasoning |
|----------|------------------|-----------|
| Disclose immediately before any patch exists | ❌ Problematic | Invites attackers to exploit it before users can protect themselves |
| Develop a patch first, then notify affected parties | ✅ Best practice | Balances transparency with protection |
| Delay notification indefinitely | ❌ Unethical | Leaves users exposed; violates Deontological duty of honesty |
| Disclose only to regulators, not users | ❌ Insufficient | Users have the right to protect themselves |
| Never disclose | ❌ Unethical | Prioritizes organizational reputation over user safety |

**The general principle:** Disclose *after* a fix is available, *before* the window for exploitation closes, and *fully* to all affected parties.

#### Other Cybersecurity Ethical Issues

| Issue | The Tension |
|-------|-------------|
| **Resource Allocation** | Security costs money and slows systems — but not investing enough is ethically irresponsible |
| **Network Monitoring** | Organizations need to monitor their networks — but employees have privacy interests |
| **Ransomware payments** | Paying restores operations — but funds criminal enterprises and encourages future attacks |
| **Encryption weakening** | Law enforcement wants access — but weakening encryption harms everyone's security |
| **Accountability** | Cybersecurity failures involve many teams — clear responsibility chains are an ethical obligation |

---

## Topic 9 — Best Practices: Data Ethics + Cybersecurity

### Why They're Almost Identical

Both data ethics and cybersecurity ethics ultimately serve the same goal: responsible stewardship of systems and information that affect human lives.

### Shared Best Practices

| Practice | Data Ethics | Cybersecurity Ethics |
|---------|------------|---------------------|
| **Keep ethics in the spotlight** | Not just compliance — ongoing judgment | Not just compliance — ongoing judgment |
| **Consider the humans behind the data/systems** | Every data point = a real person | Every system failure = real lives affected |
| **Establish clear chains of responsibility** | Counter the Problem of Many Hands | Counter diffused accountability |
| **Focus on downstream risks** | Think about future misuse, not just intended use | Think about future attack vectors |
| **Design for privacy and security from the start** | Privacy by Design | Security by Design |
| **Invite diverse stakeholder input** | Marginalized groups often bear the most risk | Different teams find different blind spots |

### What's Unique to Cybersecurity

- **Disaster planning and crisis response** — incident response plans must exist *before* the breach
- **Promote transparency, autonomy, and trustworthiness** — users deserve honest communication about risks

---

## Topic 10 — SDAIA Four Disclosure Cases ⭐

### The Framework

SDAIA published guidelines on when a Data Controller is legally permitted to share personal data — even without the individual's consent.

**Default rule:** Personal data cannot be disclosed without the data subject's consent.  
**Exceptions:** The following four cases allow disclosure under specific conditions.

---

### Case 1 — Disclosure Without Consent (Legal Necessity)

**When:** There is a specific legal basis that overrides the consent requirement.

| Condition | Example |
|-----------|---------|
| Required by another applicable law | A law requiring financial institutions to report suspicious transactions |
| To fulfill a contractual obligation | Sharing data with a service provider as part of a signed agreement |

**Data Controller's role:**
- Verify the legal basis exists in writing
- Document the disclosure with full justification
- Apply Data Minimization — share only what the law requires

---

### Case 2 — Public Entity Request for Public Interest

**When:** A government authority requests data for: public interest, security purposes, implementing another law, or fulfilling judicial requirements.

**The critical principle:** *"The minimum amount of personal data necessary to fulfill the purpose is collected and processed"* → **Data Minimization**

> This is exactly what Quiz 2 Q4 tested. The correct answer was "Collect only what is needed for the purpose."

**Data Controller's role:**
- Verify the requesting entity is a legitimate public authority
- Apply strict Data Minimization — resist requests for broader data than necessary
- Document the request, the data shared, and the purpose
- Maintain audit trail for accountability

---

### Case 3 — Research and Statistical Purposes

**When:** Data is needed for scientific research, statistics, or historical records that cannot feasibly be conducted without personal data.

**Conditions that must be met:**
- The research serves a legitimate public benefit
- The research cannot be conducted with anonymized data alone
- Results will not be used to make decisions about identifiable individuals

**Data Controller's role:**
- Ensure anonymization or pseudonymization wherever possible
- Require data use agreements with researchers
- Confirm the research meets ethical standards (IRB/Ethics committee approval)

---

### Case 4 — Emergency Situations

**When:** Disclosure is necessary to protect the vital interests of the data subject or another person — particularly life-threatening situations.

**Principle:** In genuine emergencies, safety overrides privacy.

**Example:** A person is unconscious and medical staff need their health history to treat them — disclosure to treating physicians is permitted.

**Data Controller's role:**
- Act quickly — document the emergency justification
- Limit disclosure to what is strictly necessary for the emergency
- Notify the data subject afterward when they are able to receive the notification
- Report to SDAIA if required by the severity of the situation

---

### SDAIA Cases vs US Privacy Act 2020 — Comparison

| Dimension | SDAIA Cases 2024 | US Privacy Act 2020 |
|-----------|-----------------|---------------------|
| **Default rule** | No disclosure without consent | No disclosure without written consent |
| **Number of exceptions** | 4 structured cases | 12 enumerated exceptions |
| **Data Minimization** | Explicit and mandatory | Implied — not always explicit |
| **Scope** | Public and private sector | US federal agencies only |
| **Cultural grounding** | Islamic values + Vision 2030 | US constitutional privacy tradition |
| **Similarity** | Both require justification for every disclosure | Both treat consent as the default |
| **Key difference** | SDAIA explicitly requires minimum data even for permitted disclosures | US act focuses more on categorizing permitted uses |

---

## Quick Reference — Concepts That Connect Across Topics

| Concept | Where it appears | The connection |
|---------|-----------------|----------------|
| **Data Minimization** | GDPR + PDPL + SDAIA Case 2 | Core principle: collect only what's needed |
| **Problem of Many Hands** | Week 14 + Week 16 | Distributed responsibility = no accountability |
| **Transparency** | Big Data Ethics + Cybersecurity Issues + GDPR | Core value across all contexts |
| **Contextual Integrity** | Privacy + Information Disclosure | Data should flow as appropriate to original context |
| **CIA Triad** | Week 4 + Week 16 | Foundation of both privacy and security |
| **Design for Privacy/Security** | Best Practices (Data + Cyber) | Build it in from the start |
| **Consent** | GDPR + PDPL + All disclosure cases | Default requirement across all frameworks |

---

## Exam Answer Framework

### For Case Studies
```
1. IDENTIFY  → What happened? Who is affected? (Stakeholders)
2. CLASSIFY  → What type of issue? (Privacy / Bias / IP / Cybersecurity / Ethics)
3. ANALYZE   → Apply 2-3 ethical theories
4. REGULATE  → Which law/standard was violated? (GDPR / PDPL / CIA / DASCA)
5. RECOMMEND → What should have been done? (Best Practices)
```

### For Theory Application Questions
> Always show you understand the theory by **applying it** — not just defining it.
> State the verdict AND explain the reasoning using the theory's logic.

### For Comparison Questions  
> Use a two-column structure or explicit "X means... whereas Y means..."
> Always end with: "The key difference is..."

### For T/F Questions — Common Traps
| Statement | Answer | Why |
|-----------|--------|-----|
| Authentication ensures data integrity | **False** | Different concepts entirely |
| Trade secret loses protection when leaked | **True** | Protection depends on secrecy |
| Trademark protects the underlying algorithm | **False** | Trademark = brand identity only |
| Mathematical algorithms can be patented | **False** | Federal law prohibits it |
| GDPR requires opt-out by default | **False** | GDPR requires explicit opt-in |
| Virtue ethics focuses on rules and duties | **False** | That's Deontology — Virtue = character |

---

## Topic 11 — Intellectual Property Rights (IP)

### Why It Appears in the Exam
Quiz 2 tested Trade Secret (Samsung/ChatGPT case) and Trademark directly. IP is also connected to data licensing and algorithmic ownership.

### The Four Types — What Each Protects

| Type | What it protects | Duration | Enters Public Domain? | Key Rule |
|------|-----------------|----------|-----------------------|----------|
| **Trade Secret** | Confidential info giving competitive advantage | **Never expires** | No — stays secret as long as protected | Reverse engineering is **legal** |
| **Trademark** | Brand name, logo, service mark | **Never expires** | Can lose protection if name becomes generic | Must be actively defended |
| **Patent** | New inventions — grants exclusive rights | **20 years** | Yes — after 20 years | Requires full public disclosure |
| **Copyright** | Original expression (code, books, art) | Limited term | Yes — after term ends | Ideas not protected, only expression |

### Critical Rules — Frequently Tested

**Trade Secret:**
- Loses protection the moment it becomes publicly known — **whether leaked intentionally or accidentally**
- Samsung/ChatGPT case: employees pasted proprietary code into ChatGPT → code entered training data → trade secret protection lost
- Reverse engineering by a competitor = **legal** (they discovered it independently)

**Trademark:**
- Protects the **brand** — not the underlying technology or algorithm
- Statement: *"Trademarks can protect the underlying AI algorithm"* → **FALSE**
- Risk: if the trademark name becomes a common noun (e.g., "escalator" was once a trademark), protection can be lost

**Patent:**
- **Mathematical algorithms and formulas cannot be patented** under US federal law
- Only the specific *application or process* can be patented — not the abstract math behind it
- Requires full disclosure of the invention to the public

**Copyright:**
- Protects the *expression* of an idea, not the idea itself
- Protects software code — but not the algorithm or logic behind it

### Three Types of IP Infringement

| Type | Description | Example |
|------|-------------|---------|
| **Direct** | Knowingly copies, uses, or sells protected work | Downloading and distributing a copyrighted movie |
| **Inducement** | Intentionally supports others' infringement | Running a platform that knowingly hosts pirated content |
| **Contributory** | Takes part in the infringement | Providing tools specifically designed for piracy |

### Data and IP — Licensing

| License | Meaning |
|---------|---------|
| **CC0 (Public Domain)** | Owner waives all rights — free to use for anything |
| **CC BY** | Free to use — must attribute the original creator |
| **Trade Secret** | Data algorithm kept secret — no sharing permitted |

---

## Topic 12 — Virtue Ethics + Virtue Continuum

### Core Concept
Virtue Ethics asks: **"What kind of person should I be?"** — not "What rule applies?" or "What outcome will result?"

| Theory | Core Question |
|--------|--------------|
| Consequentialism | What outcome will this produce? |
| Deontology | What is my duty? |
| **Virtue Ethics** | **What kind of person/professional should I be?** |

### The Virtue Continuum (Golden Mean)

From Quiz 2: The Virtue Continuum diagram shows that virtuous action = **balance between two extremes.**

```
DEFICIENCY ←————————— VIRTUE ————————————→ EXCESS
(too little)              (the mean)           (too much)

Cowardice          ←→  Courage          ←→  Foolhardiness
Slothfulness       ←→  Temperance       ←→  Workaholism
Pride              ←→  Diligence        ←→  Degradation
Selfishness        ←→  Respect          ←→  Enablement
Corruption         ←→  Integrity        ←→  Legalism
Licentiousness     ←→  Courage          ←→  Strictness
```

> Quiz 2 Q2: *"Which actions follow virtue ethics theory?"* → **Balance between two extremes** ✅
> Following laws strictly = Legalism (excess). Ignoring moral values = deficiency. The mean = virtuous action.

### Key Aristotelian Terms

| Term | Greek | Meaning |
|------|-------|---------|
| **Virtue** | Arete | Excellence of character |
| **Flourishing** | Eudaimonia | Living well — the ultimate goal |
| **Practical Wisdom** | Phronesis | Knowing the right action in complex situations |
| **Golden Mean** | Mesotes | Virtue = balance between excess and deficiency |

### Virtues Most Relevant to Data/Cybersecurity Professionals

| Virtue | Deficiency | Mean | Excess |
|--------|-----------|------|--------|
| **Transparency** | Concealment | Appropriate disclosure | Over-disclosure (harmful) |
| **Courage** | Cowardice (ignoring bias) | Speaking up about problems | Recklessness |
| **Integrity** | Dishonesty | Honest reporting | Legalism (rigid rule-following) |
| **Temperance** | Recklessness | Data minimization | Over-restriction |

### Moral Exemplars
A **moral exemplar** = a person who embodies virtues at a high level — someone worth emulating.
- Virtue is developed through **habit and practice**, not rules
- Having role models in your professional community raises the ethical standard for everyone
- Appears in Best Practices for individuals (Week 14 + 16): *"Look for Moral Exemplars"*

---

## Topic 13 — Stakeholder Analysis + Business Ethics

### Who Are Stakeholders?
> **Stakeholder** = anyone impacted by a decision-maker's decision — directly or indirectly.

**Why identification matters:**
> Failing to identify stakeholders is one of the most common causes of unethical decisions — the decision-maker didn't realize there *was* a moral dilemma.

| Stakeholder | How affected by data/tech decisions |
|-------------|-------------------------------------|
| Shareholders | Financial returns, reputational risk |
| Employees | Job security, working conditions, surveillance |
| Customers | Data privacy, algorithmic fairness, service quality |
| Local community | Environmental impact, economic effects |
| Future users | Precedents set today affect them tomorrow |

### Friedman vs Porter

| | Friedman | Porter |
|--|---------|--------|
| **Core claim** | "The social responsibility of business is to increase its profits" | Create **Shared Value** = economic + social simultaneously |
| **Who matters** | Shareholders only | All stakeholders |
| **Social responsibility** | Not a business obligation | Core business strategy |
| **Example** | Traditional quarterly returns | GE Ecomagination — clean energy that is also profitable |

### Porter's Three Recommendations for Shared Value
1. **Expand the customer base** — include bottom-of-pyramid non-consumers
2. **Expand value chains** — partner with NGOs, governments, academic institutions
3. **Create regional clusters** — support economic ecosystems (Silicon Valley, Electronic City Bangalore)

### Ethical Dilemma Test — Four Questions
When facing an ethical decision in business:
1. Does this fall within acceptable professional norms?
2. Would I be comfortable explaining this publicly?
3. How would the media report this decision?
4. How would all stakeholders feel about it?

### Ethical Leadership
- Leaders set the ethical tone for the entire organization
- Employees take cues from leadership behavior — not just policy documents
- Uber case: aggressive, unrestrained culture = leadership failure, not just employee failure

---

## Topic 14 — Passwords + Physical Security

### Password Strength — Brute Force Resistance

From Quiz 2 Q1 (Hive Systems data):

| Password type | Brute-force time (2025, 10 chars) |
|---------------|----------------------------------|
| Numbers only | Instant |
| Lowercase only | Minutes |
| Upper + lowercase | Hours |
| Upper + lower + numbers | Months |
| **Upper + lower + numbers + symbols** | **164+ years** |

> `G7$kP!92xL` = 10 characters, all four types → extremely secure
> `qwerty`, `password`, `123456` → cracked instantly

### The Four "Never" Password Rules
1. **Never publicize** a password
2. **Never write it down** anywhere
3. **Never choose** an easy-to-guess password
4. **Never keep** the same password for a long time

### Physical Security — Four Mechanisms (in order)

| Order | Mechanism | When applied | How |
|-------|-----------|-------------|-----|
| 1st | **Deterrence** | Before intrusion attempt | Create an atmosphere that discourages intrusion |
| 2nd | **Prevention** | During potential intrusion | Barriers, locks, access controls |
| 3rd | **Detection** | Intrusion in progress | Sensors, CCTV, alarms |
| 4th | **Response** | After other mechanisms fail | Security personnel, law enforcement |

---

## Topic 15 — KKU Code of Ethics + Academic Integrity

### What Quiz 1 Q5 Tested
A student copies material from an online journal without citation and submits it as their own work.
**Under KKU Code of Ethics → This is a violation of academic integrity policies.**

Key rules:
- Plagiarism = using others' work without attribution, regardless of:
  - Whether the material is publicly available
  - Whether the student's performance is otherwise good
  - Whether the material is used to "improve learning"
- All of the above are irrelevant — academic integrity policies apply universally

### Connection to Broader Ethics
- **Deontology:** There is a duty to credit original sources — regardless of outcome
- **Virtue Ethics:** Integrity is a virtue — its deficiency is dishonesty
- **Code of Ethics:** Academic codes are a real-world example of professional codes of ethics in an educational context

---

## Topic 16 — DPO Role (Data Privacy Officer)

### Definition
> **DPO** = the person inside an organization responsible for ensuring data privacy compliance.

### Three-Role Comparison

| Role | Decides | Responsible for |
|------|---------|----------------|
| **Data Owner** | Grants access rights | Their own personal data |
| **Data Controller** | Why and how data is processed | Legal compliance, protection |
| **Data Processor** | Nothing — follows instructions | Processing on behalf of controller |
| **DPO** | Compliance strategy | Overseeing all of the above |

### DPO's Core Function — From Quiz 2 Q10
> *"How does a Data Officer help balance privacy?"*
> **By enforcing policies that protect personal data while allowing necessary uses for business needs.**

This balance is the DPO's defining challenge:
- Too restrictive → business cannot function
- Too permissive → privacy violations

### DPO Responsibilities

| Responsibility | Detail |
|----------------|--------|
| Monitor compliance | Ensure GDPR/PDPL requirements are met |
| Staff training | Educate employees on data protection |
| DPIA (Data Protection Impact Assessment) | Assess privacy risks before new projects |
| Point of contact | For data subjects exercising their rights |
| Liaison with regulators | Communicate with SDAIA/GDPR authorities |

### When is a DPO Required?
- Under GDPR: mandatory for public authorities and large-scale data processors
- Under PDPL: organizations processing large volumes of personal data must designate a responsible person

---

## Updated T/F Quick Reference — All Topics

| Statement | Answer | Topic |
|-----------|--------|-------|
| Authentication ensures data integrity | **False** | CIA — different concepts |
| Trade secret loses protection when leaked | **True** | IP — secrecy is the protection |
| Trademark protects the underlying AI algorithm | **False** | IP — trademark = brand only |
| Mathematical algorithms can be patented | **False** | IP — federal law prohibits it |
| GDPR requires opt-out by default | **False** | Privacy — opt-in is required |
| Virtue ethics focuses on rules and duties | **False** | That's Deontology — Virtue = character |
| Code of Conduct includes disciplinary actions | **True** | Ethics vs Conduct |
| DDoS violates Availability in CIA Triad | **True** | CIA — blocks access |
| Copying without citation is minor if material is public | **False** | Academic integrity — always a violation |
| Consequentialism judges by intent, not outcome | **False** | That's Deontology — Consequentialism = outcomes |
| A company's hacked budget report = Personal Privacy | **False** | It's Institutional Privacy |
| Reverse engineering a trade secret is illegal | **False** | It is legal — independent discovery |
