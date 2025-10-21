<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/bd6e7412-a886-4b45-96ee-4f6fb08fb54e" />
<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/d97c91d4-db3d-4375-af90-1364f4c5c686" />

🌍 Predicting Air Pollution Levels Based on IoT Sensors
Author: Shaikhstan Margulan
Affiliation: Department of Artificial Intelligence Technologies, L.N. Gumilyov Eurasian National University
Conference: 2025 1st International Conference on Cybersecurity, Digital Forensics and AI Applications (ICCSDFAI)

📖 Overview
This project focuses on predicting Air Quality Index (AQI) levels using data from IoT-based air monitoring systems and machine learning algorithms.
The study demonstrates how real-time sensor data, combined with Random Forest regression, can accurately forecast pollution levels across urban environments.

The system integrates:
IoT sensor networks (both fixed and mobile)
Cloud and edge computing
Data preprocessing and visualization
Predictive modeling for AQI forecasting

🎯 Objectives
Develop an IoT-driven air quality monitoring framework.
Implement data cleaning, normalization, and anomaly detection techniques.
Use Random Forest regression to predict AQI with high accuracy.
Visualize pollution patterns through heatmaps, geospatial plots, and correlation analyses.

🧠 Methodology
1. Data Collection
Pollutants monitored: PM2.5, PM10, NO₂, CO, O₃
Sources: IoT sensor data, open datasets (Kaggle, Google API, Earth Engine)
Transmission: NB-IoT (Narrowband IoT) for low-power, wide-area communication

2. Data Preprocessing
Missing value imputation
Outlier detection (IQR, Z-score)
Normalization and feature encoding
Time alignment and timestamp correction

3. Machine Learning Model
Algorithm: RandomForestRegressor
Metrics:
Mean Squared Error (MSE): 23.22
R² Score: 0.997
Result: High correlation between predicted and actual AQI values

4. Visualization Tools
AQI distribution histograms
Pollutant correlation heatmaps
Geospatial pollution mapping
Residual and regression plots

💡 Key Findings
IoT + ML integration enables real-time and scalable air quality prediction.
Random Forest provides high accuracy with limited computational cost.
Combining fixed and mobile IoT sensors offers better spatial coverage.
Cloud computing enhances large-scale data aggregation, while edge computing improves local responsiveness.

⚙️ Technologies Used
Programming Language: Python
Libraries: pandas, scikit-learn, matplotlib, seaborn, numpy
Data Sources: IoT sensor data, public AQI datasets
Architecture: Cloud + Edge hybrid system

🔍 Future Work
Integration of meteorological data (temperature, humidity, wind speed)
Application of deep learning models (LSTM, CNN) for time-series forecasting
Development of real-time AQI dashboard for smart cities

📊 Example Results
Metric	Value
Mean Squared Error	23.22
R² Score	0.997
Primary Pollutants	PM2.5, NO₂
Model Used	Random Forest Regressor

🧾 Citation
If you use this research in your work, please cite:
Shaikhstan Margulan, Sadvakassov Ramazan. Predicting Air Pollution Levels Based on IoT Sensors.
Proceedings of the 2025 1st International Conference on Cybersecurity, Digital Forensics and AI Applications (ICCSDFAI), Astana, Kazakhstan, 2025.

📫 Contact
Shaikhstan Margulan
📧 Email: shaihstanmargulan@gmail.com
🌐 L.N. Gumilyov Eurasian National University
