**# LOAN AMOUNT PREDICTION PROJECT #**



This project is about predicting LOAN AMOUNT with a given set of features like GENDER,AGE,MONTHLY INCOME,SAVINGS,MONTHLY EMI,HAS LOAN,LOAN STATUS, CIBIL SCORE, EXISTING EMI,LOAN TERM

THE TOOL USED HERE IS KNIME

Process of operations



1. Loading the data using CSV READER NODE
2. viewing the columns if there is any missing values using STATISTICS NODE
3. Filling the missing values with MISSING VALUES NODE
4. Selecting the required columns using COLUMN FILTER NODE
5. Type casting the columns using COLUMN AUTO TYPE CAST NODE
6. Converting categorical columns to numbers using ONE TO MANY NODE
7. Splitting the data to train and test using TABLE PARTIONER NODE
8. Training the training set with RANDOM FOREST LEARNER NODE
9. Testing the test data using RANDOM FOREST PREDICTOR NODE.
10.Evaluating the test results using NUMERIC SCORER NODE.
11. Visualising two features using SCATTERPLOT NODE.
12. Saving the output results using CSV WRITER NODE.


THE FOLDER CONTAINS INPUT DATASET,KNIME WORKFLOW,SCATTER PLOT CHART,OUTPUT PREDICTIONS TABLE.