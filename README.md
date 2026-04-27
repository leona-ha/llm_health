# Health-seeking with Large Language Models: Prevalence, Predictors, and Adverse Effects

This repository contains code and materials for the study:

**Health-seeking with Large Language Models: Prevalence, Predictors, and Adverse Effects**

Julian Herpertz<sup>1,*</sup>, Leona Hammelrath<sup>2,*</sup>, John Torous<sup>3</sup>, Gabriel Bonnin<sup>4</sup>, Phileas Heim<sup>2</sup>, Christine Knaevelsrud<sup>2</sup>, DigiHero Coauthors, Rafael Mikolajczyk<sup>5,†</sup>, André Kerber<sup>2,†</sup>, Nils Opel<sup>1,†</sup>

<sup>1</sup> Charité – Universitätsmedizin Berlin, Department of Psychiatry and Psychotherapy, Campus Benjamin Franklin, Berlin, Germany  
<sup>2</sup> Division of Clinical-Psychological Intervention, Department of Education and Psychology, Freie Universität Berlin, Berlin, Germany  
<sup>3</sup> Department of Psychiatry, Beth Israel Deaconess Medical Center, Boston, MA, USA  
<sup>4</sup> Mental Health Research and Treatment Center, Faculty of Psychology, Ruhr University Bochum, Bochum, Germany  
<sup>5</sup> Institute for Medical Epidemiology, Biometrics and Informatics, Interdisciplinary Centre for Health Sciences, Medical Faculty of the Martin Luther University Halle-Wittenberg, Universitätsmedizin Halle, Halle (Saale), Germany  

\* Julian Herpertz and Leona Hammelrath contributed equally to the present work and should both be considered first authors.  
† Nils Opel, André Kerber, and Rafael Mikolajczyk contributed equally to the present work and should all be considered senior authors.

---

## Study context

Large Language Models (LLMs), such as ChatGPT, Gemini, Claude, Grok, Perplexity, and related systems, have rapidly become part of everyday information-seeking behavior. Increasingly, these systems are also used for health and mental health purposes, including symptom checking, interpretation of medical information, emotional support, and preparation for medical or psychotherapeutic care.

However, the public health implications of LLM-based health-seeking remain insufficiently understood. In particular, little is known about which population groups use LLMs for health-related purposes, whether health-related use follows the same sociodemographic pattern as general LLM adoption, and whether users report adverse effects such as perceived dependency or reduced decision-making autonomy.

The present study addresses this gap by investigating the prevalence, predictors, and adverse effects of LLM-based health-seeking behavior using a dual-cohort design:

- **DigiHero general population sample:** N = 28,910  
- **PSYMPACT clinical sample:** N = 2,313  

The analyses examine general LLM use, health-related LLM use, and mental health-related LLM use. In addition, adverse effects associated with health-related LLM use are compared with adverse effects reported in an external face-to-face psychotherapy reference sample.

---

## Study aims

The study addressed the following research questions:

1. **Prevalence**  
   How common is general LLM use, health-related LLM use, and mental health-related LLM use in a general population sample and a clinical sample?

2. **Predictors**  
   Which sociodemographic and clinical characteristics are associated with general, health-related, and mental health-related LLM use?

3. **Cohort differences**  
   Do patterns of LLM use differ between a general population cohort and a clinical cohort?

4. **Adverse effects**  
   Are health-related LLM users more likely to report adverse effects, such as dependency or reduced decision-making autonomy?

5. **Risk groups**  
   Are adverse effects concentrated in specific sociodemographic or clinical subgroups?

---

## Summary of main findings

The analyses showed that general LLM adoption clustered among socioeconomically advantaged participants. In contrast, health-related LLM use was more prevalent among participants with disadvantaged sociodemographic characteristics and greater clinical vulnerability across both cohorts.

Adverse effects associated with health-related LLM use exceeded those reported in an external face-to-face psychotherapy sample, particularly for:

- **Dependency:** OR = 2.82, 95% CI [2.34, 3.40]  
- **Reduced decision-making autonomy:** OR = 5.25, 95% CI [3.99, 6.90]  

Notably, although men used LLMs less often for mental health purposes, they exhibited significantly higher rates of associated adverse effects.

Together, these findings identify populations at risk, inform public health initiatives, and underscore the need for regulatory frameworks and practitioner education regarding the unsupervised use of generative AI in personal healthcare.

---

## Repository structure

```text
.
├── code/
│   ├── DigiHero_Descriptives_&_LLM_Use.ipynb
│   ├── DigiHero_Regression_Sensitivity_Mediation.ipynb
│   ├── DigiHero_Stratified_Analyses.ipynb
│   ├── Psympact_Data_Preprocessing_And_Regression.ipynb
│   └── Sample_Comparison.ipynb
├── materials/
│   └── study materials, questionnaires, codebooks, or supplementary documentation
└── README.md
```

---

## Code and notebook descriptions

The `code/` folder contains the analysis notebooks used for the manuscript. Each notebook corresponds to a specific part of the analytic workflow.



## Data availability

Individual-level data are not included in this repository because they contain sensitive health-related information and are subject to data protection regulations.

The code is provided to document the analytic workflow and support reproducibility for researchers with authorized access to the underlying data.

Researchers interested in data access should contact the corresponding authors and the responsible study teams. 

---


## Reproducibility notes

Because the raw study data are not publicly distributed, the repository primarily supports analytic transparency rather than full public reproduction.

The notebooks document:

- Variable recoding decisions
- Inclusion and exclusion criteria
- Construction of LLM-use outcomes
- Construction of clinical and sociodemographic predictors
- Statistical model specifications
- Sensitivity analyses
- Sample comparisons
- Adverse effect comparisons

Researchers with authorized access to the data should be able to reproduce the reported analyses after adapting local file paths.

---

## Citation

If you use this repository, please cite the corresponding manuscript:

> Herpertz, J., Hammelrath, L., Torous, J., Bonnin, G., Heim, P., Knaevelsrud, C., DigiHero Coauthors, Mikolajczyk, R., Kerber, A., & Opel, N.  
> **Health-seeking with Large Language Models: Prevalence, Predictors, and Adverse Effects.**

A full citation, including journal, volume, pages, DOI, or preprint link, will be added upon publication.

---



## Contact

For questions about the code, analyses, or data access, please contact the corresponding authors of the manuscript.

---

## License

Please see the repository license for terms of use.

If no license is provided, all rights remain reserved by the authors.