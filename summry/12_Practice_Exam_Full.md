# Practice Exam — Data and Ethics
**Includes: T/F | MCQ | Short Questions | Case Studies**

---

## Section 1 — True / False

> Write **True** or **False** and provide a one-sentence justification.

---

**1.** Authentication is one of the three elements of the CIA Triad.

**False.**
Authentication verifies user identity and belongs to Access Control — not the CIA Triad. The three CIA elements are Confidentiality, Integrity, and Availability.

---

**2.** A trade secret loses its legal protection once it becomes publicly known, even if leaked accidentally.

**True.**
Trade secret protection depends entirely on secrecy. Once the information is publicly known — whether through intentional disclosure or accidental leak — the legal protection is lost. (e.g., Samsung/ChatGPT case)

---

**3.** Under GDPR, organizations can use opt-out as the default consent model for collecting personal data.

**False.**
GDPR requires explicit opt-in consent. Pre-ticked boxes and opt-out defaults are not considered valid consent.

---

**4.** A trademark can protect the underlying AI algorithm of a product.

**False.**
A trademark protects brand identity (name, logo, service mark) — not the technology or algorithm behind the product. Algorithms may only be protected as trade secrets or, in limited cases, as patents.

---

**5.** Under deontological ethics, a company that experiences a minor data breach may ethically remain silent if disclosure would cause public panic.

**False.**
Deontology judges by duty and intent, not consequences. Honesty and timely disclosure are moral duties regardless of outcome — silence to avoid panic still violates the duty of honesty.

---

**6.** Representation Bias occurs when training data reflects past societal prejudices.

**False.**
That is Historical Bias. Representation Bias occurs when the population sampled for the dataset does not represent the real-world population that will actually use the model.

---

**7.** A Code of Ethics governs specific actions and typically includes disciplinary procedures for violations.

**False.**
That describes a Code of Conduct. A Code of Ethics governs decision-making through broad principles — it is advisory and inspirational, not procedural.

---

**8.** Reverse engineering a competitor's trade secret is illegal under US law.

**False.**
Reverse engineering is legal. Trade secret law prohibits theft or misappropriation — but independently discovering the same information through legitimate means is fully permitted.

---

**9.** Virtue Ethics focuses on the consequences of actions as the primary basis for moral judgment.

**False.**
That describes Consequentialism. Virtue Ethics focuses on the character of the moral agent — asking "What kind of person should I be?" rather than "What outcome will this produce?"

---

**10.** A company's confidential budget report being hacked is a violation of Institutional Privacy.

**True.**
Institutional Privacy protects confidential data belonging to an organization as a whole. A hacked budget report is organizational data exposed without authorization — a clear Institutional Privacy violation.

---

**11.** Under the SDAIA Personal Data Disclosure Guidelines, a public entity requesting data for national security purposes may collect all available data.

**False.**
Even in Case 2 (public entity / public interest), the Data Minimization principle applies — only the minimum data necessary for the stated purpose may be collected and processed.

---

**12.** Deployment Bias occurs when the benchmark dataset used to evaluate the model does not represent the actual user population.

**False.**
That is Evaluation Bias. Deployment Bias occurs when the model is used in a context or manner different from how it was designed and evaluated.

---

## Section 2 — Multiple Choice (MCQ)

> Choose the correct answer and provide a brief justification.

---

**1.** Which element of the CIA Triad is violated when a DDoS attack prevents users from accessing a hospital's patient records system?

- A) Confidentiality
- B) Integrity
- **C) ✅ Availability**
- D) Authentication

**Justification:** A DDoS attack blocks legitimate access to information — an Availability violation. The data was not stolen (Confidentiality) or modified (Integrity).

---

**2.** A data scientist discovers that her hiring model consistently rejects candidates from a specific region because most training data came from a different region. This is an example of:

- A) Historical Bias
- B) Measurement Bias
- **C) ✅ Representation Bias**
- D) Deployment Bias

**Justification:** The sample used for training does not represent the real-world population — candidates from a specific region are under-represented, causing the model to disadvantage them.

---

**3.** According to deontological ethics, which of the following best justifies ethical hacking?

- A) It produces better security outcomes for the organization
- B) It is more cost-effective than traditional security audits
- **C) ✅ It is performed as a legitimate duty with proper authorization and correct intent**
- D) Most stakeholders would agree it is the right approach

**Justification:** Deontology judges by duty, intent, and method — not outcomes (A) or majority opinion (D). Ethical hacking is authorized, purposeful, and correctly motivated.

---

**4.** What is the PRIMARY difference between a Code of Ethics and a Code of Conduct?

- A) A Code of Conduct is more general and inspirational
- **B) ✅ A Code of Ethics governs decision-making through principles; a Code of Conduct governs specific actions through rules**
- C) A Code of Ethics always includes disciplinary procedures
- D) A Code of Conduct applies only to senior management

**Justification:** Code of Ethics = principles that guide judgment (rooted in ethical theories). Code of Conduct = specific rules that govern behavior, often with defined consequences.

---

**5.** An organization uses customer medical data — originally collected for treatment purposes — to train a marketing AI model. Which principle is MOST directly violated?

- A) Data Minimization
- **B) ✅ Purpose Limitation — data is used beyond its original context**
- C) Availability
- D) Trademark protection

**Justification:** Purpose Limitation means data collected for one purpose cannot be used for another. This also violates Contextual Integrity — the data flows in a way inconsistent with its original context.

---

**6.** Under SDAIA's Personal Data Disclosure Guidelines, when a government entity requests personal data to serve public interest, the Data Controller must:

- A) Provide all requested data without question
- B) Refuse the request to protect individual privacy
- **C) ✅ Provide only the minimum data necessary to fulfill the stated purpose**
- D) Wait for a court order before responding

**Justification:** Case 2 of the SDAIA Guidelines explicitly requires the Data Minimization principle — even legitimate public entity requests are limited to the minimum data necessary.

---

**7.** A risk assessment tool was designed to inform a judge's sentencing decision. Courts begin using it to automatically determine sentences without any human review. This is an example of:

- A) Evaluation Bias
- B) Historical Bias
- C) Aggregation Bias
- **D) ✅ Deployment Bias — the model is used beyond its intended scope**

**Justification:** The model was designed to assist human judgment — not replace it. Using it as an automated decision-maker represents a context shift that the model was never validated for.

---

**8.** According to consequentialism, which of the following would be considered ethical?

- A) Following company policy regardless of outcomes
- **B) ✅ Collecting user data without consent if it leads to significantly greater societal benefits**
- C) Acting based on professional duty alone
- D) Refusing any action with uncertain outcomes

**Justification:** Consequentialism judges solely by outcomes. If overall benefits exceed harms, the action is considered ethical under this theory — regardless of method or intent.

---

**9.** Which of the following BEST describes the role of a Data Privacy Officer (DPO)?

- A) Collect and store all organizational data
- B) Make final decisions on what data to collect
- **C) ✅ Balance data protection requirements with legitimate organizational data uses through policy enforcement**
- D) Report directly to external regulators only

**Justification:** The DPO's core function is achieving balance — protecting personal data while enabling the organization to conduct necessary business activities.

---

**10.** Virtue Ethics argues that the best way to ensure ethical data practices is to:

- A) Create stricter regulations and enforce them rigorously
- B) Calculate the consequences of every data decision before acting
- **C) ✅ Cultivate character traits such as honesty, fairness, and practical wisdom in professionals**
- D) Follow the organization's Code of Conduct at all times

**Justification:** Virtue Ethics is character-based — it focuses on who the professional is and what virtues they embody, rather than rule-following (D) or outcome-calculation (B).

---

**11.** Which password would take the LONGEST time to crack using brute-force methods in 2025?

- A) DataEthics2024
- B) 12345678910
- **C) ✅ Kx#9mP!3vL@**
- D) iloveprivacy

**Justification:** `Kx#9mP!3vL@` uses all four character types (uppercase, lowercase, numbers, symbols) across 11 characters — estimated at hundreds of years to crack using modern hardware.

---

**12.** Which IP protection type requires full public disclosure of the protected invention as a condition for receiving protection?

- A) Trade Secret
- B) Copyright
- C) Trademark
- **D) ✅ Patent**

**Justification:** A patent grants exclusive rights for 20 years in exchange for full public disclosure of the invention — the opposite of a trade secret, which relies entirely on secrecy.

---

## Section 3 — Short Questions

> Answer precisely — one or two focused paragraphs maximum.

---

**Q1. What is the difference between Morality, Ethics, and Law? How does each one influence data protection regulations like PDPL?**

**Model Answer:**

**Morality** is the personal, internal sense of right and wrong — it originates from the individual and varies from person to person.

**Ethics** is the systematic, external study of morality recognized by a social group or profession — it translates individual moral values into shared standards and principles.

**Law** is the formal, enforceable set of rules decreed by a governing authority — derived from moral codes and backed by defined penalties.

Applied to PDPL: the moral value of human dignity and privacy (Morality) shaped the societal belief that personal data deserves protection (Ethics), which Saudi Arabia then formalized into the Personal Data Protection Law (Law). PDPL's consent requirement, data minimization principle, and breach notification obligation are direct translations of ethical principles into enforceable legal rules.

---

**Q2. Explain the "Problem of Many Hands" and its relevance to biased AI systems.**

**Model Answer:**

The Problem of Many Hands describes situations where responsibility for an outcome is distributed across so many contributors that no single person can be held accountable when something goes wrong.

In AI development, a biased model may be the product of: data collected by one team, labeled by another, features selected by a third, the model trained by a fourth, and deployment approved by a fifth. When the model causes discriminatory harm, each party can point to someone else — and the result is that no individual bears accountability despite real harm occurring.

This is precisely why establishing clear, named chains of responsibility is a core best practice in both Data Ethics and Cybersecurity Ethics — accountability must be assigned to specific individuals, not shared abstractly across teams.

---

**Q3. What is the Golden Mean in Virtue Ethics? Apply it to the concept of transparency in data science.**

**Model Answer:**

The Golden Mean, from Aristotle's virtue ethics, holds that every virtue represents a balance between two extremes — a deficiency (too little) and an excess (too much).

Applied to **transparency** in data science:

- **Deficiency:** Concealment — hiding model limitations, data sources, or potential biases from stakeholders, violating trust and preventing informed decisions.
- **Virtue (the mean):** Appropriate disclosure — clearly communicating what data was used, how the model functions, what its limitations are, and who could be affected.
- **Excess:** Over-disclosure — revealing security-sensitive implementation details or raw personal data in the name of openness, which creates entirely new harms.

The virtuous data scientist discloses what stakeholders need to make informed decisions, while protecting information whose exposure would cause harm.

---

**Q4. Compare Symmetric and Asymmetric encryption. When should each be used?**

**Model Answer:**

| | Symmetric | Asymmetric |
|--|-----------|-----------|
| Keys | One shared key | Two keys: public + private |
| Speed | Faster | Slower |
| Weakness | Key distribution problem | Computational complexity |

**Symmetric encryption** is appropriate when encrypting large volumes of data and both parties already share a secure channel — for example, encrypting stored database records.

**Asymmetric encryption** is appropriate when the parties have no prior secure channel — for example, establishing an HTTPS connection or creating digital signatures that verify both sender identity and message integrity. In practice, many systems use asymmetric encryption to securely exchange a symmetric key, then switch to symmetric for efficiency.

---

**Q5. What are the four SDAIA Personal Data Disclosure Cases? Describe the Data Controller's role in each.**

**Model Answer:**

| Case | When Permitted | Data Controller's Role |
|------|--------------|----------------------|
| **1 — Legal Necessity** | Required by another applicable law or contractual obligation | Verify legal basis in writing; apply Data Minimization; document fully |
| **2 — Public Entity / Public Interest** | Government request for security, public interest, or judicial purposes | Verify legitimacy; apply strict Data Minimization; maintain audit trail |
| **3 — Research / Statistical** | Scientific research that cannot be conducted with anonymized data alone | Ensure anonymization where possible; require formal data use agreements |
| **4 — Emergency** | Vital interests at risk — life-threatening situations | Act quickly; limit disclosure strictly to what is necessary; notify the data subject afterward |

In all four cases, the Data Controller must document every disclosure, enforce Data Minimization, and maintain accountability records for regulatory review.

---

**Q6. What are the three types of Privacy? Give one example of a violation for each.**

**Model Answer:**

| Type | Definition | Example of Violation |
|------|-----------|---------------------|
| **Personal Privacy** | Protection of an individual's physical and behavioral attributes | Disclosing an employee's medical diagnosis without consent |
| **Informational Privacy** | Protection of personal data from unauthorized access or use | A hacker accessing email records or browsing history |
| **Institutional Privacy** | Protection of confidential data belonging to an organization | Proprietary source code leaked when an employee uses an external AI tool (Samsung/ChatGPT) |

---

## Section 4 — Case Studies

> Analyze each case using the framework: Identify → Classify → Apply Theories → Violated Standards → Recommendation.
> **Be precise — do not exceed one-third of a page per case.**

---

### Case Study 1 — Cambridge Analytica

**Scenario:**
A third-party developer created a personality quiz app on Facebook. The app collected data not only from users who took the quiz but also from their friends — totaling approximately 87 million users. This data was sold to Cambridge Analytica for political profiling without users' knowledge or consent. Facebook's developer policies had permitted this type of data collection at the time.

**Write an ethical analysis of this case.**

---

**Model Answer:**

**Classification:** Privacy violation | Purpose limitation breach | Lack of informed consent

**Ethical Analysis:**

- **Consequentialism:** The harm — 87 million users' data used without consent for political manipulation — vastly outweighs any benefit to the developer or the data firm. Unethical.
- **Deontology:** Facebook and the developer each had a duty of transparency and protection toward users. Permitting silent data harvesting of non-consenting friends violated that duty regardless of outcome. Unethical.
- **Virtue Ethics:** Neither party demonstrated honesty, fairness, or responsibility — the core professional virtues a data organization must embody.

**Violated Standards:**
- GDPR: No lawful basis for collection; purpose limitation violated; no valid consent
- DASCA Principles: Failed "Protect Privacy and Confidentiality" and "Maintain Transparency and Accountability"
- Big Data Ethics (all four): Transparency, Accountability, Individual Agency, and Data Privacy all violated

**Recommendation:**
Require explicit opt-in consent for third-party data access; prohibit collection of non-consenting users' data; conduct regular third-party developer audits; appoint a DPO to oversee ongoing compliance.

---

### Case Study 2 — The Employee and the AI Tool

**Scenario:**
A software engineer at a major technology company copies portions of the company's proprietary source code into ChatGPT to get debugging assistance. The company had no explicit AI usage policy at the time. The engineer genuinely believed he was being helpful and had no intention of causing harm.

**Write an ethical analysis of this case.**

---

**Model Answer:**

**Classification:** Trade Secret violation | Institutional Privacy breach

**Ethical Analysis:**

- **Deontology:** The engineer had an implicit professional duty to protect company confidentiality. Even without an explicit policy, professional norms establish that proprietary code is confidential. Good intent does not excuse a wrong method.
- **Human Nature:** The engineer had the technical capability to understand the risk of entering proprietary code into an external AI system. Possessing that capability without exercising it constitutes moral responsibility.
- **Consequentialism:** The code entered ChatGPT's training data — potentially exposing it to competitors permanently. The harm (irreversible loss of trade secret protection) outweighs the benefit (faster debugging).

**Violated Standards:**
- IP Law: Trade secret protection lost once the code entered a publicly accessible training dataset
- Institutional Privacy: Proprietary organizational data disclosed to an external, uncontrolled system
- DASCA Code of Ethics: Violated "Protect Intellectual Property" and "Act with Integrity"

**Recommendation:**
Establish a clear AI tool usage policy immediately; classify data by sensitivity level and train all staff accordingly; implement technical Data Loss Prevention (DLP) controls to prevent uploading proprietary code to external services.

---

### Case Study 3 — The Loan Approval Model

**Scenario:**
A bank deploys a deep learning model to approve or reject loan applications. The model achieves 94% overall accuracy. However, an investigative journalist discovers that the rejection rate for applicants from a specific ethnic group is three times higher than for other groups. When customers ask why their application was rejected, the bank cannot provide an explanation because the model operates as a "black box."

**Write an ethical analysis of this case.**

---

**Model Answer:**

**Classification:** Algorithmic bias | Transparency and Autonomy harm | Potential GDPR Article 22 violation

**Ethical Analysis:**

- **Consequentialism:** Systematic financial exclusion of a specific ethnic group is serious, measurable societal harm. High overall accuracy does not offset group-level discrimination. Unethical.
- **Deontology:** The bank has a duty to treat all customers fairly and to explain decisions that materially affect their financial lives. Black-box decisions that cannot be explained violate this duty directly.
- **Virtue Ethics:** Fairness and transparency are foundational professional virtues — both are absent in this design and deployment.

**Bias Sources:** Likely **Representation Bias** (training data under-represented the affected group) and/or **Historical Bias** (historical lending patterns encoded past discriminatory practices into the model).

**Violated Standards:**
- GDPR Article 22: Customers are entitled to human review and meaningful explanation of automated decisions
- SDAIA AI Principles: Violated Fairness, Transparency, and Accountability principles
- DASCA: Violated "Promote Fairness and Avoid Bias"

**Recommendation:**
Conduct subgroup fairness analysis before any deployment; implement explainable AI methods (e.g., SHAP values); require human review for all rejections; conduct regular post-deployment audits for disparate impact.

---

### Case Study 4 — The Hospital Data Breach

**Scenario:**
A hospital's IT team discovers a breach of patient records on a Monday morning. The breach occurred over the previous weekend. They confirm that names, diagnoses, and insurance information of 50,000 patients were accessed by an unauthorized party. Hospital leadership decides to delay public notification for two weeks to "assess the full scope" and avoid negative media coverage before their annual charity fundraiser.

**Write an ethical analysis of this case.**

---

**Model Answer:**

**Classification:** Cybersecurity breach | Transparency and Disclosure failure | Regulatory violation

**Ethical Analysis:**

- **Deontology:** The hospital has an absolute duty to notify affected patients promptly. Delaying notification to protect organizational reputation violates this duty entirely — and doing so for a fundraiser makes it worse, placing institutional benefit above patient welfare.
- **Consequentialism:** During the two-week delay, 50,000 patients remain exposed to identity theft, insurance fraud, and targeted attacks without the ability to protect themselves. The harm of silence far outweighs any reputational benefit.
- **Virtue Ethics:** The decision reflects an absence of integrity, courage, and care — the hospital chose self-interest over its core professional obligation to patients.

**Violated Standards:**
- GDPR: Supervisory authority must be notified within **72 hours** of discovering a breach; notification of affected individuals required without undue delay
- PDPL: Similar timely notification obligations apply under Saudi law
- CIA Triad: Confidentiality was violated — sensitive health data accessed without authorization
- HIPAA (if applicable): Notification required within 60 days; delay for reputational reasons is prohibited

**Recommendation:**
Notify the regulatory authority (SDAIA/GDPR supervisory body) immediately upon confirmation; notify all 50,000 affected patients without further delay; provide concrete protective guidance (credit monitoring, insurance fraud alerts); conduct a post-incident review; implement stronger intrusion detection and access logging systems.

---

## Pattern Recognition Guide

### When you see these keywords → think:

| Keyword in the Question | Concept / Theory |
|------------------------|-----------------|
| "outcomes," "benefits," "harms," "consequences" | Consequentialism |
| "duty," "obligation," "regardless of outcome," "intent" | Deontology |
| "character," "virtue," "what kind of person" | Virtue Ethics |
| "cultural context," "different societies," "at that time" | Relativism |
| "feelings," "makes people uncomfortable," "emotional response" | Emotivism |
| "capability," "elderly," "children," "coerced" | Human Nature |
| "cannot access," "service down," "DDoS," "ransomware" | CIA — Availability |
| "tampered," "modified," "altered records" | CIA — Integrity |
| "leaked," "unauthorized access," "read without permission" | CIA — Confidentiality |
| "hacked budget," "proprietary code," "company data" | Institutional Privacy |
| "health condition," "personal phone number," "student grades" | Personal Privacy |
| "training data," "demographic group," "past societal patterns" | Historical or Representation Bias |
| "proxy variable," "unfair measurement," "prior arrests" | Measurement Bias |
| "used beyond intended purpose," "judge replaced by model" | Deployment Bias |
| "minimum data," "public entity," "security purposes" | SDAIA Case 2 / Data Minimization |
| "no disclosure without consent," "written consent," "12 exceptions" | US Privacy Act 2020 |
| "balance between extremes," "too much / too little" | Virtue Ethics — Golden Mean |
| "guidelines govern principles vs. rules" | Code of Ethics vs Code of Conduct |
