# MASTER SHEET — Cross-Topic Connections & Exam Prep
**Course:** Data and Ethics | All Weeks

---

## 🔗 How ALL Topics Connect

```
WEEK 2: Ethical Theories + Law + Codes of Ethics
   ↓ provides the lens to analyze everything below
WEEK 4: Anonymity + Security (CIA/Encryption) + Privacy
   ↓ privacy violations lead to...
STAKEHOLDER ANALYSIS: Who is affected? Who is responsible?
   ↓ responsibilities fall on...
WEEK 5: Bias & Fairness in ML — how data harms specific groups
   ↓ documentation solutions...
WEEK 9: Intellectual Property — who owns data, models, algorithms?
   ↓ ethical use of owned/shared data...
PRIVACY MODULE: GDPR, SDAIA, Opt-in/Opt-out
   ↓ all of this plays out in practice in...
WEEK 14-15: Ethics and Data — collection, storage, analysis, accountability
   ↓ when systems are attacked or misused...
WEEK 16: Cybersecurity Ethics — protecting what we've built
```

---

## 🔑 Concepts That Appear in Multiple Weeks

| Concept | Week 2 | Week 4 | Stakeholders | Week 5 | Week 9 | Week 14 | Week 16 |
|---------|--------|--------|-------------|--------|--------|---------|---------|
| Transparency | Big Data Ethics Principle | - | Porter's Shared Value | Data Cards | IP disclosure | Best Practice #3 | Disclosure dilemma |
| Accountability | Code of Ethics objectives | Data Controller | Ethical Leadership | Datasheets | IP enforcement | Problem of Many Hands | Best Practice #3 |
| Problem of Many Hands | - | - | - | - | - | ✅ Core concept | ✅ Core concept |
| CIA Triad | - | ✅ Core concept | - | - | - | - | Balance dilemma |
| Ethical Theories | ✅ Core concept | Applied to cases | Applied to Friedman | Applied to bias | Applied to IP crime | Applied to harms | Applied to cyber decisions |
| Privacy | Anonymity intro | ✅ Full coverage | FB Cambridge Analytica | Data bias → privacy | IP data licensing | Collection challenges | Network monitoring |
| GDPR | Reference | ✅ Mentioned | - | - | - | Opt-in context | Disclosure compliance |
| Best Practices (7-8) | - | - | Porter's 3 recs | Data Cards steps | - | ✅ 7 practices | ✅ 8 practices |
| Design for Privacy/Security | - | - | - | - | - | Practice #7 | Practice #7 |

---

## ⚡ Quick-Reference: Key Numbers to Memorize

| What | Number | Details |
|------|--------|---------|
| Ethical Theories | **6** | Consequentialism, Deontology, Human Nature, Relativism, Hedonism, Emotivism |
| Consequentialism subtypes | **3** | Egoism, Utilitarianism, Altruism |
| ML Bias Sources | **7** | 3 Data Gen + 2 Model Build + 2 Eval/Deploy |
| IP Types | **4** | Trade Secret, Trademark, Patent, Copyright |
| Patent duration | **20 years** | Then public domain |
| Privacy elements | **4** | Solitude, Anonymity, Intimacy, Reserve |
| Privacy types | **3** | Personal, Informational, Institutional |
| Physical Security mechanisms | **4** | Deterrence, Prevention, Detection, Response |
| Firewall types | **3** | Packet Filter, Proxy Server, Stateful Inspection |
| Password "Never" rules | **4** | Publicize, Write down, Easy to guess, Keep same |
| Code of Ethics objectives | **5** | Disciplinary, Advisory, Educational, Inspirational, Publicity |
| Code of Ethics forms | **4** | Principles, Public Policies, Codes of Conduct, Legal Instruments |
| ACM imperatives | **24** | Adopted 1992 |
| Facebook-Cambridge Analytica | **87M** users, **$5B** fine | 2018 |
| Equifax breach | **147M** people, **$700M** settlement | 2017 |
| Facebook 2021 breach | **533M** users | Largest breach |
| Big Data Ethics Principles | **4** | Transparency, Accountability, Individual Agency, Data Privacy |
| Porter's recommendations | **3** | Customer base, Value chains, Regional clusters |
| Universal Business Norms | **3** | Fairness, Honesty, Reciprocity |
| Datasheets sections | **6** | Motivation, Composition, Collection, Uses, Distribution, Maintenance |
| Data Cards steps | **4** | Ask, Inspect, Answer, Audit |
| Best Practices (Data Ethics) | **7** | organizational + 5 individual |
| Best Practices (Cybersecurity) | **8** | organizational + 5 individual |

---

## 📋 "Compare X vs. Y" — Exam Favorites

### Ethics vs. Morality vs. Law
| | Morality | Ethics | Law |
|--|---------|--------|-----|
| Source | Individual/Internal | Social/External | Government/Formal |
| Origin | Latin "mos" (custom) | Greek "ethos" (character) | Derived from moral codes |
| Fixed? | Relatively stable | Changes with society | Can be changed |
| Enforced? | By conscience | By professional norms | By courts |

### Natural Law vs. Conventional Law
| | Natural Law | Conventional Law |
|--|-------------|-----------------|
| Written? | No | Yes |
| Universal? | Yes | No |
| Origin | Pre-civilization | Human deliberation |
| Example | Self-defense right | GDPR, Penal Code |

### Code of Ethics vs. Code of Conduct
| | Code of Ethics | Code of Conduct |
|--|----------------|-----------------|
| Governs | Decision-making | Actions/behavior |
| Nature | Broad principles | Specific rules |
| Audience | Professionals/institutions | Employees/members |

### Symmetric vs. Asymmetric Encryption
| | Symmetric | Asymmetric |
|--|-----------|-----------|
| Keys | 1 shared key | 2 keys (public + private) |
| Speed | Faster | Slower |
| Problem | Key distribution | Complexity |
| Use case | Large data | Key exchange, digital signatures |

### Opt-in vs. Opt-out
| | Opt-in | Opt-out |
|--|--------|---------|
| Default | Not sharing | Sharing |
| Consent | Active/explicit | Passive |
| Protection | Higher | Lower |
| GDPR preference | ✅ Opt-in | ❌ |

### Friedman vs. Porter
| | Friedman | Porter |
|--|---------|--------|
| Goal | Maximize profit | Shared value (economic + social) |
| Stakeholders | Shareholders only | All stakeholders |
| Social responsibility | Not a business concern | Core strategy |

### Datasheets vs. Data Cards vs. Model Cards
| | Datasheets for Datasets | Data Cards Playbook | Model Card |
|--|------------------------|---------------------|------------|
| Focus | The dataset | The dataset | The model |
| Origin | Gebru et al. 2021 | Google Research 2022 | Google |
| Process | Document checklist | Ask→Inspect→Answer→Audit | Template |

---

## 🎯 Applying Ethical Theories to Cases (Exam Strategy)

When asked to apply theories to a scenario, use this structure:

**Scenario:** A company collects users' health data without explicit consent and sells it to pharmaceutical companies.

| Theory | How it applies | Verdict |
|--------|---------------|---------|
| **Consequentialism** | What are the outcomes? Users harmed by loss of privacy, possible discrimination in insurance. Pharma gains commercial advantage. | Wrong — net harm outweighs benefit |
| **Deontology** | Was this done as a duty? Was there a good reason? No — data was taken without consent. | Wrong — the intent and method are flawed |
| **Human Nature** | Do decision-makers have the capability to understand the harm? If yes and they proceed anyway, it's worse. | Wrong — knowing harm and proceeding = capability without conscience |
| **Relativism** | Does the culture/country allow this? Under GDPR: No. Under other regimes: possibly. | Context-dependent — highlights regulatory gap |
| **Hedonism** | Does this maximize pleasure/wellbeing for all? No — only benefits the company. | Wrong |
| **Emotivism** | How does it make users feel? Violated, unsafe, distrustful. That emotional response = ethically significant. | Wrong — user emotional harm matters |

---

## 📌 Expected Exam Topics (from topic slides you shared)

Based on the exam topic slides, prioritize:

| Topic | Key Concepts to Master | Covered In |
|-------|----------------------|-----------|
| **Moral, ethics, law and society** | Ethics vs Morality vs Law; Natural vs Conventional Law | Week 2 |
| **Ethical theories — differences, applying to cases** | All 6 theories + subtypes; apply to data scenarios | Week 2 |
| **Code of ethics vs code of conduct** | Definition + 5 objectives + 4 forms | Week 2 |
| **Security — CIA triad** | All 3 elements + what each prevents | Week 4 |
| **Encryption, digital signature** | Symmetric vs Asymmetric vs Hash; Digital Signature | Week 4 |
| **Privacy and information/data disclosure** | 4 elements; 3 types; violations; Data Controller | Week 4 |
| **Definition, anonymity, Acts, Data controller** | Pseudo vs Untraceable; GDPR/CCPA/SDAIA; Who is Data Controller | Week 4 |
| **Bias and fairness — Seven Sources of Harm** | All 7 sources + stage + example | Week 5 |
| **Intellectual property types** | All 4 types + duration + ML/AI/Data application | Week 9 |
| **ML/AI/Data in patent/copyright/trade secret** | Algorithms not patentable; CC licenses for data | Week 9 |
| **Data and ethics** | 3 harms; best practices; Problem of Many Hands | Week 14-15 |
| **Ethical issues in data/cybersecurity** | 4 cybersecurity ethical issues; challenges | Week 16 |
| **Best practices in data/cybersecurity** | 7 data + 8 cybersecurity organizational practices | Week 14+16 |
| **SDAIA Personal Data Disclosure Cases 2024** | Saudi context; PDPL | Privacy module |
| **GDPR** | EU regulation; consent; rights | Week 4 + Privacy |

---

## 💡 Exam Strategy

1. **For "compare X vs Y" questions:** Use a table in your mind — what does each one govern, where does it come from, what's the key difference?

2. **For "apply theory to case" questions:** Go through all relevant theories, show you understand them by applying — don't just define them.

3. **For "explain X" questions:** Definition → why it matters → example from lecture → connection to real case.

4. **For numerical answers:** Patent = 20 years. Cambridge Analytica = 87M users, $5B fine. Equifax = 147M people, $700M. ACM = 24 imperatives, 1992. 7 ML bias sources. 6 ethical theories.

5. **When in doubt:** Connect to a real example from the slides. British Airways, Facebook, Equifax, Samsung/ChatGPT, Uber, Cambridge Analytica — these were used intentionally and may appear in questions.

---

## 📌 Additional Topics (Week 3, Privacy, Virtue Ethics)

### Week 3 — DASCA & SDAIA AI Principles

| What | Detail |
|------|--------|
| **DASCA** | Data Science Council of America — 8 principles |
| **SDAIA AI Principles (2025)** | 7 principles — Human-Centricity, Fairness, Transparency, Privacy, Safety, Accountability, Sustainability |
| **PDPL** | Saudi Personal Data Protection Law — equivalent to GDPR |
| **Key link** | DASCA "Do No Harm" ↔ Consequentialism | SDAIA Transparency ↔ Black Box (Week 14) |

### Privacy and Information Disclosure

| What | Detail |
|------|--------|
| **GDPR breach notification** | 72 hours to supervisory authority |
| **7 GDPR rights** | Access, Rectification, Erasure, Restriction, Portability, Object, Anti-automated decision |
| **7 GDPR principles** | Lawfulness, Purpose limitation, Minimization, Accuracy, Storage limitation, Integrity, Accountability |
| **5 C's of Data Ethics** | Consent, Clarity, Consistency, Control, Consequence |
| **NDMO** | National Data Management Office (Saudi) — 4 data classification levels |
| **DPO** | Data Privacy Officer — compliance overseer inside organization |
| **Contextual Integrity** | Data flows ethically when matching original context norms |

### Virtue Ethics

| What | Detail |
|------|--------|
| **Origin** | Aristotle — character-based ethics |
| **Core question** | "What kind of person should I be?" |
| **Eudaimonia** | Human flourishing — the goal |
| **Phronesis** | Practical wisdom — most important virtue for professionals |
| **Golden Mean** | Virtue = balance between excess and deficiency |
| **4 Cardinal Virtues** | Prudence, Justice, Fortitude, Temperance |
| **Moral Exemplar** | Role model embodying virtues — in Week 14 + 16 best practices |
| **Key contrast** | Deontology = rules | Consequentialism = outcomes | Virtue = character |
