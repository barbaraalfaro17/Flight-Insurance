Authors: Xiangwen Gao, Barbara Alfaro, Karla Legarde

### Project Overview
This project focuses on optimizing profitability for an insurance company (Allianz Partners) by analyzing flight delay data from 2022–2024.

We developed a data-driven solution to:
- Predict flight delays
- Estimate insurance claim costs
- Optimize pricing strategies
- Improve decision-making

### Business Problem
Flight delays create uncertainty and financial risk for travel insurance providers due to unpredictable claim payouts.

### Key Business Questions
- How many high-delay flights are expected in 2025?
- What is the expected insurance payout cost?
- What pricing strategy maximizes profit?
- Can we predict flight delays to adjust pricing dynamically?

### Data Sources
- U.S. Bureau of Transportation Statistics  
  https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGK&QO_fu146_anzr=b0-gvzr  
- Federal Aviation Administration (FAA) Aircraft Registry
https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download  
- Open-Meteo Weather API  
  https://open-meteo.com/  
- Statista (Passenger Load Factor)  
  https://www.statista.com/statistics/691292/airlines-us-domestic-passenger-load-factor/  
- Insubuy (Travel Insurance Statistics 2024)  
  https://www.insubuy.com/travel-insurance-statistics/  
- Allianz Travel Insurance (OneTrip Basic Plan)  
  https://www.allianztravelinsurance.com/find-a-plan/onetrip-basic.htm  

### Methodology
1. Forecasting
- Model: SARIMA
- Forecasted 5,227 high-delay flights in 2025
2. Price Optimization
- Model: Linear Regression
- Optimal strategy: 3-tier pricing model
- Profit increase: +3.3% (~$5.44B total profit)
3. Classification Model
- Models tested:
  - Random Forest (selected)
  - Logistic Regression
  - Gradient Boosting
- Used to predict flight delay likelihood

## Key Insights
- Insurance claims projected: $104M in 2025
- Tiered pricing outperforms flat pricing
- Demand decreases predictably as price increases
- Predictive models improve pricing accuracy

## Tools & Technologies
- Python (Pandas, Scikit-learn)
- Power BI
- Time Series (SARIMA)
- Machine Learning

## Full Presentation
You can view the full presentation here: 
👉 [Download Presentation](./FinalPresentation.pdf)

## Dashboard Preview
<img width="1433" height="797" alt="image" src="https://github.com/user-attachments/assets/5f28f5d5-29af-4717-ac00-dd181efca4e2" />
<img width="1432" height="790" alt="image" src="https://github.com/user-attachments/assets/7c884ee6-0f37-4e14-8145-1e04b29ee89d" />


