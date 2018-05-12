# Interesting things to study with 2D analysis
1. Perpetual question: do trends differ if you look at pre-2009 and post-2009 subsets of the data?
	* Do this comparison for every bivariate analysis if possible
	* May also be useful to keep in mind there was a late 2012/early 2013 dip in loans too


12. CS vs. Monthly payment - seeing a positive correlation. Why would your monthly payment be higher 
		for a better credit score? That, barring anything else, would suggest a higher rate...
		* FLAGGED FOR MULTIVARIATE EXPLORATION. Will be good to parse by loan term and/or 
		original loaned amount (perhaps higher CS folks tend to take shorter terms or take out a much
		higher principal, resulting in higher monthly payments?)


	
4. APR vs. Rate + correlation
 	* Monthly Payment vs. Borrower Rate - saw *negative* correlation between these, 
			which is counterintuitive.
		* This is still super confusing, I'll need to try and parse it by a third variable as well.
			Will be useful to do Term and Principal too, but may need more...
 	* Rate vs. loan status
 		* Need to explore this more in Multivariate section. In particular, my "vicious cycle" concern
 			needs to be explored more: if I add in the variable of credit score, do I see the 
 			"high CS = low rates = good loan outcomes" trend I'm expecting?

3. Term vs. Loan Status
3. Listing Date vs. Closed Date and correlation analysis - how related is your start date to your
 end date and how does this change pre-/post-2009?
6. Listing Category vs. Loan Status
11. Employment Status vs. Loan Status (spine plot?)
13. Delinq vs. LoanStatus
16. MonthlyPayment vs. Loan Status
14. MonthlyIncome vs. LoanStatus
15. LoanOrigAmt vs. Loan Status




# Interesting things to study with multivariate analysis
1. 
 