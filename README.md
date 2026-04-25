# AcademiGuard — Research Project Website

**Adaptive & Explainable AI for Personalized Academic Interventions**  
Department of Information Technology · Sri Lanka Institute of Information Technology (SLIIT)  
CDAP Research Project 2025–2026

🌐 **Live Site:** https://sanka11.github.io/academiguard_web/

---

## About the Research

AcademiGuard is a proactive student monitoring platform that detects early signs of academic disengagement *before* grades reflect the problem — powered by:

| Component | Technology | Key Result |
|-----------|-----------|------------|
| Hybrid Ensemble Engine | RF + XGBoost + LightGBM (2:2:1) | **97.8% accuracy** |
| Temporal Anomaly Detector | GRU Autoencoder | 97th percentile threshold |
| Adaptive Intervention Agent | Q-Learning RL + LLaMA | 40.9% soft-nudge rate |
| Explainability Layer | SHAP TreeExplainer | Per-feature attribution |

---

## Repository Structure

```
academiguard_web/
├── index.html        ← Complete single-page website (all sections)
├── css/
│   └── style.css     ← Full design system & responsive styles
├── .gitignore
└── README.md
```

---

## Website Sections

- **Home** — Hero with animated stats panel and typewriter effect
- **Domain** — 6-tab research overview (Literature, Gap, Problem, Objectives, Methodology, Technologies)
- **Milestones** — 11-item timeline with dropdown navigation
- **Documents** — 9 project documents with submitted/pending status
- **Slides** — 4 presentation cards
- **About Us** — Supervisors and team member profiles
- **Contact** — Contact info and message form

---

## Research Team

| Name | Student ID | Role |
|------|-----------|------|
| Ravisanka U.V.P | IT22354792 | Team Leader |
| Perera I.A.T.D | IT22902702 | Team Member |
| Disanayaka S.T | IT22370228 | Team Member |
| Nimanji D.L.K | IT22365750 | Team Member |

**Supervisor:** Sanjeevi Chandrasiri — sanji.c@sliit.lk  
**Co-Supervisor:** Ishara Weerathunga — ishara.w@sliit.lk

---

## Deploying to GitHub Pages

1. Go to the repository → **Settings** → **Pages**
2. Under *Source*, select **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)**
4. Click **Save** — site goes live in ~2 minutes

---

*Built with HTML · CSS · JavaScript — no frameworks, no build step*
