# Hi, I'm Riya 👋

I'm a data scientist with an **MSc in Health Data Science (Distinction)** from the University of Birmingham Dubai. I build and evaluate
machine-learning systems for healthcare, on multimodal data that spans multi-omics, medical imaging, and
clinical records. My focus is what decides whether a model is actually used: whether it can be explained,
audited, and trusted. In healthcare that means designing for clinical sign-off and regulation from the start.

---

## Publication

**Shet R.D., Zhang L. (2026).** *Reliability analysis for BraTS-GoAT segmentation: a controlled robustness
study of deep-ensemble uncertainty.* MICCAI 2026 Satellite Events (BraTS-GoAT workshop), Springer LNCS 17254.
[Paper](https://papers.miccai.org/miccai-2026-sat/BraTS_GoAT_015.html) · [Code](https://github.com/riyashet-hds/brats-goat-reliability)

My MSc dissertation, as a first-author paper. Under simulated scanner and protocol shift, a single model's
confidence stayed flat while its accuracy fell. Disagreement across a deep ensemble caught the shift that
the model's own confidence missed.

---

## Focus Areas

I work end to end, from raw data to the evidence a model needs before anyone signs it off. My main areas:

- **Machine learning on multimodal data**, across multi-omics, medical imaging, and clinical or tabular records
- **Explainable and responsible AI**, including model auditing, model risk, and SHAP-based interpretation
- **Simulation, decision analysis, and risk modelling**, from Monte Carlo cost-effectiveness to risk scoring
- **Data governance and regulation**, from data-fabric design to privacy and compliance frameworks
- **Critical appraisal and communication**, including how data and figures can mislead

---

## Selected Projects

### [TracHeal: Post-Discharge Care-Continuity Tool](https://github.com/riyashet-hds/trachealhackathon)

A clinical decision-support MVP built and deployed in 48 hours at the Harvard HSIL Hackathon 2026. It reads
discharge notes and flags the follow-up gaps that put patients at risk after they go home.

**My role:** team lead; output schema, risk framework, integration of the team's components, deployment
**Tools:** Python (Flask), LLM APIs with a fallback chain, CI smoke tests, Vercel

### [Multimodal Integration for Colorectal Cancer](https://github.com/riyashet-hds/crc-multimodal-integration)

A reproducible multi-omics pipeline that fuses metabolomics, biochemistry, and diet to classify colorectal
cancer, comparing intermediate and late fusion.

**Methods:** DIABLO, regularised CCA, Random Forests, stacked logistic regression, SHAP, surrogate trees
**Impact:** Recovers coherent shared biology and verified markers, while showing fusion adds little to raw prediction
**Tools:** Python, R (mixOmics), scikit-learn

### [Diabetic Retinopathy Algorithmic Audit](https://github.com/riyashet-hds/dr-algorithmic-audit)

A safety audit of a diabetic retinopathy classifier using the Medical Algorithmic Audit framework.

**Methods:** algorithmic auditing, subgroup testing, adversarial robustness, FMEA risk scoring
**Impact:** Exposes failure modes that headline accuracy hides, scored the way a model-risk review would
**Tools:** Python

### [Health-Economic Simulation of AI Triage](https://github.com/riyashet-hds/health-economic-simulation-ai-triage)

A Monte Carlo framework that estimates whether an AI triage tool is worth funding, running synthetic cohorts
through two care pathways.

**Methods:** Monte Carlo, Bayesian updating, ICER and QALYs, one-way sensitivity analysis
**Impact:** Turns an accuracy question into a cost-effectiveness decision under uncertainty
**Tools:** Python, NumPy, SciPy

---

## More Projects

- **[Retinal Fundus Classification](https://github.com/riyashet-hds/retinal-fundus-classification):**
  transfer learning that compares CNNs and Vision Transformers for diabetic retinopathy grading, with Grad-CAM.
  *(Python, PyTorch)*
- **[Healthcare Revenue Cycle Risk Prediction](https://github.com/riyashet-hds/healthcare-ftr-prediction):**
  flags patient-level financial risk on synthetic EHR data so a billing team can intervene early, with about a
  9.4x lift over baseline. *(Python, scikit-learn)*

---

## Writing & Design

- **[Pharmacogenomics-Guided Medication Safety in CVD](https://github.com/riyashet-hds/pgx-cvd-medication-safety):**
  a health-data implementation plan for CYP2C19-guided antiplatelet prescribing in the UAE, using data-fabric
  design, CPIC and PharmCAT translation, and HL7 FHIR Genomics with CDS Hooks.
- **[Explainable AI in Cancer Research](https://github.com/riyashet-hds/explainable-ai-oncology-review):**
  a review of deep learning and explainable AI for multimodal data integration in oncology, across thirteen
  case studies.
- **[Bias in Genomic Data](https://github.com/riyashet-hds/genomic-data-bias):**
  a critical analysis of ancestry bias in GWAS and polygenic risk scores, using the 2024 All of Us controversy.

More on my [repositories](https://github.com/riyashet-hds?tab=repositories).

---

## What I'm Looking For

Roles where I take models from data to deployment in settings where the result has to be trusted: clinical,
regulated, or otherwise high-stakes. I'm most engaged by:

- Applied machine learning and responsible AI
- Model risk, auditing, and evaluation
- Simulation, decision analysis, and risk modelling

I'm drawn to teams that treat explainability and real-world deployment as part of the engineering, not an
afterthought.

---

## Technical Skills

**Programming Languages**
Python (pandas, scikit-learn, SHAP, PyTorch, matplotlib) • R (mixOmics, tidyverse, statistical modelling)

**Machine Learning**
Classification • Survival analysis • Model stacking and fusion • Explainability and model auditing (SHAP,
surrogate models) • Transfer learning

**Quantitative Methods**
Monte Carlo simulation • Bayesian updating • Cost-effectiveness and decision analysis • Risk scoring •
Sensitivity analysis

**Health and Multi-Omics Data**
Multi-omics integration (DIABLO, rCCA) • EHR and claims data • Pharmacogenomics • Medical imaging • Data
governance (PDPL, ADHICS, SaMD)

**Tools**
Git/GitHub • Jupyter • RStudio • Reproducible workflows • BioRender

---

## Regional Focus

Based in **Dubai, UAE**. Open to roles in the UAE or remote.

I'm especially drawn to challenges that matter in the Gulf and Middle East:

- Precision medicine and genomics in diverse populations
- Equitable, well-governed health-data systems
- Risk, cost, and decision modelling for health and public services

---

## Let's Connect

I'm always happy to discuss machine learning, responsible AI, and work that moves from analysis to real
decisions.

**GitHub:** [@riyashet-hds](https://github.com/riyashet-hds)
**LinkedIn:** [linkedin.com/in/riyashet](https://www.linkedin.com/in/riyashet)
**Email:** riyashet.psy@gmail.com

**Updated:** October 2026
