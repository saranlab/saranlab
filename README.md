<!-- Profile README for github.com/saranlab (repo name must be: saranlab/saranlab) -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Saran%20Rangsanthia&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Statistics%20%C2%B7%20Applied%20ML%20%C2%B7%20Experimentation&descSize=17&descAlignY=60" alt="Saran Rangsanthia" />

<a href="https://github.com/saranlab">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1400&color=58A6FF&center=true&vCenter=true&width=640&height=40&lines=Statistics+%40+Thammasat+University;I+ship+ML+as+working+products;Credit+risk+%7C+Churn+%7C+Experimentation;Looking+for+a+Data+Science+internship" alt="Typing banner" />
</a>

<br/>

<a href="https://www.linkedin.com/in/saran-rangsanthia-b09726372/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:saranforwork0@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://opti-sim.vercel.app"><img src="https://img.shields.io/badge/Live%20demo-OptiSim-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="OptiSim demo" /></a>

</div>

---

## About

```python
class Saran:
    studying    = "B.S. Statistics @ Thammasat University"
    building    = ["LoanLens", "LoyalScale", "OptiSim"]
    cares_about = ["explainable models", "uncertainty quantification", "decisions, not just metrics"]
    organizing  = "QuantTU, a quant-finance + AI student group"
    looking_for = "Data Science internship"
```

I like models that end in a decision: *who do we approve, who do we call, which variant do we ship.*
Every project below goes past the accuracy number to the business action it supports.

---

## Projects

<table>
<tr>
<td width="33%" valign="top">

### LoanLens
**Credit-risk scorecard**

WoE + logistic scorecard on 150K loans with reason codes for declined applicants, a profit-maximizing approval cutoff, and a FastAPI + Streamlit service.

**AUC 0.855** &nbsp;|&nbsp; **131 tests in CI**

`Python` `scikit-learn` `LightGBM` `FastAPI` `Streamlit`

[Repository](https://github.com/saranlab/loanLens)

</td>
<td width="33%" valign="top">

### LoyalScale
**Churn diagnostic suite**

Stacked XGBoost / LightGBM / CatBoost tuned with Optuna, split conformal prediction (MAPIE), Cox PH time-to-churn, k-NN case explanations, and fuzzy schema mapping for uploaded CSVs.

**Banking ROC-AUC 0.88** &nbsp;|&nbsp; **~95% coverage**

`Python` `MAPIE` `Optuna` `lifelines` `Streamlit`

[Repository](https://github.com/saranlab/LoyalScale)

</td>
<td width="33%" valign="top">

### OptiSim
**Experimentation platform**

Anytime-valid sequential testing, CUPED variance reduction, FDR-controlled guardrails, Thompson Sampling, and a MILP rollout optimizer. FastAPI backend, Next.js frontend.

**66 tests** &nbsp;|&nbsp; **[live demo](https://opti-sim.vercel.app)**

`Python` `SciPy` `FastAPI` `Next.js` `HiGHS`

[Repository](https://github.com/saranlab/OptiSim)

</td>
</tr>
</table>

<details>
<summary><b>How OptiSim turns a test result into a rollout decision</b></summary>

<br/>

```mermaid
flowchart LR
    A[User arrivals<br/>and session logs] --> B[Confidence sequences<br/>safe to peek]
    A --> C[CUPED<br/>variance reduction]
    B --> D[Guardrail metrics<br/>FDR control]
    C --> D
    D --> E[Conservative 95%<br/>lift floor]
    E --> F[MILP knapsack<br/>under budget and latency limits]
    F --> G[Decision memo]
```

Peeking at a dashboard inflates false positives; confidence sequences stay valid at every look.
The optimizer then picks which features to roll out under real resource constraints.

</details>

<details>
<summary><b>Also: TU Class Check</b></summary>

<br/>

A course-scheduling web app I initiated after seeing classmates cross-check class and exam times by hand: course search, automatic conflict detection, a 4-year plan, and calendar export.
Led the product and UX design. [Try it](https://tuclasscheck.chukite.me)

</details>

---

## Toolbox

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />

</div>

<br/>

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saranlab&layout=compact&hide_border=true&bg_color=0:0f2027&title_color=58A6FF&text_color=c9d1d9" alt="Top languages" />
</div>

---

## Elsewhere

- **Quant research:** WorldQuant Research Consultant (2025-26), WorldQuant Challenge Gold
- **Competitions:** Super AI Engineer Season 6, Thai document OCR with Typhoon-OCR
- **Teaching:** math tutoring (algebra, coordinate geometry); I like explaining things plainly

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=90&section=footer" alt="" />

</div>
