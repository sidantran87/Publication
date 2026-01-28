🎵 Flexible Approach to Churn Prediction using Time Series Classification
This research proposes a flexible approach based on time series classification to early-detect customer churn on online music platforms (KKBOX).

🎯 Research Novelty
Flexible Approach: Instead of static monthly predictions, the model provides weekly forecasts, allowing businesses to intervene in a timely manner.

MiniRocket-SHAP Model: Combines the ultra-fast time series classification algorithm (MiniRocket) with the SHAP explanation method to overcome the "black box" limitations of deep learning models.

🛠 Research Methodology
Data: Analyzes listening behavior, transaction history, and demographics from 249,086 training samples.

Features: Extracts Lag features and Rolling statistics (mean, std, skew) to emphasize temporal properties.

Explainability: Uses Shapley values to rank feature importance and time-step importance.

📈 Results and Business Application
Performance: The MiniRocket-SHAP model achieved 0.95 Accuracy and a 0.79 F1-score.

Churn Drivers: "Actual amount paid" was found to be the most significant factor.

Intervention Timing: Churn signals appear clearly as early as 8 weeks before the customer actually stops the service.

💡 Strategic Recommendations
Businesses should use the model to cluster churning customers (based on payment levels) to offer targeted promotional programs.

Perform diagnostic analysis at "sensitive time steps" to prevent early intent to leave.
