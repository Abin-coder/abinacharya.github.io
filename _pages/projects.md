---
title: "Projects"
permalink: /projects/
---

<!-- ============ EDIT / ADD PROJECTS BELOW ============
     Each project: a ### heading, an italic tech-stack line,
     and a bullet list. Add links like [Code](https://github.com/...) -->

### Explainable AI for Malware Prediction

*Python · PyTorch · TabTransformer · CNN · SHAP · LIME · BoolXAI*

- Engineered a malware detection pipeline with a CNN baseline and a TabTransformer on 10K+ samples from the Microsoft Malware Kaggle dataset.
- Integrated BoolXAI for rule-based interpretability, producing human-readable Boolean explanations without sacrificing accuracy.
- Applied SHAP and LIME to analyze per-feature contributions and identify the top predictive features.

### Adaptive RL Tutor for Algebra Education

*Python · Double DQN · OpenAI Gym · Streamlit*

- Built an RL-based intelligent tutoring system using Double DQN to adaptively select algebra problems based on real-time student mastery across 10 skill categories.
- Designed a custom RL environment with reward shaping and a state representation encoding student performance history, reaching 85%+ simulated mastery convergence.
- Developed a Streamlit demo for interactive tutoring sessions with LLM-generated hints.

### Virtual Try-On Using Neural Networks

*Python · PyTorch · GANs · U-Net · OpenCV*

- Developed a GAN-based virtual try-on system with a Geometric Matching Module and a U-Net try-on module using TPS cloth warping and pose estimation.
- Achieved 8% normalized MSE on a 2,000-image test set with sub-second inference time.

### Discussion Forum Web Application

*Python · Django · HTML/CSS · JavaScript · SQLite*

- Built a full-stack Q&A platform with authentication, posting, search, and trending-post algorithms serving 50+ concurrent test users.
- Implemented a content-based recommendation engine using cosine similarity, increasing average session engagement by 25% in user testing.

[Go to home](/)
