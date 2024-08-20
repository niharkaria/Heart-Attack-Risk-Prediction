
# Heart Attack Risk Prediction Using Health and Lifestyle Data

## Project Overview
This project aims to predict heart attack risk using a dataset containing various health indicators, lifestyle choices, and socioeconomic factors. The goal is to develop a machine learning model that can assist healthcare providers in identifying high-risk patients and providing early interventions.

## Problem Statement
Heart attacks are a leading cause of death globally. Early detection of high-risk individuals can save lives through timely treatment and lifestyle changes. This project uses a dataset containing health metrics, lifestyle factors, and medical history to predict the likelihood of a heart attack. By leveraging this data, we aim to develop a predictive model that can provide actionable insights for healthcare practitioners.

## Dataset
- **File**: heart_attack_dataset.csv
- **Key Features**:
  - **Patient Information**: Age, Sex, Country, Continent, Hemisphere
  - **Health Indicators**: Cholesterol, Blood Pressure, Heart Rate, Diabetes, BMI, Triglycerides
  - **Lifestyle Factors**: Smoking, Obesity, Alcohol Consumption, Exercise Hours Per Week, Diet, Stress Level, Sedentary Hours Per Day, Physical Activity Days Per Week, Sleep Hours Per Day
  - **Medical History**: Family History, Previous Heart Problems, Medication Use
  - **Socioeconomic Factors**: Income
- **Target Variable**: Heart Attack Risk (0 = No Risk, 1 = At Risk)

## Project Workflow
1. **Data Exploration and Preprocessing**:
   - Handle missing values and outliers.
   - Normalize/standardize features where necessary.
  
2. **Feature Engineering**:
   - Create derived features if needed (e.g., categorizing cholesterol levels).

3. **Data Visualization**:
   - Analyze the relationship between different factors and heart attack risk using visualizations like bar plots, heatmaps, and distribution plots.
  
4. **Predictive Modeling**:
   - Train models such as Logistic Regression, SVC, Naive Bayes, Decision Trees, and Random Forest to predict heart attack risk.
   - Evaluate models using metrics like accuracy, precision, recall, and F1-score.

5. **Results and Insights**:
   - The Logistic Regression, SVC, and Naive Bayes models achieved the highest accuracy of 64.18%. These models identified high-risk patients with reasonable accuracy, indicating a solid foundation for further refinement.

## Tools and Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Data Visualization**: Matplotlib, Seaborn

## Project Results
- The models identified high-risk patients with an accuracy of 64.18%.
- Insights generated from the analysis can guide healthcare decisions and patient education.

## How to Run the Project
1. Clone the repository.
2. Install required libraries using:
   ```bash
   pip install -r requirements.txt
Run the Jupyter notebook or Python script to execute the analysis.

## Conclusion
This project demonstrates how data can be leveraged to predict heart attack risk, highlighting the importance of early detection in preventive healthcare. While the models provide a good baseline, future work could involve incorporating additional features or exploring advanced machine learning techniques.

## Future Work
- Incorporate more features like genetic data or environmental factors.
- Explore deep learning models for better prediction accuracy.

## License
This project is licensed under the MIT License.
