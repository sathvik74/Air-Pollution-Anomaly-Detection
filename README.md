# Air-Pollution-Anomaly-Detection
 Air Pollution Anomaly Detection in Indian Cities (2015–2024)
This project uses real-world air quality data from major Indian cities to explore pollution trends and apply unsupervised machine learning models for detecting anomalies in pollutant concentrations. The goal is to uncover hidden spikes and outliers in pollution levels that may correspond to environmental events, festivals, or unexpected emissions.

📁 Dataset
Source: Kaggle - Air Quality Data in India (2015–2024)

Cities Covered: Delhi, Mumbai, Chennai, Kolkata, Bangalore

Columns Used:

Pollutants: PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene

AQI & AQI Bucket

Datetime & City

🎯 Project Goals
Perform exploratory analysis on air pollution trends over time

Detect abnormal pollution events using unsupervised ML models

Visualize and interpret pollution spikes across cities and seasons

🛠️ Tools & Technologies
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Isolation Forest

Autoencoder (Keras/TensorFlow)

📊 Exploratory Data Analysis (EDA)
Trends in AQI over years and months

City-wise comparison of pollutant levels

Seasonal variations in pollution

Most frequent AQI buckets

Pollutant-wise contribution to AQI over time

Findings:

AQI dropped sharply during 2020 lockdown

Mumbai had highest average AQI

Winter months (especially December and March) showed elevated pollution levels

PM2.5 and PM10 were most dominant pollutants

🤖 Anomaly Detection Approach
1. Isolation Forest
Unsupervised method to isolate anomalies in high-dimensional space

Input: pollutant concentrations

Output: binary labels (normal vs anomaly)

2. Autoencoder
Neural network trained to reconstruct input features

Large reconstruction error = potential anomaly

Offers a deep-learning-based alternative to Isolation Forest

🎯 Evaluation:
Visual inspection of anomalies using scatterplots

Time series overlays showing pollution spikes

City-wise anomaly heatmaps

🧠 Key Insights
Anomalies aligned with known high-pollution events (e.g., post-Diwali, winter months)

Isolation Forest was lightweight and effective

Autoencoder gave deeper insights but needed more tuning

Traditional AQI classification/regression approaches revealed actionable insights and anomaly detection added real value

This project and dataset are shared under the CC0: Public Domain license.

🙋‍♂️ Author
Sathvik Isikella
Aspiring ML/Data practitioner exploring data-driven insights into environmental issues.

