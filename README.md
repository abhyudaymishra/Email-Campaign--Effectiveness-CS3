# Email-Campaign--Effectiveness-CS3


![1-Signatures-blog](https://user-images.githubusercontent.com/122104510/229057222-1ad282d6-ef99-4a9b-85a4-093e84729ca6.gif)




**Problem Statement and Project Description**

Most of the small to medium business owners are making effective use of Gmail-based Email marketing Strategies for offline targeting of converting their prospective customers into leads so that they stay with them in business. The main objective is to create a machine learning model to characterize the mail and track the mail that is ignored; read; acknowledged by the reader. Data columns are self-explanatory.

Email marketing is a technique used by businesses to keep their customers informed about their new products, updates, and important notices through email. It helps in building relationships with leads, new and past customers by allowing businesses to communicate directly with them in their inbox at their convenience. However, sometimes emails are ignored due to various reasons like improper structure, too many images or links, complex vocabulary or length. In this project, we aim to develop machine learning models that can predict if an email will be ignored, read or acknowledged, and identify the important features that prevent an email from being ignored.


💾**Project Files Description**

This project contains one executable file, a technical Summary document.

**Executable Files**

1.Abhyuday-Email-Campaign--Effetiveness-CS-3 - Google Collab notebook containing data summary, exploration, visualisations and modeling,containg model hyperparameter tuning, model performance, evaluation and conclusion.

2.Summaryemail.pdf- Includes the Summary about the project.

**📈 Exploratory Data Analysis**

1.Despite having a very modest number of emails, campaign 1's emails had a far higher open rate than the rest.only 1% of emails from email campaign type 2 are acknowledged, while the majority of emails are marked as ignored.
![download (1)](https://user-images.githubusercontent.com/122104510/229045106-2f85ae12-70b1-4137-a667-577d1464796f.png)


2. we created distribution plots for Total Links, Total Images, and Total Past Communications. From the current analysis, it can be observed that the distribution of Word Count is similar to that of Total Past Communications and follows a normal distribution. However, the distributions for Total Links and Total Images are positively skewed, indicating the presence of extreme values or outliers in the data.
![download](https://user-images.githubusercontent.com/122104510/229045278-4fbbd040-f132-436c-85aa-f627e2c00f15.png)


📈 **Results**

* Based on the evaluation results, we can conclude that the XGBoost model with SMOTE data and feature selection performed the best, with an accuracy of 0.80 on the test data. This model had higher precision, recall, and F1-scores for all classes compared to other models. The XGBoost model with random undersampled data also performed reasonably well with an accuracy of 0.57, but the performance was much lower for the minority classes.

**📜 Credits**

**Abhyuday Mishra**

Organic Growth| Data Analyst| Business Analyst




[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhyuday-mishra)


