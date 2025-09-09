📊 Trader Behavior & Market Sentiment Analysis
📌 Objective
The goal of this project is to explore the relationship between trader behavior/performance and market sentiment, uncover hidden patterns, and deliver actionable trading insights.
We specifically predict market sentiment (Fear vs. Greed) based on aggregated trader activity.

📂 Project Structure
├── historical_data.csv        # Trader activity dataset
├── fear_greed_index.csv       # Market sentiment dataset
├── Preprocessing_Enhanced_v2.ipynb   # Main analysis & modeling notebook
├── models/                    # Saved ML models (joblib)
│   ├── logistic_regression_model.joblib
│   └── random_forest_model.joblib
└── README.md                  # Project documentation

🔑 Key Steps
Data Preprocessing
Cleaned & merged trader activity with sentiment data.
Engineered features like avg_pnl, total_volume, buy_ratio, etc.
Exploratory Data Analysis (EDA)
Correlation between trader metrics and sentiment.
Visualized patterns in performance vs. market conditions.
Predictive Modeling
Target: Market sentiment classification (Fear/Greed).
Models used:
Logistic Regression
Random Forest Classifier
Evaluated using accuracy, confusion matrix, and classification report.
Random Forest feature importance highlighted top drivers of sentiment.
Results
Trader behavior (PnL, volume, buy ratio) has a measurable relationship with market sentiment.
Random Forest achieved better predictive performance than Logistic Regression.
Feature importance indicates which trader metrics align most with Fear vs. Greed periods.

📈 Results Summary
Logistic Regression: Baseline model for interpretability.
Random Forest: Stronger predictive accuracy & feature ranking.
Insights:
High trading volume often aligns with Greed sentiment.
Negative PnL spikes correlate with Fear sentiment.

🛠️ Tech Stack
Python (Pandas, NumPy, Scikit-learn, Matplotlib)
Jupyter Notebook
Joblib (for saving ML models)


📬 Contact

👤 Sauleha Khan
📧 khansauleha08@gmail.com
