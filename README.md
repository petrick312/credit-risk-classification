# CryptoClustering
Module 20 challenge - Credit Risk

## Instructions
The instructions for this Challenge are divided into the following subsections:<br>
    Split the Data into Training and Testing Sets<br>
    Create a Logistic Regression Model with the Original Data<br>
    Write a Credit Risk Analysis Report<br>

## Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:<br>
  - Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.<br>
  - Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.v
  - Split the data into training and testing datasets by using train_test_split.<br>

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:<br>
    Fit a logistic regression model by using the training data (X_train and y_train).   <br>
    Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.<br>
    Evaluate the model’s performance by doing the following:<br>
        Generate a confusion matrix.<br>
        Print the classification report.<br>
    Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels? <br>

## Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.<br>
Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:<br>
    An overview of the analysis: Explain the purpose of this analysis.<br>
    The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.<br>
    A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.<br>


## Requirements
### Split the Data into Training and Testing Sets (30 points)
To receive all points, you must:<br>
    Read the lending_data.csv data from the Resources folder into a Pandas DataFrame. (5 points)<br>
    Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. (10 points)<br>
    Split the data into training and testing datasets by using train_test_split. (15 points)<br>

### Create a Logistic Regression Model (30 points)
To receive all points, you must:<br>
    Fit a logistic regression model by using the training data (X_train and y_train). (10 points)<br>
    Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model. (5 points)<br>
    Evaluate the model’s performance by doing the following:<br>
        Generate a confusion matrix. (5 points)<br>
        Generate a classification report. (5 points)<br>
        Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels? (5 points)<br>

### Write a Credit Risk Analysis Report (20 points)
To receive all points, you must:<br>
    Provide an overview that explains the purpose of this analysis. (5 points)<br>
    Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model. (5 points)<br>
    Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. (10 points)<br>

### Coding Conventions and Formatting (10 points)
To receive all points, you must:<br>
    Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants. (3 points)<br>
    Name functions and variables with lowercase characters, with words separated by underscores. (2 points)<br>
    Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. (3 points)<br>
    Use concise logic and creative engineering where possible. (2 points)<br>

### Code Comments (10 points)
To receive all points, your code must:<br>
    Be well commented with concise, relevant notes that other developers can understand. (10 points)<br>