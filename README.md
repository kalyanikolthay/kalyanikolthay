# Kalyani Sanjay Kolthay 
MSc Business Analytics (Distinction), Queen's Business School, Queen's University Belfast 

I am a business analytics graduate seeking a business analyst role in Belfast. My work on using data to answer practical business questions and turning the findings int o clear, actionable recommendations. 

I make a point of questioning assumptions before accepting a solution and I apply that approach to every analysis I undertake. 

## Projects

**Predicting Product Success in Beauty Retail Using Customer Reviews**

| MSc dissertation | 

Using scraped data from Sephora's public catalogue of 2,351 reviewed skincare products, I tested whether customer review text adds predictive value beyond structured product data when classifying products as High or Low performers. I extracted five customer-perception concepts (effectiveness, irritation, texture, fragrance and value) from reviews using a zero-shot NLP model, validated the extraction against a manually annotated gold standard of reviews and compared six classifiers with and without these features. 

Key findings: 
- Review-based features significantly improved prediction in five of the six models
- The best model (XGBoost) reached ROC-AUC of 0.913 and PR-AUC of 0.801
- Effectiveness and fragrance sentiment were the strongest signals of product success
- The framework is designed to support assortment reviews, flagging products that warrant managerial attention

`R` `Python` `Hugging Face Transformers` `XGBoost` `SHAP` 

**Supplier Delivery Risk Analysis**

| Consulting project for a wholesale business, completed through the Data Duo mentoring programme | 

The business was planning orders around the lead times quoted by its suppliers. I analysed six months of order and delivery data to measure how far actual delivery times differed from quoted lead times, identified the highest-risk suppliers and recommended more reliable planning lead times. 

Key findings: 
- 29.8% of all orders arrived later than the quoted lead time
- 151 of 185 active suppliers had at least one late delivery during the period
- 17 suppliers had at least one severe delay of more than 20 days, with delays of uptown 60 days; trend analysis showed 3 of these were worsening
- The average delay was -1.36 days, meaning orders arrived slightly early on average, This masked the risk, because a minority of orders arrived very late

Approach and recommendations: 
- Cleaned the data by excluding invalid records and converting quoted lead-time from weeks to days
- Classified suppliers as High, moderate or Low risk based on their share of severe delays
- Replaced the average with a 90th percentile lead time, the number of days within which 90% of a supplier's orders have arrived, as the planning figure
- Recommended renegotiating lead times with high-risk supplier using P90 figures, prioritising follow-up with 3 worsening suppliers, and re-running the analysis quarterly
- Delivered the results as a presentation and a formatted Excel workbook, with suppliers holding fewer than three orders flagged as low confidence

`R` `Excel`

**Reducing Work Burden on Northern Ireland's GP Practices (Data for Good Hackathon, First Place)**

| Winning entry at the Data for Good Hackathon 2026, Queen's University Belfast | 

The number of GP practices in Northern Ireland has fallen by 11% in a decade while patient lists have grown and the pressure falls hardest on practices in deprived areas. Our team analysed data for all 312 GP practices across the five Health and Social Care Trusts, covering 12 chronic conditions and proposed a way to redistribute patients more fairly using existing resources. 

Key findings: 
- Hypertension was the most common condition at 143.5 per 1,000 patients, near twice the rate of asthma (65) and diabetes (56.3)
- Multimorbidity varied significantly between Trusts: South Eastern has the highest median burden, Southern the lowest and Belfast the widest variation between practices
- Produced a ranked list of 20 practices with he highest multi morbidity burden as a priority list for intervention
- The rebalancing model flagged 47 practices as over capacity and 89 to absorb patients, identifying 12,431 patients who could be reassigned

Approach and recommendations 
- Exploratory analysis of disease burden by condition, Trust and practice
- Machine learning model to flag underperforming practices
- A dynamic Markov reallocation model to find the best redistribution of patients from overloaded practices to nearby practices with spare capacity
- An interactive browser-based dashboard for commissioner that flags over-capacity practices, filters by Trust and simulates the reallocation for any practice
- Two supporting proposals: mobile treatment zones run by community nurse practitioners in the highest-burden areas, and a patient-facing app showing practice capacity and waiting times to support voluntary registration changes

`R`

## Technical Skills 

**Programming:** R, Python, SQL
**Tools:** Excel, PowerBI, Tableau
**Methods:** Classification modelling, consulting, supply chain management 

## Areas of Interest 

Business analysis, retail analytics, consulting, supply chain mangement

## Contact 
[LinkedIn] www.linkedin.com/in/kalyani-sanjay-kolthay
