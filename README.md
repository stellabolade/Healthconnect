# 3MTT CAPSTONE PROJECT
## DATA ANALYSIS FOR A FICTITIOUS ORGANIZATION CALLED HEALTHCONNECT; A COMPANY PROVIDING INNOVATIVE HEALTHCARE SOLUTIONS. 
## Dataset
![image](https://github.com/user-attachments/assets/3fc6c698-97d7-4727-aefb-0a7dc7a70822)

## Project Overview
The project is designed to analyze patient data, discover trends, and build insightful dashboards to aid management in decision-making.

## Data Description
The dataset  includes the following key columns:
1. Name: The name of each patient.
2. Age : The age of each patient.
3. Gender: Patient's gender
4. Bloodtype: Patients's blood group.
5. Medical condition: Patient's diagnosis.
6. Date of Admission: The date patient was admitted to the Hospital.
7. Doctor: Physician who treated each patient
8. Hospital: Facility handling patient's care
9. Insurance provider: Organization handling patient's health insurance.
10. Billing Amount: Cost of health service provided
11. Room number: Patient's ward number
12. Admission type: Type of admission bades on patient's case
13. Discharge date: Date of discharge from the Hospital
14. Medication: Treament medication/ plan
15. Test result: Treatment outcome
16. Region (Added Column): Geographical location of each Hospital

## Data Source
This dataset was downloaded from Kaggle as a csv file. 

## Time Period
The dataset spans from 2019-2024

## Explorative Data Analysis
This project was designed to address the following analysis goals:
- Patient demographics distribution across different health conditions.
- Treatment success rates by diagnosis.
- Geographical distribution of health conditions.

 ## Tools and Methods Used

Data cleaning and modification: Utilizing the Power query, data consistency was ensured by formatting names into proper case using the proper function, test result (Normal, inconclusice, and abnormal) was also modified into Treatment Outcome (Successful and unsuccesful) by creating a conditional column. Also, number of days on admission was calculated by subtracting Discharge date from Admission date using the date function in the add column tab. 
Data Analysis: The data was analyzed using Microsoft Excel, utilizing Pivot Tables to organize, summarize, and filter the data for easier interpretation.
Data Visualization: Utilizing Tableau, Different visualizations were created represent the key insights.

## ANALYSIS, VISUALIZATION, AND INFERENCE

##  Excel Analysis
### Cleaned and Modified data
![image](https://github.com/user-attachments/assets/271e9b1a-cec7-4892-b804-fd9ecd38a941)


### 1.Geographical distribution of each diagnosis

![image](https://github.com/user-attachments/assets/c5c49953-63ac-4507-8791-4f5e15db92db)

### 2.Success rate of each treatment plan
![image](https://github.com/user-attachments/assets/2455c2b6-e67c-4c7a-a4d6-6f71b1aa2183)

### 3. Age group of patients with specific health condition
![image](https://github.com/user-attachments/assets/f7e343f4-7408-49ad-94e3-82fb8472756d)

### 4. Gender of patients with specific health condition
![image](https://github.com/user-attachments/assets/544e40b8-03cc-438b-be81-f6062562bc23)

### 5. Treatment outcome of each Medical condition.
![image](https://github.com/user-attachments/assets/de6ee7e0-b951-4046-a711-c643fac55ca2)

### 6. Successful rate of each medication
![image](https://github.com/user-attachments/assets/23b2600c-3147-4227-bccf-e0fa634aefff)

## Visualization with Tableau

### Dashboard Overview

![image](https://github.com/user-attachments/assets/df6a45fd-7832-43b8-82ce-d1a5b89aad17)

### Visuals and inference

### Dashboard Overview

![image](https://github.com/user-attachments/assets/df6a45fd-7832-43b8-82ce-d1a5b89aad17)

### Visuals and inference

### The most common diagnosis by region
![image](https://github.com/user-attachments/assets/a4cb6e20-ef4b-4af7-958e-5f800192a8d9)

- Arthritis is the most commonly reported diagnosis, indicating it has the highest prevalence among the local governments surveyed.

- Obesity is the least commonly reported diagnosis, suggesting it has the lowest prevalence among the listed conditions.

- Diabetes, Cancer, Asthma, and Hypertension have relatively similar counts, indicating that these conditions are reported at comparable levels across the local governments.

### Regional distribution of each diagnosis
![image](https://github.com/user-attachments/assets/3d92be64-d5bc-4c71-adce-8930839da06e)
![image](https://github.com/user-attachments/assets/669a48dc-177d-447f-ab1f-b0504d3f8933)

#### Local Government Areas:

The chart includes the following LGAs: Ibadan North, Ibadan North-East, Ibadan South-East, Lagelu, Ibadan North-West, Ibadan South-West, Egbeda, Ona Ara, Ido, and Akinyele.

#### Medical Conditions:

Arthritis (Blue): Most prevalent in Lagelu and Ibadan North Local governments, with significant counts also observed in Ona-ara, Egbeda, and Ibadan North-West and moderate cases in other regions.

Asthma (Orange): Highest counts in Egbeda and Ibadan North, with significant counts also observed in Ibadan South-West, Ibadan North-West, and Ibadan South-East and moderate cases in other regions.

Cancer (Red): Notably prevalent in Ibadan South-West and Akinyele, with significant counts also observed in Ibadan North-West, Ibadan North-East, and Lagelu and moderate cases in other regions.

Diabetes (Light Blue): Significantly prevalent in Ibadan South-East. Notable prevalence is also recorded in Ibadan South-West, and Ido. 

Hypertension (Green): Most prevalent in Ibadan North, also notably prevalent in Ibadan North-East, Ibadan South-West, and Akinyele. Moderate cases reported in other regions.

Obesity (Yellow): High prevalence recorded in Ona ara and Ibadan North-East. Signigicant prevalence is also recorded in Lagelu, Ibadan South-East, Egbeda, and Ido Local governments. Moderate cases reported in other LGAs.

### Success rate of various treatment plans
![image](https://github.com/user-attachments/assets/2848b36b-bbc7-4446-8ce0-29843aed4446)

- Arthritis: 29% successful, 71% unsuccessful.
- Asthma:  32% successful, 68% unsuccessful.
- Cancer: 33% successful, 67% unsuccessful.
- Diabetes: 31% successful, 69% unsuccessful.
- Hypertension: 34% successful, 66% unsuccessful.
- Obesity: 37% successful, 63% unsuccessful.

### Age group of patients with specific health conditions
![image](https://github.com/user-attachments/assets/efeabea3-ed3d-4526-8d04-b14cb3dd6af1)

#### Age groups:
- Young: 18-35 years
- Young Adult: 36-50 years
- Adult: 51-85 years

#### Arthritis:
- Adults: 98 cases
- Young: 42 cases
- Young Adults: 38 cases

#### Asthma:
- Adults: 79 cases
- Young: 47 cases
- Young Adults: 41 cases

#### Cancer:
- Adults: 85 cases
- Young: 46 cases
- Young Adults: 31 cases

#### Diabetes:
- Adults: 77 cases
- Young: 51 cases
- Young Adults: 41 cases

#### Hypertension:
- Adults: 81 cases
- Young: 46 cases
- Young Adults: 37 cases

#### Obesity:
- Adults: 86 cases
- Young: 34 cases
- Young Adults: 35 cases

### Gender of patients with specific health conditions
![image](https://github.com/user-attachments/assets/f0f28a12-b200-4022-8b8d-3d8d9c8309b2)

#### Arthritis:
- Female: 88 patients
- Male: 90 patients
Arthritis affects both genders almost equally, with a slightly higher count in males.

#### Asthma:
- Female: 74 patients
- Male: 93 patients
Asthma has a higher prevalence in males compared to females.

#### Cancer:
- Female: 90 patients
- Male: 77 patients
Cancer is more prevalent in females than in males.

#### Diabetes:
- Female: 73 patients
- Male: 96 patients
Diabetes shows a higher prevalence in males compared to females.

#### Hypertension:
- Female: 79 patients
- Male: 85 patients
Hypertension affects both genders fairly equally, with a slight male predominance.

#### Obesity:
- Female: 71 patients
- Male: 84 patients
Obesity is more common in males than in females.

### Patient distribution across each year
![image](https://github.com/user-attachments/assets/bf6def87-a2ce-406e-b5c4-3abab84f1ef8)

- 2019: Data is only available from May to December. August and November recorded high admissions than other months of the year.
- 2020: Admissions are more evenly distributed throughout the year, although with notable no of admissions with the month of January and May.
- 2021: Similar to 2020, with a slight increase in admissions in the month of February, August, and December.
- 2022: Significant peak is recorded in the month of June; also notable is number of admissions in the month July, September, and December.
- 2023: Shows a relatively even distribution across the year with slight peak in the months of January and September.
- 2024: Data is only available from January to May, within which, high number of admission is recorded in the month of January and March.

### Overall inference
1) Arthritis appears to be a significant health issue within the surveyed local governments, while obesity is less frequently reported. The similar reporting levels for diabetes, cancer, asthma, and hypertension suggest these conditions are widespread and may require similar levels of attention for public health initiatives and resource allocation. This information can guide health authorities in prioritizing medical resources and interventions.

 2)Treatment outcome exhibits the same trend of high levels of unsuccessful rate. This depicts that the treatments plans are inefficient for the health conditions. Therefore, there should be an overall evaluation and overhaul of the entire treatment plans. 

3) Adults have the highest prevalence of all the examined health conditions, indicating a need for targeted healthcare interventions for this age group. For Young Adults and Young have relatively lower counts for all conditions, suggesting they might be less prone to these health issues, or they may have better access to preventive measures. Asthma and Diabetes show notable cases in younger age groups, indicating early intervention and management in this area could be beneficial.


