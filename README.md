**PROBLEM STATEMENT**  
There is concern about credit card payment delays at FinanKu, which could harm the business. Therefore, individuals who are likely to experience payment delays should be predicted more quickly to determine appropriate strategies for addressing future conditions.

**OBJECTIVE**  
To develop a model that can predict at least 60% of customers who will experience credit card payment delays [Accuracy & Recall above 60%].

**AVAILABLE VARIABLES**  
The dataset contains several available data points:

1. Customer ID: Unique customer identifier  
2. Branch: Customer's registered branch location  
3. City: Customer's registered city location  
4. Age: Customer's age during the observation period  
5. Avg. Annual Income/Month: Customer's average monthly income  
6. Balance (Q1-Q4): Customer's end-of-quarter balance  
7. Num of Products (Q1-Q4): Number of products held by the customer at the end of each quarter  
8. HasCrCard (Q1-Q4): Credit card ownership status of the customer at the end of each quarter  
9. Active Member (Q1-Q4): Customer's activity status  
10. Unpaid Tagging: Customer's default payment status

**EXPERIMENT**  
**Review Period:**  
- Customers are reviewed over the past year  
- Customers are reviewed over the past 6 months  

**Variable Adjustments:**  
- The balance is averaged over the review period and observed for changes from the beginning to the end of the review period.  
- The number of products owned is assessed based on the average, maximum, and minimum during the review period.  
- Customer activity status is assessed in monthly terms.
