# Financials
## Summary
Here are our basic requirements
* We need to create a Customer.
* We need to create an Invoice.
* We need to create a Credit.
* We need to view a Customer Statement (A listing of all the invoices and credits in date order) 
* Finally, we want to see a Customer's Balance (Total invoice value minus total credit value)

## The Technology
* You'll need to decide which language to program with
* You'll need some form of data store

## Further Information
## Customer Records
We deal with businesses so we want to record
* Company Name
* Account Code (in the format AAANNN where A is an Alphanumeric and N is a Numeric eg ABC001)
* Contact Email
## Transaction : Invoices and Credits
These will be divided into:
#### Main Information
* ID Number - must be unique
* Date - the date we create the Transaction
* Due - the date the Transaction must be paid by.
* Customer - the customer who is the Transaction is for
#### Item Information
* Qty
* Product Name
* Unit Price
#### Totals
* Total value of Transaction
## Statements
* Statements are Customer-specific
* Report column headings are
    * Date
    * Type (Invoice / Credit)
    * Value (Invoices ADD to the balance, Credits REDUCE the balance)
## Balances
* A report showing what each customer owes
* Report column headings are
    * Customer
    * Balance Owed
## Extra Points
Here are some further challenges if you like.
* Design a PDF format for the Invoice and Credit.
* Design a Customer statement in PDF (or Spreadsheet) format.
* Send a PDF to the customer by Email.

## Extend the Project
* Consider adding Sales Tax to the Line Items. 
* Consider including Payments (Money received) and Refunds.
* Remember that the Statement must also include the Payments and Refunds to give an accurate Customer balance.


## Some further thoughts
There are no right or wrong answers here, just things to think about as you work through this challenge.
* Is it better to store
* If you are developing using OOP - would a class called Transaction be a good parent for Invoice and Credit? Would it also work well for Payments and Refunds (if you have added these)?
* Does having a Transaction parent class force your Invoice/Credit or Payment/Refund classes to have a method that doesn't make sense?
* If the Invoice/Credit or Payment/Refund classes are forced to have a method that doesn't make sense - how does this break the SOLID principles?