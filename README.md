# Customer-SKU Reorder Prediction & Prioritization
An end-to-end machine learning and business intelligence project for predicting customer-SKU reorder opportunities and prioritizing them using historical retail transaction data. The project combines customer behavior analysis, feature engineering, machine learning, retrospective evaluation, opportunity prioritization and an interactive Power BI report to transform historical purchase data into actionable reorder insights.

## Project Overview
Retail businesses often have thousands of customer-product combinations and limited resources for targeted customer engagement. Instead of treating every customer-SKU combination equally, this project develops a predictive system that:
- Estimates the probability that a customer will reorder a SKU
- Identifies customer-SKU reorder opportunities
- Evaluates the predictions against actual reorder behavior
- Prioritizes opportunities based on predicted probability
- Identifies high-confidence reorder opportunities
- Summarizes customer and product-level opportunities
- Presents the results through an interactive Power BI report

## Relevant Graphs & Plots
1. Shows the distribution of total orders across customers, highlighting variation in customer purchase frequency:
<img width="1501" height="737" alt="Screenshot 2026-10-03 172158" src="https://github.com/user-attachments/assets/c845a073-e41b-40f9-9f97-7f22fdaf60a7" />

2. Shows the distribution of time intervals between repeat purchases, with a median reorder interval of approximately 33.8 days:
<img width="1302" height="680" alt="Screenshot 2026-10-03 172418" src="https://github.com/user-attachments/assets/5f47a7f8-23c9-47e2-92c7-d38179dd14a1" />

3. Compares the ROC performance of the evaluated classification models, with Random Forest achieving the highest validation ROC-AUC of 0.821:
<img width="1261" height="915" alt="Screenshot 2026-10-03 172912" src="https://github.com/user-attachments/assets/51718497-7669-416f-9000-5ee6250057a6" />

4. Shows the final Random Forest classification performance at the selected 0.54 decision threshold across reorder and non-reorder outcomes:
<img width="870" height="668" alt="Screenshot 2026-10-03 172558" src="https://github.com/user-attachments/assets/1501efb2-03c4-4aec-9560-2a0456dd8db2" />

5. Demonstrates the strong relationship between predicted probability and observed reorder behavior, with actual reorder rates increasing from 5.05% to 89.91%:
<img width="1144" height="688" alt="Screenshot 2026-10-03 173327" src="https://github.com/user-attachments/assets/cb414280-0ee3-47f3-ba66-2c418f1ad942" />

6. Shows the distribution of 2,978 predicted reorder opportunities across Medium, High, and Very High priority levels:
<img width="865" height="679" alt="Screenshot 2026-10-03 173621" src="https://github.com/user-attachments/assets/289cbf33-2371-45bc-a896-8f037d803f07" />

7. Highlights the products with the largest number of predicted customer-SKU reorder opportunities, led by Root Vegetables, Beans, and Other Vegetables:
<img width="1323" height="649" alt="Screenshot 2026-10-03 173225" src="https://github.com/user-attachments/assets/d8c0b120-7b24-4370-8ee1-11f1b8826f4e" />
