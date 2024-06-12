
# HR_Analytics

### About Practice Problem: HR Analytics"
HR analytics is revolutionizing the way human resources departments operate, leading to higher efficiency and better results overall. Human resources has been using analytics for years. However, the collection, processing, and analysis of data have been largely manual, and given the nature of human resources dynamics and HR KPIs, the approach has been constraining HR. Therefore, it is surprising that HR departments woke up to the utility of machine learning so late in the game. Here is an opportunity to try predictive analytics in identifying the employees most likely to get promoted.

**Data Collection: Analytics vidya:** https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1/

### Problem Statement: 
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

- They first identify a set of employees based on recommendations/ past performance
- Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
- At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion.
  
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 

They have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

 

### Dataset Description:
| Variable	| Definition |
|--|--|
| employee_id	| Unique ID for employee | 
| department	| Department of employee |
| region	| Region of employment (unordered) |
| education |	Education Level |
| gender | Gender of Employee |
| recruitment_channel	| Channel of recruitment for employee |
| no_of_trainings	| no of other trainings completed in previous year on soft skills, technical skills etc. |
| age	| Age of Employee |
| previous_year_rating | Employee Rating for the previous year |
| length_of_service	| Length of service in years |
| KPIs_met >80%	| if Percent of KPIs(Key performance Indicators) >80% then 1 else 0 |
| awards_won?	 | if awards won during previous year then 1 else 0 |
| avg_training_score	| Average score in current training evaluations |
| is_promoted	| (Target) Recommended for promotion |
 
### Evaluation Metric:
The evaluation metric for this competition is F1 Score.

### Public and Private Split:
Test data is further randomly divided into Public (40%) and Private (60%) data.

- Your initial responses will be checked and scored on the Public data.
- The final rankings would be based on your private score which will be published once the competition is over.

### Dependencies:
Python 3.x Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter.
