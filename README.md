# Lending Club Case Study
> Lending Club is a loan lending company whose aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.The company wants to understand the driving factors behind loan default.


## Table of Contents
* [General Info](#general-information)
* [Libraries Used](#Libraries-used)
* [Conclusions](#conclusions)


## General Information
- Being the loan lending company,If one is able to identify risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.Identification of such applicants using EDA is the aim of this case study.
- Dataset used is Loan.csv which has information about past loan applicants and whether they ‘defaulted’ or not. 
- The dataset has 111 distinct columns and 39717 rows.
- In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.


## Conclusions
- Univariate Analysis Inferences:
    - The loan amount between 5000 - 10000 is requested the most by the loan applicants.
    - People with the annual salary between 40000-60000 have applied for the loans the most than the poeple falling in other salary brackets.
    - Most of the applicants interest rate lies between 10 - 14 %.
    - Most of the people who applied for loan have their DTI between 10 - 15.
    - Most of the loan installments lies bewteen 160 - 300 per month.
    - Close to 78 % of the people have fully paid their loan.
    - 36 months EMI is common amongst the loan applicants.
    - Debt Consolidation leads the purpose race as the reason behind the loan applications.
    - Lending Club has classified most if it's applicatnts as Grade B and Grade A.
    - Most of the loan applicants are living on a rented property followed by mortgage.
    - Most of the applicants are freshers i.e having experience of less than or equal to 2 years followed by experts having more than 10 years of expereince.
    - Number of loan applicants increased over the years with 2011 leading over the other years. December is the most common months for people to apply for a loan.
    - Almost 85 % have no bad public record or any case of bankruptcies.
    - People from CA state have applied for the loans the most.

- Segemented Univariate Analysis Inferences:
    - While there is no significant difference bewteen the two loan status over the loan amount but the median loan amount has significantly increased over the years with 2011 leading the
race.
    - The median loan amount for small_business is the most,then the second is debt consolidation.Also,same is the case for people who have homeownership of mortgage.
    - The average loan amount for the people who are verified is more than the people who are either souce verified or not verified.
    - Average ROI for the loan taken for small business is the most.
    - People who took loan for the purpose of debt_Consolidation have higher DTI.
    - People who have higher annual salary tend to take loan for home improvement the most and have mortgage as homeownership..
    - The expreince level plot shows that the average annual salary increase with the years of expreince.
    - The average DTI amongst the loan applicants has increased over the years.
    - The average ROI is less for grade A applicants while grade G have the highest. Average DTI for Grade A applicants is least too.
    - There is a significant increase in the ROI as the loan amount increases.
    - The rate of interest on 60 months term is more than that of 36 months term.
    - ROI is more for the people who have the verified.
    - When the loan amount is more , people opt for 60 months of term.
    - There is a slight difference in the DTI of a 36 months tenure applicants as compared to 60 month term.
    - DTI of verified people is slightly more than the source verified and not verified.
    - Installemnts increase with the increase in the loan amount and interest rate.

- Bivariate Analysis Inferences:
    - People belonging to Grade 'G' and 'F' tend to pay high rate of interest and hence are likely to be at default.
    - Maximum people who are at default for higher loan amount belong to grade 'F' and 'G'.
    - People who have ownership as 'Mortgage' are likely to be at default for higher loan amount, higher rate of interest and higher DTI.
    - Most of the people who are at default took loan for the purpose of small_business when the loan amount is higher 
    - When the rate of interest is high then people who took loan for house and home_improvment are likely to be at default.
    - In case of high DTI ,credit_card is purpose behing people being at default.
    - People who are verified usually tends to be charged off when the loan amount is higher.
    - Maximum people who are charged off have are having higher DTI.
    - People who have experience of more than 10 years are ikely to be at default for higher amount and rate of interest.
    - People who took loan for tenure of 60 months are likey to be default for higher amount, rate of interest and DTI.
    - As the rate of interest increases with the loan amount , people are more likely to be at default. 
    - Maximum applicants from charged off group have high loan and more bankruptcies records on their name.
    - Maximum applicants from charged off group with higher DTI have 1 bankruptcy record.
    - Maximum applicants from charged off group have higher rate of interest have more records for derogatory on their name.
    - Maximum applicants from charged off group with higher DTI have 1 derogatory record.

- Driving Variables:
    - Interest rate - When the interest rate is high , a person is higly likely to be at deafult.
    - Term  - People opting for 60 months tenure are highly likely to be at default.
    - Grade - People belonging to grade 'G' and 'F' are likely to be at default.
    - Subgrade - People belonging to Subgrade 'F5' are likely to be at default.
    - Purpose - People who took loan for credit_card, House and small business are likely to be at default at higher loan amount.
    - Ownership - People have ownership of 'Mortgage' are likely to be at default.
    - Employee Length - People having expereince of more than 10 years are likely to be at default as they seek higher loan amount which has higher ROI.
    - Verification Status - People having verification status as Verified are likely to be at default at higher loan amount.
    - Pub record and bankruptcies - People with Derogatory Public Record and any record for bankruptcies are likely to be at default.
 


## Technologies/Libraries Used
- Python 3.10.9
- Numpy 1.23.5
- Pandas 1.5.3
- Matplotlib 3.7.0
- Seaborn 0.12.2


## Contact
Created by [Kushagra007-dev] & [mata.ashutosh@gmail.com] - feel free to contact us!
