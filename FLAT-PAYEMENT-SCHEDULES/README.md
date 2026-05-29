

## 1

#### In this article, I will try to shed some light on the topic of retirement planning. However, to understand retirement concepts properly, it is important to first understand flat payment schedules. This is a fundamental concept for understanding loan tables and amortisation schedules.

A Flat Payment Schedule is a loan repayment schedule in which the borrower makes the same payment amount in each period. These payments can be made monthly, quarterly, or annually.

At first glance, it looks very simple:

For example:

|YEAR  | PAYMENT
|------|------
|1     | £100
|2	   | £100
|3	   | £100
|4	   | £100
|5	   | £100

Important note: although the payment amount remains the same throughout the loan term, the composition of each payment changes over time.

|Payment  Component | 	What Happens
|-------------------|----------------
|Interest           | High at the beginning, then gradually decreases
|Principal Repayment| Low at the beginning, then gradually increases
|Loan Balance	    | Decreases until it reaches zero

In reality, each payment consists of two components:

  * Interest 	
  * Principal Repayment 

At the beginning of the repayment period, a larger portion of the payment goes toward interest because the outstanding loan balance is still high. As the balance decreases over time, the interest charged on the loan also becomes smaller. As a result, a larger portion of each payment is applied to repaying the principal.

As a consequence:

  * Interest ↓ decreases 	
  * Principal Repayment ↑ increases 
  * Loan Balance ↓ falls to zero 

To calculate the constant payment amount, the PMT formula is used:

#### PMT=(r⋅PV)/(1-(1+r)^(-n) )

Where: 

  * PV — Present Value (loan amount) 
  * r — interest rate per period 
  * n — number of periods 
  * PMT — constant payment amount 

In Google Sheets or Microsoft Excel, the same calculation can be performed using the PMT() function.

Flat Payment Schedules are extremely important in financial modelling because they help us understand:

* How loans and credit facilities work 
	
* Debt amortisation 
	
* The relationship between cash flow and interest expenses 

* The foundations of IRR (Internal Rate of Return), NPV (Net Present Value), and Discounted Cash Flow (DCF) analysis 

  
Understanding flat payment schedules is often the first step toward understanding more advanced financial concepts, including investment appraisal and retirement planning models.

<img width="1284" height="692" alt="image" src="https://github.com/user-attachments/assets/463bc493-6d3f-4e1d-81d4-970f1d144b2c" />
