# CancerDrugAnalysis
This study was a part of the small project titled "Integration and analysis of cancer drug response data" under Dr. Debarka Sengupta.
It was done in two parts:
1) Understanding the Symbolic Regression using a small dataset [data.txt](data.txt) and storing the following things in a dataframe(Extracted_data.csv): 
- Sample id
- Predicted label (+1,-1)
- Predicted value returned by the equation 
also reporting the following:
- Overall AUC ROC
- Sensitivity and Specificity
- F1 score
The code can be seen in the Copy_of_Ip.ipynb file.
2) The main task of Cancer drug Analysis
The goal was to predict the viability of Combinational drugs for cancer treatment. We worked on the cancer drug response dataset (An Unbiased Oncology Compound Screen to Identify Novel Combination Strategies | Molecular Cancer Therapeutics). 
It was a regression task for which we had to use multiple strategies such as the classical regression pipeline as well as the more recent, symbolic regression. We had to use our designed modules in gplearn library, mostly dealing with genetic programming. This particular task differsfrom other ML paradigms as the metric used are RMSE, MSE & R2 scores.
