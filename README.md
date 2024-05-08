# EDA Case Study for Loan Defaulter Analysis
> Various attributes affecting defaulter need to be identified based on the loan.csv data 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- loan.csv with attributes related to the loan payment to be analysed
- Loan Approval process needs to be improvised as there are still a lot of loan defaulters
- Avoid having a Loan Defaulters as its a loss to the business
- loan.csv dataset is being used

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
| Package    | Version                                                             |
|------------|---------------------------------------------------------------------|
| Python     | 3.8.19 (default, Mar 20 2024, 19:55:45) [MSC v.1916 64 bit (AMD64)] |
| Matplotlib | 3.7.2                                                               |
| Numpy      | 1.24.3                                                              |
| Pandas     | 2.0.3                                                               |
| Seaborn    | 0.12.2                                                              |

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Very less Loan applicants in below:
  - Grade F and G
  - OWN house
- A lot more Loan applicants are in below:
  - debt_consolidation
  - CA
- As the Grade towards D,E,F,G the percentage of having a defaulter is higher
- Higher Interest Rate has higher defaulter. esp., above 12.5%
- Higher the enquiries on the credit status of the applicant, higher the chances of default
- Lower the total_rec_late_fee higher the chances are to Fully Pay the loan. So having lesser recovery late fees would help in having the loans paid fully
- Lower the pub_rec_bankruptcies higher the chances are to Fully Pay the loan. So the time pub_rec_bankruptcies are more its an indication of being a defaulter
- As the Grades move towards D,E,F,G the chances of being a default is higher. Also, F4 and G3 have the highest chances of being default
- if the verification_status is Verified there are chances of being default. So this process need to be revisited
- For purpose of Small Business there are higher chances of having defaulter.
- For addr_state  = NE (0.6 value in heatmap) , there are higher chances of having the loan defaulted
- For Loan Amount in higher ranges, the defaulter chances are higher. Esp between 21k-23k & 29k-35k
- With higher interest rates, the higher are the chances of Default. Esp., for 21%-23.5% the chances of Default are 50%
- For emp_length in years esp., for the range between 6.5-7 and 9.5-10 years have high chances of default
- For the zip_code area 304xx-350xx and 850xx-999xx , the chances of default are higher
- For Debt-to-Income ratios of 11-26, there are chances of loan default.
- For more inquiries in credit status of the applicant in last 6 months have higher chances of default
- With number of derogatory public records between 0-2 , there are higher chances of default. Even in case of higher than 2, it seem the value is 0. So for any number of pub_rec there needs to be proper investigation for loan approval

