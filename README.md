# CMU MSML (Advanced Study) – Research Prep & Portfolio

> **Goal:** Deepen theory (probabilistic graphical models, RL, ML theory) and extend it into **scalable, reproducible, and trustworthy** ML systems. This repo tracks coursework prep, research scaffolding, and reproducible code toward CMU’s **MS in Machine Learning – Advanced Study** and a pathway into research with 1) **ICSD** or 2) **Safe AI Lab**.

---

# [Program Overview](https://ml.cmu.edu/academics/primary-ms-machine-learning-advanced-study-masters)

## 🔗 Program & Lab Alignment

- **CMU MS in Machine Learning – Advanced Study (MSML-AS):**  
  https://ml.cmu.edu/academics/primary-ms-machine-learning-advanced-study-masters

- **ML Department (SCS) – Program Overview & Curriculum:**  
  https://www.ml.cmu.edu/  
  https://ml.cmu.edu/academics/machine-learning-masters-curriculum

- **Master’s Student Handbook (latest posted):**  
  https://ml.cmu.edu/current-students/index

- **Institute for Complex Social Dynamics (ICSD):**  
  https://www.cmu.edu/dietrich/social-dynamics/

- **Safe AI Lab @ CMU:**  
  https://safeai-lab.github.io/  
  https://www.ri.cmu.edu/robotics-groups/cmu-safe-ai-lab/

- **Faculty of Interest**  
  - **Nihar B. Shah (MLD/CSD):** https://www.cs.cmu.edu/~nihars/  
  - **Atoosa Kasirzadeh (Philosophy; courtesy in S3D):** https://www.cmu.edu/dietrich/philosophy/people/faculty/atoosa-kasirzadeh.html

---

## 🧭 Research Tracks (What this repo advances)

1. **Trustworthy Forecasting & Infrastructure Readiness**  
   - Stabilizing time-series models (e.g., SARIMA-aware LSTMs), seed-sensitivity studies, and seasonality/heteroskedasticity controls for energy + compute demand planning.  
   - Reproducibility guarantees (multi-seed protocols, deterministic configs, artifact logging).

2. **Evaluation Science & Auditing (ICSD-aligned)**  
   - Methods for robust evaluation, peer-review modeling/assignment, and bias auditing; bridging formal theory with applied pipelines and data-centric checks.

3. **Safe RL & Agents (Safe AI Lab-aligned)**  
   - Safety in control/decision-making under uncertainty; sim-to-real considerations; verification hooks in RL pipelines.

---

## 🗂 Repository Structure (to be updated - just an example). 

.
├── 00_admin/
│ ├── sop/ # Statements of purpose & notes
│ ├── advisor-notes/ # Running notes for faculty fit (Shah, Kasirzadeh, others)
│ └── checklists/ # Reproducibility, ethics, and release checklists
├── 10_theory/
│ ├── pgm/ # Graphical models: notes, derivations, tiny experiments
│ ├── rl/ # RL fundamentals + safe RL reading summaries
│ └── ml_theory/ # Generalization, stability, convex analysis notes
├── 20_projects/
│ ├── energy-forecasting/ # SARIMA-aware LSTM with seed-stability analysis
│ │ ├── data/ # (gitignored) raw/processed
│ │ ├── notebooks/ # EDA, modeling, seed-stability plots
│ │ ├── src/ # package-like code
│ │ └── reports/ # writeups & figures
│ └── llm-auditing/ # ICSD-inspired evals & audit tooling
│ ├── datasets/ # pointers + cards (licenses, provenance)
│ ├── notebooks/
│ ├── src/
│ └── reports/
├── 30_eval_tooling/
│ ├── metrics/ # eval metrics, calibration, uncertainty, robustness
│ ├── reproducibility/ # seeds, env pinning, run manifests (JSON/YAML)
│ └── viz/ # standardized plots (R², reliability, CIs)
├── 40_course-prep/
│ ├── probability/
│ ├── convex-optimization/
│ ├── deep-rl/
│ ├── pgm/
│ └── ml-graphs/
├── 90_bibliography/
│ ├── papers.bib # master BibTeX
│ └── reading-notes/ # structured paper notes (1-pagers)
---

🔬 Research Milestones (proposed)

**Spring 2026**
- Apply Intelligent Systems and Robotics and Probability/Simulation to a relevant project, build upon capstone and deepen knowledge, await for feedback. 
- Will lead into 

**Summer 2026, if accepted**
Reach back out to Dr. Shah, show progress, and see next steps. Try to align early and begin research. 
  - [Alignment to his research group] # insert here

**Semester 1**

- [Intro to Machine Learning](https://www.cs.cmu.edu/~hchai2/courses/10701/)
   -[Insert branch on getting ahead on research]
- [Statistics](https://www.stat.cmu.edu/~siva/teaching/700/)
   -[Insert branch]
- [Convex Optimization](https://www.stat.cmu.edu/~siva/teaching/725/)
   -[Insert branch]

## Research

- Begin on work purposed in [Alignment to his research group].
- Rebuild forecasting pipeline with stricter determinism; publish a reproducibility report (R² distributions vs seeds; calibration).
- Draft an evaluation taxonomy for LLM auditing (annotation robustness; agreement modeling; reviewer assignment framing).


**Semester 2**
 - [Probabilistic Graphical Models](https://andrejristeski.github.io/10708S25/)
   -[Insert branch]
 - [Machine Learning in practice](https://www.cs.cmu.edu/~smithv/10718/)
   -[Insert branch]
 - [Machine Learning with graphs](https://www.cs.cmu.edu/~yiming/Syllabus.pdf)
   -[Insert branch]

## Continue into research, build thesis foundations. 

**Summer**
# TBD based off lessons learned from previious semester, probably research. 
Safe RL prototype in a simulator (risk constraints, verification hooks).
Submit a short workshop paper (reproducibility or evaluation).


**Electives to focus on**
- To be updated.
- Deep Reinforcement Learning, Graduate Artificial Intelligence. 
🧑‍🏫 **Advising Fit & Notes (living)**
With Prof. Nihar Shah: evaluation science, peer-review modeling, theory with deployments.

With Prof. Atoosa Kasirzadeh: AI governance/ethics methods integrated with technical pipelines and evaluation.

With Safe AI Lab: verification-minded RL/agents and safety for high-stakes systems.

-Problem Statement: Think high level how to tie all three together. It may take some time. 

Maintain running notes, alignment, and annotations.

📚 **Literature Tracker**
To be updated

🔁 **Related Prior Work (external)**
MSDS Alignment Project (baseline + direction):
https://github.com/EthanNorton/MSDS-alignment/tree/ai-alignment-problem
