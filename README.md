# Project 1 — Final Portfolio Submission

## Executive Memo

### Bottom Line Up Front (BLUF)
This project replicates Card and Krueger’s (1994) classic study of the New Jersey minimum wage increase and its effect on fast-food employment. The core finding is that the increase in New Jersey’s minimum wage did not reduce employment relative to neighboring Pennsylvania, and my extension suggests that treatment effects may vary across restaurant subgroups.

### The Mechanism
The project uses a Difference-in-Differences (DiD) design. In simple terms, this method compares how employment changed over time in New Jersey, where the minimum wage increased, to how employment changed over the same period in Pennsylvania, where it did not. The intuition is similar to a natural experiment: instead of randomly assigning restaurants to different wage policies, we use a real policy change and a nearby comparison group to estimate the causal effect.

### Visual Evidence
The main visual in this project is the coefficient plot / treatment effect comparison figure produced in the final extension notebook. The figure shows the estimated effect of the New Jersey policy change on employment and highlights how the magnitude of the effect differs across subgroups in the heterogeneity analysis. The chart is designed to make the core empirical conclusion easy to understand: the baseline employment effect is not negative, and subgroup results provide additional nuance rather than overturning the original conclusion.

> **Figure Caption:** Difference-in-Differences estimates of the New Jersey minimum wage increase on fast-food employment, including baseline and heterogeneous treatment effect results.

### Business / Policy Implications
The policy implication is that moderate minimum wage increases do not automatically reduce employment in low-wage service sectors. For policymakers, this suggests that labor standards can be raised without assuming a mechanical tradeoff with jobs. For business leaders and analysts, the results imply that adjustment may occur through channels other than immediate employment cuts, such as prices, productivity, or staffing composition. Future research should continue testing when and for whom these effects differ.

### Peer Audit Integration
This final portfolio incorporates peer-audit feedback by improving notebook comments and making visualization titles and captions more descriptive for non-technical readers.

---

## Repository Structure

- `note book/01_Data_Cleaning.ipynb` — Cleans and structures the raw Card and Krueger data
- `note book/02_Replication_Analysis.ipynb` — Replicates the baseline Difference-in-Differences results
- `note book/03_Extension_and_Results.ipynb` — Extends the analysis with heterogeneous treatment effects
- `README.md` — Executive memo and final portfolio overview

---

## Reproducibility
The project is organized so that readers can follow the workflow from raw data cleaning to final regression results and visualizations. Raw and processed data are kept conceptually separate, and notebook outputs document the main empirical steps.

---

## Reference
Card, D., & Krueger, A. B. (1994). Minimum wages and employment: A case study of the fast-food industry in New Jersey and Pennsylvania. *American Economic Review, 84*(4), 772–793.
