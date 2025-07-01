# Capstone_3
🏨 Hotel Booking Cancellation Prediction
This project uses a machine learning classification model to predict the likelihood of a hotel booking being canceled, based on historical reservation data and customer behavior.

🎯 Objective
High cancellation rates can lead to lost revenue and operational inefficiencies in the hospitality industry. By predicting which bookings are likely to be canceled, hotel managers can:

Optimize room allocation and pricing strategies

Reduce operational overhead (e.g., unnecessary room preparation)

Improve financial forecasting and resource planning

🛠️ Approach
We use the XGBoost classifier integrated into a preprocessing pipeline with Grid Search optimization focused on maximizing recall, to ensure most cancellation cases are captured.

Key steps include:

Data preprocessing (numerical, ordinal, and binary categorical encoding)

Class imbalance handling using scale_pos_weight

Model evaluation using metrics such as precision, recall, f1-score

Threshold tuning to align with business cost-benefit objectives

📦 Output
Trained model saved as cancellation_model.pkl

Evaluation metrics & plots

Feature importance analysis

Optional cost-benefit estimation to guide decision thresholds

🧠 Tech Stack
Python 3

scikit-learn

XGBoost

Pandas, NumPy, Matplotlib

Jupyter / Google Colab
