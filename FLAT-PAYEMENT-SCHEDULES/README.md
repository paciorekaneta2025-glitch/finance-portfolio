
# Part 1: Flat Payment Schedules Explained
Building the Foundations of Financial Planning

## 1. 

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

<img width="1284" height="1276" alt="image" src="https://github.com/user-attachments/assets/a1dfeea1-7534-470d-b38b-98cef313b849" />


### Why Is Future Value Important?

Future Value is the foundation of many financial concepts because it demonstrates the effect of compound interest.

Understanding Future Value helps explain:

*   How savings accounts grow 
*	How investment portfolios accumulate wealth 
*	How pension funds increase over time 
*	Why starting to save early can make a significant difference 
*	The relationship between Present Value (PV) and Future Value (FV) 

Before moving on to more advanced retirement calculations involving regular contributions, annuities, and pension planning, it is essential to understand how a single lump-sum investment grows through compounding over time.

Future Value helps us:
*	Plan investments 
*	Build savings 
*	Analyse retirement plans 
*	Create financial forecasts 
*	Better understand compound interest 

The Most Important Observation

The longer money remains invested, the faster it grows.

This happens because of compound interest:
* Interest earned on an investment begins to generate additional interest over time.
* As a result, time becomes one of the most important factors in finance and investing.

Many people focus primarily on the amount they invest, but in reality, the length of time the money remains invested can have an even greater impact on the final outcome.

## 3. Future Value with Annual Deposits

In finance, we often encounter situations where we do not invest one large lump sum at the beginning. Instead, we make regular contributions of the same amount each year.

This approach is commonly used in:
*	Retirement plans 
*	Savings accounts 
*	Investment funds 
*	ISA accounts 
*	Long-term wealth-building strategies 

Assume that we contribute the same deposit at the beginning of each year. Each contribution starts earning interest and benefits from the power of compound growth.

Unlike the simple Future Value example, where only one initial investment is made, here multiple deposits are made over time. Because earlier deposits remain invested for longer, they earn more interest than later deposits.

Example

Assume the following:
*	Annual deposit: £1,000 
*	Interest rate: 10% per year 
*	Investment period: 10 years 
*	Deposits are made at the beginning of each year 

<img width="840" height="753" alt="image" src="https://github.com/user-attachments/assets/6addf8d6-b0c8-42eb-a68d-e54a2774522d" />

In this case, the Future Value of the investment will be approximately £17,531.

The most important concept to understand is that:

* The first deposit earns interest for the full 10 years. 
* The second deposit earns interest for 9 years. 
* The third deposit earns interest for 8 years. 
* And so on. 

As a result, wealth grows not only because of the additional deposits being made each year, but also because of the compound interest earned on earlier contributions.

This creates a powerful snowball effect, where both the invested capital and the accumulated interest continue to generate additional returns over time.

Mathematically, this model is known as:

#### Future Value of an Annuity Due 

An Annuity Due refers to a series of equal payments made at the beginning of each period.

The Future Value of an Annuity Due can be calculated using the following formula:

#### FV=PMT×(1+r)^n-1┤/r×(1+r)

Where:

*	FV = Future Value 
*	PMT = Annual deposit 
*	r = Interest rate per period 
*	n = Number of periods 

This is precisely why regular contributions, even relatively small ones, can grow into substantial wealth over time.

In practice, this is one of the most important concepts used in:
	
	* Retirement planning 
	* Pension schemes 
	* ISA and investment accounts 
	* Long-term wealth accumulation 
	* Financial modelling and forecasting 

The key lesson is simple:

Building wealth is often less about investing a large amount at once and more about investing consistently and giving compound interest enough time to work.



