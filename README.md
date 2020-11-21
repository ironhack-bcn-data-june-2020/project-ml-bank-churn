
# Module 3 - Project 2 (ML) - Churn Analysis


*Victor, Susanna, Vero & Anna*

*Data Analytics-Part Time Course | Barcelona June 2020*



## Content
- [Project Description and Workflow](#Project_Description_and_Workflow)
- [Organization](#Organization)
- [Links](#Links)



## Project Description and Workflow


### Description

This project is to practice Machine Learning.

**Dataset**
The dataset chosen is data of 10k clients from Bank - Direct [Link to kaggle](https://www.kaggle.com/adammaus/predicting-churn-for-bank-customers). Note: the dataset contained in this repository (the one you must use) differs from the original kaggle dataset.

**Metadata**
 
    - RowNumber: corresponds to the record (row) number and has no effect on the output. This column will be removed.
    - CustomerId: contains random values and has no effect on customer leaving the bank. This column will be removed.
    - Surname: the surname of a customer has no impact on their decision to leave the bank. This column will be removed.
    - CreditScore: can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
    - Geography: a customer’s location can affect their decision to leave the bank. We’ll keep this column.
    - Gender: it’s interesting to explore whether gender plays a role in a customer leaving the bank. We’ll include this column, too.
    - Age: this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
    - Tenure: refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
    - Balance: also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
    - NumOfProducts: refers to the number of products that a customer has purchased through the bank.
    - HasCrCard: denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank. (0=No,1=Yes)
    - IsActiveMember: active customers are less likely to leave the bank, so we’ll keep this. (0=No,1=Yes)
    - EstimatedSalary: as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
    - Exited: whether or not the customer left the bank. This is what we have to predict. (0=No,1=Yes)


**Goal**

Classify if a customer from a Bank is going to churn or not. *What if would be possible to predict if a customer will leave our company?*




### Workflow

1. Environment

2. Data Preparation
    
    2.1 Data Wrangling
    
        - Explore Data
        - Clean Data
        - Transform Data
    
    2.2 Feature Selection  
    
        - Delete not useful variables
        - Correlation      
    
    2.3 Feature Engineering
    
        - Log transformation
        - MinMaxScaler
        - Creat new columns


3. Select From Model (Classification Models)
        
        - LogisticRegression
        - SVM
        - KNeighborsClassifier
        - DecisionTreeClassifier
        - LinearDiscriminantAnalysis
        - GaussianNB
        - RandomForestClassifier
        - MLPClassifier

4. Train Models (Machine Learning Classification Models)

        - LogisticRegression
        - SVM
        - RFC
        - NeuralNetworks
   
5. Ensemble Methods

        - XGBoost
        - Stacking



## Organization

**Main Organization of the project thought Trello board:**

1. Organize a Project GitHub board with main tasks and timings
2. Create a repository including a .gitignore file and a Readme.md
3. Data Preparation
4. Modeling
5. Tuning
6. Write conclusions
7. Complete Readme.md


**Inside this repository you can find:**

CSVs raw data:

    - Churn_Modelling.csv

CSVs clean data:

    - Churn_Clean.csv
    - Churn_Norm.csv
    - Churn_norm_LDA.csv
    - Churn_LDA.csv

Jupyter notebook of the data wrangling:

    - DataPreparation.ipynb
    - SelectFromModel.ipynb
    - PCA-LDA.ipynb
    - ML_logistic_regression_regularized_models.ipynb
    - ML_RFC.ipynb
    - MODEL_SVM.ipynb
    - ML_MLPC.ipynb
    - EnsembleLearning.ipynb


Other:

    - Gitignore.txt
    - README.md



## Links 

[Repository](https://github.com/ironhack-bcn-data-june-2020/project-ml-bank-churn/tree/main)
[PowerPoint Presentation](https://docs.google.com/presentation/d/10QSgmnRCWzjXK7wGMTpAvt8cKHXmIogWoy7x_48_Qbc/edit#slide=id.p)
[GitHub Project](https://github.com/ironhack-bcn-data-june-2020/project-ml-bank-churn/projects/1)

