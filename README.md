# Psychometrics – Candidate Outcomes Analysis (Public Demo)

This repository contains a public example of an analysis evaluating the **predictive validity** of a psychometric risk assessment (DRA) for recruitment. 

### What this analysis shows
- Descriptive statistics and visual comparisons of risk scores across outcome groups
- ROC curves to assess discrimination for binary outcomes
- Predictive modelling using random forests (with SMOTE for class imbalance)


### Important notes
- **All data is fully synthetic** — generated to match realistic distributions, correlations, and broad patterns from the original analysis. No real individual, candidate, or client data is included.
- **Dimension names** have been generalised or renamed to protect intellectual property. The underlying constructs and relationships remain representative.
- Minor differences in subgroup averages or model performance compared to the original analysis are expected due to simulation noise.

### How to view the report
The full rendered report is available via **GitHub Pages**:

→ [View the live report][(https://your-org-name.github.io/your-repo-name/)](https://ax-consult-group.github.io/psychometrics-DRA-candidate-outcomes/)

### Technologies used
- Quarto for reproducible reporting
- R (tidyverse, ggplot2, randomForest, caret, pROC, smotefamily, etc.)
- Simulated data generation via copula and conditional sampling
---
*Last updated: January 2026*
