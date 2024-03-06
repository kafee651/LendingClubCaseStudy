# Lending Club Case Study
> The company wants to reduce credit loss by identifying risky loan applicants. This involves understanding the driving factors behind loan default.
To address the business objectives outlined, we will conduct an Exploratory Data Analysis (EDA) to understand the driving factors behind loan default. This will involve identifying strong indicators of default by analyzing various variables related to borrowers and loans.

We are going to follow following five steps of EDA in two sections:
1. Data sourcing
2. Data cleaning
3. Univariate analysis
4. Bivariate analysis
5. Derived metrics


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement: The company wants to reduce credit loss by identifying risky loan applicants. This involves understanding the driving factors behind loan default.
- Data Collection and Preparation: Obtain data related to borrowers, loans, and default status. Preprocess the data to handle missing values, outliers, and any inconsistencies.
- Univariate Analysis: Examine individual variables to understand their distributions, central tendencies, and outliers. This will help identify potential predictors of default.
- Bivariate Analysis: Explore relationships between pairs of variables, particularly focusing on their association with the default status. This will help identify strong indicators of default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the Univariate Analysis:
   -  From the distribution of home ownership plot, we can understand "Rent" and Mortgage" categories are mostly provided the loan.
   -  From the distribution of loan purpose plot, we can understand debt consolidation high purpose for loan applying.
   -  From the distribution of loan term plot, we can understand 6 years loan higher in count.
   -  From the distribution of loan Issue date plot, we can understand there is increase in applicant receiving by the months.
   -  From the distribution of loan status plot, we can understand there are high number of applicate have already paid their loan.
   -  From the spread of loan amount, we can see median is around 10000
   -  From the spread of annual income, we can see there are two outliers
- Conclusion 2 from the Segmented Univariates analysis
   -  From the applicant years of employment, It is clearly visible avg income has increased
- Conclusion 3 from the Bivariate analysis
   -  High loan amount are more defaulter 
   -  High Interest rate is more defaulter 
   -  High Installment are more defaulter 
   -  Higher term are more defaulter
   -  9 years employment is less defaulter. 
   -  Mortgage ownership is less defaulter. 
   -  Small business are more defaulter
   -  Defaulter trend has changed from higher to lower to higher again with passing months.
- Conclusion 4 from the Derived Metrics analysis
   -  In the year 2007 Probability of defaulter is higher as compare to other years. 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.11.5
- matplotlib.pyplot
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Google Play Store Analysis
- https://www.kaggle.com/code/ecemboluk/google-play-store-analysis


## Contact
Created by [@kafee651] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->