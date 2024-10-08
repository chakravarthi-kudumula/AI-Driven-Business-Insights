# AI-Driven-Business-Insights

<h3>Overview</h3>

This project focuses on building machine learning models to generate key business insights, including profit prediction, revenue prediction, sales forecasting, customer churn prediction, and pricing optimization. Each model uses a separate dataset and is implemented directly in Google Colab. The project leverages Random Forest algorithms to improve predictive accuracy and efficiency. All datasets used in this project are sourced from Kaggle.

<h3>Project Structure</h3>

<h5>The project is structured as follows:</h5>

**Datasets:** Uploaded individually into Google Colab for each insight.<br>
**Model Implementation:** Each machine learning model is implemented sequentially within the Google Colab notebook for the respective insights.<br>
**No Frontend:** Currently, no frontend is implemented for reporting outputs. All results are displayed directly in the Colab notebook.<br>

<h3>Algorithms Used</h3>
Random Forest Regressor<br>
Random Forest Classifier<br>

<h3>Libraries Used</h3>
pandas: For data manipulation and cleaning.<br>
numpy: For numerical operations.<br>
scikit-learn: For machine learning models (Random Forest Regressor and Classifier).<br>
matplotlib & seaborn: For visualizing data insights and model performance.<br>

<h3>Datasets</h3>

<h5>Datasets are sourced from Kaggle for each business insight:</h5>
<a href="https://www.kaggle.com/datasets/pythonafroz/companies-profit"> Profit Data </a><br>
<a href="https://www.kaggle.com/datasets/mrsimple07/restaurants-revenue-prediction"> Revenue Data </a><br>
<a href="https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast/data?select=train.csv">Sales Data</a><br>
<a href="https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset"> Customer Churn Dataset</a><br>
<a href="https://www.kaggle.com/datasets/suddharshan/retail-price-optimization"> Pricing Optimization Dataset</a><br>

<h3>How to Run</h3>
1.Clone the repository or access the notebook from Google Colab.<br>
2.Upload the datasets into the Colab environment.<br>
3.Run the cells sequentially to train the models and view the results.<br>

<h3>Future Enhancements</h3>
1.Adding a frontend using Streamlit to display predictions and insights.<br>
2.Expanding the dataset and models for more granular predictions.<br>



<h1> Key Insights and Their Impact </h1>

<p>Our analysis yielded several key insights with significant impacts on business operations and strategy. These insights span profit prediction, revenue forecasting, sales projections, customer churn prediction, and pricing optimization, each contributing to more informed decision-making.</p>

<h3>Profit Prediction:</h3>
By predicting expected profit based on R&D spend, administration costs, marketing spend, and geographical factors, we can optimize budget allocation and identify high-return investment areas. Understanding the expense-profit relationship allows for strategic decisions to cut costs or increase investments where needed, leading to enhanced profitability.

<h3>Revenue Prediction:</h3>
Forecasting monthly revenue using variables such as customer count, menu pricing, marketing spend, cuisine type, customer spending patterns, promotions, and reviews provides a robust framework for optimizing pricing, marketing strategies, and promotions. This predictive capability facilitates better planning and dynamic strategy adjustments, ultimately maximizing revenue.

<h3>Sales Forecasting:</h3> 
Predicting future sales based on historical sales data, holiday indicators, and economic factors like temperature, fuel prices, CPI, and unemployment rates is instrumental for inventory management, staffing, and planning promotional events. Accurate sales forecasts help balance supply and demand, reducing costs and improving customer satisfaction.

<h3>Customer Churn Prediction:</h3>
By identifying attributes such as credit score, age, tenure, balance, number of products, credit card ownership, active membership, estimated salary, and geographical and gender information, we can effectively target retention strategies. Understanding the factors leading to customer churn enables personalized interventions, enhancing customer retention and lifetime value.

<h3>Pricing Optimization:</h3>
<p>Analyzing product attributes and competitor pricing helps set optimal prices that are both competitive and profitable. By considering factors such as product ID, quantity, total price, freight price, unit price, product photos quantity, product weight, and competitor prices, we ensure our pricing strategies attract customers while maximizing profits.</p><br>

<p>These insights collectively empower businesses to make data-driven decisions, leading to improved operational efficiency, customer satisfaction, and financial performance. Integrating predictive analytics into business processes allows for proactive strategy adjustments, ensuring sustained growth and competitive advantage.</p>
