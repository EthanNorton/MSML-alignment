# 6-Month Learning Plan (Prep for CMU MSML-AS and Research Launch)

**Objective:**  
Over the next 6 months (≈ 26 weeks), build strong foundations in:
- Mathematical theory (probabilistic models, convex optimization, reinforcement learning)  
- Systems & coding fundamentals (CS algorithms, C/C++, memory + networks)  
- Research literacy & domain alignment (evaluation science, reproducibility, ML for infrastructure)  
- Project incubation (mini-projects aligned with your themes: annotation bias, seed-stability, energy infrastructure)  

**Timeline Overview:**  
| Month | Key Focus Areas | Milestones |
|-------|-----------------|------------|
| Month 1 | Math & ML Core Foundations | Complete 2 YouTube playlists + chapters of Linear Algebra & Probability |
| Month 2 | Systems & Algorithms | LeetCode fundamentals + review of memory/CS basics + project skeleton 1 |
| Month 3 | Convex Optimization & PGMs | Read/skim Boyd chapters + Koller/Friedman chapters + project 1 draft |
| Month 4 | Reinforcement Learning & Infrastructure ML | Study Sutton/Barto + RL deployment case study + project 2 dev |
| Month 5 | Research Literacy & Domain Dive | Deep dive into Dr. Shah’s work + evaluation science papers + project 1 & 2 polish |
| Month 6 | Integration & Presentation | Finalise mini-projects, prepare GitHub portfolio, draft research agenda for CMU labs |

**Weekly Commitment:**  
~10 hours/week (≈ 60 minutes/day) broken as:  
- 3 hrs math/theory  
- 2 hrs systems/algorithms  
- 2 hrs research reading  
- 3 hrs project/dev work  

**Mini-Project Themes:**  
1. *Seed-Stability Module*: Re-run neural forecasting (energy) across multiple seeds, generate reproducibility report.  
2. *Annotation Bias Audit*: Build a simulation of human review/LLM annotation, model reviewer assignment biases, tie to Dr. Shah’s reviewer-assignment work.  
3. *(Stretch)* *Edge RL Sandbox*: Develop a small RL environment (grid/energy or IoT), simulate safe-agent constraints.

**Deliverables by End of 6-Months:**  
- GitHub folder `/prep/6-month/projects/` with two mini-projects, documentation, Jupyter notebooks or C++ modules.  
- A markdown summary: `prep/6-month/summary.md` containing: research agenda, next-steps for CMU MSML labs, faculty alignment (Shah/Cohen).  
- Updated CV/Resume reflecting completed modules and project outcomes.  
- Reflective blog post or LinkedIn update summarising “6-Month Prep: My Path to CMU MSML.”

---

## 📅 Detailed Weekly Breakdown  

### **Month 1 (Weeks 1-4):**  
- Week 1: StatQuest playlist (Regression, Gradient Descent), 3Blue1Brown Linear Algebra parts 1-3.  
- Week 2: Continue Linear Algebra (eigenvalues, SVD), begin Probability introduction (events, Bayes).  
- Week 3: YouTube Systems Intro (Ben Eater, memory/CPU basics), start LeetCode “Arrays + Two Pointers” (2 problems).  
- Week 4: Math review: vector spaces & transformations, project skeleton – fork your forecasting repo and document seed-stability plan.

### **Month 2 (Weeks 5-8):**  
- Week 5: LeetCode “Hash Tables + BFS/DFS” (2 problems each), read chapters on Algorithms from Sedgewick (selected).  
- Week 6: Systems deep dive: Memory vs Cache, C++ tutorial, build simple simulator of energy-sensor pipeline.  
- Week 7: Project 1: implement forecasting baseline with 10 seed runs, log results.  
- Week 8: Math: review Optimisation basics (Gradients, Hessians), start Boyd Chapter 1 & 2.

### **Month 3 (Weeks 9-12):**  
- Week 9: Convex Optimization chapters: Convex sets & functions. LeetCode “Graphs” (2 problems).  
- Week 10: Boyd chapters: Duality & KKT. PGMs intro (Koller & Friedman chapters 1-2).  
- Week 11: Project 1: expand forecasting model to include seed-stability report, visualise R² distributions.  
- Week 12: Systems + CS: review networking fundamentals (CS144 style), build simple client-server simulation.

### **Month 4 (Weeks 13-16):**  
- Week 13: Reinforcement Learning theory: Sutton & Barto chapters 1-3.  
- Week 14: RL environments: OpenAI Gym, small grid world simulation. Project 2 skeleton.  
- Week 15: Infrastructure ML: read case studies on energy grid RL/actions, begin project 2 implementation.  
- Week 16: Math review: stochastic processes overview (Markov chains), complete LeetCode “Dynamic Programming” (2–3 problems).

### **Month 5 (Weeks 17-20):**  
- Week 17: Research literacy: read Dr. Shah’s papers (reviewer assignment, information asymmetries), take notes.  
- Week 18: Evaluation science: read “The More You Automate, The Less You See” & “Benchmarking in NLP” → draft blog summary.  
- Week 19: Project 2: run RL simulation, incorporate safety constraints, log results, begin write-up.  
- Week 20: Systems wrap-up: containerisation, reproducible pipelines, Docker + MLflow for your forecasting project.

### **Month 6 (Weeks 21-26):**  
- Weeks 21-22: Finalise Project 1 & Project 2: clean notebooks, write readme, commit code.  
- Week 23: Prepare portfolio: update GitHub README, link your 6-month prep path, link projects, update CV.  
- Week 24: Draft research agenda: “Next steps for CMU MSML” – embed your courses, your lab alignment (Shah/Cohen), your 1-year plan.  
- Week 25: Mock interviews: prepare 5 slides summarising each project, rehearse your narrative.  
- Week 26: Publish blog/LinkedIn update: “6-Month Prep for CMU MSML: My Path & Outcomes.” Celebrate milestone, network with Dr. Shah again with progress update.

---

## ✅ Branch Setup Instructions  
1. Create branch: `git checkout -b prep/6-month-plan`  
2. Add folder: `mkdir -p prep/6-month`  
3. Add file: `prep/6-month/README.md` with content above  
4. Commit and push:  
   ```bash
   git add prep/6-month/README.md  
   git commit -m "Add 6-month learning plan aligned with CMU MSML-AS"  
   git push origin prep/6-month-plan  
