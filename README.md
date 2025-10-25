# GLM Analysis of Low Birth Weight – A Statistical Study

This project explores the relationship between maternal and demographic factors and the probability of low birth weight, using **Generalized Linear Models (GLM)** with a **binomial (logistic) link**.

We applied exploratory data analysis, variable selection, and diagnostic evaluation to identify key predictors of low birth weight, including maternal age, race, smoking status, and socioeconomic indicators.

### Methods
The main model was a **Logistic Regression (GLM with logit link)**:
$$
\text{logit}(P(Y=1)) = \beta_0 + \beta_1 X_1 + \dots + \beta_p X_p
$$
where \(Y\) represents low birth weight status.

### Results
The final model highlighted significant predictors such as:
- Race (Black vs. White)
- Smoking status during pregnancy
- Mother’s age and education level  

Model performance was evaluated using **AIC**, **Residual Deviance**, and **Pseudo R²** measures.  
Diagnostic plots were used to validate model assumptions and detect influential observations.

### Files
- `Rmd/work_Itay_and_Eden_final.Rmd` – full reproducible R code and analysis  
- `report/work-Itay-and-Eden-final.docx` – detailed written report  

© 2025 Eden Malka and Itay Ben Avraham. All rights reserved.
