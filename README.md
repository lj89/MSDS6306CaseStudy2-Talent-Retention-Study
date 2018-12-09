## Talent Retention Study

DDSAnalytics is an analytics company that specializes in talent management solutions for Fortune 1000 companies. Talent management is defined as the iterative process of developing and retaining employees. It may include workforce planning, employee training programs, identifying high-potential employees and reducing/preventing voluntary employee turnover (attrition). To gain a competitive edge over its competition, DDSAnalytics is planning to leverage data science for talent management. The executive leadership has identified predicting employee turnover as its first application of data science for talent management. Before the business green lights the project, they have tasked your data science team to conduct an analysis of existing employee data. 

### Objectives:

Your team has been given a dataset (CaseStudy2-data.csv) to conduct exploratory data analysis (EDA) to determine factors that lead to attrition. 

1. Identify (at least) the top three factors that contribute to turnover.

2. Provide any other interesting jobrole specific trends and observations from your analysis.

3. Build a model to predict attrition.

### Deliverables:
1. A model that will attain at least 60% overall accuracy for the training and the validation set

2. One prediction file, “Case2PredictionsXXXX.csv”, ordered by ID where 'XXXX' with all team members'last name

3. RMarkdown file with R code that does the following:

    a. fits the model on only the training set  ... you must call this dataframe dfTrain and it must have the exact format of the csv file given to you.  

    b. uses that model to predict the labels of the test set. you must call this dataframe dfVal and it must have the exact format of the csv file given to you.  

    c. make a dataframe with only the ids in one column and the labels in the second column .. you must call this dataframe 
dfPreds.

    d. prints those ids and predictions to a csv file, to my working directory using write.csv


4. Individual presentation on YouTube with link to be included in RMarkdown file

5. Submit Link to GitHub repo to 2DS
