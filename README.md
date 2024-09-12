# Predictability of Career and Professional Excellence

## Overview
This project explores LinkedIn job postings to predict trends in career and professional excellence. The dataset, consisting of over 33,000 job posts from LinkedIn, was analyzed using various techniques such as regression, clustering, and classification. Our analysis provides valuable insights into salary predictions, experience level requirements, and industry trends that can guide individuals, organizations, and policymakers in career and workforce development.

## Dataset

- **Source**: The dataset was sourced from LinkedIn job postings collected over two separate time periods. Each posting contained details such as job title, description, salary, location, and more. Additional supplementary datasets on company profiles and skills were also included to enhance the depth of the analysis.
  - **Size**: 33,000+ job postings
  - **Attributes**: 28 features per job posting, including job title, salary range, location, work type, experience level, skills, etc.

## Data Processing

### Data Preparation
- **Cleaning**: 
  - Missing values were handled by removing records without salary information.
  - Data imputation was applied where applicable, and outliers were identified in salary fields.
- **Feature Selection**: 
  - Selected key fields such as job title, salary, work type, location, and experience level for analysis.
  - Columns such as job posting URLs and non-relevant fields were excluded for better analysis focus.
- **Derived Variables**:
  - Created new attributes such as average salary and dummy variables for work types and skill attributes.
  
(Data Preparation Details: [View the report](./Data_Preparation.docx))

### Data Understanding
- **Exploratory Data Analysis (EDA)**: 
  - Data profiling was conducted to understand key patterns and trends.
  - Visualizations (box plots, histograms) helped identify salary trends, industry demands, and experience levels.
  
(Data Understanding Details: [View the report](./Data_Understanding.docx))

### Data Modeling
- **Modeling Techniques**:
  - **Regression**: Used for salary range prediction.
  - **Clustering**: K-means clustering to group job postings based on location and work types.
  - **Classification**: Decision tree classification to predict experience level requirements.
- **Model Evaluation**:
  - Models were evaluated using metrics such as Mean Absolute Error (MAE), Silhouette Score for clustering, and accuracy scores for classification.
  
(Data Modeling Details: [View the report](./Data_Modelling.docx))

## Tools and Technologies Used
- **Data Cleaning**: Microsoft Excel, Microsoft Access
- **Data Modeling**: IBM SPSS Modeler
- **Visualizations**: Tableau
- **Programming**: Python for preprocessing and additional analytics

## Key Findings
- Salary predictions can be accurately modeled using job title, location, and skill descriptions.
- Experience levels are a strong indicator of salary and job suitability.
- There is a significant variance in salary by job location and industry, with tech and healthcare industries leading the highest salary ranges.

## Insights
- **For Individuals**: Guides job seekers on in-demand skills, emerging job trends, and strategic locations for career development.
- **For Organizations**: Provides insights into talent acquisition strategies and benchmarks for competitive compensation.
- **For Policymakers**: Helps in curriculum and policy development to address workforce trends and needs.

## Authors
- Saikeshav Motwani
- Ayush Patel
- Viraj Bhavsar
- Mitesh Singh
- Sherin Jacob
- Vedant Pandya

## License
This project is licensed under the MIT License.
