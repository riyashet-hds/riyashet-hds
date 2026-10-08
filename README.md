# Hi, I'm Riya 👋

I'm a data scientist in Dubai with an **MSc in Health Data Science (Distinction)** from the University of
Birmingham Dubai. I build machine-learning and AI systems with Python and SQL, then test whether they can be
trusted before anyone relies on them: how they fail, when their confidence misleads, and what decision they
should actually support.

---

## Publication

**Shet R.D., Zhang L. (2026).** *Reliability analysis for BraTS-GoAT segmentation: a controlled robustness
study of deep-ensemble uncertainty.* MICCAI 2026 Satellite Events (BraTS-GoAT workshop), Springer LNCS 17254.
[Paper](https://papers.miccai.org/miccai-2026-sat/BraTS_GoAT_015.html) · [Code](https://github.com/riyashet-hds/brats-goat-reliability)

My MSc dissertation, as a first-author paper. Under simulated scanner and protocol shift, a single model's
confidence stayed flat while its accuracy fell. Disagreement across a deep ensemble caught the shift that
the model's own confidence missed.

---

## What I Do

- **Build predictive models and AI tools**: Python, SQL, PyTorch and scikit-learn, from data extraction to a
  deployed product
- **Evaluate and stress-test models**: performance under new data, subgroup failures, uncertainty, and
  results reported honestly even when they disappoint
- **Work with LLMs and AI agents**: LLM-based applications with structured outputs and fallbacks, and agentic
  workflows that review and check work
- **Turn analysis into decisions**: risk scoring, simulation and cost-effectiveness, explained clearly to
  people who are not technical
- **Make work reproducible**: Git, Docker, Linux HPC, fixed seeds, and pipelines someone else can rerun

---

## Selected Projects

### [Diabetic Retinopathy Algorithmic Audit](https://github.com/riyashet-hds/dr-algorithmic-audit)

A safety audit of a diabetic retinopathy classifier using the Medical Algorithmic Audit framework.

**Methods:** algorithmic auditing, subgroup testing, adversarial robustness, FMEA risk scoring
**Impact:** A 0.88 headline score hid only 48.6% sensitivity on the most urgent grade; failure modes ranked the
way a model-risk review would
**Tools:** Python, PyTorch

### [Health-Economic Simulation of AI Triage](https://github.com/riyashet-hds/health-economic-simulation-ai-triage)

A Monte Carlo framework that estimates whether an AI triage tool is worth funding, running synthetic cohorts
through two care pathways.

**Methods:** cohort of 10,050 admissions extracted from MIMIC-IV with SQL (BigQuery), Monte Carlo over 10,000
runs, Bayesian updating, ICER and QALYs, sensitivity analysis
**Impact:** Turns an accuracy question into a cost-effectiveness decision under uncertainty
**Tools:** Python, SQL (BigQuery), NumPy, SciPy

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

---

## More Projects

- **[Retinal Fundus Classification](https://github.com/riyashet-hds/retinal-fundus-classification):**
  transfer learning that compares CNNs and Vision Transformers for diabetic retinopathy grading, with Grad-CAM.
  *(Python, PyTorch)*
- **[Healthcare Financial-Toxicity Risk Prediction](https://github.com/riyashet-hds/healthcare-ftr-prediction):**
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

Data science, AI engineering and AI analyst roles where results have to be trusted: healthcare and health
insurance, banking and fintech, and government and public-sector AI. I'm especially interested in teams that
are moving AI from pilots into real use, and that care whether it works.

---

## Technical Skills

**Languages and data:** Python (pandas, NumPy, scikit-learn, PyTorch, SHAP) • SQL (Google BigQuery) • R
(tidyverse, mixOmics)

**Machine learning:** classification and risk models • deep learning and computer vision • ensembles and
uncertainty • model evaluation, auditing and robustness testing • explainability (SHAP)

**AI and LLMs:** LLM application development (Gemini, DeepSeek APIs) with structured outputs and fallback
chains • agentic workflows with Claude Code • prompt design

**Engineering:** Git and GitHub • Docker • Linux HPC (SLURM) • Flask REST APIs • CI smoke tests • Vercel

**Quantitative methods:** statistics • Monte Carlo simulation • Bayesian updating • cost-effectiveness and
decision analysis • sensitivity analysis

**Domains:** healthcare data (EHR, medical imaging, claims, multi-omics) • data governance (UAE PDPL, ADHICS)

---

## Based in Dubai

Based in **Dubai, UAE**, and open to roles across the UAE. I expect to hold a UAE Golden Visa from
December 2026.

---

## Let's Connect

I'm always happy to discuss machine learning, responsible AI, and work that moves from analysis to real
decisions.

**GitHub:** [@riyashet-hds](https://github.com/riyashet-hds)
**LinkedIn:** [linkedin.com/in/riyashet](https://www.linkedin.com/in/riyashet)
**Email:** riyashet.psy@gmail.com

**Updated:** October 2026
