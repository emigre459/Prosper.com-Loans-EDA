# Interesting Multivariate Plots
1. CS vs. Monthly payment - seeing a positive correlation. Why would your monthly payment be higher 
		for a better credit score? That, barring anything else, would suggest a higher rate...
		* FOR FINAL PLOTS: add color = ListingCreationDate too and provide hlines to show max payment per
			facet


	
2. Rates
 	* Rate vs. loan status
 		* Need to explore this more in Multivariate section. In particular, my "vicious cycle" concern
 			needs to be explored more: if I add in the variable of credit score, do I see the 
 			"high CS = low rates = good loan outcomes" trend I'm expecting?




# FINAL PLOTS
1. Plot of loans (raw count) by state in light background, with loans per capita in foreground
	* c("DC", "GA", "MD", "IL", "CT", "OR")
	* c(9, 12, 16, 22, 8, 39)


2. Borrower Rate, Loan Status, Credit Score facet
	* Try to figure out a way to do a colored background (red for bad statuses, green for good ones)
		without throwing the discrete/continuous error

3. CS vs. monthly payment: facet by Term, size by Principal, color = listing creation date
	* 5 DIMENSIONS OF DATA!