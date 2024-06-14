# Loan Approval Prediction 📊

# Background 🔍
LOANS are a major requirement of the modern world. By this, banks get a major part of the total profit. It is beneficial for students to manage their education and living expenses, and for people to buy any kind of luxury like houses, cars, etc. But when it comes to deciding whether the applicant’s profile is relevant to be granted a loan or not. Banks have to look after many aspects.	We will develop one such model that can predict whether a person will get his/her loan approved or not by using some of the applicant's background information like the applicant’s gender, marital status, income, etc.

# Dataset Information 🔍
[Download Dataset from here](https://www.kaggle.com/datasets/armanjitsingh/loan-approval-prediction-data)

### The Dataset Contains 13 features

<b>1. Loan_ID: </b> A unique identifier for each loan application. It doesn't contribute to the decision-making process but can be useful for record-keeping

<b>2. Gender: </b> Lending institutions might consider gender as a factor in loan approval, depending on historical data or institutional policies. For instance, if there's evidence of gender-based discrimination, it could affect loan approval.

<b>3. Married: </b> Married individuals may be perceived as more financially stable and responsible. Lenders might be more inclined to approve loans for married applicants.

<b>4. Dependents: </b> The number of dependents could influence loan approval, as more dependents might mean higher financial responsibilities. Lenders may assess the applicant's ability to repay the loan considering their family size.

<b>5. Education: </b> The level of education might be a proxy for the applicant's earning potential and financial stability. Graduates may be perceived as having better job prospects and, consequently, higher repayment capabilities.

<b>6. Self-employed: </b> Self-employed individuals may face different income patterns compared to salaried individuals. Lenders might scrutinize the stability of self-employed applicants' income sources.

<b>7. ApplicantIncome: </b> Higher income generally indicates a better ability to repay a loan. However, extremely high or low incomes might be red flags. Lenders may set income thresholds for loan approval.

<b>8. CoapplicantIncome: </b> The income of the coapplicant can supplement the household income, affecting the overall repayment capacity. A higher coapplicant income may positively influence loan approval

<b>9. LoanAmount: </b> The amount of the loan applied for is crucial. Lenders will assess whether the requested loan amount aligns with the applicant's income and financial situation

<b>10. Loan_Amount_Term: </b> The term of the loan affects monthly repayment amounts. Shorter terms might indicate a quicker repayment ability, while longer terms might be associated with higher overall interest payments.

<b>11. Credit_History: </b> This is likely one of the most critical factors. A good credit history (1.0) is generally associated with a higher likelihood of loan approval. Lenders heavily rely on credit history to assess risk.

<b>12. PropertyArea: </b> The location of the property can influence loan approval. Urban areas might have different risk profiles than rural areas, and lenders may have specific criteria for different regions.

# Life Cycle of ML Project 🔍
<b>1. Data Collection</b>

Gather relevant data for model training. This may include historical loan data, customer information, credit scores, employment history, and other relevant features. Ensure that the data is representative and diverse

<b>2. Data Cleaning</b>

Clean the data to handle missing values, outliers, and inconsistencies. This step is crucial for the model's accuracy and generalization. We may need to impute missing values, standardize or normalize features, and deal with any data anomalies.

<b>3. Exploratory Data Analysis (EDA)</b> 

Conduct exploratory data analysis to understand the relationships between different variables, identify patterns, and gain insights. Visualization tools can be helpful in this phase.

<b>4. Feature Engineering</b>

Create new features or modify existing ones to improve the model's performance. This might involve transforming variables, creating interaction terms, or encoding categorical variables.

<b>5. Data Splitting</b>

Split the dataset into training and testing sets. The training set is used to train the model, and the testing set is used to evaluate its performance

<b>6. Model Selection</b>

Choose an appropriate machine learning algorithm for your problem. Common algorithms for loan approval prediction include logistic regression, decision trees, random forests, and support vector machines.

<b>7. Model Training</b>

Train the selected model using the training dataset. This involves feeding the algorithm the features and corresponding labels and letting it learn the patterns in the data.

<b>8. Model Evaluation</b>

Evaluate the model's performance on the testing dataset using appropriate metrics such as accuracy, precision, recall, and F1 score

# Machine Learning Models used in the Project 🔍
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. KNeighbors Classifier





