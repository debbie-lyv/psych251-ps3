# Psych 251 — Problem Set 3: Reproducibility checks

## Published reports (Posit Connect Cloud)

| Part | Paper | Report |
|---|---|---|
| Part A (known case: Group B, Choice 3) | de la Fuente, Santiago, Román, Dumitrache, & Casasanto (2014), *Psychological Science* — Experiment 2 | [ps3_check (Part A)](https://connect.posit.cloud/debbie-lyv/content/01a20609-f510-583a-2254-3ab95d37fe9e) |
| Part B (a classmate's project paper) | Feng & Rutledge (2024), *Nature Communications* — Experiment 2 | [ps3_check (Part B)](https://connect.posit.cloud/debbie-lyv/content/01a2060a-7168-399b-7737-a501b3e5aae1) |

## Repository contents

- `Part A/`
  - `ps3_check.qmd`: reproducibility check write-up.
  - `reproducibilityReport.Rmd` and its `.html`: the full reproduction report for the Experiment 2 target outcomes.
  - `fig2.png`: the original Figure 2, for comparison.
- `Part B/`
  - `ps3_check.qmd`: reproducibility check of the key effect. It translates the authors' MATLAB code (`run_mainfigures.m`) into R.

## Data and materials not included

The article PDFs, data files, and AI transcripts are not committed. To re-run the analyses, place the data in each part's `data/` folder.

- **Part A data:** [psych251/problem_sets — ps3/Group B/Choice 3/data](https://github.com/psych251/problem_sets/tree/master/ps3/Group%20B/Choice%203) (originally from [OSF](https://osf.io/uh3in)).
- **Part B data:** `Exp2_data.mat` from [RutledgeLab/2024_sensory_surprises_risky_decisions](https://github.com/RutledgeLab/2024_sensory_surprises_risky_decisions) (`data_mat/`), also on [OSF](https://doi.org/10.17605/OSF.IO/PA75Q).
