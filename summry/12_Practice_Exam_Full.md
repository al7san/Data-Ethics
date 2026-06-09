# اختبار تدريبي شامل — البيانات والأخلاقيات
**يشمل: T/F | MCQ | Short Questions | Case Studies**

---

## القسم الأول — صح / خطأ (T/F)

> اكتب **صح** أو **خطأ** وأعطِ سبباً بجملة واحدة.

---

**1.** Authentication is one of the three elements of the CIA Triad.

**✅ خطأ**
Authentication verifies user identity and belongs to Access Control — not CIA. The CIA Triad consists of Confidentiality, Integrity, and Availability.

---

**2.** A trade secret loses its legal protection once it becomes publicly known, even if leaked accidentally.

**✅ صح**
Trade secret protection depends entirely on secrecy. Once information is publicly known — whether intentionally disclosed or accidentally leaked — the protection is gone. (Samsung/ChatGPT case)

---

**3.** Under GDPR, organizations can use opt-out as the default consent model for collecting personal data.

**✅ خطأ**
GDPR requires explicit opt-in consent. Pre-ticked boxes and opt-out defaults are not considered valid consent under GDPR.

---

**4.** A trademark can protect the underlying AI algorithm of a product.

**✅ خطأ**
A trademark protects brand identity (name, logo, service mark) — not the technology or algorithm behind it. Algorithms may only be protected as trade secrets or, in limited cases, patents.

---

**5.** Under deontological ethics, a data breach that causes minimal harm is acceptable if keeping it secret prevents public panic.

**✅ خطأ**
Deontology judges by duty and intent, not consequences. Honesty and disclosure are moral duties regardless of the outcome — staying silent violates the duty of honesty.

---

**6.** Representation Bias occurs when the training data reflects past societal prejudices.

**✅ خطأ**
That is **Historical Bias**. Representation Bias occurs when the population sampled for the dataset does not represent the real-world population that will use the model.

---

**7.** The Code of Ethics governs specific actions and includes disciplinary procedures.

**✅ خطأ**
That describes a **Code of Conduct**. A Code of Ethics governs decision-making and is rooted in broad ethical principles — it is advisory and inspirational, not procedural.

---

**8.** Reverse engineering a competitor's trade secret is illegal under US law.

**✅ خطأ**
Reverse engineering is **legal**. Trade secret law only prohibits theft or misappropriation — independently discovering the same information through legitimate means is permitted.

---

**9.** Virtue Ethics focuses on the consequences of actions as the primary basis for moral judgment.

**✅ خطأ**
That describes Consequentialism. Virtue Ethics focuses on the **character** of the moral agent — asking "What kind of person should I be?" rather than "What outcome will this produce?"

---

**10.** A company's confidential budget report being hacked is a violation of Institutional Privacy.

**✅ صح**
Institutional Privacy protects confidential data belonging to an organization. A hacked budget report = organizational data exposed without authorization = Institutional Privacy violation.

---

**11.** Under the SDAIA Personal Data Disclosure Guidelines, a public entity requesting data for national security purposes may collect all available data.

**✅ خطأ**
Even in Case 2 (public entity / public interest), the **Data Minimization** principle applies — only the minimum data necessary for the stated purpose may be collected and processed.

---

**12.** Deployment Bias occurs when the benchmark dataset used to evaluate the model does not represent the actual user population.

**✅ خطأ**
That is **Evaluation Bias**. Deployment Bias occurs when the model is used in a context or manner different from how it was designed and evaluated.

---

## القسم الثاني — اختيار من متعدد (MCQ)

> اختر الإجابة الصحيحة وأعطِ سبباً قصيراً.

---

**1.** Which element of the CIA Triad is violated when a DDoS attack prevents users from accessing a hospital's patient records system?

- A) Confidentiality
- B) Integrity
- **C) ✅ Availability**
- D) Authentication

**السبب:** DDoS يمنع الوصول المشروع للمعلومات → انتهاك Availability. لم تُسرَّق البيانات ولم تُعدَّل.

---

**2.** A data scientist discovers that her hiring model consistently rejects candidates from a specific region because most training data came from another region. This is an example of:

- A) Historical Bias
- B) Measurement Bias
- **C) ✅ Representation Bias**
- D) Deployment Bias

**السبب:** العينة لا تمثل السكان الحقيقيين — المرشحون من منطقة معينة غير ممثَّلين في بيانات التدريب.

---

**3.** According to deontological ethics, which of the following best justifies ethical hacking?

- A) It produces better security outcomes for the organization
- B) It is cost-effective compared to traditional security audits
- **C) ✅ It is done as a legitimate duty with proper authorization and correct intent**
- D) Most people would agree it is the right thing to do

**السبب:** Deontology يحكم بالواجب والنية والطريقة — ليس النتائج (A) ولا الرأي العام (D).

---

**4.** What is the PRIMARY difference between a Code of Ethics and a Code of Conduct?

- A) A Code of Conduct is more general and inspirational
- **B) ✅ A Code of Ethics governs decision-making through principles; a Code of Conduct governs specific actions through rules**
- C) A Code of Ethics always includes disciplinary actions
- D) A Code of Conduct applies only to senior management

**السبب:** Code of Ethics = مبادئ توجّه القرارات. Code of Conduct = قواعد تحكم الأفعال وتتضمن عواقب.

---

**5.** An organization uses customer medical data — originally collected for treatment purposes — to train a marketing AI. Which ethical principle is MOST directly violated?

- A) Data Minimization
- **B) ✅ Purpose Limitation — data used beyond its original context**
- C) Availability
- D) Trademark infringement

**السبب:** Purpose Limitation = البيانات لا تُستخدَم لغير الغرض الذي جُمعت من أجله. هذا أيضاً انتهاك لـ Contextual Integrity.

---

**6.** Under SDAIA's Personal Data Disclosure Guidelines, when a government entity requests personal data to serve a public interest, the Data Controller must:

- A) Provide all requested data without question
- B) Refuse the request to protect individual privacy
- **C) ✅ Provide only the minimum data necessary to fulfill the stated purpose**
- D) Wait for a court order before responding

**السبب:** Case 2 في SDAIA تشترط صراحةً مبدأ Data Minimization حتى في طلبات الجهات العامة.

---

**7.** A risk assessment tool is designed to inform a judge's sentencing decision. However, courts begin using it to automatically determine sentences without human review. This is an example of:

- A) Evaluation Bias
- B) Historical Bias
- C) Aggregation Bias
- **D) ✅ Deployment Bias — used beyond its intended scope**

**السبب:** النموذج نُشر واستُخدم بطريقة مختلفة عن تصميمه — القاضي كان المقرر يُساعَد، لا يُستبدل.

---

**8.** According to consequentialism, which action would be considered ethical?

- A) Following company policy regardless of outcomes
- **B) ✅ Collecting user data without consent if it leads to significantly greater societal benefits**
- C) Acting based on professional duty alone
- D) Refusing any action with uncertain outcomes

**السبب:** Consequentialism = الحكم بالنتائج. إذا الفوائد الإجمالية تفوق الأضرار → يُعدّ أخلاقياً تحت هذه النظرية (لاحظ: هذا لا يعني أنه صحيح عالمياً).

---

**9.** Which of the following BEST describes the role of a Data Privacy Officer (DPO)?

- A) Collect and store all organizational data
- B) Make final decisions on what data to collect
- **C) ✅ Balance data protection requirements with legitimate organizational uses through policy enforcement**
- D) Report directly to external regulators only

**السبب:** الـ DPO يحقق التوازن بين حماية الخصوصية والسماح بالاستخدامات الضرورية للأعمال — هذا جوهر دوره.

---

**10.** Virtue Ethics argues that the best way to ensure ethical data practices is to:

- A) Create stricter regulations and enforce them
- B) Calculate the consequences of every data decision
- **C) ✅ Cultivate character traits like honesty, fairness, and practical wisdom in professionals**
- D) Follow the rules of the organization's Code of Conduct

**السبب:** Virtue Ethics = بناء الشخصية والفضيلة، لا الاتباع الآلي للقواعد أو حساب النتائج.

---

**11.** Which password would take the LONGEST time to crack using brute-force methods?

- A) DataEthics2024
- B) 12345678910
- **C) ✅ Kx#9mP!3vL@**
- D) iloveprivacy

**السبب:** `Kx#9mP!3vL@` = 11 حرفاً من جميع الأنواع الأربعة (كبيرة + صغيرة + أرقام + رموز) = مئات السنين للاختراق.

---

**12.** Which IP protection type requires full public disclosure of the protected invention as a condition for protection?

- A) Trade Secret
- B) Copyright
- C) Trademark
- **D) ✅ Patent**

**السبب:** براءة الاختراع تمنح حقوقاً حصرية لـ20 عاماً في مقابل الإفصاح الكامل للعموم — عكس السر التجاري الذي يعتمد على السرية.

---

## القسم الثالث — أسئلة قصيرة (Short Questions)

> أجب بدقة — فقرة أو فقرتان كحد أقصى.

---

**Q1. What is the difference between Morality, Ethics, and Law? How does each one influence data protection regulations like PDPL?**

**الإجابة:**

**Morality** is the personal, internal sense of right and wrong — it comes from the individual and varies from person to person.

**Ethics** is the systematic, external study of morality recognized by a social group or profession — it translates individual moral values into shared standards.

**Law** is the formal, enforceable set of rules decreed by a government authority — derived from moral codes and backed by penalties.

Their influence on PDPL:
- The moral value of human dignity and privacy (Morality) shaped the societal belief that personal data should be protected (Ethics), which Saudi Arabia then formalized into the Personal Data Protection Law (Law). PDPL's consent requirement, data minimization, and breach notification obligations are direct translations of ethical principles into enforceable rules.

---

**Q2. Explain the concept of "Problem of Many Hands" and how it applies to biased AI systems.**

**الإجابة:**

The "Problem of Many Hands" refers to situations where responsibility for an outcome is so widely distributed across many contributors that no single person can be held accountable when something goes wrong.

In AI development, a biased model may be the product of: data collected by one team, labeled by another, features selected by a third, the model built by a fourth, and deployment approved by a fifth. When bias causes harm, each party can point to someone else. The result is that no individual is held accountable even though real harm occurred.

This is why establishing **clear chains of responsibility** — assigning specific named individuals to specific aspects of data and model governance — is one of the key best practices in both Data Ethics and Cybersecurity Ethics.

---

**Q3. What is the Golden Mean in Virtue Ethics? Apply it to the concept of transparency in data science.**

**الإجابة:**

The Golden Mean, from Aristotle's virtue ethics, holds that every virtue is the balance between two extremes — a deficiency (too little) and an excess (too much).

Applied to **transparency** in data science:
- **Deficiency (too little):** Concealment — hiding model limitations, data sources, or potential biases from stakeholders. This violates trust and prevents informed decision-making.
- **Virtue (the mean):** Appropriate disclosure — being clear about what data was used, how the model works, what its limitations are, and who could be affected.
- **Excess (too much):** Over-disclosure — revealing security-sensitive details, proprietary methods, or raw personal data in the name of transparency, which creates new harms.

The virtuous data scientist discloses what stakeholders need to know to make informed decisions, while protecting what could cause harm if revealed.

---

**Q4. Compare Symmetric and Asymmetric encryption. When should each be used?**

**الإجابة:**

| | Symmetric | Asymmetric |
|--|-----------|-----------|
| Keys | One shared key | Two keys: public + private |
| Speed | Faster | Slower |
| Weakness | Key distribution problem | Complexity |

**Symmetric encryption** should be used when encrypting large volumes of data where both parties already have a secure channel to share the key — for example, encrypting stored database records.

**Asymmetric encryption** should be used when the parties have no prior secure channel — for example, establishing a secure HTTPS connection, or creating **digital signatures** (which verify sender identity and message integrity). In practice, many systems use asymmetric encryption to securely exchange a symmetric key, then switch to symmetric for speed.

---

**Q5. What are the four SDAIA Personal Data Disclosure Cases? What is the Data Controller's role in each?**

**الإجابة:**

| Case | When permitted | Data Controller's role |
|------|--------------|----------------------|
| **1 — Legal Necessity** | Required by another applicable law or contractual obligation | Verify legal basis in writing; apply minimization; document |
| **2 — Public Entity / Public Interest** | Government request for security, public interest, or judicial purposes | Verify legitimacy; apply strict Data Minimization; maintain audit trail |
| **3 — Research / Statistical** | Scientific research that cannot be conducted with anonymized data | Ensure anonymization where possible; require data use agreements |
| **4 — Emergency** | Vital interests at risk — life-threatening situations | Act quickly; limit disclosure to what's strictly necessary; notify subject afterward |

In all four cases, the Data Controller must document the disclosure, ensure Data Minimization, and maintain accountability records.

---

**Q6. What is the difference between the three types of Privacy? Give an example of a violation for each.**

**الإجابة:**

| Type | Definition | Example of Violation |
|------|-----------|---------------------|
| **Personal Privacy** | Protection of an individual's physical and behavioral attributes | Disclosing an employee's health condition without consent |
| **Informational Privacy** | Protection of personal data from unauthorized access | A hacker accessing email records or medical history |
| **Institutional Privacy** | Protection of confidential organizational data | A company's proprietary source code being leaked (Samsung/ChatGPT case) |

---

## القسم الرابع — دراسات الحالة (Case Studies)

> حلّل كل حالة باستخدام الإطار: تعريف → تصنيف → تحليل بالنظريات → القانون/المعيار المنتهَك → التوصية.
> **لا تتجاوز ثلث الصفحة.**

---

### Case Study 1 — Cambridge Analytica

**الحالة:**
A third-party developer created a personality quiz app on Facebook. The app collected data not only from users who took the quiz, but also from their friends — totaling approximately 87 million users. This data was sold to Cambridge Analytica, which used it for political profiling without users' knowledge or consent. Facebook had permitted this data collection under its developer policies at the time.

**اكتب تحليلاً أخلاقياً لهذه الحالة.**

---

**✅ الإجابة النموذجية:**

**Classification:** Privacy violation + Purpose limitation breach + Lack of informed consent

**Ethical Analysis:**
- **Consequentialism:** The harm — 87 million users' data used without consent for political manipulation — vastly outweighs any benefit. Unethical.
- **Deontology:** Facebook and the developer had a duty of transparency and protection toward users. Permitting silent data harvesting violated that duty regardless of outcome. Unethical.
- **Virtue Ethics:** Neither Facebook nor the developer demonstrated honesty, fairness, or responsibility — the core virtues a data professional must embody.

**Violated Standards:**
- GDPR: No lawful basis for collection; purpose limitation violated
- DASCA Principles: Failed "Protect Privacy" and "Maintain Transparency"
- Big Data Ethics: Violated all four principles — Transparency, Accountability, Individual Agency, and Data Privacy

**Recommendation:**
Implement explicit opt-in consent for third-party data access; prohibit collection of non-consenting friends' data; conduct regular third-party audits; appoint a DPO to oversee compliance.

---

### Case Study 2 — الموظف والذكاء الاصطناعي

**الحالة:**
A software engineer at a major technology company is asked to speed up the development process. He copies portions of the company's proprietary source code into ChatGPT to get debugging help. The company had no explicit policy about using AI tools at the time. The engineer genuinely believed he was being helpful and did not intend to cause harm.

**اكتب تحليلاً أخلاقياً لهذه الحالة.**

---

**✅ الإجابة النموذجية:**

**Classification:** Trade Secret violation + Institutional Privacy breach

**Ethical Analysis:**
- **Deontology:** The engineer had an implicit duty to protect company confidentiality. Even without an explicit policy, professional norms establish that proprietary code is confidential. The good intent does not excuse the breach — method was wrong.
- **Human Nature:** The engineer had the technical capability to understand the risk of inputting code into an external AI system. Having that capability and not applying it = moral responsibility.
- **Consequentialism:** The code entered ChatGPT's training data — potentially exposing it to competitors. The harm (loss of trade secret protection) outweighs the benefit (faster debugging).

**Violated Standards:**
- IP Law: Trade Secret lost protection once code became part of training data
- Institutional Privacy: Proprietary organizational data disclosed to an external system
- Professional Ethics (DASCA): Violated "Protect Intellectual Property" and "Act with Integrity"

**Recommendation:**
Establish a clear AI tool usage policy immediately; train staff on data classification and what constitutes confidential information; implement technical controls (DLP tools) to prevent uploading code to external services.

---

### Case Study 3 — نظام قرار القرض

**الحالة:**
A bank deploys a deep learning model to approve or reject loan applications. The model achieves 94% overall accuracy. However, a journalist discovers that the rejection rate for applicants from a specific ethnic group is 3x higher than for other groups. When customers ask why their application was rejected, the bank cannot provide an explanation because the model is a "black box."

**اكتب تحليلاً أخلاقياً لهذه الحالة.**

---

**✅ الإجابة النموذجية:**

**Classification:** Algorithmic bias (Representation/Historical) + Transparency/Autonomy harm + Potential GDPR Art. 22 violation

**Ethical Analysis:**
- **Consequentialism:** The outcome — systematic discrimination against a specific ethnic group — is serious societal harm. Unethical despite high overall accuracy.
- **Deontology:** The bank has a duty to treat all customers fairly and to be able to explain decisions that affect their financial lives. Black-box decisions violate this duty.
- **Virtue Ethics:** Fairness and transparency are core professional virtues — both are absent here.

**Bias Sources:** Likely **Representation Bias** (training data under-represented the affected group) and/or **Historical Bias** (historical lending patterns encoded discriminatory practices).

**Violated Standards:**
- GDPR Article 22: Right against automated decision-making — customers are entitled to human review and explanation
- SDAIA AI Principles: Violated Fairness, Transparency, and Accountability principles
- DASCA: Violated "Promote Fairness and Avoid Bias"

**Recommendation:**
Conduct subgroup fairness analysis before deployment; require explainability (use interpretable models or SHAP values); implement human review for borderline cases; audit the model regularly for disparate impact.

---

### Case Study 4 — اختراق بيانات المستشفى

**الحالة:**
A hospital's IT team discovers a breach of patient records on a Monday morning. The breach occurred over the previous weekend. They confirm that names, diagnoses, and insurance information of 50,000 patients were accessed. The hospital's leadership decides to delay public notification for two weeks to "assess the full scope" and avoid negative media coverage before their annual charity fundraiser.

**اكتب تحليلاً أخلاقياً لهذه الحالة.**

---

**✅ الإجابة النموذجية:**

**Classification:** Cybersecurity breach + Transparency/Disclosure failure + Regulatory violation

**Ethical Analysis:**
- **Deontology:** The hospital has an absolute duty to notify affected patients promptly. Delaying notification to protect reputation violates this duty entirely. The reason for delay (fundraiser) makes it worse — personal benefit at patients' expense.
- **Consequentialism:** During the two-week delay, 50,000 patients are exposed to identity theft, insurance fraud, and targeted phishing without the ability to protect themselves. The harm of silence far outweighs the reputational benefit.
- **Virtue Ethics:** The decision demonstrates a complete absence of integrity, courage, and care — the hospital prioritized its own interests over patient welfare.

**Violated Standards:**
- GDPR: Supervisory authority must be notified within **72 hours** of discovering a breach
- PDPL: Similar notification requirements apply in Saudi Arabia
- CIA Triad: Confidentiality was violated — patient health data accessed without authorization
- HIPAA (if US): Notification required within 60 days; delay for reputational reasons is prohibited

**Recommendation:**
Notify SDAIA/regulatory authority immediately; notify affected patients without delay; provide guidance on protective measures (credit monitoring, password changes); conduct a post-incident review; implement stronger access controls and intrusion detection systems.

---

## ملخص الأنماط — كيف تتعرف على نوع السؤال

### إذا السؤال ذكر...

| الكلمة المفتاحية | النظرية/المفهوم |
|----------------|----------------|
| "outcomes," "benefits," "harms," "consequences" | Consequentialism |
| "duty," "obligation," "regardless of outcome," "intent" | Deontology |
| "character," "virtue," "what kind of person" | Virtue Ethics |
| "cultural context," "different societies," "at the time" | Relativism |
| "feelings," "makes people uncomfortable," "emotional response" | Emotivism |
| "capability," "elderly," "children," "coerced" | Human Nature |
| "cannot access," "service down," "DDoS" | CIA — Availability |
| "unauthorized modification," "tampered," "altered" | CIA — Integrity |
| "leaked," "unauthorized access," "read without permission" | CIA — Confidentiality |
| "hacked budget," "proprietary source code," "company data" | Institutional Privacy |
| "health condition," "personal phone number," "individual grades" | Personal Privacy |
| "training data," "demographic group," "past data" | Historical / Representation Bias |
| "proxy variable," "unfair measurement," "criminal justice score" | Measurement Bias |
| "used beyond its intended purpose," "judge replaced by model" | Deployment Bias |
| "minimum data," "public entity," "security purposes" | SDAIA Case 2 / Data Minimization |
| "no disclosure without consent," "12 exceptions" | US Privacy Act 2020 |
