About this spreadsheet:	
	BalanceForecast.xlsm
	Version:  1.1  (1/05/2011)
	Author:  bobbo33
	http://lifehacker.com/people/bobbo33
	
How it works:	
	Simple enter a starting balance in row 1, and the date of that balance (i.e. the date of your last statement, or last online update).
	
	You can enter transactions directly in the table starting on line 5, but the easiest way is to use the "Add Transaction" button.  You'll need to enter:
	* Description (anything that's description to you)
	* Type:  deposit (results in a positive transaction) or withdrawal (results in a negative transaction)
	* Amount in dollars
	* Next due date
	* Frequency:  weekly, biweekly, monthly, quarterly, biannual, annual, or only-once
	
	Once you've entered several transactions, you may want to sort them using the sort button.  Note that when you sort, overdue transactions (ones that occur before today's date) come to the top of the list and are highlighted in red.
	
	After using this spreadsheet for a while, you may find you have several overdue transactions that have cleared your bank (i.e. are included in the current balance), and you want to update those transactions to their next due date.  You can do this automatically using the "Roll Forward" button:  this will set the due date on each overdue transaction to the next upcoming occurrence after today's date.
	
	Now that your transactions have been entered, you're ready to run the forecast!  Simply click the "Run Forecast!" button, and enter the desired date range for the forecast (it defaults to starting with today's date and forecasting for the next three months).  You'll have one option to set:  whether to include any past due transactions in the current balance or to ignore these transactions (the default is to include them, which adds them to your starting balance).
	
	One more note on forecasting:  You're not restricted to starting from today's date!  You can select dates in the past or the future, and the forecast calculation will project in either direction based on the transactions you have scheduled.

Changelog:
	1.0 Initial Release
	1.1 Forecast calculates a daily subtotal (rather than simple transaction list)
	    Update function based off of balance date (rather than today's date)
