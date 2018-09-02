# predicting-default-risk
Predict who can default on bank loans
The Business Problem
You work for a small bank and are responsible for determining if customers are creditworthy to give a loan to. Your team typically gets 200 loan applications per week and approves them by hand.

Due to a financial scandal that hit a competitive bank last week, you suddenly have an influx of new people applying for loans for your bank instead of the other bank in your city. All of a sudden you have nearly 500 loan applications to process this week!

Your manager sees this new influx as a great opportunity and wants you to figure out how to process all of these loan applications within one week.

Fortunately for you, you just completed a course in classification modeling and know how to systematically evaluate the creditworthiness of these new loan applicants.

For this project, you will analyze the business problem using the Problem Solving Framework and provide a list of creditworthy customers to your manager in the next two days.

You have the following information to work with:

Data on all past applications
The list of customers that need to be processed in the next few days
Steps to Success
Step 1: Business and Data Understanding
Your project should include a description of the key business decisions that need to be made.

Step 2: Explore and Cleanup the Data
To properly build the model, and select predictor variables, you need to explore and cleanup your data.

Here are some guidelines to help you clean up the data:

Are any of your numerical data fields highly-correlated with each other? The correlation should be at least .70 to be considered “high”.
Are there any missing data for each of the data fields? Fields with a lot of missing data should be removed
Are there only a few values in a subset of your data field? Does the data field look very uniform (there is only one value for the entire field?). This is called “low variability” and you should remove fields that have low variability. Refer to the "Tips" section to find examples of data fields with low-variability.
Your clean data set should have 13 columns where the Average of Age Years should be 36 (rounded up)
Note: If you decide to impute any data field, for the sake of consistency in the data cleanup process, impute the data using the median of the entire data field.

Step 3. Train your Classification Models
You should choose 70% to create the Estimation set and 30% to create the Validation set. Set the Random Seed to 1 if you're using Alteryx.

Train your dataset using these models:

Logistic Regression
Decision Tree
Forest Model
Boosted Tree
Step 4. Writeup
Compare all of the models’ performance against each other. Decide on the best model and score your new customers.

Important: Your manager only cares about how accurate you can identify people who qualify and do not qualify for loans for this problem.

Write a brief report on how you came up with your classification model and write down how many of the new customers would qualify for a loan.
Review
Use the project rubric to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project.

Submission Template
Use the submission template at the bottom of this section to submit your project. After filling it out, save it as a PDF and submit the PDF in the next section. You may also include your Alteryx workflow if you'd like. If your submission does not meet specifications, having the workflow may help the review identify mistakes.

Workflow Template
Use the Alteryx workflow template to help quickly get started with the project. For the sake of the reviews consistency, you must use this Alteryx workflow.

Data
credit-data-training.xlsx - This file contains all credit approvals from your past loan applicants the bank has ever completed.

customers-to-score.xlsx - This is the new set of customers that you need to score on the classification model you will create.

Non Alteryx Software
For students using software other than Alteryx to create the classification models, make sure to format the data as follows and do not sort the data before you run it through your classification models. This allows you to get consistent results reviewers expect.

Variable	Data Type
Credit-Application-Result	String
Account-Balance	String
Duration-of-Credit-Month	Double
Payment-Status-of-Previous-Credit	String
Purpose	String
Credit-Amount	Double
Value-Savings-Stocks	String
Length-of-current-employment	String
Instalment-per-cent	Double
Guarantors	String
Duration-in-Current-address	Double
Most-valuable-available-asset	Double
Age-years	Double
Concurrent-Credits	String
Type-of-apartment	Double
No-of-Credits-at-this-Bank	String
Occupation	Double
No-of-dependents	Double
Telephone	Double
Foreign-Worker	Double
Project Checklist
This is here to make sure you know the concepts necessary to complete the project and that you know where to go find answers if you need help. If you do not feel confident in the topics addressed please review the course material or reach out on the forums, slack, or on a one on one!

Task List










We have received some feedback around the legitimacy of excluding the Telephone variable since it potentially could be useful to collect debts so could make you more creditworthy. We think this is fair but for the sake of this project please exclude Telephone from your data with the reasoning that there is no logical reason for including the variable.

Forums: https://discussions.udacity.com/c/nd008-bizand-classification-models/band-project-4
Slack: https://udacity-pand.slack.com
If you run into errors in Alteryx or unexpected results from a tool we have a guide to help you figure out what is going on.

Alteryx Debugging Guide:

https://docs.google.com/document/d/1ec7SiDCMAZAMjbPvL3aegPoL1PZznHarsxEZ4bjptdI/edit?usp=sharing

To Download Files below please right click on the link and select "Save Link As"

Supporting Materials
 Credit Data Training
 Customers to Score
 Alteryx Workflow Template
 Submission Template
 All Project Files
