# Multi-Omics Longitudinal Study of Chronic Autoimmune Disease Progression


## 📌 Project Overview
Chronic autoimmune diseases are highly heterogeneous, characterized by unpredictable periods of clinical remission alternating with acute inflammatory flares. While some patients maintain long-term stability under standard care, others experience recurrent relapses and progressive organ involvement requiring hospitalization or therapeutic escalation.

This project investigates the complex interplay shaping disease progression using a simulated multi-omics longitudinal cohort dataset collected over a **10-year follow-up period across three tertiary referral centers (A, B, and C)**. The analysis incorporates:
* **Clinical & Demographic Profiles** (Age, sex, baseline inflammation, prior relapse history).
* **Treatment Interventions** (Standard vs. biologic therapies, corticosteroid usage).
* **Genetic Variability** (Genotype dosage matrices across multi-locus susceptibility regions).
* **Longitudinal Proteomics** (Repeated cytokine biomarker measurements over time).

---

## 🎯 Study Objectives
The analytical pipeline is designed to address four core biological and statistical challenges:

1. **Disease Activity Progression:** Identify key clinical, environmental, and baseline biological determinants driving the transition from remission to active inflammatory flare and secondary organ complications.
2. **Time-to-Event Analysis:** Investigate survival dynamics and model the risk covariates associated with severe clinical clinical outcomes (hospitalization and treatment failure).
3. **Molecular Association Analysis:** Evaluate how specific genetic susceptibility loci (SNPs) and dynamic longitudinal cytokine patterns act as drivers or indicators of disease evolution.
4. **Integrated Risk Prediction:** Build and validate predictive machine learning/statistical models that blend static clinical indicators, genomic configurations, and dynamic molecular measurements for personalized patient stratification.

Specifically, the core points investigated: 
- Defining a binary outcome corresponding to the occurrence of a severe disease activity within 5 years (hospitalization or treatment failure) with the exclusion of the patients who are censored before 5 years;
- Studying the effect of treatment strategy on progression to severe clinical outcome. The endpoint of interest is time_to_severe_outcome, where the event is defined as the occurrence of hospitalization or treatment failure.
