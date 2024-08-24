---
layout: post
author: Name
title: "Applied Data Science Project Documentation"
categories: ITD214
---
## 1.Project Background
In a recent survey reported by Channel News Asia, it was found that the prevalence of mental health issues in Singapore is rising, with young adults having the highest proportion at 25.3%. In February 2024, Deputy Prime Minister Lawrence Wong passed a motion on advancing mental health, highlighting the growing importance of this issue both in Singapore and globally.
As part of a support group initiative, this project aims to develop a platform focused on providing emotional support, fostering a sense of community, and ensuring anonymity for those seeking help. By applying machine learning models such as Support Vector Machine (SVM), Random Forest and conducting correlation analysis, this study seeks to predict the likelihood of depression and identify the most influential features. 
Leveraging these data-driven insights allows for the identification of key demographic and behavioural factors contributing to depression risk, enabling tailored interventions and content optimization. The goal is to create a positive and engaging environment that empowers users to address their mental health challenges effectively.

##1.1 Project Plan 
![image](https://github.com/user-attachments/assets/04e754a5-4a5f-4e85-998f-210eeff4f672)

##1.2 Business Goals
1	Support Initiative	As a member of a support group, we aim to set up an online support system to improve emotional support and provide a sense of community and anonymity to those taking part and seeking help.
2	Community Engagement	The online community allows individuals who feels lonely or socially isolated to connect with others experiencing similar challenges and share coping strategies.
3	Content Optimization	By understanding user needs, preferences, and behaviours of the R/foreveralone community, we can optimize the platform's content to better meet their expectations. 
4	Positive Environment	To create a positive and supportive online environment that fosters a strong sense of community and empowers users to effectively address their challenges. 
5	Goal Measurement	As a measurement of our goal, we hope to see an increase in positive sentiment expressed by users' post by 20%.

##1.3 Busines Objectives
Depression Prediction	Determine the likelihood of depression in users based on their demographic and behavioural attributes

##1.4 Dataset
Title:The Demographic /r/ForeverAlone Dataset
Description:	Last year a redditor created a survey to collect demographic data on the subreddit /r/ForeverAlone. Since then they have deleted their account but they left behind their data set.
URL:	https://www.kaggle.com/datasets/kingburrito666/the-demographic-rforeveralone-dataset?resource=download

## 2.Work Accomplished

### Data Preparation
The below are the data preprocessing steps I completed prior to analysis:
1. Checking for outliers
![image](https://github.com/user-attachments/assets/12f1b4b6-8a99-4f67-a9dc-cb745862a60d)
![image](https://github.com/user-attachments/assets/3d1b5954-ae31-42d9-9ca5-6e55ca34243c)
There is a concentration between age 20-25.
Observed that there are outliers for number of friends in the 400+ and 600+ region 
2.Handling Missing Values - There are two columns (‘job_title’ and ‘improve_yourself_how’) with missing values. 
Performed Fillna. Verified No missing values
3. Removing Special characters - Columns with special characters identified
4. Adding new columns - To categorize sensitive data such as age and income.
5.Dataset transformation - Transform columns (virgin, prostitution_legal,pay_for_sex,social_fear,depressed,attempt_sucide)  to Boolean for modelling purposes
6.Exploratory Data Analysis - In accordance with the results of the below we understand that
![image](https://github.com/user-attachments/assets/81d17dc8-d05e-43cf-b8bd-877d147e6c18)
Histogram & Bar chart – Majority of the users are young (Gen Z & Millennial) with no income
![image](https://github.com/user-attachments/assets/f172db6a-28d5-43e2-8c29-392d732ecc41)
Income and Age: There's a clear trend where higher income categories correspond to older median ages, possibly indicating more experience or advanced career stages.
Income and Education: Higher educational levels are associated with higher income categories. There's a clear clustering of higher income individuals in educational levels beyond a bachelor’s degree.
These visualizations provide insights into how age, income, and education level are interrelated, with higher income often correlating with older age and higher educational attainment.
![image](https://github.com/user-attachments/assets/7bdb0056-e554-4bc1-af1e-dbef4ba32bed)
Majority of the users are Caucasian at 72.1%, Asian 11.5% and Hispanic 6.8%
7. Further Data Cleaning 

### Modelling
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum neque eget nunc mattis eu sollicitudin enim tincidunt. Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit. Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum. In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

### Evaluation
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum neque eget nunc mattis eu sollicitudin enim tincidunt. Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit. Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum. In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

## Recommendation and Analysis
Explain the analysis and recommendations

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum neque eget nunc mattis eu sollicitudin enim tincidunt. Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit. Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum. In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

## AI Ethics
Discuss the potential data science ethics issues (privacy, fairness, accuracy, accountability, transparency) in your project. 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum neque eget nunc mattis eu sollicitudin enim tincidunt. Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit. Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum. In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

## Source Codes and Datasets
Upload your model files and dataset into a GitHub repo and add the link here. 
ITD214 Project Code - https://github.com/Kenchency/ITD214_Proj
