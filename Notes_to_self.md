# Interesting things to study with 2D analysis
1. Perpetual question: do trends differ if you look at pre-2009 and post-2009 subsets of the data?
	* Do this comparison for every bivariate analysis if possible
	* May also be useful to keep in mind there was a late 2012/early 2013 dip in loans too
7. BorrowerState vs. Loan Status (scatterplot? OR stacked bar chart of statuses?)
		* Also do per capita loan counts by state (use `geom_bar(weight = 1/Population)`)
	* BorrowerState vs. Listing Date - should see a dropoff for some states post-2009
	* Listing Category vs. State
	* CreditScoreMidPt vs. State
2. BorrowerRate vs. CreditScoreMidPt - saw *positive* correlation between these, 
	which is counterintuitive. Let's see what's going on!
3. Term vs. Loan Status
3. Listing Date vs. Closed Date and correlation analysis - how related is your start date to your
 end date and how does this change pre-/post-2009?
4. APR vs. Rate + correlation
 	* IF APR and Rate aren't super-correlated, then do the rest of these for both; otherwise,
 	 focus on Rate
 	* Rate vs. Listing creation date + correlation
 	* Rate vs. closing date + correlation
 	* Rate vs. loan status
5. LenderYield vs. Rate + correlation: expect this to have r = 1 or nearly so
6. Listing Category vs. Loan Status
11. Employment Status vs. Loan Status (spine plot?)
	* Employment Status vs. Creation Date
12. CSMidpt vs. Loan Status
	* CS vs. Employment
	* CS vs. Creation Date
	* CS vs. ListCat
13. Delinq vs. LoanStatus
	* Delinq vs. CS
	* Delinq. vs. Rate
	* Delinq. vs. EmployStatus
14. MonthlyIncome vs. LoanStatus
	* Income vs. EmploymentStatus
	* Income vs. Rate
15. LoanOrigAmt vs. Laon Status
	* LoanOrigAmt vs. ListDate
	* LoanOrigAmt vs. EmployStatus
16. MonthlyPayment vs. Loan Status
	* MPayment vs. Creation Date
	* MPayment vs. Term (expect linear)



# Interesting things to study with multivariate analysis
1. 
 