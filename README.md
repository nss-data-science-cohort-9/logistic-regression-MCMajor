## Logistic Regression Exercise

**Part 1: Load and explore**

1. Load the dataset and display the first few rows.  
2. How many movies in the dataset were nominated for Best Picture?  
3. What percentage of movies were nominated?  
4. Compute the average revenue for:  
    * nominated movies  
    * non-nominated movies  
Does revenue look associated with nominations?

**Part 2: Logistic Regression: Revenue Only**

5. Fit a logistic regression model for whether a movie was nominated based on its revenue.  
6. Interpret the sign of the coefficient for Revenue.  
7. Use the model to estimate the probability of nomination for a movie with $10M revenue, $100M revenue, and $500M revenue.  
8. Make a plot of predicted probability vs. revenue.

**Part 3: Add Genre**

9. Fit a model for whether a movie was nominated based on its revenue and whether or not it is a drama.  
10. Interpret the coefficient for Genre_Drama. 
11. Using your final model, compute the predicted probabilities of nominations for:  
    * $20M non-drama
    * $20M drama
    * $300M non-drama
    * $300M drama  
12. Which variable has the larger effect: being a drama or revenue?

**Part 4: Stretch Questions**  

13. How do the empirical and estimated probabilities look for the revenue-only model? What about the model that uses both revenue and the drama genre?    
14. Revenue is highly skewed, which means that log revenue might make for a better model fit. Try fitting a model using log revenue. Then compare these models. You can look at [Akaike Information Criterion](https://en.wikipedia.org/wiki/Akaike_information_criterion) or the (log-likelihood)[https://en.wikipedia.org/wiki/Likelihood_function]. You might also look at a [calibration curve](https://encord.com/glossary/calibration-curve/).  
15. Add other genres to your model. Which genres have the largest effect on the estimated probability of being nominated?  
16. Instead of revenue, use profit. How does this change the model?