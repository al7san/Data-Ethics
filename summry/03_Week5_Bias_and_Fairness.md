# Week 5 — Bias and Fairness in ML/AI
**Course:** Data and Ethics | Dr. Ali Algarni  
**Key Paper:** Gebru et al. (2021), Datasheets for Datasets — Communications of the ACM

---

## 🗺️ Big Picture

```
ML Model Lifecycle
      ↓
  DATA GENERATION  →  MODEL BUILDING  →  EVALUATION/DEPLOYMENT
  (3 bias sources)    (2 bias sources)    (2 bias sources)
                                     ↓
                            Real-world harms to individuals & groups
                                     ↓
                    Solution: DOCUMENTATION (Datasheets + Data Cards + Model Cards)
```

---

## 1. The Seven Sources of Harm in ML

> **Framework:** "A Framework for Understanding Sources of Harm throughout the Machine Learning Life Cycle"

This framework maps where bias enters at each stage of the ML pipeline.

---

### Stage 1 — Data Generation (3 sources)

#### Source 1: Historical Bias
- **What it is:** The training data reflects historical prejudices and stereotypes — even if collected perfectly
- **It exists even when:** data collection is flawless and representative
- **Example from slides:** Word Embedding — words like "doctor" associated with "he," "nurse" with "she" — because historical text had this bias

#### Source 2: Representation Bias
- **What it is:** The population sampled for the dataset doesn't represent the real-world population that will use the model
- **Example from slides:**
  - **Population Sampling:** A model trained mostly on data from one demographic group fails on others
  - **Geographic Diversity in Image Datasets:** If training images are mostly from Western countries, a model fails to recognize objects/people from other regions

#### Source 3: Measurement Bias
- **What it is:** The features selected to measure a concept don't actually capture that concept fairly for all groups
- **Example from slides:**
  - **Feature Selection:** Choosing a proxy variable that correlates with race/gender introduces bias
  - **Risk Assessments in the Criminal Justice System:** Using "prior arrests" as a risk factor inherits the bias of policing patterns

---

### Stage 2 — Model Building (2 sources)

#### Source 4: Aggregation Bias
- **What it is:** A single model is built for a diverse population as if everyone is the same ("one-size-fits-all")
- **Example from slides:**
  - **One-size-fits-all model:** A diabetes prediction model trained on mixed data fails because the disease manifests differently across ethnic groups
  - **Social Media Analysis:** Sentiment analysis trained on English text fails for other languages

#### Source 5: Learning Bias
- **What it is:** The model's training process (optimization choices) amplifies certain patterns over others
- **Example from slides:**
  - **Accuracy-Pruning tradeoff:** Pruning a model to improve speed/accuracy on the majority group hurts minority groups

---

### Stage 3 — Evaluation and Deployment (2 sources)

#### Source 6: Evaluation Bias
- **What it is:** The benchmark dataset used to evaluate the model doesn't represent the actual use population
- **Example from slides:**
  - **Commercial Facial Analysis Tools:** Benchmarked on datasets that are mostly light-skinned → performs poorly on dark-skinned faces (documented in Gender Shades study)

#### Source 7: Deployment Bias
- **What it is:** The model is used in a context or way that is different from how it was designed and evaluated
- **Example from slides:**
  - **Risk Assessment Tools in Practice:** A risk assessment tool designed to *inform* a judge's decision gets used as if it *makes* the decision — the tool was not designed for that level of authority

---

### All Seven — Summary Table

| # | Source | Stage | Root Problem | Lecture Example |
|---|--------|-------|-------------|-----------------|
| 1 | Historical Bias | Data Generation | Past prejudice embedded in data | Word embeddings |
| 2 | Representation Bias | Data Generation | Sample ≠ population | Geographic image diversity |
| 3 | Measurement Bias | Data Generation | Proxy features are unfair | Criminal justice risk scores |
| 4 | Aggregation Bias | Model Building | Ignores group differences | One model for all demographics |
| 5 | Learning Bias | Model Building | Optimization favors majority | Pruning hurts minorities |
| 6 | Evaluation Bias | Evaluation | Benchmark ≠ use population | Facial recognition benchmarks |
| 7 | Deployment Bias | Deployment | Use ≠ design purpose | Risk tool used as judge |

---

## 2. Bias vs. Variance — The Technical Dimension

> This connects the ethical problem to the ML technical concept.

| | Bias | Variance |
|--|------|---------|
| **Type of error** | From oversimplifying the model | From extreme sensitivity to training data |
| **Result** | Underfitting — model misses real patterns | Overfitting — model learns noise, not signal |
| **Analogy** | A ruler that's always 5cm short | A ruler that bends differently each time |
| **Ethical implication** | Consistently wrong predictions for certain groups | Unpredictable — works sometimes, fails others |

**The ethical goal (from slides):** Ensuring that algorithms do not **unfairly harm, discriminate against, or produce untrustworthy results** for individuals or groups — this requires balancing bias and variance while also auditing for fairness across groups.

---

## 3. Datasheets for Datasets

### Why it exists
> *"Standardize process for documenting datasets and solve severe consequences when machine learning models are used in high-stakes domains."*

**Paper:** Gebru, T., et al. (2021). *Datasheets for datasets*. Communications of the ACM, 64(12), 86-92.

**Two key groups it serves:**
1. **Dataset creators** — must be transparent about what they built
2. **Dataset consumers** — must be able to select appropriate datasets and avoid misuse

> Transparency from creators → enables consumers to select appropriately → prevents unintentional misuse

### What goes in a Datasheet?

| Section | What it documents |
|---------|------------------|
| **Motivation** | Why was this dataset created? Who funded it? |
| **Composition** | What does it contain? Are there labels? Missing data? |
| **Collection Process** | How was it collected? Who collected it? Over what time? |
| **Recommended Uses** | What is this dataset appropriate for? What is it NOT appropriate for? |
| **Distribution** | How will the dataset be distributed? Under what license? |
| **Maintenance** | Who maintains it? How will it be updated? |

### What Datasheets Achieve

| Benefit | How |
|---------|-----|
| ✅ Increase transparency and accountability | Dataset creators must document decisions |
| ✅ Mitigate unwanted biases | Consumers can see biases before training |
| ✅ Facilitate reproducibility | Others can replicate results |
| ✅ Help select appropriate datasets | Consumers know what a dataset is and isn't good for |

---

## 4. Google Data Cards Playbook

> **Developed by:** Google Research  
> **Reference:** Pushkarna, M., Zaldivar, A., & Kjartansson, O. (2022). Data cards: Purposeful and transparent dataset documentation for responsible AI.

### Three Core Objectives

| Objective | What it means |
|-----------|--------------|
| **Transparency** | A clear "nutrition label" for datasets — what's in it, what are its limitations |
| **Responsible AI** | Identify biases and ethical issues *before* a model is ever trained on the data |
| **Usability** | Make complex data information accessible to non-technical stakeholders (policy experts, legal teams, researchers) |

### The Four-Step Framework

| Step | Action |
|------|--------|
| **Ask** | What questions do different stakeholders need answered about this dataset? |
| **Inspect** | Evaluate existing data to see if it meets those needs |
| **Answer** | Fill out the Data Card template with context and technical details |
| **Audit** | Review the completed card for accuracy, clarity, and completeness |

---

## 5. Google Model Card

### What it is
> Simple, structured overviews of how an advanced AI model was designed and evaluated — supporting Google's approach to responsible AI.

### What each Model Card includes

| Section | Purpose |
|---------|---------|
| **Model Training and Development Evaluation** | How was the model built and tested? |
| **Human Red Teaming** | Attempts by humans to find flaws and failure modes |
| **Risks and Mitigations** | Known risks and how they're addressed |
| **Safety Policies** | What the model will and won't do |
| **Ethics & Safety Reviews** | Formal review process |

**Example:** Gemini 3 Pro Model Card — publicly available at Google DeepMind

---

## 6. Data Card vs. Datasheet vs. Model Card

| | Datasheets for Datasets | Data Cards Playbook | Model Card |
|--|------------------------|---------------------|------------|
| **Focus** | The dataset | The dataset (more stakeholder-centered) | The trained model |
| **Origin** | Academic paper (Gebru et al. 2021) | Google Research (Pushkarna et al. 2022) | Google |
| **Audience** | ML community broadly | Also policy, legal, non-technical teams | Anyone using the model |
| **Process** | Documentation checklist | Ask → Inspect → Answer → Audit | Template with specific sections |

---

## 🔗 How Week 5 Connects to Other Topics

| Week 5 Concept | Connected To |
|---------------|-------------|
| Historical Bias in data | Week 14 (Ethical Challenges in Data Collection) |
| Measurement Bias (risk assessment) | Stakeholder Analysis (who bears the harm?) |
| Aggregation Bias | Week 14 (one-size-fits-all = fairness problem) |
| Deployment Bias | Week 16 (cybersecurity tools used beyond their scope) |
| Transparency (Datasheets) | Week 2 (Big Data Ethics Principles — Transparency) |
| Accountability (documentation) | Week 14 (Human Accountability in Data Practices) |

---

## ✅ Expected Exam Questions

### Multiple Choice

**Q1. How many sources of harm are identified in the ML lifecycle framework?**
- A) 5
- B) ✅ 7
- C) 9
- D) 4

**Q2. A facial recognition system trained mostly on light-skinned faces performs poorly on dark-skinned faces. This is an example of:**
- A) Deployment Bias
- B) Learning Bias
- C) ✅ Evaluation Bias — benchmark data didn't represent the use population
- D) Historical Bias

**Q3. "The risk assessment tool was designed to inform judges, but courts started using it to make decisions automatically." This is:**
- A) Measurement Bias
- B) Aggregation Bias
- C) Evaluation Bias
- D) ✅ Deployment Bias — used differently from its design purpose

**Q4. Word embeddings that associate "doctor" with "he" and "nurse" with "she" is an example of:**
- A) Representation Bias
- B) ✅ Historical Bias — reflects historical gender roles in text
- C) Aggregation Bias
- D) Measurement Bias

**Q5. Datasheets for Datasets were proposed to address needs of:**
- A) Government regulators only
- B) Model trainers only
- C) ✅ Dataset creators AND dataset consumers
- D) End users of applications

**Q6. In the Data Cards Playbook, the step "Inspect" means:**
- A) Auditing the completed card
- B) Identifying stakeholder questions
- C) ✅ Evaluating existing data to see if it meets identified needs
- D) Filling in the Data Card template

**Q7. High bias in a model leads to:**
- A) Overfitting
- B) ✅ Underfitting — the model misses real patterns
- C) High variance
- D) Better generalization

**Q8. The Gemini 3 Pro Model Card is an example of:**
- A) Datasheets for Datasets
- B) Data Cards Playbook
- C) ✅ Google Model Card
- D) ACM Code of Ethics

### Essay Questions

**Q: Describe the seven sources of harm in the ML lifecycle. For each, state at which stage it occurs and give an example.**  
*Structure:* Data Generation (Historical, Representation, Measurement) → Model Building (Aggregation, Learning) → Evaluation/Deployment (Evaluation, Deployment)

**Q: What is the purpose of "Datasheets for Datasets"? What sections does a datasheet include and what does each document?**

**Q: Compare the Datasheets for Datasets, Google Data Cards Playbook, and Google Model Cards. What does each document and who is it for?**

**Q: Explain the difference between Bias and Variance in ML models. What are the ethical implications of each?**

---

## ⭐ Must-Know for Exam

- **7 sources of harm** — know all 7 names + which stage + one example each
- **3 in Data Generation:** Historical / Representation / Measurement
- **2 in Model Building:** Aggregation / Learning
- **2 in Evaluation/Deployment:** Evaluation / Deployment
- **Historical Bias ≠ Representation Bias:** Historical = past prejudice in content. Representation = wrong population sampled.
- **Deployment Bias ≠ Evaluation Bias:** Deployment = used wrong way. Evaluation = benchmarked on wrong population.
- **Datasheets paper:** Gebru et al. 2021, Communications of the ACM
- **6 Datasheet sections:** Motivation, Composition, Collection, Recommended Uses, Distribution, Maintenance
- **Data Cards 4 steps:** Ask → Inspect → Answer → Audit
- **Model Card sections:** Training, Red Teaming, Risks, Safety Policies, Ethics Review
- **Bias → Underfitting | Variance → Overfitting**
