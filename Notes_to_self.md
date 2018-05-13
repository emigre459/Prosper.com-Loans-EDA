# Interesting Multivariate Plots
1. CS vs. Monthly payment - seeing a positive correlation. Why would your monthly payment be higher 
		for a better credit score? That, barring anything else, would suggest a higher rate...
		* FLAGGED FOR MULTIVARIATE EXPLORATION. Will be good to parse by loan term and/or 
		original loaned amount (perhaps higher CS folks tend to take shorter terms or take out a much
		higher principal, resulting in higher monthly payments?)

	
2. Rates
 	* Monthly Payment vs. Borrower Rate - saw *negative* correlation between these, 
			which is counterintuitive.
		* This is still super confusing, I'll need to try and parse it by a third variable as well.
			Will be useful to do Term and Principal too, but may need more...listing category?
			* Is there a bubble plot option that could be used for principal and then coloring for term?
 	* Rate vs. loan status
 		* Need to explore this more in Multivariate section. In particular, my "vicious cycle" concern
 			needs to be explored more: if I add in the variable of credit score, do I see the 
 			"high CS = low rates = good loan outcomes" trend I'm expecting?
