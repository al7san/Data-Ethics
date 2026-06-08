# Week 14-15 — Ethics and Data
**Course:** Data and Ethics | Dr. Ali Algarni  
**Source:** Markkula Center for Applied Ethics, Santa Clara University

---

## 🗺️ Big Picture

```
DATA PRACTICES affect people's ability to LIVE WELL
        ↓
Three areas of ethical risk:
  ├── Collection & Use      → consent, purpose, over-collection
  ├── Storage & Stewardship → security, accountability, lifecycle
  └── Analysis & Presentation → fairness, transparency, autonomy
        ↓
Ethical obligations require:
  ├── Understanding harms AND benefits
  ├── Human accountability (avoiding "problem of many hands")
  └── Best practices — not just compliance
```

---

## 1. What Does Ethics Have to Do with Data?

> *"Ethical issues are everywhere in the world of data."*

### The "Perfect Storm" of Ethical Risk (from Slide 7)

Three conditions creating compounding risk:
1. **Increasingly powerful, potentially misleading data analytics** — tools that are easy to misuse
2. **Poorly regulated commercial environment** — market incentives often conflict with ethical practice
3. **Absence of widespread, well-designed standards** — across industry, university, nonprofit, and government

### Data Ethics Goes Beyond Just Big Data
Big data is NOT just about large datasets. It includes:
- Data generation, mining, scraping, and sampling
- AI and ML; natural language and image processing
- Cloud computing and storage
- Cybersecurity

> **All of these have ethical dimensions** — not just the data itself.

### The Three Stories — Discussion from Slide 9

These show how data practices produce real-world life impacts:

| Person | Situation | Data Ethics Issue |
|--------|-----------|------------------|
| **Rosalina** | Denied promotion despite being objectively best candidate | Algorithmic bias in HR decision systems |
| **John** | Receives customized cancer treatment that achieves 75% remission | Beneficial predictive medicine — data saves lives |
| **The Patels** | Family in India gets flood warning days early — time to evacuate | Data for social good; life-saving early warning systems |

---

## 2. Benefits of Ethical Data Practices

### Three Categories of Benefit (Slide 12)

#### Human Understanding
- Data enriches our understanding of ethically significant relationships
- Helps us understand how complex systems interact
- The more we understand → the more intelligently we can act

#### Social, Institutional, and Economic Efficiency
- Once we have accurate picture of how the world works → design better systems
- Example from slides: **Big data helps manage regional traffic** → reduces congestion, emissions, time

#### Predictive Accuracy and Personalization
- Helps social systems work more efficiently
- Enables customized healthcare, education, services

---

## 3. Harms from Data Practices

### Three Categories of Harm (Slide 13)

| Category | Examples | Ethical Theory Applied |
|----------|----------|----------------------|
| **Harms to Privacy & Security** | Data breaches; identity theft; unauthorized access | Deontology (violated duty to protect), Consequentialism (real harm to millions) |
| **Harms to Fairness & Justice** | Algorithmic discrimination; biased hiring tools | Human Nature (decision-makers lack capabilities), Relativism (varies by context) |
| **Harms to Transparency & Autonomy** | "Black box" deep learning decisions | Emotivism (people feel powerless), Consequentialism (bad outcomes from opacity) |

**Concrete example from slides:**
> Loan approval by Deep Learning → can't explain to customer why they were denied.  
> This violates **transparency** AND **autonomy** simultaneously — you can't make an informed decision about your own financial life.

---

## 4. Ethical Challenges in Data Collection and Use

### Question 1: Are we respecting the original purpose?
- Personal data shared for **medical research** → can we sell it to a data broker for any purpose? **No** — ethically this violates the original purpose
- The key concept: **contextual integrity** — data should flow in ways appropriate to its original context

### Question 2: Are we avoiding over-collection?
- Are we collecting more data than the situation justifies?
- **When is web scraping ethical?** Depends on purpose, public nature of data, and terms of service
- **Ethical test:** Would we collect this data if we had to ask each person individually?

### Question 3: Have we given appropriate forms of choice?

| | Opt-in | Opt-out |
|--|--------|---------|
| **Default** | User is NOT sharing until they agree | User IS sharing unless they explicitly stop |
| **Protection level** | Higher — requires active consent | Lower — relies on users finding the opt-out |
| **Example** | Newsletter signup | Cookie tracking that continues until disabled |
| **Design trick** | Consent button prominent | Opt-out buried in settings (dark pattern) |

> "Are data subjects 'boxed in' by the circumstances?" — pressure or lack of real alternatives undermines consent.

### Question 4: Is the policy actually understandable?
- Avoid unnecessarily **legalistic or technical jargon**
- Does the UI design **encourage careful reading**? (UX/UI matters ethically)
- Are there clear paths to getting more information? ("Why am I seeing this ad?")
- Are there accessible options to disable sharing?

### Question 5: Are data subjects compensated fairly?
- Data has value — are users being fairly compensated for providing it?
- Are users being **exploited** — do they understand the interaction as we do?
- Should users retain rights to **withdraw, correct, or update** their data?

---

## 5. Data Storage, Security, and Responsible Stewardship

### Key Questions for Responsible Storage (Slide 18-19)

| Question | Why it matters |
|---------|---------------|
| How do we responsibly store PII (Personally Identifiable Information)? | Breaches of PII cause direct harm to individuals |
| Are subjects given clear, accurate information about storage terms? | Transparency obligation |
| Who in our organization is responsible for which aspects of the data? | Accountability structure |
| What are our concrete action plans for a data breach? | Mitigation strategies must exist before a breach |
| Are our investments in security infrastructure appropriate? | Under-investment = ethical failure |
| Are we using reliable storage/security vendors? | Third-party risk management |

### Privacy-Preserving Techniques

| Technique | How it works | When to use |
|-----------|-------------|------------|
| **Data Anonymization** | Remove or mask personally identifiable information | Before sharing datasets |
| **Obfuscation** | Make data appear random/useless to attackers even if breached | Sensitive stored data |
| **Scrambling** | Rearrange data so it cannot be read meaningfully | Data at rest |

---

## 6. Data Lifecycle — End-to-End Plan

> From Slide 20: "Do we have an end-to-end plan for the lifecycle of the data we collect?"

### The Data Lifecycle
```
Collection → Storage → Analysis → Dissemination → [Archival or Deletion]
```

At each stage:
- Who is responsible? (Data Steward)
- What are the standards for deletion/correction/update?
- Is the plan accessible to affected/interested parties?

**Data Steward** = the designated person(s) responsible for data governance throughout the lifecycle

---

## 7. Data Hygiene and Relevance

> **Data Hygiene** = maintaining the accuracy, consistency, and reliability of data over time.

### Key Practices (from Slide 21)

| Practice | Purpose |
|---------|---------|
| **Validation and auditing** | Ensure data conforms to necessary constraints |
| **Parsing and consistency** | Standardize field labels when integrating from different sources |
| **Integrity during transfer** | Prevent data corruption when moving between systems |
| **Scrubbing dirty data** | Remove or fix inaccurate, duplicate, or corrupt records |
| **Relevance assessment** | Ask: how long is this data likely to remain accurate/useful? |
| **Refresh plan** | What happens when datasets become outdated? |

---

## 8. Validation and Testing of Data Models

### Ethical Challenges in Testing (Slide 22)

| Challenge | The ethical issue |
|-----------|-----------------|
| **Adequate testing** | Have we tested thoroughly enough before deployment? |
| **Black box transparency** | Deep Learning decisions may be inexplicable — ethically problematic |
| **Reliability across new contexts** | Drug approved for Condition A; used for Condition B? |
| **Auditing for disparate outcomes** | Are results fair across different demographic groups? |
| **Responding to accusations** | What happens if the system causes harm — what's our response process? |

---

## 9. Human Accountability in Data Practices

### The Problem of Many Hands (Slide 23)

> **"Problem of Many Hands"** = when many people each contribute to an outcome, it becomes unclear who is responsible when something goes wrong.

**From slides:** AI or model bias isn't the programmer's fault alone — it comes from data from different resources and places — the developer, the data annotators, the team that chose the features, the manager who deployed it — all contributed.

### Accountability Framework

| Question | Why ask it |
|---------|-----------|
| Who is designated as responsible for each aspect? | Specific individuals must be accountable |
| Who is accountable for harms that result? | Accountability requires names, not committees |
| Do we have effective organizational policies? | Policies must be established before problems occur |
| To what extent should our practices be open for inspection? | Transparency to the public has its own ethical value |

---

## 10. Best Practices for Data Ethics

### For Organizations (7 practices — Slide 26)

| Practice | What it means in practice |
|---------|--------------------------|
| **1. Keep Ethics in the Spotlight** | Treat ethics as ongoing judgment, not a compliance checkbox |
| **2. Consider Human Lives Behind Data** | Every data point represents a real person with real stakes |
| **3. Focus on Downstream Risks** | Think about how data could be misused, not just how it's intended to be used |
| **4. Mind the Gap** | The difference between what users expect and what you actually do is an ethical gap |
| **5. Treat Data as a Conditional Good** | Data is not inherently good — it's good only when used appropriately |
| **6. Establish Chains of Responsibility** | Clear accountability structure — no "problem of many hands" |
| **7. Design for Privacy and Security** | Build privacy in from the start (Privacy by Design), not as an afterthought |

### For Individuals (5 practices)
1. **Look for Moral Exemplars** — find role models who embody ethical practice
2. **Exercise Moral Imagination** — imagine the impact of your decisions on others
3. **Practice Self-Reflection** — regularly examine your own assumptions and biases
4. **Acknowledge Your Moral Strength** — you have the power and responsibility to act ethically
5. **Seek the Company of Other Moral Persons** — ethics is socially reinforced

---

## 🔗 How Week 14-15 Connects to Other Topics

| Week 14-15 Concept | Connected To |
|-------------------|-------------|
| Problem of Many Hands | Week 16 (Cybersecurity Accountability) |
| Opt-in vs. Opt-out | Privacy module (GDPR requires explicit consent) |
| Black Box problem | Week 5 (Bias — evaluation bias; unexplainable models) |
| Data Lifecycle | Week 9 (IP in data management — licensing, sharing) |
| Contextual Integrity | Week 4 (Privacy — personal vs. informational privacy) |
| "Design for Privacy" | Week 16 (cybersecurity — security by design) |

---

## ✅ Expected Exam Questions

### Multiple Choice

**Q1. "Problem of Many Hands" means:**
- A) Too many employees working on the same dataset
- B) ✅ When responsibility is diffused across many people, making accountability unclear
- C) A method of distributed data processing
- D) Multiple data sources creating contradictions

**Q2. Which technique makes data appear useless even if an attacker accesses it?**
- A) Data Anonymization
- B) ✅ Obfuscation
- C) Encryption only
- D) Access Controls

**Q3. A data scientist collects survey data from users "for medical research" and then sells it to advertisers. This violates:**
- A) Hedonism
- B) ✅ Contextual integrity — data was shared for a specific purpose and used for another
- C) Deontology only
- D) Representation Bias

**Q4. Opt-out default settings are ethically weaker because:**
- A) Users prefer them
- B) They are illegal under GDPR
- C) ✅ Users share data automatically unless they take active steps to stop it
- D) They cost more to implement

**Q5. "Design for Privacy and Security" as a best practice means:**
- A) Adding privacy features after the product is built
- B) ✅ Building privacy and security into systems from the very beginning
- C) Only encrypting sensitive fields
- D) Publishing a privacy policy

**Q6. Deep Learning's "Black Box" problem is primarily a harm to:**
- A) Privacy and Security
- B) Fairness and Justice
- C) ✅ Transparency and Autonomy
- D) Data collection practices

**Q7. Data Hygiene includes:**
- A) Washing servers physically
- B) ✅ Validating, cleaning, and maintaining accuracy of data over time
- C) Deleting all old data
- D) Encrypting all records

### Essay Questions

**Q: Describe the three categories of ethical harm from data practices. Give an example and the relevant ethical theory for each.**

**Q: What is the "Problem of Many Hands"? How does it relate to ML/AI development? How should organizations address it?**

**Q: Explain the seven best practices for data ethics (organizational level). For each, explain why it matters.**

**Q: Compare Opt-in vs. Opt-out data sharing. Which is more ethically sound and why? Give examples of each.**

---

## ⭐ Must-Know for Exam

- **3 "perfect storm" conditions** creating ethical risk in data
- **3 categories of benefits:** Human Understanding / Efficiency / Predictive Accuracy
- **3 categories of harm:** Privacy+Security / Fairness+Justice / Transparency+Autonomy
- **Black Box = Transparency/Autonomy harm** (Deep Learning can't explain decisions)
- **Problem of Many Hands** = diffused accountability → no one responsible
- **Opt-in > Opt-out** in terms of user protection
- **Contextual integrity** = data should flow as appropriate to its original context
- **7 organizational best practices** — know all 7, especially #1 and #7
- **3 privacy-preserving techniques:** Anonymization / Obfuscation / Scrambling
- **Data Steward** = responsible for data lifecycle governance
- **PII** = Personally Identifiable Information — must be protected
- **Data Hygiene** = ongoing accuracy, consistency, relevance maintenance
