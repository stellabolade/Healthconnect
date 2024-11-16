# PRACTICE PROJECT
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

### Total sales by product

![Total sales by product](https://github.com/user-attachments/assets/1a2ca644-8c1b-4ce4-92a9-262fd00d842d)

- Shoes are the highest selling product with total sales of $613K, indicating they are the most popular and possibly the most profitable product.

- Shirts are the second highest selling product with sales of $486K, also indicating strong sales performance.

- Hats and Gloves have moderate sales, with $316K and $297K respectively, suggesting a steady demand.

- Jackets have lower sales at $208K, which might indicate a more niche market or seasonal demand.

- Socks have the least sales at $181K, making them the least popular product among the six.

### Total sales by region

![Total sales by region](https://github.com/user-attachments/assets/f6e57e12-0202-40df-a0b4-74e044e0a131)

- The South region has the highest total sales, amounting to $928K. This indicates a strong market presence or a larger customer base in the South.

- The East region follows, with total sales of $486K, suggesting moderate market performance.

- The North region has total sales of $387K, showing it has a smaller market share compared to the South and East.

- The West region has the lowest total sales at $300K, indicating the smallest market size or presence among the four regions.

### Quantity sold by product

![Quantity sold by product](https://github.com/user-attachments/assets/6d734c3b-d977-40b1-a5fa-6c49075a5475)

- The highest selling product is Hat with 16k units sold; this is followed by Shoes with 14k units sold.

- Shirts and Gloves each have 12K units sold, suggesting a similar level of demand for these products.

- Socks have a lower quantity sold at 8K, indicating they are less popular compared to Hats, Shoes, Shirts, and Gloves.

- Jackets have the lowest quantity sold at 5K, making them the least popular item among the six products.

### Quantity sold by region

![Quantity by region](https://github.com/user-attachments/assets/2f3d3739-e78f-4827-a604-ef8ce28ecac9)

The chart reveals that the South region has the highest quantity sold at 24K, indicating it is the most significant market or has the highest demand for the products. The East region follows with 20K units sold, showing a strong market presence but less than the South. The North region has a total of 12K units sold, suggesting moderate demand compared to the South and East, while the West region has the lowest quantity sold at 11K, indicating it is the smallest market or has the lowest demand for the products.

### Total sales by year and month

### 2023
![Total sales by year and month](https://github.com/user-attachments/assets/fac6602f-1f17-490a-903a-79c389bf5263)

### 2024
![year 2024](https://github.com/user-attachments/assets/eb8e7724-e0a8-468d-8231-bcf04f9af829)

- January 2023 starts with moderate sales, while February 2023 shows a significant peak with the highest sales exceeding $600K.

- March 2023 experiences a sharp drop to about $248K, followed by a further decrease in April 2023 to $7K, the lowest sales month.

- Sales gradually recover in May 2023 ($60K) and June 2023 ($99K), with a noticeable spike in July 2023 ($238K) and October 2023 ($134K).

- A decline in November 2023 ($104K) and December 2023 ($49K) suggests lower end-of-year activity.

- Sales increase again in January 2024 to $198K, followed by a sharp decline in February 2024 ($29K), then moderate recovery through March 2024 ($95K) and April 2024 ($39K).

- The second half of 2024 shows significant sales improvement, with peaks in June 2024 ($148K), July 2024 ($137K), and August 2024 ($174K), indicating stronger sales performance compared to the same months in the previous year.

### Quantity sold by year and month

![Quantity by month and year](https://github.com/user-attachments/assets/ce15dd5e-a9e4-4c80-a4e6-40d5718416a0)

- In 2023, there were significant peaks in sales quantities in February and July, with quantities sold reaching 5.0K and 5.9K, respectively. These peaks suggest strong market demand during these months, possibly due to seasonal factors or promotional events. However, sales dipped sharply in April and May, with quantities dropping to 1.5K and 1.0K, indicating a period of low demand.

- For 2024, the sales quantities exhibit a fluctuating pattern. January 2024 started strong with 4.0K units sold, and the highest quantity sold in February and March at 5.5K each, indicating continued strong demand in the early part of the year. However, sales dropped significantly in April and May, similar to the previous year, with quantities at 2.0K and 1.5K. Sales then picked up again in June with 3.9K units and fluctuated for the rest of the year.

### Recommendations

- For high performing products like Shoes and Shirts, Increase marketing efforts to maintain and boost sales. Expansion and introduction of new designs should be considered.
- For low performing products, Campaigns and promotions should be intensiified. Discounts or bundles can be offered, to attract customers.
- Regions with high revenue should maintain and strengthen the market presence with targeted marketing campaigns, ensuring sufficient inventory to meet high demand; while others should engage in localized promotions to boost sales.
- The store should utilize peak Months and Plan major marketing campaigns maximize sales, launch new products or limited-time offers during these periods; while low performing months should intensify promotion, implement clearance sales.
