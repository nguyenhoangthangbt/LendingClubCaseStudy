# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Raw data](#Raw-dataset)
* [Key findings](#Key-findings)
* [Recommendation](#Recommendation)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Business background & Objective
- We are the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
Like most other lending companies, our lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters’. 
Once we identify risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
Out objectives are to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default and utilize this knowledge for its portfolio and risk assessment. 

### Raw dataset
loan.csv

## Key findings
- Problem univariate analysis: 14 to 15% total loan cases and loan amounts
- Correlation analysis: 
    + Loan status has positive relationship with total payment received, the more we receive the better loan status. It means, the less amount we have received, the more likely there are charged off or default cases. 
    + Loan status has negative relationship with total collection recovery fees or late payment received. 
    Besides, there are risks associated with the grade of profile and those loans with high interest rate (but not strong) as following more detailed views.
- Bivariate analysis: Charged off loans are more likely at higher interest rate loans, and less likely at the higher grade (more reliable with more assets) profiles

## Recommendation
- For current loans, because the charged off loans are highly correlated with total payment received up-to-date, thus we need to monitor and push very closely the on-time payments to lower the risks of default. Once there are signals of late payments, urgent actions need to be taken to prevent higher risks of later default. The more customers pay, the lower rate of default or lower our business losses
- For future loans, we need to watch out the payment history of customers to past loans, the more they paid on-time, the lower risk of their default in next loans. Besides, watch out the lower grade profiles and high interest rate loan for early risks detection. We need to reduce or reject the late-paid customer’s loan applications and low grade profile (even they can accept the high interest rate loan) to lower the risks and prevent the business losses.


## Technologies Used
Following lib imported:
- pandas 
- seaborn
- matplotlib

## Contact
feel free to contact me!
Name: Thang Nguyen 
Email ID: thang.lzdvn@gmail.com
Phone no: +84 932835378 