# Cancer Patient Analysis

![Dashboard Image 1](https://github.com/BalajiRamGanesh/Cancer-Patient-Analysis/blob/main/Dashboard%20Images/Cancer%20Patient%20Dashboard1.PNG?raw=true)

![Dashboard Image 2](https://github.com/BalajiRamGanesh/Cancer-Patient-Analysis/blob/main/Dashboard%20Images/Cancer%20Patient%20Dashboard2.PNG?raw=true)

![Dashboard Image 3](https://github.com/BalajiRamGanesh/Cancer-Patient-Analysis/blob/main/Dashboard%20Images/Cancer%20Patient%20Dashboard3.PNG?raw=true)

## Overview
This project analyzes cancer patient data from the UAE to uncover key insights about medical conditions, treatment types, and patient outcomes. It aims to identify trends and relationships that can support better healthcare decisions and understanding of cancer dynamics in the region.

## Problem Statement
The analysis aims to explore the following key questions:
- What is the most common medical condition among patients?
- What are the outcomes of cancer patients?
- How do treatment types relate to survival rates?
- How do treatment outcomes vary across different medical conditions?
- What is the average time gap between diagnosis and treatment initiation?
- What are the treatment patterns based on cancer stage?
- How do treatment outcomes differ by smoking history?
- How are admissions distributed across hospitals?
- What are the most common comorbidities among patients?
- Which medical conditions are most common across different ethnic groups?


## Tools Used
- Python - Programming language
- Pandas - Data cleaning and analysis
- Matplotlb and Seaborn - Data visualizaton
- Jupyter Notebook - Interactive development environment


## Methodology

- **Data Import**: Loaded the dataset into the notebook using pandas for further analysis.
- **Data Cleaning**:  Addressed missing values in `Comorbidities`, dropped `Death_Date` and `Cause_of_Death` columns, and converted date columns to datetime format.
- **Exploratory Data Analysis**: Visualized distributions and relationships between cancer types, treatments, patient outcomes, and more using charts.
- **Feature Engineering**: Created a `Time_Gap_Before_Treatment` column to analyze patterns between diagnosis and treatment dates.
- **Insight Generation**: Interpreted analysis results to extract meaningful insights and provide relevant recommendations.


## Insights
- Leukemia is the most common cancer type among patients; however, liver, lung, and pancreatic cancers follow closely with only slightly lower occurrences.
- Nearly 50% of patients have recovered, while around 40% are still undergoing treatment. Unfortunately, 10% of the patients have died.
- All treatment types are used relatively evenly across patients, with immunotherapy showing a slightly higher usage rate compared to other treatment options.
- Leukemia has the highest number of both recovered and under-treatment patients, while pancreatic cancer shows the highest death rate.
- Ovarian cancer stands out with the lowest number of deaths and also has a high recovery rate and under-treatment count. Overall, the distribution of treatment outcomes is fairly consistent across cancer types.
- Most of the treatments does not have any fixed days after diagnosis. However, It takes average of 90 days between treatment and diagnosis.
- Most of the patients are suffering from stage of two and three across all cancer types.
- Smoking status is not directly affecting outcome of patient treatment. Hoowever, They are nearly half of the patients are either smoker or former smoker across all treatment outcome.
- Patient admissions have been consistent from 2015 to 2023 across all hospitals. Unfortunately, we only have data up to March 2024 to consider for the year 2024.
- 59.5% of patients are suffering from comorbidities. Among them, hypertension is the most common comorbidity, affecting 29.5% of patients.
-South Asian patients have the highest number of leukemia cases compared to other ethnicities and cancer types.
- The highest number of European patients suffer from liver cancer, which is also the highest among all ethnicities.
- The highest number of African patients suffer from colorectal cancer, East Asians from leukemia, and Arabs from breast cancer.


## Recommendation
- Promote early diagnosis campaigns to reduce treatment delays, especially since the average time gap between diagnosis and treatment is around 90 days.
- Encourage regular screenings and preventive check-ups for patients with a history of smoking or comorbidities.
- Design targeted health interventions by analyzing cancer trends across ethnicities to improve outreach and equity in cancer care.
- Focus on pancreatic cancer by enhancing early detection methods, increasing awareness, and providing specialized treatment plans to address its high mortality rate.
- Address smoking habits by implementing preventive measures and awareness campaigns, as nearly half of the patients are current or former smokers. While smoking doesn’t directly impact treatment outcomes in this data, it may contribute significantly to cancer occurrence.


## Getting Started

1. Clone the repository
```bash
git clone https://github.com/BalajiRamGanesh/Cancer-Patient-Analysis.git
```
2. Navigate to the project directory
```bash
cd Cancer-Patient-Analysis
```

3. Install the necessary libraries
```bash
pip install pandas matplotlib seaborn jupyter
```

4. Launch jupyter notebook
```bash
jupyter notebook
```
5. Open and run `Cancer Patient Analysis.ipynb` notebook


