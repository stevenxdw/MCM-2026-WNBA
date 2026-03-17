# 🏀 MCM/ICM 2026 — Managing Sports for Success

**Team #2603847 | Problem D**

A mathematical modeling paper submitted to the 2026 MCM/ICM competition, addressing the strategic trade-off between competitive performance and financial sustainability in WNBA franchise management.

---

## 📄 Abstract

We develop a **Discounted Dynamic Programming (DP)** framework to optimize a franchise's long-term "total utility" — balancing on-court wins and financial profitability over a multi-season horizon.

Key methods:
- **Age-Adjusted Performance Index** to evaluate player lifecycle value
- **Canonical Correlation Analysis (CCA)** to find the optimal weighting between competitive and financial objectives (α = 0.26)
- **Logistic S-curve** modeling of media revenue dynamics
- **Dynamic ticket pricing** model using game appeal and demand elasticity

---

## 🔑 Key Findings

- The optimal strategy allocates **26% weight to wins** and **74% to financial objectives**
- "Win-now" superstar lineups peak around 2021–22, then **collapse after 2024–25**
- Young, salary-disciplined rosters **steadily surpass** elite rosters in the long run
- League expansion from 12 → 20 teams causes a **45% utility drop**, recoverable by ~30% with proactive roster adjustment

---

## 🛠️ Methods & Tools

- Dynamic Programming, CCA, Lagrangian Optimization
- Python (simulation, Gurobi for pricing optimization)
- Data: NBA 2022–23 player stats (Kaggle) as WNBA proxy

---

## 📁 Files

| File | Description |
|------|-------------|
| `MCM_2603847.pdf` | Full competition paper (25 pages) |

---

*2026 MCM/ICM Competition — Problem D*
