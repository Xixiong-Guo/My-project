# Introduction
[LendingClub](https://www.lendingclub.com/) is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

# Data 


# Data merge and preliminary cleaning
[1. Data collection, import and concatenation.ipynb](https://github.com/Xixiong-Guo/My-project/blob/master/Lending%20club%20load%20data%20analysis/1.%20Data%20collection%2C%20import%20and%20concatenation.ipynb)

This notebook includes:
1) Download the raw data from [LendingClub](https://www.lendingclub.com/info/download-data.action)
2) Concatenate the data from each year/quarter into one dataset
3) Delete some features with more than 27% missing data, to reduce the memory cost and improve the computing efficiency 

# Get to know all the features
[2. Feature explore](https://github.com/Xixiong-Guo/My-project/blob/master/Lending%20club%20load%20data%20analysis/2.%20Feature%20explore%20and%20target%20encode.ipynb)
This notebook includes:
1) Explore the meanings of all features from [LendingClub](https://www.lendingclub.com/info/download-data.action).
Divided the features into 2 categories: Borrower relevant and loan relevant features. 
2) Further delete a few unrelated features after better understanding the dataset. 
3) Encode the target feature, classify whether it is a good or bad loan based on the loan_status.

# To be continued
