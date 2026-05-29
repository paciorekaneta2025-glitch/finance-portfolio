

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


## 2. Understanding Simple Future Value – The Future Value of Money

A Flat Payment Schedule shows how a single fixed payment repays a loan over time — part of the payment goes toward interest, while the remainder reduces the principal balance until the loan is fully repaid.
This concept serves as the bridge between IRR calculations and a loan amortisation table.

### What is Future Value?

Future Value (FV) represents how much money invested today will be worth at a future date after earning interest.

Put simply:

Future Value helps us estimate how money grows over time.

It is one of the fundamental concepts used in:

	* Investing 
	* Saving 
	* Loans and credit 
	* Retirement planning 
	* Financial modelling 

A Simple Example

Suppose you invest:
 
	* £1,000 
	* At an annual interest rate of 5% 	
	* For 3 years 

Your money grows each year because the interest earned is added to the investment balance.

Future Value Formula

#### FV=PV(1+r)n

Where:
	* FV = Future Value 
	* PV = Present Value (the amount invested today) 
	* r = annual interest rate 
	* n = number of years

Calculation

FV=1000(1+0.05)^3

Result:

FV≈1,157.63

After 3 years, an investment of £1,000 grows to approximately:

£1,157.63

<img width="1284" height="816" alt="image" src="https://github.com/user-attachments/assets/9fddea61-7bbb-4747-ba98-a3d46ec77d91" />



