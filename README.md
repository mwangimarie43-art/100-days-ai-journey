# 100 Days of AI Safety, Alignment & Formal Verification

An intensive, structured 100-day roadmap bridging undergraduate mathematics and computational methods with frontier AI alignment, mechanistic interpretability, and formal verification.

---

## 🎯 Mission & Objectives

The goal of this 100-day sprint is to transition from core mathematical foundations into active technical AI safety and robustness research. By pairing university coursework in pure/applied mathematics with daily dedicated deep-work blocks, this journey culminates in a public capstone portfolio project and applications to elite alignment fellowships (ARENA, MATS, Anthropic Fellows) and postgraduate research positions.

### Key Milestones
1. **Solidify Deep Learning & Alignment Fundamentals:** Complete fast.ai core modules, PyTorch mastery, and the BlueDot AI Safety Fundamentals (AISF) curriculum.
2. **Master Interpretability & Verification Tools:** Hands-on circuit analysis with `TransformerLens` and neural network verification with `Marabou`, `alpha-beta-CROWN`, and `Lean 4`.
3. **Execute a Capstone Research Project:** Scope, build, evaluate, and write up a public portfolio-grade project with reproducible code.
4. **Target Fellowship & Academic Applications:** Submit competitive applications to ARENA, MATS, and relevant PhD/RA programs.

---

## 🧭 Roadmap Overview

---

## 📅 Detailed Phase Breakdown

### Phase 1: Foundations & Setup (Days 1–16 | Weeks 1–2)
*Focus: Environment initialization, mathematics refresher, and core PyTorch fluency.*
- **Mathematical Refresher:** Linear algebra (eigenvalues, vector spaces via 3Blue1Brown), multi-variable calculus, and probability distributions (MIT OCW 18.05).
- **Tooling & Environments:** Set up Python 3, VS Code, Git/GitHub, and PyTorch environment.
- **Deep Learning Kickoff:** PyTorch 60-Minute Blitz, tensors & autograd practice, fast.ai Lessons 1 & 2.
- **AI Safety Initiation:** Enroll in BlueDot AISF; cover Transformative AI trajectories.
- **Interactive Proving Setup:** Install Lean 4 and configure VS Code or pycharm

### Phase 2: Deep Learning & Alignment Core (Days 17–44 | Weeks 3–6)
*Focus: Neural network mechanics, transformer architectures, outer/inner alignment, and neural verification.*
- **Week 3 (Neural Nets & Outer Alignment):** fast.ai Lessons 3–4; BlueDot AISF outer alignment (specification gaming, reward misspecification, RLHF); Lean 4 Chapters 1–2 (types, terms, basic tactics).
- **Week 4 (Transformers & Inner Alignment):** Attention mechanisms (*The Illustrated Transformer*); Hugging Face Transformers pipeline and fine-tuning; inner alignment (mesa-optimization, goal misgeneralization); Lean 4 Chapters 3–4 (structured proofs).
- **Week 5 (Mechanistic Interpretability & Threat Models):** Neel Nanda's interpretability curriculum; attention pattern & circuit analysis with `TransformerLens`; BlueDot AISF threat models; Lean 4 inductive types.
- **Week 6 (Neural Network Verification & Safety):** Robustness verification via `Marabou` and `alpha-beta-CROWN` on MNIST models; *Mathematics in Lean*; define path weighting (Alignment/Mech-Interp vs. Formal Verification).

### Phase 3: Specialization Practice & Project Scoping (Days 45–58 | Weeks 7–8)
*Focus: Guided safety exercises and scoping a rigorous capstone project.*
- **Week 7 (Specialization Exercises):** Implement ARENA-style exercises (mechanistic interpretability / RL); BlueDot AISF technical safety approaches; formalize a proof in Lean 4.
- **Week 8 (Project Scoping):** Brainstorm 3 candidate project proposals (interpretability, neural verification, or hybrid); draft a 1-page specification with success metrics and repo skeleton.

### Phase 4: Capstone Portfolio Project (Days 59–86 | Weeks 9–12)
*Focus: 4-week dedicated sprint to build, test, polish, and publish an end-to-end research artifact.*
- **Week 9 (Core Build I):** Environment setup, baseline data/model pipeline, supporting formal definitions/proofs.
- **Week 10 (Core Build II):** Extended implementation, experimental runs, verification sweeps, debugging.
- **Week 11 (Results & Draft Write-up):** Finalize empirical results; draft methodology, results, and limitation sections.
- **Week 12 (Code Polish, Write-up & Release):** Clean, lint, and document repository; write a top-level technical report / blog post; open-source the project repository.

### Phase 5: Applications, Synthesis & Next Cycle (Days 87–100 | Weeks 13–14)
*Focus: Professional presentation, community outreach, and future roadmap planning.*
- **Week 13 (Application Sprint):** Update CV, portfolio site, and LinkedIn; prepare and submit applications for the next ARENA cohort, MATS, and Anthropic Fellows; shortlist university RA/PhD opportunities.
- **Week 14 (Buffer, Synthesis & Next Cycle):** Revisit challenging topics; compile all notes into an indexed knowledge base; conduct a retrospective on completed vs. skipped milestones; establish Q1 goals.

---

## 🛠 Tech Stack & Core Resources

| Domain | Key Tools & Libraries | Primary Learning Resources |
| :--- | :--- | :--- |
| **Deep Learning** | `PyTorch`, `HuggingFace`, `NumPy` | [fast.ai Practical Deep Learning](https://course.fast.ai), [PyTorch Tutorials](https://pytorch.org/tutorials) |
| **AI Safety & Alignment** | AISF Curriculum, ARENA Material | [BlueDot AI Safety Fundamentals](https://aisafetyfundamentals.com), [ARENA](https://www.arena.education) |
| **Interpretability** | `TransformerLens`, PyTorch | [Neel Nanda's Mech Interp](https://neelnanda.io), Jay Alammar's Illustrated Transformer |
| **Verification & Proving**| `Lean 4`, `Marabou`, `alpha-beta-CROWN` | [Theorem Proving in Lean 4](https://leanprover.github.io), [Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/) |

---

## ⏱ Time Management & Operating Rhythm

To maintain consistency alongside a full-time university STEM workload (Real Analysis, Group Theory, Fluid Mechanics, Numerical Analysis, Computer Graphics, Estimation Theory, ODEs):

* **Weekday Slots (1.0 – 2.0 hours):** Scheduled in morning or evening non-class windows (e.g., 18:00–20:00) focused on targeted reading, tutorial notebooks, and exercise sets.
* **Weekend Deep-Work Blocks (2.5 – 3.0 hours):** Dedicated sessions on Saturdays and Sundays for heavy implementation, multi-layer circuit debugging, and formal proof authoring.
* **Weekly Retrospectives (Sunday Evenings):** Review completion status, commit updated notes, and plan the upcoming week's focus areas.

---

## 📊 Progress Tracking

Daily progress is tracked via the accompanying `100-Day Tracker` spreadsheet:
- **`Done`**: Task completed and committed to repository.
- **`In Progress`**: Ongoing implementation or multi-day experiment.
- **`Skipped`**: Moved to buffer days in Week 14 to preserve overall velocity.
