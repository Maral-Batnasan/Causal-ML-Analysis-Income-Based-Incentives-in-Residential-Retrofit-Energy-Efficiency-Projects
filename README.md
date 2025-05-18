# Causal-ML-Analysis-Income-Based-Incentives-in-Residential-Retrofit-Energy-Efficiency-Projects

## Causal ML Analysis: Assisted vs. Market Treatment Effects 

This analysis explores the impact of assisted vs. market rate incentives on project outcomes using Causal ML methods. S-Learner and X-Learner has been applied using different base models: Linear Regression, XGBoost, and Random Forest.

As the 'Pre-Retrofit Home Heating Fuel Type' was proven to be the most important feature, the study focused on treatment effect heterogeneity by using 'Pre-Retrofit Home Heating Fuel Type' as an effect modifier in X-Learner and estimating treatment effects separately across fuel types.

As S-Learners can't explicitly model instruments or effect modifiers like X-Learners, used X-Learner to explore treatment effect heterogeneity by heating fuel type. X-Learner estimated separate models for treated and control groups, then learnt how treatment effects vary based on key variables like fuel type. This helps identify whether incentives work better for certain heating sources.

### 🔍 Key Findings

- **Fuel Type is Critical**: The most influential factor across all models was the *Pre-Retrofit Home Heating Fuel Type*. This variable consistently drove the variation in energy savings, highlighting the importance of tailoring incentives based on fuel usage.
- **Strong Financial Influence**: Features like *Total Incentives*, *Total Project Cost*, and *Volume of Home* were also highly predictive, reinforcing that both economic and structural characteristics impact retrofit effectiveness.
- **Significant Treatment Effect Heterogeneity**: X-Learner estimates revealed stark differences in treatment effects by fuel type. Homes using *Propane* and *Electricity* saw the greatest energy savings, while those using *Wood Pellets* or *Natural Gas* showed weaker responses.
- **Assisted vs. Market Incentives**: Assisted incentive recipients consistently experienced larger energy savings across all fuel types, suggesting that income-based assistance plays a vital role in driving retrofit outcomes.
- **Policy Insight**: These findings support differentiated incentive structures—offering higher subsidies for homes reliant on high-cost fuels like Propane and Electricity and reevaluating allocations for homes using lower-impact fuels such as Natural Gas.


