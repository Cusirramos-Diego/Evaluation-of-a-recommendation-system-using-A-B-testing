# Evaluation of a recommendation system using A/B testing

📌 Project Description:  
The impact of a new recommendation system on user behavior within a digital platform was evaluated to determine whether it improved conversion rates across the purchasing funnel.

🔍 Methodology:  
•	Constructed a sequential conversion funnel to compare the performance of groups A and B.  
•	Identified inconsistencies in the experimental data (e.g., participants appearing in both groups, records captured outside the experiment's timeframe) and redefined the analysis using a strict funnel approach that applied logical filters based on the A/B test design.  
•	Validated observed differences using z-tests for proportions and statistical analysis of conversion rates.

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

💭 Recommendations:  
It was recommended not to implement the new recommendation system, as the observed differences did not demonstrate statistically significant improvements in funnel conversion rates.

▶️ How to Run:  
•	Clone the repository: git clone https://github.com/Cusirramos-Diego/Evaluation-of-a-recommendation-system-using-A-B-testing.git  
• Open the notebook in Jupyter Notebook or Jupyter Lab.  
• Run the cells sequentially to reproduce the analysis and visualizations.  
• Review insights, conclusions, and recommendations.
