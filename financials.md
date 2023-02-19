# Financials
## Summary
Here are our basic requirements
* We need to create an Invoice (to show our Customer owes us).
* We also must create a Credit as well.

We want the system to hold details of our Customers and Products too.

After we create an Invoice and Credit, we want to be able to view a report for a customer which lists the invoices and credits in date order

We need to see what the Customer's balance is too.

## Further Information
### Customer Records
We deal with businesses so we want to record
* Company Name
* Account Code (in the format AAANNN where A is an Alphanumeric and N is a Numeric eg ABC001)
* 

## Extra Points
Here are some further challenges if you like.
* Design a PDF format for the Invoice and Credit
* Send a PDF to the customer by Email

## Extend the Project
* Consider extending the system to also include Payments (Money received from a Customer) and Refunds (Money sent back to the Customer).
* Remember that the Statement must also include the Payments and Refunds to give an accurate Customer balance.


## Some further thoughts
There are no right or wrong answers here, just things to think about as you work through this challenge.
* If you are developing using OOP - would a class called Transaction be a good parent for Invoice and Credit?
* Does having a Transaction parent class force your Invoice or Credit class to have a method that doesn't make sense?
* If the Invoice/Credit classes are forced to have a method that doesn't make sense - how does this break the SOLID principles?