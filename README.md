# Different-ab-testing-approaches
## by Ahmed Tryaq


## Dataset

This dataset simulates a learning website which is to implement a new page design for one of their courses. And want to measure how the new page affected their convertion rate before making the decision to implement it.

## Summary of Findings

- Resulting  𝑝  value is  0.91 , which is much greater than our significance level ( 𝛼=0.05 ), thus, we fail to reject null hypothesis.
In other words, the previous analysis didn't show any significant increase in conversion rate in users who experienced the new page in comparison to users who experienced the old one.
## Regression model results:
- Our model summary results suggest that users who were displayed the old page are  1.07  times more likely to convert compared to users who were shown the new page. Users from US and UK are  1.02 ,  1.01  times more likely to convert, respectively, compared to users from Canada. While holding all other variables are constant.

- Users who were displayed the new page and are from US or UK are  1.05,1.08  times respectively more likely to convert, compared to baseline, while holding all other variables constant.

- Although these results can be very helpful in predicting user behaviour, they are not significant as they didn't meet our significance level of  (𝛼=0.05) , gathering more related features can help in improving our model accuracy.
