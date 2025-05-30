---
layout: project
title: About My Project
permalink: /about-my-project.html

subtitle: Reinforcement Learning for Personalized Treatment
project_title: "AI-Driven Comorbidity Management in Type 1 Diabetes Using Deep Q-Networks"

problem: |
  Many AI systems in healthcare rely on static models or rule-based logic that struggle to adapt to the evolving nature of real-world patient data. In complex chronic conditions like Type 1 Diabetes (T1D), where patients may also face comorbidities such as thyroid dysfunction or cardiovascular risk, treatment isn’t one-size-fits-all—it needs to learn and adapt.

  This project investigates how **Reinforcement Learning (RL)**, particularly **Deep Q-Networks (DQNs)**, can be applied to dynamically recommend personalized treatment strategies based on multi-condition patient profiles. The RL agent learns from ongoing health signals, allowing it to propose context-aware interventions that adjust as patient states evolve.

approach: |
  The technical foundation of this project lies in applying Deep Q-Learning to model healthcare decision-making as a **Markov Decision Process (MDP)**. The project pipeline includes:

  - Defining states from health data such as glucose levels, thyroid biomarkers, insulin usage
  - Encoding treatment actions like dose adjustments, dietary shifts, and intervention timing
  - Designing a reward function that balances glucose control, comorbidity impact, and long-term stability
  - Simulating environment dynamics to allow the agent to learn through experience replay and policy refinement
  - Implementing the DQN with exploration strategies (e.g., decaying epsilon-greedy), experience buffers, and safety constraints for clinical realism
  - Benchmarking the AI’s performance against standard guidelines and evaluating its decisions using interpretability tools (like SHAP)

  The system is built in Python using frameworks like PyTorch and integrated with data analysis libraries (Pandas, NumPy), with Jupyter/Colab used for experimentation.

outcome: |
  By the end of the program, this project will deliver:

  - A trained Deep Q-Network that adapts to patient health trajectories to optimize treatment decisions
  - A simulated testbed with realistic patient scenarios for model evaluation
  - A reproducible pipeline for applying reinforcement learning in multi-objective health contexts
  - An AI explainability summary showing how decisions align with clinical markers
  - A final report and team presentation outlining methodology, insights, and future expansion directions

final_report_url: https://bit.ly/submit-projectplan2025

grad_mentor:
  name: Ricky Gole
  linkedin: https://www.linkedin.com/in/ricky-gole/

faculty_mentor:
  name: Dr. Jamell Dacon
  linkedin: https://daconjam.github.io/
---
