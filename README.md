# Data-project-Analysis on the loan data
After the quick analysis of the data sets, 
It shows a total sum of loan amount of 142,557,050 is granted for the reciepients whose income source is not verified. This can be an issue to be pointed. I have plotted a graph using this data in the image named "plot of sum of loan_not verified.JPG".

After performing regression analysis, between loan amount and home ownership. I have classified the value of home ownership into, the rent category is made as 0, own and mortgage is made 1 and then performed regression for the first 569 values using these categories.

Results found:
The significance F for the regression was found to be 0.00159459315512862. The P-value for Intercept was found to be 1.90257532297592E-117. The regression line is loan amount(y) = 11380.96+1918*ownership value.

Similarly, I also did the regression analysis using "The number of 30+ days past-due incidences of delinquency in the borrower's credit file for the past 2 years (delinq_2yrs)" with the loan amount. The significance F was found to be 3.3459118017224E-07. The regression line is loan amount(y) = 12417.8970628975-673.194748805412*delinq_2yrs.

Another regression analysis was performed between loan amount and "A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income(dti)." The significance F was found to be 3.37397642683175E-09. The regression line is loan amount(y)= 11509.722525368+58.245563255592*dti

The next regression is between loan amount and employment length. THe significance F was found to be 7.11321218755962E-88. The regression line is loan amount(y) = 10346.6568867142+373.20189958641*employment length.

Also, the grade division according to interest rate is
A-less than 8% interest rate
B-more than 9% interest rate
C-more than 13% interest rate 
D-more than 16% interest rate
E-more than 18% interest rate
F-more than 21% interest rate

Similarly, many other insights can be obtained from the data. The classification of data and logistic regression needs to be computed to find the relations between the attributes of the data. Due to the time restriction I could not perform them. However a simple plot is attached here in doc.
