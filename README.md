📞 Project Title: AI-Powered EMI Call Prediction and Advisory System
This project presents a smart solution designed to improve the efficiency of EMI collection calls in call centers using Machine Learning and Generative AI. A Random Forest classifier is trained on historical call center data to predict whether a customer is likely to answer a phone call based on key features such as customer age, occupation, gender, city, number of previous calls, days overdue, and whether it's a weekday or weekend.
The system evaluates every business hour (from 9 AM to 5 PM) for each customer and identifies the best time to call — the hour with the highest success probability. To support decision-making, it integrates the FLAN-T5 language model from Hugging Face to generate a brief, natural language explanation justifying why that hour is ideal for calling.
The complete solution is deployed using Streamlit, offering:

• Upload support for Excel/CSV customer datasets.

• Real-time prediction of call answer likelihood.

• Best call time recommendation per customer.

• AI-generated one-line explanation.

• Visual charts showing call timing trends by age and gender.

• Downloadable Excel report for business use.

This intelligent system helps reduce missed calls, improve customer contact rates, and assist agents with actionable insights, making it a valuable tool for financial institutions or NBFCs.
