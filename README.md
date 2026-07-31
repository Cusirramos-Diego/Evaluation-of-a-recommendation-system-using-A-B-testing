# Evaluation of a recommendation system using A/B testing

📌 Project Description:  
The impact of a new recommendation system on user behavior within a digital platform was evaluated to determine whether it improved conversion rates across the purchasing funnel.

❓ Business Challenge:  
A new recommendation system was introduced with the expectation of increasing user progression through the purchase funnel. The business needed to determine whether the observed changes in user behavior were sufficiently robust to justify deploying the new recommendation engine across the platform.

🔍 Methodology:  
•	Constructed a sequential conversion funnel to compare the performance of groups A and B.  
•	Identified inconsistencies in the experimental data (e.g., participants appearing in both groups, records captured outside the experiment's timeframe) and redefined the analysis using a strict funnel approach that applied logical filters based on the A/B test design.  
•	Validated observed differences using z-tests for proportions and statistical analysis of conversion rates.

🧠 Why this analytical approach?:  
Reliable experimentation depends on data quality as much as statistical testing. Before evaluating conversion differences, I verified the integrity of the experiment by identifying duplicated participants, overlapping experimental groups, and events occurring outside the evaluation window. This ensured that subsequent statistical conclusions reflected actual product behavior rather than inconsistencies in the experimental dataset.

⚙️ Main analytical decisions:  
•	Reconstructed the purchase funnel using a strict sequential approach to preserve the logical progression of user actions.  
•	Excluded records that violated the experimental design to minimize potential bias.  
•	Evaluated conversion rates at each stage of the funnel instead of relying exclusively on overall purchase rates.
•	Applied one-tailed statistical hypothesis tests because the business objective was specifically to evaluate whether the new recommendation system improved conversion.
•	Prioritized business interpretation of statistical results by translating findings into product recommendations.

🛠️ Technical Tools:  
Python | Pandas | SciPy | Statsmodels | Matplotlib | Seaborn

🏆 Achievements:  
• Analyzed the behavior of over 6,000 users involved in the experiment, using visit logs from both versions of the recommendation system.  
•	Evaluated three stages of the conversion funnel using statistical tests, identifying critical transition points where visitors dropped off.  
•	Generated evidence-based recommendations to support decision-making regarding the implementation of the new system.

📈 Graphical visualization:  
• Analysis and temporal validation of the number of participants in groups A and B:  
<img width="1858" height="765" alt="image" src="https://github.com/user-attachments/assets/b77b58ee-e663-44b9-91f0-085a721555e0" />

• Comparison of performance in the main funnels of both groups:  
<img width="1546" height="765" alt="image" src="https://github.com/user-attachments/assets/22b2861e-fe74-4f81-b8f2-de8f07e25a5d" />

🎯 KPIs to change:  
•	Product Page → Cart Conversion.  
•	Cart → Purchase Conversion.  
•	Purchase Rate.  
•	Revenue per User.  
•	Average Order Value.  

🤔 Subsequent hypothesis worth evaluating:  
If recommendations are personalized using the user's browsing and purchase history, the conversion rate from product viewing to purchase will increase.

💡 Recommended decision for the Product Manager:  
The results indicate that the new recommendation system should not be implemented in its current state, as it did not produce statistically significant improvements in purchase funnel conversion rates.

🚀 Expected impact:  
•	Increased conversion.  
•	Higher revenue per user.  
•	Improved shopping experience.  
•	Experimental validation before final deployment.  

💭 General recommendations:  
It was recommended not to implement the new recommendation system, as the observed differences did not demonstrate statistically significant improvements in funnel conversion rates.

🔮 What I would do next:  
The next step would be to design a new A/B experiment using personalized recommendations based on users' browsing and purchase history. I would also analyze heterogeneous treatment effects across different customer segments, evaluate long-term retention after exposure to recommendations, and measure incremental revenue rather than conversion alone to estimate the true business value of the feature.

▶️ How to Run:  
•	Clone the repository: git clone https://github.com/Cusirramos-Diego/Evaluation-of-a-recommendation-system-using-A-B-testing.git  
• Open the notebook in Jupyter Notebook or Jupyter Lab.  
• Run the cells sequentially to reproduce the analysis and visualizations.  
• Review insights, conclusions, and recommendations.
