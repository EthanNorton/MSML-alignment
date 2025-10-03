# Is Correctness All You Need?
*Ethan Norton*  
Northwestern University — MS in Data Science  
Revision: October 3rd, 2025  

## Overview
This project explores evaluation frameworks for large language models (LLMs), using the **HelpSteer dataset** (~37k annotated responses scored on correctness, coherence, helpfulness, verbosity, and complexity).  

The central question: **Is correctness sufficient as the primary signal of LLM quality, or do other dimensions meaningfully contribute?**

Early findings:
- **Correctness** is the strongest predictor of overall helpfulness, but its distribution skews high (70% of responses labeled as “3” or “4”), limiting discriminative power.  
- **Verbosity bias** inflates helpfulness scores (longer responses judged more helpful even when factually weak).  
- **Hybrid models** (engineered + annotated features) outperform either approach alone.  

---

## Research Alignment
This work aligns with **Dr. Nihar Shah’s research** on:
- **Evaluation correctness** and reproducibility in scientific systems.  
- **Reviewer expertise** as a hidden driver of annotation reliability.  
- **Hybrid frameworks** where automation provides baseline scoring, but humans focus on edge cases requiring domain knowledge.  

Like Shah’s perspective on peer review, this project suggests that **annotation expertise is not optional**—and LLM evaluations require grounding in reproducible, expertise-sensitive protocols.

---

## Contributions
1. **Empirical analysis** of HelpSteer annotations.  
2. **Hybrid modeling framework** combining engineered verbosity/complexity features with human labels.  
3. **Bias audit** of verbosity and coherence effects on perceived helpfulness.  
4. **Methodological link** between LLM evaluation and Shah’s peer-review expertise model.  

---

## Future Work
- **Extend** to multimodal/multilingual LLM evaluations.  
- **Semi-automated pipelines**: LLMs propose scores, humans validate high-variance cases.  
- **Bias modeling**: treat verbosity and other social cues as evolving norms within annotation communities.  
- **Cross-institutional collaborations** with ICSD and peer review projects to create reproducible benchmarks.  
- **Policy implications**: connect findings to AI audit standards (e.g., EU AI Act, Algorithmic Accountability Act).  
