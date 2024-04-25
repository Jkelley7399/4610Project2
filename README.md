### Dataset Description

**Title:** Conditions Contributing to COVID-19 Deaths, by State and Age, Provisional 2020-2023

**Source:** The dataset was obtained from the U.S. Centers for Disease Control and Prevention (CDC) through the Data.gov catalog.

**Dimensions:** The dataset comprises 621,000 entries with 14 columns.

**Description:** This dataset tracks conditions that contributed to deaths involving COVID-19 by state and age group from January 2020 to September 2023. It includes both direct causes and contributing factors of death as classified by ICD-10 codes.

**Columns and Data Types:**
- **Data As Of (object):** The date when the data was last updated.
- **Start Date, End Date (object):** The time range for the reported data.
- **Group (object):** Categorization of the data, such as by total or by year.
- **Year (float64), Month (float64):** The year and month to which the data corresponds.
- **State (object):** The U.S. state or territory.
- **Condition Group (object), Condition (object):** The group and specific medical conditions linked to COVID-19 deaths.
- **ICD10_codes (object):** The International Classification of Diseases, Tenth Revision, code for the condition.
- **Age Group (object):** The age range of the individuals.
- **COVID-19 Deaths (float64):** The number of deaths where COVID-19 was a cause or contributing factor.
- **Number of Mentions (float64):** Times a specific condition was mentioned in conjunction with COVID-19 deaths.
- **Flag (object):** Indicator of certain conditions in the data reporting, such as suppressed data for privacy.

### Research Questions

1. **How do COVID-19 death rates vary across different age groups and states?**
   - Importance: This question aims to uncover disparities in the impact of COVID-19 on various demographic groups, potentially influencing public health policies and resource allocation.

2. **What are the most common comorbid conditions that contribute to COVID-19 deaths, and how do they vary by age?**
   - Importance: Understanding comorbid conditions can help in tailoring healthcare responses and preventive measures for at-risk populations, highlighting the need for targeted healthcare interventions.

These questions are directly related to the dataset as they utilize the demographic (age, state) and medical condition data provided within.

### Data Manipulations

- **Filtering and Grouping:** The data may be filtered by specific states or age groups and aggregated to summarize COVID-19 deaths and comorbidities.
- **Calculations:** Calculation of death rates by dividing the number of COVID-19 deaths by the total number of mentions to understand the prevalence of comorbid conditions.

### Analysis and Results

Using Tableau, we will visualize the data to answer the proposed questions. The visualizations will likely include:
- Bar graphs showing the distribution of COVID-19 deaths by age and state.
- Pie charts or heat maps displaying the prevalence of different comorbid conditions across various demographics.

The implications of our analysis could inform public health strategies, resource distribution, and awareness campaigns focused on the most affected populations.

### Tableau Packaged Workbook

Upon completion of the analysis, the project will be saved and exported as a Tableau packaged workbook file, which will be included in the GitHub repository, providing a comprehensive view of the data and visualizations created.

This detailed approach should provide a robust understanding of the dataset and the health phenomena it represents, catering to both informed and uninformed readers.

