# Week 4 — Anonymity, Security, Privacy & Civil Liberties
**Course:** Data and Ethics | Dr. Ali Algarni  
**Sources:** Ch. 5 — Ethical & Social Issues in the Information Age

---

## 🗺️ Big Picture — How Everything Connects

```
Why does information need protection?
  └─ Information has increased in value → demand is high
        ├─ High digitalization + declining costs of communication
        ├─ Miniaturization of devices (always connected)
        └─ Greater public awareness of abuse potential
              ↓
  Three threats to address:
        ├─ ANONYMITY — who are you online?
        ├─ SECURITY — how do we protect systems?
        └─ PRIVACY — what rights do individuals have over their data?
```

---

## 1. Anonymity

### Definition
> Anonymity = **absence of identity**; the state of being nameless or having no identity.

Living in total anonymity is extremely difficult for anyone — we always leave *some* trace.

### Two Types of Anonymity

| Type | Description | Real-World Analogy |
|------|-------------|-------------------|
| **Pseudo Identity** | Known by a pseudonym, code, or number | Writer's pen name; Reddit username |
| **Untraceable Identity** | Not known by any name — including pseudo names | Deep web anonymous actors |

> Pseudo Identity is the **most common** variant.

### Anonymity on the Internet

The Internet's lack of political, cultural, religious, and judicial boundaries creates space for anonymous actors.

**Two channels for anonymous acts:**

| Channel | How it works |
|---------|-------------|
| **Anonymous Servers** | Use encryption; subtypes: truly anonymous and pseudonymous |
| **Anonymous Users** | Individuals masking their identity through various means |

**Critical point from slides:** No anonymity type is 100% anonymous. Anyone with basic networking knowledge can trace misuse.

### Pros vs. Cons of Anonymity

| Advantages ✅ | Disadvantages ❌ |
|--------------|----------------|
| Whistleblowing — checking unhealthy activities inside organizations | Criminals exploit it, especially on social networks |
| National security operations | No accountability possible |
| Protecting sensitive relationships and identities | Hard to enforce laws |

---

## 2. Security — The CIA Triad

### Definition
> Security = preventing **unauthorized access, use, alteration, theft, or physical damage** to property.

### 🔺 CIA Triad — The Core of Security

| Element | Full Name | What it Prevents | Example of Violation |
|---------|-----------|-----------------|---------------------|
| **C** | Confidentiality | Unauthorized disclosure to third parties | Attacker reads your encrypted messages |
| **I** | Integrity | Unauthorized modification of files | Attacker tampers with medical records |
| **A** | Availability | Unauthorized withholding of information from those who need it | DDoS attack takes down a hospital system |

> **Exam tip:** All three must be in balance. Prioritizing one at the expense of another creates risk. (e.g., extreme security measures → poor availability)

---

### Physical Security

> A facility is physically secure if it is surrounded by a barrier, has secure interior/exterior areas, and can resist penetration.

**Four Mechanisms of Physical Security (in order of escalation):**

| Mechanism | When used | How it works |
|-----------|-----------|-------------|
| **Deterrence** | Before intrusion attempt | Creates atmosphere to scare off intruders |
| **Prevention** | During potential intrusion | Stops intruders from gaining access (fences, locks) |
| **Detection** | Intrusion in progress | Identifies intruder who has/is gaining access |
| **Response** | After other mechanisms fail | Stops and/or prevents damage |

**Physical Security Barriers:**
- Fences, brick walls, motion detection sensors
- Security lighting, CCTV
- Window breakage detectors, infrared/ultrasonic detectors
- Interior microwave systems, guard dogs

**Electronic Access Controls:**
- Card access systems
- Firewalls
- Passwords

---

### Passwords — The Four "Never" Rules (from Slide 14)

| Rule | Why |
|------|-----|
| **Never publicize** a password | Direct exposure |
| **Never write it down** anywhere | Physical security risk |
| **Never choose** an easy-to-guess password | Brute-force vulnerability |
| **Never keep** the same password long-term | Reduces exposure window if compromised |

**Examples of bad passwords from slides:** `abcdefg`, `password`, `monkey`, `123456`

**Organizational best practices (Microsoft 365):**
- Don't reuse org passwords for personal accounts
- Enforce multi-factor authentication (MFA)
- Enable identity protection risk policies
- Configure password resets paired with authentication apps

---

### Firewalls — Three Models

| Type | How it Works | Complexity |
|------|-------------|-----------|
| **Packet Filters** | Allow/block packets based on minimum conditions | Basic |
| **Proxy Servers** | Work on protected portions; provide info to external requests | Medium |
| **Stateful Inspection** | Combines filter + proxy functions | Advanced (most complex) |

---

### Cryptography — Information Security Controls

> Cryptography = the science of writing and reading coded messages; forms the basis for all secure transmission.

**Key terms:**
- **Plaintext** = original readable data
- **Ciphertext** = encrypted, unintelligible form
- **Encryption key** = the algorithm that transforms plaintext → ciphertext

**Three Cryptographic Functions:**

| Type | How it Works | Key Characteristic | Problem |
|------|-------------|-------------------|---------|
| **Symmetric Encryption** (Secret-Key) | Same key encrypts and decrypts | Fast, simple | Key distribution problem — how do you securely share the key? |
| **Asymmetric Encryption** (Public-Key) | Two keys: public (everyone knows) + private (only sender/receiver) | More secure | Slower |
| **Hash Function** | Input → fixed-size digest (one-way) | Cannot reverse | Not used for encryption — used for verification |

```
Symmetric:   Sender [Key A] → Ciphertext → Receiver [Key A]
Asymmetric:  Sender [Private Key] → Ciphertext → Receiver [Public Key]
Hash:        Data → Hash Digest (cannot reverse back to data)
```

> **Sniffers** = programs installed on communication channels to eavesdrop on network traffic. Cryptography protects against them.

---

### Authentication and Digital Signatures

**Authentication** = process the system uses to assure a user is genuine.

**Digital Signature** = ensures the recipient knows:
1. The identity of the sender
2. The integrity of the message (wasn't tampered with)

**A digital signature system has two parts:**
1. A method of signing a document
2. Authentication that the signature was genuinely generated by the stated person

**Authentication can be based on (from Slide 26):**
- Username / screen name
- Password
- Biometrics (retinal images, fingerprints)
- Physical location
- Identity cards

---

## 3. Privacy

### Definition
> Privacy = a **human attribute** consisting of four elements: **Solitude, Anonymity, Intimacy, Reserve**

### The Four Elements — Two Categories

```
PRIVACY
├── Control of External Influences
│   ├── Solitude    → the right to be ALONE without disturbance
│   ├── Anonymity   → the right to have NO public personal identity
│   └── Intimacy    → the right NOT to be monitored
└── Control of Personal Information
    └── Reserve     → the right to CONTROL one's personal information
                      including methods of dissemination
```

### Three Types of Privacy

| Type | What it protects | Example from slides |
|------|-----------------|---------------------|
| **Personal Privacy** | Privacy of personal attributes (physical, behavioral) | US 4th Amendment — right against unreasonable searches |
| **Informational Privacy** | Protection from unauthorized access to information itself | Medical, financial, internet data |
| **Institutional Privacy** | Organizations' data confidentiality | Samsung proprietary source code — employees used ChatGPT, exposing it |

> **Who is responsible for Institutional Privacy? (Data Controller)**
> - Executives and Senior Officials
> - Privacy Officers
> - IT Department

### Three Attributes of Privacy's Value (Slide 32)

| Attribute | What it means |
|-----------|--------------|
| **Personal Identity** | Privacy safeguards who you are |
| **Autonomy** | Less known about you → more freedom to make your own decisions |
| **Social Relationships** | Privacy enables genuine, unmonitored relationships |

> **Autonomy insight:** "People will challenge one's autonomy depending on the quantity, quality, and value of information they have about that individual." — The more data someone has about you, the more leverage they have.

---

### Real Cases — Value of Privacy

**Facebook–Cambridge Analytica (2018):**
- A third-party developer collected data of ~87 million Facebook users via a personality quiz
- No explicit consent was given
- Data was sold to Cambridge Analytica
- **Result:** $5 billion FTC fine + massive reputational damage

**Equifax Data Breach (2017):**
- Personal information (SSNs etc.) of **147 million** people accessed
- **Result:** $700 million settlement

**Apple App Tracking Transparency (2021):**
- Prompt asking users for permission to track across apps
- Gave users control → forced companies to rethink tracking-based business models
- Example of **privacy by design**

---

### Privacy Violations — Contributing Factors (Slide 34)

- Consumers give up information for prizes / registrations without reading terms
- Lack of knowledge: a small piece of info → big privacy invasion
- Inadequate privacy policies
- Institutions fail to follow their own privacy policies
- Internet temptation — businesses can reach individuals in their own homes

### Five Forms of Privacy Violation

| Form | Description |
|------|-------------|
| **Intrusion** | Wrongful entry (hacking) |
| **Misuse of Information** | Using involuntarily given data for wrong purposes |
| **Interception** | Eavesdropping on communications |
| **Surveillance** | Ongoing monitoring of individuals |
| **Information Matching** | Combining unrelated databases illegally |

---

## 4. Privacy Protection and Civil Liberties

### Civil Liberties — Four Categories (from Slide 36)
1. **Criminal justice** — police powers, personal liberty, right to fair trial
2. **Basic freedoms** — speech, assembly, association, movement, no discrimination
3. **Freedom of information**
4. **Communications and privacy**

### Why Technology Threatens Civil Liberties
- Detailed information can be cheaply moved, merged, compared, and shared
- Law enforcement (FBI) can track individuals through data
- Accessing and sharing personal data without consent is a serious threat
- Network scanning and spying tools exist alongside privacy tools

### Privacy Protection Guidelines — Three Levels

| Level | Approach | Example |
|-------|---------|---------|
| **Technical** | User self-regulation | Cookie notices; cookie management software |
| **Contractual** | Protection against unauthorized reproduction/distribution | Terms of service agreements |
| **Legal** | National laws enacted and enforced | FERPA (1974) — schools must grant students access to their own records |

---

## 5. Ethical and Legal Framework — GDPR & CCPA

### GDPR (General Data Protection Regulation)
- European Union regulation
- Governs how organizations collect, store, process personal data of EU citizens

### CCPA (California Consumer Privacy Act)
- US state-level (California) equivalent

### SDAIA (Saudi Arabia)
- The Implementing Regulation of the Personal Data Protection Law
- NCA (National Cybersecurity Authority) — Data Cybersecurity Control

---

## 🔗 How Week 4 Connects to Other Topics

| Week 4 Concept | Connected To |
|---------------|-------------|
| CIA Triad | Week 16 (Cybersecurity — CIA triad reappears) |
| Encryption types | Week 16 (data storage and encryption challenge) |
| Privacy violations | Week 14-15 (ethical challenges in data collection) |
| Data Controller | Week 14-15 (human accountability in data) |
| GDPR | Privacy & Information Disclosure module |
| Cambridge Analytica | Stakeholder Analysis (who were the stakeholders?) |

---

## ✅ Expected Exam Questions

### Multiple Choice

**Q1. The CIA Triad stands for:**
- A) Classified, Indexed, Archived
- B) ✅ Confidentiality, Integrity, Availability
- C) Control, Inspect, Authenticate
- D) Cryptography, Integration, Access

**Q2. A DDoS attack that takes down a hospital system violates which CIA element?**
- A) Confidentiality
- B) Integrity
- C) ✅ Availability
- D) Authentication

**Q3. Symmetric encryption's main weakness is:**
- A) It is too slow
- B) ✅ Key distribution — securely sharing the same key with the receiver
- C) It uses two keys
- D) It can be reversed easily

**Q4. "Solitude" in the context of privacy means:**
- A) Controlling your personal data
- B) Not being monitored
- C) Having no public identity
- D) ✅ The right to be alone without disturbance

**Q5. Facebook–Cambridge Analytica involved approximately how many users' data?**
- A) 14 million
- B) 147 million
- C) ✅ 87 million
- D) 533 million

**Q6. Which is NOT one of the four physical security mechanisms?**
- A) Deterrence
- B) Detection
- C) ✅ Destruction
- D) Response

**Q7. Hash functions are primarily used for:**
- A) Encrypting large files
- B) ✅ Creating digital signatures / verifying integrity
- C) Sharing keys between sender and receiver
- D) Replacing passwords

**Q8. Who is responsible for Institutional Privacy (Data Controller)?**
- A) External auditors only
- B) ✅ Executives, Privacy Officers, and IT Department
- C) End users
- D) The government

### Essay Questions

**Q: Explain the CIA Triad. For each element, give a real-world example of a violation.**  
*Structure:* Define CIA → Confidentiality example (data breach) → Integrity example (record tampering) → Availability example (DDoS).

**Q: Compare Symmetric vs. Asymmetric Encryption. When would you use each?**  
*Focus:* One key vs. two keys; key distribution problem; speed vs. security tradeoff.

**Q: Describe three types of privacy with examples. Who is responsible for protecting Institutional Privacy?**

**Q: What are the contributing factors to privacy violations? Give three examples from real incidents.**

---

## ⭐ Must-Know for Exam

- **CIA Triad:** Confidentiality + Integrity + Availability — know what each prevents
- **4 Physical Security Mechanisms:** Deterrence → Prevention → Detection → Response (in order)
- **3 Firewall Types:** Packet Filter / Proxy Server / Stateful Inspection (most advanced)
- **3 Cryptography Types:** Symmetric (1 key), Asymmetric (2 keys), Hash (one-way)
- **Key distribution problem** = weakness of symmetric encryption
- **Digital Signature** = ensures sender identity + message integrity
- **Privacy = 4 elements:** Solitude, Anonymity, Intimacy, Reserve
- **3 Privacy Types:** Personal, Informational, Institutional
- **Data Controller = Executives + Privacy Officers + IT**
- **Cambridge Analytica:** 87M users | $5B FTC fine
- **Equifax:** 147M people | $700M settlement
- **5 Forms of Privacy Violation:** Intrusion, Misuse, Interception, Surveillance, Information Matching
- **GDPR** = EU | **CCPA** = California | **SDAIA/PDPL** = Saudi Arabia
- **4 "Never" password rules** — know all four
