# Predictive-Models-of-Apartment-Base-Rent-in-Germany

## MultipleLinearRegression.py
1. Ensure you have the dataset downloaded and pasted the correct file path in the pd.read_csv function under the import statements
2. Ensure you have tensorflow correctly installed on your computer
3.	To get the best results, directly run the file.
4.	To get the alternative results, comment codes of dropping N/A values on line 81, then uncomment codes of filling N/A values with means on line 85 and 88, finally run the file.
5.	No hyperparameter tuning is applicable.

## PrincipalComponentRegression.py
1. Ensure you have the dataset downloaded and pasted the correct file path in the pd.read_csv function under the import statements
2. Ensure you have tensorflow correctly installed on your computer
3.	To get the best results, directly run the file.
4.	To get the alternative results, comment codes of dropping N/A values on line 81, then uncomment codes of filling N/A values with means on line 85 and 88, finally run the file.
5.	To get the results of different number of components, set the it as various numbers.

## SupportVectorRegression.py
1. Ensure you have the dataset downloaded and pasted the correct file path in the pd.read_csv function under the import statements
2. Ensure you have tensorflow correctly installed on your computer
3.	To get the alternative results, comment codes of dropping N/A values on line 81, then uncomment codes of filling N/A values with means on line 85 and 88, finally run the file. (This is not the focus of SVR and not included in the report.)
4.	The results of different Cs on line 103 are automatically generated by the for loop from line 104 to 127.
5.	To get the results of different kernels, set the kernel as ‘rbf’ or ‘linear’ on line 109.
6.	To get the results of different epsilons, set the epsilon as 100, 200, etc. on line 109.

## NN model 3.py
1. Ensure you have the dataset downloaded and pasted the correct file path in the pd.read_csv function under the import statements
2. Ensure you have tensorflow correctly installed on your computer
3. If you would like to modify the code to test different hyperparameters:
      epoch number, batch size, validation split - line 105
      learning rate - 89
      network structure - 78 to 86
