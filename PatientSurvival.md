#Introduction

This project focuses on predicting the survival of cancer patients using machine learning techniques. The dataset includes information such as patient age, sex, hospital, treatment class, and bed cost. Data preprocessing involved cleaning, handling missing values, and converting categorical features into numerical form. Two models — Decision Tree and Random Forest — were trained to predict patient survival. The goal is to help healthcare providers make data-driven decisions and improve patient care outcomes.

## Data Dictionary

Age – The age of the patient admitted for treatment.

Sex – The gender of the patient (e.g., Male or Female).

Class – The classification of treatment or patient severity level (e.g., 0, 1, 2).

Bed Cost(£) – The cost associated with the patient's hospital bed.

Hospital – The name or code of the hospital where the patient was treated.

Survived – Target variable indicating if the patient survived (1) or not (0).
## Findings

The analysis found that patient age, treatment class, and bed cost were key factors influencing survival outcomes. The Random Forest model outperformed the Decision Tree, achieving a higher accuracy of 75%. It showed better balance in predicting both survival and non-survival cases. Patients with lower class ratings and higher bed costs had lower survival rates. These insights can help healthcare providers identify high-risk patients and improve treatment strategies.
