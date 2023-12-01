# Credit_risk_resapling_

In this work study there is a clear analysis for the measures of this model being used in the feild, one the analysis came back strong and showed us we can use the model data in realworld activites, Two.) You can clearly see the subltle changes that may occure when running a dynamic model and the changes that my come into correction from the data.
>>/
>>.. The data has value in it's core of reception in the ,models preformance and


>>-#balanced_accuracy:        loan_size  interest_rate  borrower_income  debt_to_income  \
31866    19600.0         11.462            88500        0.661017   
34057    12600.0          8.501            60600        0.504950   
42929     9400.0          7.111            47500        0.368421   
62841     9000.0          6.959            46100        0.349241   
61095     6500.0          5.896            36100        0.168975   
...          ...            ...              ...             ...   
75650    17600.0         10.617            80500        0.627329   
15311     8100.0          6.583            42600        0.295775   
21011     6700.0          5.980            36900        0.186992   
12369     9000.0          6.953            46000        0.347826   
19690    11000.0          7.806            54100        0.445471   

       num_of_accounts  derogatory_marks  total_debt  
31866               13                 2       58500  
34057                6                 1       30600  
42929                3                 0       17500  
62841                3                 0       16100  
61095                1                 0        6100  
...                ...               ...         ...  
75650               11                 2       50500  
15311                2                 0       12600  
21011                1                 0        6900  
12369                3                 0       16000  
19690                5                 1       24100  

[19384 rows x 7 columns]

other variences of the data a work in the project is
in its #classification report
- classification Report:
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18793
           1       0.82      0.88      0.85       591

    accuracy                           0.99     19384
   macro avg       0.91      0.94      0.92     19384
weighted avg       0.99      0.99      0.99     19384
