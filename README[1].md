# ProsperLoan Data Exploration 
## by Aruma Vivian C

## prosperLoanData

prosperLoanData dataset is a csv file, it contains 113,937 rows(loans) with 81 variables on each row. The features(variables) includes amongst others Term, LoanOriginalAmount, Borrower's APR, loan status, 'ProsperRating (Alpha)', DebtToIncomeRatio, The dataset is provided by Udacity.

# Summary of Findings

I explored the dataset using different plotting techniques, i did univariant, Bivariant and Multivariant exploration of the dataset. I made a copy of the dataset with only variables that wound help me answer my numberous questions which mostly revoles around factors that affects the Borrower's ApR (interest rate). The foloowing insight was deduced:
> The histogram plot indicate that there seems to be no loan awarded at a rate greater than 0.42. Majority of loans was awarded at a lesser APR. 
It also showed that loam amounts ranging from 1000-35000 was accessed but the highest distributed loan amounts were 4000, 15000, 10000, 5000 accordingly. The minimum amout distributed ia 1000.
>There are 67 known distinct occupations that accessed loan from prosper and majority of others(unknown occcupation) were given followed by professionals.
>The pie chart shows the durations of loans given by prosperLoan. 77% were given at 36 months duration, 21.5% at 60 months and 1.4% at 36% duration.
>The Prosper loan dataset has a unique rating scale system and the rating counts from highest to lowest appear as follows C,B,A,D,E,HR and AA. The highest borrowers fall under C ratings followed by B and then A with the least count being AA.
>High number of persons were meeting up with their repayment schedules as the graph shows that majority are current and that a great number of persons have completed their loan. Few person defaulted and a significant number of persons are Past Due payment.

>The scatter plot indicate a negative correlation between Borrower's APR and Loan Original amount. This implies an decrease in Borrower's APr(Interest rate) as loan amount increases.There is a negative correlation between loan amount and DebtToincome ratio, a positive correlation between APR and DebtToincome ratio which implied an increase in APR as debt increases

>From the employment vs loan status, it is observed that majority of those employed have an ongoing(current) loan status and most people that are fulltime workers have completed the loan repayment.
Majority of people on 36 and 60 months loan duration have their loan status as current whereas those on 12 months duration have their loan completed.
The number of current loaners are more in all scale of rating.

>It is observed that individual's rating has some effect on the relationship between the original loan amount and APR. We can see a gradual positive relationship positive as the rating increases. Term doesn't seem to have any effect on the relationship between the loan amount and APR. This just shows that APR decreases with increase in amount despite the loan amount.


# Key Insights for Presentation

I will examine the relationship between the Borrower APR and several of variables boyh categorical and numerical variables. For example, some relationships that I examined are APR vs. loan amount and APR vs. Term.


```python

```
