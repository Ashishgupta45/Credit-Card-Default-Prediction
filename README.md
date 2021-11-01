# Credit-Card-Default-Prediction
This project is aimed at predicting the case of customers default payments in Taiwan. here we have 30,000 rows and 25 columns.
Predicting potential credit default accounts in advance is challenging. Traditional statistical techniques typically cannot handle large amounts of data and the dynamic nature of fraud and humans. To tackle this problem, recent research has focused on artificial and computational intelligence-based approaches. In this work, we present and validate a heuristic approach to mine potential default accounts in advance where a risk probability is precomputed from all previous data and the risk probability for recent transactions are computed as soon, they happen. Beside our heuristic approach, we also apply a recently proposed machine learning approach that has not been applied previously on our targeted dataset. As a result, we find that these applied approaches outperform existing state-of-the-art approaches.
That's it! We reached the end of our exercise.
Starting with loading the data so far, we have done EDA, null values treatment, In the EDA I was trying to show the best way the visuals and answering all questions need to show.
1) Using a Logistic Regression classifier, we can predict with 60.33% accuracy, whether a customer is likely to default next month.
2) Using a Stochastic Gradient Descent classifier, we can predict with 53.07% accuracy, whether a customer is likely to default next month.
3) Using a Random Forest classifier, we can predict with 81.68% accuracy, whether a customer is likely to default next month.
4) Using a K-Nearest Neighbour classifier, we can predict with 77.83% accuracy, whether a customer is likely to default next month.
5) Using a Support Vector Machine classifier, we can predict with 94.43% accuracy, whether a customer is likely to default next month.

The strongest predictors of default are the PAY_X (ie the repayment status in previous months), the LIMIT_BAL & the PAY_AMTX (amount paid in previous months).
We found that using Random Forest classifier and Support Vector Machine classifier are better.
Demographics: we see that being Female, more educated, Single and between 30-40years old means a customer is more likely to make payments on time.
