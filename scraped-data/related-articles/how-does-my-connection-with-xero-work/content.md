## How does my connection with Xero work?  
If you haven’t already, connect your Xero account to your Wise account. Once you’ve connected, you can manage the following from your _Connection settings_:

  *  **Import bills to Wise**

  *  **Automatically mark bills as paid in Xero**

  *  **Bank feeds sync**

  *  **Allow attachments to be pushed to Xero**

  *  **Advanced settings**




 ****

###  **Fees**

These feature are available as part of your Wise Business account at no extra cost, but after August 1, 2023, Xero will apply a 0.1% fee of the transfer value for international transfers and 0.2% fee of transfer value for domestic transfers. Bank feeds and attachments syncing will continue to be free.

###  **Import bills to Wise**

Turn this on to see your unpaid bills in real time and pay them seamlessly from **_Bills_**. 

We won't import any bills you mark as paid in Xero. Note that this means if you have paid a bill through another provider and haven’t marked it as paid in Xero, it will still be visible in your Bills page on Wise.

This is only available for business in the UK at the moment. 

### **Automatically mark bills as paid in Xero**

Turn this on and when you pay a bill through your Bills page on Wise, we’ll automatically mark it as paid for you in Xero. Check out our bill payment example below.

We can’t mark your bills as paid if your Xero plan doesn’t support multicurrency. _How to turn on multicurrency in Xero_.

###  **Bank feeds sync**

Turn this on to see a list of your Wise transactions in Xero. Check which Wise currency balances you connected to which Xero bank accounts in **Advanced settings**.

We automatically sync every 4 hours, but you can manually sync anytime, just go to **Sync options and status** from your Xero connection settings and click on **Sync now**. 

### **Allow attachments to be pushed to Xero**

Turn this on to automatically push to Xero any receipt file you have attached to a Wise transaction. These will be stored in your Draft Bills or Draft Invoices in Xero. You must have ‘Bank feeds sync’ turned on to use this feature.

###  **Advanced settings**

 **Connected bank accounts**

If you have ‘Bank feeds sync’ turned on, we’ll sync only with the Xero bank accounts that you select here.

If you have ‘Import bills to Wise’ and ‘Automatically mark bills as paid in Xero’ turned on, we’ll mark your bills as paid in the Xero bank accounts that you select here.

We recommend you select which accounts to connect. If you skipped this step during setup, we’ll search for a corresponding Wise account before recording a transaction to Xero. If we don’t find one, we won’t be able to sync any bank feeds or record bill payments to Xero.

###  **Example bill payment**

In this example, your bill ‘ABC123’ in the amount of £500 has been paid to ‘Supplier 1’ using the Bill pay feature on Wise, and you funded the bill with your Wise GBP account balance. 

Because you connected your Wise GBP account to your Xero bank account named ‘Wise - GBP’ from your _Advanced settings_, the bill payment transaction gets recorded in that account.

And your ‘ABC123’ bill will be marked as paid. 

### **Why was a new clearing account added? What is this?**

We’ll automatically create these clearing accounts in your Chart of Accounts for the following reasons:

  1.  **‘Expenses (Wise)’** : If you choose an external payment method, we’re not always able to retrieve information about the bank account that is funding a payment, for example a non-Wise card payment or bank payment. If this occurs, the unidentified transaction will be recorded in ‘Expenses (Wise)’.

  2. ‘ **Cross currency clearing account (Wise)** ’: To help you keep your books tidy, all transactions that include a currency exchange will be revalued to your base currency. Note that this only applies where neither of the currencies being exchanged are your base currency. We’ll record these transactions in ‘Cross currency clearing account (Wise)’ in two parts. First, a transfer from the source currency to your Xero base currency. Second, a transfer from your Xero base currency to your target currency.




Here’s an example:

Your Xero base currency is GBP and you choose to fund a USD (target) payment with your EUR (source) Wise balance. 

  * We’ll record an EUR to GBP Transfer to ‘Wise-service’ with a Reference: “ _This transfer was reported using a clearing account to allow you to reconcile multiple currencies through your base currency._ ”




  * We’ll then record a GBP to USD Transfer to ‘Payment: [Supplier name]’ with a reference.




###  **How will fees be recorded?**

Any Wise fee will be entered automatically as a separate Expense transaction to ‘Wise-service’ in a Bank Account that we’ll create for you called ‘ **Bank charges (Wise)** ’ including a Reference — you can find this in your Chart of Accounts.