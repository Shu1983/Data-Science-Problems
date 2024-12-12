# Data-Science-Problem # 1. Insurance claims- EDA &Hypothesis Testing

Overview: 
Objective – Explore the dataset and extract insights from the data. Using statistical evidence to

  Prove (or disprove) that the medical claims made by the people who smoke is greater than those who don't?
  Prove (or disprove) with statistical evidence that the BMI of females is different from that of males.
  Is the proportion of smokers significantly different across different regions?
  Is the mean BMI of women with no children, one child, and two children the same?

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Problem Statenent:
Insurance Companies face significant challenges in retaining customers and managing risks. In the case of an insurance company, attributes of customers like the ones mentioned below can be crucial in making business decisions.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Data:

_Source_: https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv

Columns

age: age of primary beneficiary

sex: insurance contractor gender, female, male

bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

children: Number of children covered by health insurance / Number of dependents

smoker: Smoking

region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

charges: Individual medical costs billed by health insurance

Format: CSV

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Approach:

Read and understand the data: Using SciPy, Pandas, Numpy, Matplotlib, Seaborn

Exploratory Data Analysis: Univariate, Bivariate and Multivariate analysis.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Conclusion based on EDA

As expected , as the age of the beneficiary increases ,the cost to insurance increases.

Males who smoke have most claims and have higher bills.

Female who are nonsmoker also have more claims to nonsmoker males this may be because of child birth , need to explore claims type to understand better.

Beneficiary with 2 or 3 dependent have billed higher compared to others people who have 5.This is unusual and may be because of uneven number of observations in each group. For example, no dependents group has 574 observations whereas five dependents group only has 18.

Customer with bmi >30 are on higher side of obesity, have more health issues and have higher claims.

Females with BMI more than 45 have billed higher to insurance.

Age, BMI and Smoking are important attributes which can cost insurance company more.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Recommendations:

Based on EDA and statistical evidence it can be seen that customer who smoke or have higher BMI have more higher claims. We can encourage customers to quit smoking by providing them incentive points for talking to life coach, get help for improving lifestyle habits, Quit Tobacco- 28 day program. Give gift cards when customer accumulates specific number of points.
We can have Active wellness programs which can help up reduce claims related to BMI.
High BMI is primarily because of unhealthy life choices. We can provide customers with Diet plans and wellness health coaches which can help them to make right choices.
Provide discount coupons for Gym or fitness devices encouraging customers to exercise.
