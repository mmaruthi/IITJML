# Assignment 1

1) Evaluation Metrics :

Log Loss :
Log Loss is the log applied on a likelihood function.
Likelihood precisely means - How much the predictions actually occur in similar to the actual outcomes.
Lower log loss means the predictions are better .

Cohen Kappa :
It compares the observed accuracy with the measured accuracy. This is useful to evaluate when there are multiple classifiers.
The coefficient how much the classifiers are inter relatable.
Coefficient k = (P0 - Pe)/1-pe
where p0 is the observed agreement and pe is the hypothetical agreement.

2) Accuracies 

Total Accuracy : 75%

Class 0 Accuracy : 67%

Class 1 Accuracy : 88%

Class 2 Accuracy : 72%

Class 3 Accuracy : 77%

Confusion Matrix:

            0  1  2  3
            
        0   33 8  4  4
        
        1   1 32  3  0
        
        2   3  2 29  6 
        
        3   2  3  3  27 
        
 Precision :
 
 Class 0 : 0.84
 
 Class 1 : 0.71
 
 Class 2 : 0.74
 
 Class 3 : 0.72
 
 Recall:
 
 Class 0 : 0.67
 
 Class 1 : 0.68
 
 Class 2 : 0.72
 
 Class 3 : 0.77
 
 
 Macro Average Precision: 0.75
 
 Macro Average Recall : 0.76 
 
 
 Weighted Average Precision : 0.76 
 
 Weighted Average call : 0.75 
 
 F-Score:
 
 Class 0 : 75 
 
 Class 1 : 79 
 
 Class 2 : 73 
 
 Class 3 : 75 
 
           Type 1 and Type 2 Error :
           
 Class 0 : 5.40 , 32.65
 
 Class 1 : 10.48 , 11.11
 
 Class 2 : 8.33, 27.50 
 
 Class 3 : 8.0, 22.85 
 
 
 Manual values are same as SK learn values.


