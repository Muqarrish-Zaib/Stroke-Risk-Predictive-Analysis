# Stroke Risk Predictive Analysis
Stroke is a disease that affects the arteries leading to and within the brain. A stroke occurs when a blood vessel that carries oxygen and nutrients to the brain is either blocked by a clot or bursts.

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.
![130395889-5cf2dc2c-060e-4f0c-a11d-4e2e7f1e6936](https://user-images.githubusercontent.com/106870714/197326943-d672956c-45ef-4050-9ff5-e0cddead62e6.jpg)
# Dataset
You can download dataset from [kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
# Features of Dataset
The entire dataset contains 5110 rows and 12 columns. Each columns in the data provides relevant information about the patient.
- id: unique identifier
- gender: "Male", "Female" or "Other"
- age: age of the patient
- hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- ever_married: "No" or "Yes"
- work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
- Residence_type: "Rural" or "Urban"
- avg_glucose_level: average glucose level in blood
- bmi: body mass index
- smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
- stroke: 1 if the patient had a stroke or 0 if not

**Note:** "Unknown" in smoking_status means that the information is unavailable for this patient
