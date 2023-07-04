## How does my connection with QuickBooks work?  
If you haven’t already, connect your QuickBooks Online account to your Wise account. Once you’ve connected, you can manage the following from your connection settings:

  *  **Import bills to Wise**

  *  **Automatically mark bills as paid in QuickBooks**

  *  **Advanced settings**




QuickBooks also allows you to sync your **Wise Bank feeds** , but that part of the connection is managed by QuickBooks. Follow these steps to see a list of transactions for each of your Wise currency accounts within your QuickBooks Banking Transactions.

###  **Eligibility**

To ‘Automatically mark bills as paid in QuickBooks’ your QuickBooks plan must have the multicurrency feature turned on. _How to turn on multicurrency in QuickBooks_.

###  **Import bills to Wise**

Turn this on to see your unpaid bills in real time and pay them seamlessly from your Bills page. 

We won't import any bills you mark as paid in QuickBooks. Note that this means if you have paid a bill through another provider and haven’t marked it as paid in QuickBooks, it will still be visible in your Bills page on Wise.

###  **Automatically mark bills as paid in QuickBooks**

Turn this on and when you pay a bill through your Bills page on Wise, we’ll automatically mark it as paid for you in QuickBooks. Fees will be recorded as Bank Charges. Check out our bill payment example below.

###  **Advanced settings**

 **Connected bank accounts**

If you have ‘Import bills to Wise’ and ‘Automatically mark bills as paid in QuickBooks’ turned on, we’ll mark your bills as paid in the QuickBooks bank accounts that you select here.

We recommend you select which accounts to connect. If you skipped this step during setup, we’ll search for a corresponding Wise account in your QuickBooks chart of accounts before recording a bill payment. If we don’t find one, we won’t be able record any bill payments to QuickBooks.

### **Example bill payment**

In this example, your bill ‘ABC456’ in the amount of €500 has been paid to ‘Vendor 1’ using the Bill pay feature on Wise, and you funded the bill with your Wise EUR account balance. 

Because you connected your Wise EUR account to your QBO bank register named ‘Wise - EUR’ from your Advanced settings, the bill payment transaction gets recorded in that register.

You’ll see a ‘Bill Payment (Check)’ in your Expenses with the amount.

And your ‘ABC456’ Bill will be marked as paid.

###  **What if there’s a fee associated with my payment?**

Any Wise fee will be entered automatically as a separate Expense transaction with the category ‘Wise bank charges’ and a Memo ‘Wise fee’.

 ****

 **Why am I seeing a clearing account? What is this?**

A clearing account will be automatically created for one of these three reasons.

  1. If you choose an external payment method, we’re not always able to retrieve information about the bank account that is funding a payment, for example a non-Wise card or bank payment. This applies for both incoming and outgoing payments. 

  2. QuickBooks requires all transactions that include a currency exchange to be converted to your Home currency to help you keep your books tidy. 




For example, if your Home currency is USD and you choose to fund a GBP bill payment with your EUR Wise balance, QuickBooks still requires us to record the transaction in USD. This means we’ll record a EUR to USD Transfer in addition to a USD to GBP Expense in your ‘Wise clearing from USD’ Bank Register including a Memo describing this. Learn more about QuickBooks home currency adjustments.

In each of these instances, we’ll record the transaction in a ‘Wise clearing from [currency]’ or ‘Wise clearing to [currency]’ Bank Register depending on whether it was an incoming or outgoing conversion.