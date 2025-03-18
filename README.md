# Causal-ML-Analysis-Income-Based-Incentives-in-Residential-Retrofit-Energy-Efficiency-Projects

## Causal ML Analysis: Assisted vs. Market Treatment Effects

This analysis explores the impact of assisted vs. market rate incentives on project outcomes using Causal ML methods. S-Learner and X-Learner has been applied using different base models: Linear Regression, XGBoost, and Random Forest.

As the 'Pre-Retrofit Home Heating Fuel Type' was proven to be the most important feature (both in Assignment 1 analysis and Assignment 2 - S-learner feature importances), the study focused on treatment effect heterogeneity by using 'Pre-Retrofit Home Heating Fuel Type' as an effect modifier in X-Learner and estimating treatment effects separately across fuel types.

As S-Learners can't explicitly model instruments or effect modifiers like X-Learners, used X-Learner to explore treatment effect heterogeneity by heating fuel type. X-Learner estimated separate models for treated and control groups, then learnt how treatment effects vary based on key variables like fuel type. This helps identify whether incentives work better for certain heating sources.

