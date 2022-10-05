# Lending Club Case Study
> This case study is to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This case study is to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.The company can utilise this knowledge for its portfolio and risk assessment. 
- Borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
- To analyse this we have the complete loan data for all loans issued through the time period 2007 to 2011 and its Data Dictionary. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Upper limit for DTI & Interest rate in each income category/funded amount by investor can be determined,more than that would be considered risky
- Subgrades D2,E1,F1,F2,G1,G2 have more ratio of defaulters, the risk is higher for these subgrades
- Borrowers with annual income less than 80K who request loan for small business have more 30% defaulters, hence considered to be risky
- Borrowers with 60 months Term tends to default more especially with Funded amount by investor in range of 0-4K and 16K-20K
- Borrowers with Education loan tends to default more with Funded amount by investor in 12K-16K and 20K-25K range
- Borrowers with Vacation loan, Small Business and Car loan tends to default more with Funded amount by investor in 12K-25K rang
- Borrower with House Ownership as ‘Others’, 'Own’ & ‘Rent’ tend to default more for Funded amount by investor in 16K-25K range


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2
- warnings 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is done as part of Execution PG on ML & AI from upgrade with partnership with IIITB


## Contact
Created by [@vighu0710] & [@ankitlohiya4] - feel free to contact us!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
