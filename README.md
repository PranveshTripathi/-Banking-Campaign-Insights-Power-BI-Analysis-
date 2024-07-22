# Banking-Campaign-Insights-Power-BI-Analysis
This project features a Power BI analysis of a Portuguese banking dataset, examining subscription rates for term deposits. The analysis explores how education levels and job types influence the likelihood of subscriptions. It evaluates the impact of different education levels on subscription rates, identifying which groups show the highest interest. Additionally, it assesses job types to determine which have the highest and lowest subscription rates. The dataset comprises records from phone call marketing campaigns conducted between 2008 and 2010, with thorough pre-processing and visualization to derive these insights.

## About
This dataset originates from the direct marketing campaigns of a Portuguese banking institution, focusing on telephonic interactions to assess client interest in subscribing to a term deposit. The data, available on Kaggle, includes four versions: `bank-additional-full.csv` and `bank-full.csv` each with 41,188 entries, and `bank-additional.csv` and `bank.csv` each with 4,119 entries. The datasets feature between 17 to 20 inputs, capturing client demographics and campaign specifics. The main classification task is to predict the subscription outcome, providing a rich multivariate dataset for analysis.

## Pre-Processing
Preprocessing is a crucial step in data analysis, involving the transformation of raw data into a clean, structured format suitable for analysis and modeling. This process ensures that data is consistent, accurate, and complete, eliminating issues that could skew results or impact the performance of machine learning models.

In Power BI preprocessing, I focus on several critical tasks to ensure the dataset is prepared for accurate analysis and effective visualization. This includes checking for NaN values, detecting and handling outliers, and addressing missing values to maintain data integrity. Additionally, I create new conditional columns and define measures for Key Performance Indicators (KPIs) to enhance data visualization. By meticulously cleaning and transforming the data, and developing KPIs, I ensure that the dataset is not only valid but also optimized for generating dynamic and insightful visualizations. This thorough preprocessing process enables clear and actionable insights, facilitating better decision-making through Power BI’s robust analytical capabilities.
Here's a revised version:

Some measures added to the dataset include:

- **Index:** A unique identifier for each record.
- **Marital Status ("martial_stat"):** Categorizes clients by marital status.
- **Subscription Rate:** Calculates the percentage of clients who subscribed.

The basic steps used in data preprocessing:

1. Removed columns
2. Filtered rows
3. Changed data types
4. Added multiple conditional columns
5. Added an index

## Visualization (Dashboard-PowerBI) & Conclusion
Data visualization is the graphical representation of information and data. It uses visual elements like charts, graphs, and maps to provide an accessible way to see and understand trends, outliers, and patterns in data. Visualization helps make complex data more comprehensible and actionable, enabling better decision-making by presenting information clearly and effectively.

**Pie Chart**
A pie chart is a circular graph divided into slices to illustrate numerical proportions. Each slice represents a category's contribution to the whole, making it easy to compare parts of a dataset.

**Donut Chart**
A donut chart is similar to a pie chart but with a central hole, giving it a ring-like appearance. It displays categorical data and proportions while allowing for additional information or multiple series in the center.

**Stacked Bar Chart**
A stacked bar chart is a bar graph where individual bars are divided into segments representing subcategories. The length of each segment is proportional to its value, showing the cumulative effect and comparison of categories within a dataset.

Pie Chart:-
![image](https://github.com/user-attachments/assets/3124707b-412c-42a7-a53b-f63c6c7b0e99)

In this interactive chart, the subscription rate is analyzed based on the contact method: 
1)telephone 
2)unknown 
3)and cellular. 

subscription rate by contact(Unknown)
![image](https://github.com/user-attachments/assets/ae21dab4-a882-43de-95a8-08edfa3cc995)

subscription rate by contact(Telephone)
![image](https://github.com/user-attachments/assets/21fb23d6-da67-4c9e-865c-b02e64d8d878)

subscription rate by contact(Cellular)
![image](https://github.com/user-attachments/assets/5f50db6b-5748-4856-b431-092acdb88ac0)


Donut Graph:-

![image](https://github.com/user-attachments/assets/1c5bc670-731c-4d56-9329-2f6125e53d00)

In the donut chart, the count of age is analyzed based on education, which has four categories:

1) Primary  
2) Secondary  
3) Tertiary  
4) Unknown  

This chart helps visualize the distribution of age across different education levels.

The count of age is analyzed based on education(Primary)
![image](https://github.com/user-attachments/assets/c53e22db-3b51-48ed-912d-7049b844614f)

The count of age is analyzed based on education(Secondary)
![image](https://github.com/user-attachments/assets/1bc9438b-0701-4919-a174-528cc47ff056)

The count of age is analyzed based on education(Tertiary)
![image](https://github.com/user-attachments/assets/c597e437-b8e2-4018-9693-918406ca2156)

The count of age is analyzed based on education(Unknown)
![image](https://github.com/user-attachments/assets/43e71e57-01cf-4f55-93bd-4d1bfdec2dff)


Stacked bar graph:-

This graph shows the impact of education on subscription.
![image](https://github.com/user-attachments/assets/4939a1fc-40da-4d09-9639-78e498a52f5c)

In this stacked bar chart, the subscription rate is analyzed by job type, which includes 12 categories:

1. Student
2. Retired
3. Unemployed
4. Management
5. Unknown
6. Admin.
7. Self-employed
8. Technician
9. Services
10. Housemaid
11. Entrepreneur
12. Blue-collar

The chart illustrates the impact of these job types on the subscription rate.

![image](https://github.com/user-attachments/assets/f073ef07-b66d-46b3-8926-be4a32e3d14a)


## Conclusion

Upon successfully completing the project, including both preprocessing and visualization stages, several key insights have been uncovered regarding the factors influencing subscription rates. 

During the preprocessing phase, the data was meticulously cleaned and transformed to ensure accuracy and consistency. This involved handling missing values, identifying and addressing outliers, and creating new conditional columns to enrich the dataset. These preprocessing steps were crucial for preparing a robust dataset that could support meaningful analysis.

In the visualization phase, various charts were employed to explore and understand the data comprehensively. The donut chart illustrated the distribution of age based on education levels, revealing how educational background correlates with age demographics. It was observed that education plays a significant role in shaping subscription rates, with certain education categories showing higher or lower subscription tendencies.

The stacked bar chart provided insights into the impact of different job types on subscription rates. By analyzing 12 job categories, the chart highlighted which occupations had the highest and lowest subscription rates. This analysis demonstrated that job type has a substantial influence on subscription outcomes, with some professions showing a strong correlation with higher subscription rates.

Additionally, the interactive chart detailing subscription rates by contact method (telephone, unknown, cellular) further emphasized how contact mode affects subscription likelihood. The data showed that unknown contact methods were associated with a particular subscription rate, providing valuable information on how different contact strategies might influence client engagement.

In conclusion, the project successfully addressed multiple questions regarding the impact of job type and education level on subscription rates. The preprocessing and visualization efforts revealed significant patterns and trends, offering actionable insights for optimizing marketing strategies and understanding client behavior. This comprehensive analysis provides a clear understanding of key factors influencing subscription decisions, paving the way for more informed and effective decision-making.
