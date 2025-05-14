# AICTE-Crop-and-Fertilizer-Recommendation-System
This AICTE internship project uses machine learning to recommend suitable crops and fertilizers based on soil and environmental data. It includes trained models and notebooks for crop and fertilizer prediction using CSV datasets, improving farming decisions with data-driven insights.

🌾 Crop and Fertilizer Recommendation using Machine Learning
This project, developed during the AICTE internship, leverages Machine Learning to assist farmers by recommending optimal crops and fertilizers based on soil and environmental parameters.

🔍 Project Modules
Crop Recommendation:

Predicts the most suitable crop using features like nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, pH, and rainfall.

Trained using a supervised classification algorithm.

Files: Crop_Predictions.ipynb, crop_model.sav, crop_scaler.sav

Fertilizer Recommendation:

Suggests appropriate fertilizers based on the current crop and nutrient deficiencies.

Files: Fertilizer_recommendation.ipynb, fertilizer_model.sav, fertilizer_scaler.sav

📂 Dataset
Crop_recommendation.csv: Contains data on soil nutrients and climatic conditions with corresponding ideal crops.

Fertilizer_Prediction.csv: Contains crop and nutrient deviation info with recommended fertilizer types.

🛠️ Technologies Used
Python

Pandas, NumPy

Scikit-learn

Jupyter Notebook

Machine Learning (Classification)

📈 Output
Trained .sav models and .ipynb notebooks ready for deployment or web integration.

Scalers saved separately for consistent preprocessing during inference.
