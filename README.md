# PIMA Diabetes Prediction
## Deployed Application
Visit my Hugging Faces Space to test the application: https://huggingface.co/spaces/datrotte/PIMA-Diabetes-Prediction

## Business Context
A healthcare clinic is looking to enhance its decision-making process for predicting the likelihood of diabetes in patients based on a set of health-related attributes. Diabetes is a growing concern, especially among certain age groups and populations with risk factors such as high blood pressure, obesity, and a sedentary lifestyle. The clinic has collected patient data, including metrics like plasma glucose concentration, blood pressure, body mass index (BMI), and others, which can be used to predict diabetes. However, they struggle with accurately identifying high-risk patients who may need further medical intervention or lifestyle changes.

The clinic seeks to leverage machine learning models to predict diabetes risk and ultimately improve patient care. By accurately predicting the probability of a patient having diabetes based on their health metrics, the clinic aims to provide early diagnosis, enabling timely intervention and better healthcare outcomes.

## Objective
I was hired as data scientist to a local the clinic to build a predictive model that can classify whether or not a patient is likely to have diabetes based on their health attributes. I developed a machine learning pipeline using a Gradient Boosting classifier to analyze patient data and predict diabetes outcomes (class label 1: diabetes, 0: no diabetes). I also peformed MLOps to deploy this model and enable real-time predictions for clinical use.

## Data Description
I used the clinic's dataset which consists of health-related attributes of patients, with the following features:

- ***Pregnancies*** (preg): Number of times the patient has been pregnant
- ***Plasma glucose concentration*** (plas): Plasma glucose concentration in an - oral glucose tolerance test
- ***Blood pressure*** (pres): Diastolic blood pressure (mm Hg)
- ***Skin thickness*** (skin): Triceps skin fold thickness (mm)
- ***Serum insulin*** (test): 2-Hour serum insulin (mu U/ml)
- ***Body mass index*** (mass): BMI (weight in kg/height in m²)
- ***Diabetes pedigree function*** (pedi): A function that scores the likelihood of diabetes based on family history
- ***Age*** (age): Age of the patient (years)
- ***Class*** (class): Diabetes outcome (1: diabetes, 0: no diabetes)

## MLOps & DevOps
*I utilized GitHub Actions to enable MLOps & Devops which allowed me to:*
- Create a system that automatically loads, cleans, transforms, and preprocesses data whenever new information is ingested
- Train and fine-tune the model to reflect the latest data
- Seamlessly deploy the updated model into production without incosistencies
- Facilitate collaboration between software developers, data scientists, operation teams, & other key stakeholders

## Results
*Here's how these MLOps practices benefit the clinic:*
- Access to deliver reliable, scalable, and timely predictions, enabling better patient care
