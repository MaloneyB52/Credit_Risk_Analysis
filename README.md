# Credit_Risk_Analysis
NO USAEBLE MODEL USING RESAMPLING/OVERSAMPLING WAS SUFFICIENT FOR THIS TASK OF PREDICTING LOAN DEFAULT (IE BAD LOANS)...

1) Naive Resampling: PRECISION WAS ONLY At 0.01, with recall of only 0.62, and the F1, or measure of accuracy, was only 0.02 (remember that highest rating is 1, lowest is zero). 
2) SMOTE Oversampling: Similar results emerged with a SMOTE model. Precision was 0.01, Recall , in laymen's terms "sensitivity", was better at .65 but F1 remained at 0.01\
3) Combination sampling only moved the needle on recall slightly( 0.70), but precision and F1 was still lacking

OVERALL: Models listed above were not predictive enough to recommend use


ENSEMBLE RESULTS

Random Forest Classifier was also insufficient : Precision= 0.04. A mere 4% accuracy rate 
                                                  Recall= 0.67 (not accurate enough to risk money on)
                                                  F1= 0.07 likely drawn down 
  
  
  NOTE: adding AdaBoost boosted numbers (precision 0.09, Recall 0.92, F1 .16) No model tested is recommended for financial decisions
