# monte_carlo_modeling
Defining if we are able to detect differences in the average number of likes per user

My colleagues from the ML department came to me and shared that they plan to roll out a new algorithm that recommends interesting posts to our users. After discussing how it works, I came to the following understanding:

The algorithm adds 1-2 views to each user.
The probability of the algorithm being triggered is 90%.
If a user has fewer than 50 views, the algorithm will not be triggered.

I assumed that an increase in the number of views would also lead to an increase in likes per user. The question arises: would we be able to detect differences in the average number of likes per user? To answer this question, I performed a Monte Carlo simulation!
