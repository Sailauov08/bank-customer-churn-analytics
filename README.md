# Bank Customer Churn Analytics & Prediction 📊🤖

This project is a professional Data Science portfolio that analyzes real-world data from 10,000 bank customers and builds an AI model to predict customer defection (churn) risks.

## 🛠️ Project Structure (Pipeline)
The project is split into 4 production-standard phases to maintain a clean workflow:
1. `1_data_collection.ipynb` — Fetches real banking data from the international OpenML server and ingests it into a local SQLite database.
2. `2_data_cleaning.ipynb` — Handles data preprocessing, type formatting, and prepares the dataset for machine learning.
3. `3_data_analysis.ipynb` — Executes complex SQL business queries to extract insights and plots visualizations using `matplotlib/seaborn`.
4. `4_machine_learning.ipynb` — Trains a `RandomForestClassifier` model optimized with class balancing to predict future customer churn.

## 📈 Key Business Insights
* The number of bank products (`num_products`) held by a customer has a direct impact on their likelihood to leave the bank.
* Customers with 4 products are in the highest risk zone, showing an absolute churn rate.

## 💻 Tech Stack & Tools
* **Languages:** Python, SQL
* **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn, SQLite3
* **Tools:** Jupyter Notebook, Microsoft Excel
