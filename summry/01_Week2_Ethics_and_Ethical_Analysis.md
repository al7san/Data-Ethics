# Week 2 — Ethics & Ethical Analysis
**Course:** Data and Ethics | Dr. Ali Algarni  
**Sources:** Ch. 3 — Ethical & Social Issues in the Information Age

---

## 🗺️ Big Picture — How Everything Connects

```
SOCIETY
  └─ sets norms → MORALITY (personal, internal)
        └─ studied systematically → ETHICS (external, social)
              └─ enforced formally → LAW
                    └─ when tech disrupts all of the above → COMPUTER ETHICS
```

> **Key insight from lectures:** The same human action (e.g., hacking) can be judged differently depending on which ethical theory you apply. That's exactly why we study these theories — not to memorize definitions, but to *reason* through real cases.

---

## 1. The Foundation — Society, Morality, Ethics, Law

### What is each?

| Concept | Definition | Source | Example from slides |
|---------|-----------|--------|---------------------|
| **Society** | Group of people sharing common values | Community | Zoom, Minecraft, Reddit, Discord — all are online societies |
| **Morality** | Personal internal compass of right/wrong | Individual | Traffic light as a moral tool; integrity statement |
| **Ethics** | Systematic study of morality; rules recognized by an external social system | Social/External | "Is this action right or wrong? Good or bad? Guilty or not?" |
| **Law** | Rules decreed by a formal body, enforceable | Government | SDAIA regulations, GDPR |

### Etymology (important for exam!)
- **Ethics** ← Greek *"ethos"* = character
- **Morals** ← Latin *"mos"* = custom

### How they relate to each other
- Laws are **derived from** moral codes — law follows morality, not the other way around
- Ethics is the **systematic study** of morality — it's a discipline, not a feeling
- Technology disrupts all three: it creates new societies (online), new moral dilemmas, and gaps in law

---

## 2. Law — Two Types

### Natural Law (Moral Law)
- **Unwritten but universal** — exists before governments
- Civilization is built on it
- Consists of three core rights:
  1. Self-defense / preservation
  2. Individual property
  3. Liberty
- **Connection to data:** Human dignity in data-driven technologies falls under natural law

### Conventional Law (Physical Law)
- Created **by humans, for humans** — through public deliberation
- **Varies** from society to society (unlike natural law which is universal)
- Purpose:
  - Protect human life, property, and liberty
  - Prescribe punishments — the Penal Code

| | Natural Law | Conventional Law |
|--|-------------|-----------------|
| Written? | No | Yes |
| Universal? | Yes | No — varies by society |
| Origin | Pre-civilization | Human deliberation |
| Example | Right to self-defense | GDPR, criminal codes |

> **Exam tip:** "Laws are derived from moral codes" — this means if you understand the morality, you understand the law's intent.

---

## 3. The Six Ethical Theories

> These theories are **engines** to help understand and justify human actions. They haven't changed with technology, but the scenarios they're applied to have.

### Theory 1 — Consequentialism
**Core idea:** Judge an action by its **outcomes/consequences**, not the action itself.

**Three subtypes:**

| Subtype | Focus | Data Science Example |
|---------|-------|---------------------|
| **Egoism** | Individual's interests above everyone else | Building a model that maximizes your company's profit regardless of user harm |
| **Utilitarianism** | Group's interests above self | Deploying a healthcare AI that helps millions even if a few individuals are misclassified |
| **Altruism** | Consequences are good for everyone *except* the actor | A researcher publishing a dataset publicly at career risk, for the community's benefit |

**From slides — ML/AI connection:**
> *"The ethical theory of consequentialism can explain why a model's deployment is relevant to its moral evaluation."*

This means: you can't just say "we built a good model" — you have to ask what happens *after* you deploy it.

---

### Theory 2 — Deontology (Duty Theory)
**Core idea:** An action is good if it is done **as a duty** and for a **good reason** — regardless of outcome.

**From the slides — exact examples:**

| Action | Deontological View |
|--------|--------------------|
| Hacking | Wrong — violates duty |
| **Ethical Hacking** | Right — done as a duty to protect |
| Data breach (stealing) | Wrong |
| Finding vulnerabilities before attackers do | Right — same technical act, different duty |
| Killing | Wrong |
| Killing to save many lives | Could be right — the duty changes the judgment |

> **Key distinction from Consequentialism:** Deontology asks *why* you did it. Consequentialism asks *what happened* as a result.

---

### Theory 3 — Human Nature
**Core idea:** Actions are judged based on the **capabilities of the actor**.

- We're supposed to discover and develop our capabilities, then use them as benchmarks
- "Guilty by reasons of insanity" is a legal application of this theory
- **Data example from slides:**
  - A person committing an unethical action may be "lacking in some capabilities"
  - Making data decisions without technical/analytical skills = ethically questionable because you lack the capability to understand the impact

---

### Theory 4 — Relativism
**Core idea:** Right and wrong are **relative to society** — no universal norms. Also, moral norms are **not fixed in time**.

**From slides — exact examples:**
- Marrying from within the royal family — acceptable in some cultures, not others
- **Accessing children's phones/data in KSA vs. US** — legal and moral standards differ

**Why this matters for data ethics:**
- A data practice legal in one country may violate another's laws
- What was acceptable data collection 10 years ago may be unacceptable today (norms change over time)

---

### Theory 5 — Hedonism
**Core idea:** Pleasure is the **only good** in human life. People ought to seek pleasure — that is the moral good.

- Ethical hedonism = maximizing pleasure for all is the ethical goal
- Application: designing products/systems that maximize user satisfaction/pleasure could be justified under this theory

---

### Theory 6 — Emotivism
**Core idea:** Ethical statements are **neither true nor false** — they are expressions of **how someone feels**.

**From slides — exact examples:**
- "Restrictions on gun ownership are bad" → really means "restrictions make me feel unsafe"
- **Data collection via survey (bothering people?)** — if people feel bothered, that emotional response is ethically significant under emotivism
- **Using machines with elderly patients / bank transactions** → makes them nervous = morally relevant feeling

---

### Theories Side-by-Side Comparison

| Theory | Judges Action By | Key Question | Lecture Example |
|--------|-----------------|--------------|-----------------|
| Consequentialism | Outcomes | "What happened as a result?" | ML model deployment impact |
| Deontology | Intent + Duty | "Was it done for the right reason?" | Ethical hacking |
| Human Nature | Actor's capabilities | "Was the actor capable of knowing better?" | Non-technical decision makers |
| Relativism | Cultural/temporal context | "Right by whose standards, when?" | KSA vs. US data access laws |
| Hedonism | Pleasure produced | "Does it maximize wellbeing?" | User-centered design |
| Emotivism | Emotional response | "How does it make people feel?" | Elderly patients with machines |

### How to Apply Theories as a Data Scientist (from Slide 18)
When you collect, analyze, store, or disseminate data — ask:
- **Consequentialism:** What are the downstream impacts of this data decision?
- **Deontology:** Am I doing this because it's genuinely my duty, or just because I can?
- **Human Nature:** Do I have the skills/capabilities to truly understand the ethical implications?
- **Relativism:** Does this practice respect the cultural/legal context of the data subjects?
- **Hedonism:** Does this serve user wellbeing?
- **Emotivism:** How will this make people feel?

---

## 4. Ethical Decision-Making Framework

### What triggers an ethical decision?
> Ethical decision making is the process of making a decision which **may result in one or more moral conflicts**.

### The Full Framework (8 steps from Slide 20)

| Step | What to Do |
|------|-----------|
| 1 | **Recognize** inherent ethical conflicts — comprehend, appreciate, evaluate all ethical dimensions |
| 2 | **Understand** the problem and the facts |
| 3 | **Know** the parties involved (stakeholders) |
| 4 | **Be aware** of alternatives |
| 5 | **Demonstrate** knowledge of ethical practices |
| 6 | **Understand** how the decision will be implemented and who will be affected |
| 7 | **Understand** the impact on affected parties |
| 8 | **Comprehend** the full impact on all involved |

> **Notice:** Steps 6, 7, 8 are variations of impact assessment — the framework keeps circling back to *impact*, because that's the hardest part.

---

## 5. Codes of Ethics

### Definition
> Ethics governed by a particular regiment of rules = **Code of Ethics**

### Forms a Code of Ethics can take (from slides)

| Form | Description | Example |
|------|-------------|---------|
| **Principles** | Guidelines, references, bases for documents | ACM Principles |
| **Public Policies** | Acceptable behavior norms for society | SDAIA AI Ethics |
| **Codes of Conduct** | Include ethical principles, govern actions | Company employee handbook |
| **Legal Instruments** | Enforce good conduct through courts | GDPR |

### Code of Ethics vs. Code of Conduct

| | Code of Ethics | Code of Conduct |
|--|----------------|-----------------|
| **Governs** | Decision-making | Actions/behavior |
| **Nature** | Broad principles and values | Specific rules and procedures |
| **Audience** | Professionals / institutions | Employees / members |
| **Enforcement** | Advisory / inspirational | Often mandatory |

### Objectives of Codes of Ethics (5 — from Slide 24)

| Objective | Explanation |
|-----------|-------------|
| **Disciplinary** | Ensures professionalism and integrity among members |
| **Advisory** | Offers tips, guidance, and advice |
| **Educational** | Teaching tool, especially for newcomers |
| **Inspirational** | Carries subliminal messages to inspire "good" behavior |
| **Publicity** | Shows clients that members are committed to basic values |

### Real Example — ACM Code of Ethics (1992)
- Adopted October 16, 1992
- Contains **24 imperatives**
- Example imperative (3.3): *"Organizational leaders are responsible for ensuring that computer systems enhance, not degrade, the quality of working life."*

---

## 6. Technology and Values

**Why technology creates ethical urgency (from Slide 26):**
- New technologies reshape society and raise moral/ethical concerns
- Technological success often **weakens** individual moral values
- Global cultural, political, and social values are changing rapidly
- **The speed of change overwhelms society's ability to adapt**
- Society cannot develop and implement ethical values quickly enough

> This is why "policy gaps" exist — technology moves faster than ethics and law.

---

## 7. Data Ethics in Practice

### Real Cases from Slides

**British Airways Breach (September 2018):**
- Hackers injected malicious code into BA's website
- Traffic redirected to a fraudulent replica
- Stolen: login details, payment info, addresses, travel bookings
- *Which ethical theory applies?* Deontology (wrong duty/intent) + Consequentialism (serious harm to thousands)

**Facebook Data Breach (March 2021):**
- 533 million users' data posted on open hackers' forum
- One of the largest breaches ever
- Raised question: *Should organizations even be allowed to collect this much data?*
- *Which principle was violated?* Individual Agency + Data Privacy

### Big Data Ethics Principles (Datacamp — Slide 29)

| Principle | What it means | If violated… |
|-----------|--------------|-------------|
| **Transparency** | Clear communication about collection, storage, sharing | Users don't know their data is being sold |
| **Accountability** | Organizations take responsibility for data they hold | No one owns the breach response |
| **Individual Agency** | Users can access, correct, or delete their data | GDPR violation |
| **Data Privacy** | Personal data protected from unauthorized exposure | Facebook 2021 |

---

## 8. Anonymity (intro — continues in Week 4)

### Definition
> Anonymity = absence of identity; the state of being nameless

### Two Types

| Type | Description | Common? |
|------|-------------|---------|
| **Pseudo Identity** | Identified by pseudonym, code, or number (like a pen name) | Most common |
| **Untraceable Identity** | Not known by any name — including pseudo names | Rare |

### Anonymity on the Internet
- Internet has no political, cultural, religious, or judicial boundaries → creates space for anonymous actors
- Two channels for anonymous acts:
  - **Anonymous servers** (through encryption) — two subtypes: anonymous and pseudonymous
  - **Anonymous users**
- **Important:** No anonymity is 100% — anyone with basic networking knowledge can find misusers

### Pros and Cons

| Advantages | Disadvantages |
|-----------|---------------|
| Internal whistleblowing | Criminals exploit it (especially on social networks) |
| National security operations | Accountability becomes impossible |
| Protecting sensitive relationships | |

---

## 🔗 How Week 2 Connects to the Rest of the Course

| Week 2 Concept | Where it appears later |
|---------------|----------------------|
| Ethical Theories | Used to judge cases in every week — cybersecurity, IP, data |
| Code of Ethics vs Conduct | Week 4 (SDAIA, NCA), Stakeholder Analysis |
| Data Privacy principles | Week 4 (Privacy deep dive), Week 14-15 |
| Anonymity intro | Week 4 (full coverage) |
| Technology + values gap | Week 16 (cybersecurity policy gaps) |

---

## ✅ Expected Exam Questions

### Multiple Choice

**Q1. Which ethical theory judges an action purely by its consequences?**
- A) Deontology
- B) Relativism  
- C) ✅ Consequentialism
- D) Emotivism

**Q2. A security researcher hacks into a system to find vulnerabilities before attackers do. Which theory best justifies this?**
- A) Hedonism
- B) Relativism
- C) Emotivism
- D) ✅ Deontology — the action is done as a duty, for good reason

**Q3. "Accessing children's phone data is acceptable in KSA but not in the US" is an example of:**
- A) Hedonism
- B) Deontology
- C) ✅ Relativism
- D) Human Nature

**Q4. Which is NOT one of the five objectives of a Code of Ethics?**
- A) Disciplinary
- B) Inspirational
- C) Publicity
- D) ✅ Regulatory (not listed — legal instruments are a *form*, not an objective)

**Q5. "Using a machine to handle elderly patients makes them nervous" is an example of which theory?**
- A) Consequentialism
- B) ✅ Emotivism
- C) Deontology
- D) Relativism

**Q6. Laws are derived from:**
- A) Government decisions
- B) Technology advancements
- C) ✅ Moral codes
- D) Cultural traditions

**Q7. Utilitarianism is a type of:**
- A) Deontology
- B) Relativism
- C) ✅ Consequentialism
- D) Human Nature

**Q8. What distinguishes Code of Ethics from Code of Conduct?**
- A) Code of Conduct is more general
- B) Code of Ethics is only for engineers
- C) ✅ Code of Ethics governs decision-making; Code of Conduct governs actions
- D) They are the same thing

### Short Answer / Essay

**Q: Explain the six ethical theories and apply each to one data science scenario.**  
*Focus:* Show you understand each theory by applying it, not just defining it. Use examples from the lecture.

**Q: A data scientist collects survey data about users without informing them. Apply THREE different ethical theories to evaluate this action.**  
*Hint:* Consequentialism (what harm results?), Deontology (was it the right duty?), Emotivism (how do users feel?)

**Q: What is the difference between Natural Law and Conventional Law? Why does it matter in the context of data technologies?**  
*Focus:* Natural law = universal, pre-civilization. Conventional law = varies by country. Data crosses borders → conventional laws conflict → natural law (human dignity) is the common baseline.

**Q: What are the objectives of a Code of Ethics? Explain each with an example.**

---

## ⭐ Must-Know for Exam

- **6 theories** — name + one-line definition + one data example each
- **3 types of Consequentialism:** Egoism / Utilitarianism / Altruism
- **Code of Ethics (decisions) ≠ Code of Conduct (actions)**
- **5 objectives of Code of Ethics:** Disciplinary, Advisory, Educational, Inspirational, Publicity
- **4 forms of ethical codes:** Principles, Public Policies, Codes of Conduct, Legal Instruments
- **2 types of law:** Natural (universal, unwritten) vs. Conventional (varies, written)
- **4 Big Data Ethics principles:** Transparency, Accountability, Individual Agency, Data Privacy
- **2 types of anonymity:** Pseudo Identity (most common) vs. Untraceable Identity
- **ACM Code of Ethics:** adopted 1992, 24 imperatives
- **Technology creates policy gaps** because it moves faster than ethics and law
- Laws are derived from **moral codes**, not the other way around
