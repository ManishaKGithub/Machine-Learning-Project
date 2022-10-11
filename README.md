# Machine Learning Project
Objective :
To apply knowledge and skills of Python programming and business analytics to organize and  analyze real-life data for meaningful insights.

Executive summary :
Crowdfunding means collecting funds for a project or commercial endeavor by soliciting contributions from a large number of people using an online platform. Our project focuses on Kiva.org, one of the world's most popular crowdfunding platforms.

Kiva.org is a prosocial crowdfunding platform where people from all around the world lend money to people in need. Kiva's purpose is to alleviate poverty in underdeveloped nations by allowing crowd-funded interest-free loans to underprivileged individuals and organizations. Kiva has made $1.63 billion in loans to over 4 million borrowers in 77 countries from over 1.9 million lenders since its inception in 2005. Despite its rapid expansion, Kiva has managed to keep a 96.2 percent repayment rate.

Project motivation/background :

Kiva.org, which was founded in 2005, is one of the largest online crowdfunding platforms in the world, allowing people to lend money to under represented entrepreneurs all around the world. Kiva's objective is to "connect people through loans to alleviate poverty," and it aims to give safe and cheap access to capital in areas where traditional banking services are unavailable, allowing people to become entrepreneurs and create possibilities for themselves and their families.

Kiva serves borrowers and lenders via the internet. Lenders who are willing to invest look through the various profiles of people looking for microcredit based on the loan request and borrower's attributes and invests on them. Kiva does not get any income on the loans it facilitates, and neither do Kiva lenders. Borrowers, on the other hand, pay interest to the financing process's intermediates, known as field partners, who are effectively the ones that carry the majority of the risk.

Kiva is active in 77 underdeveloped countries and collaborates with 304 field partners, according to statistics obtained in March 2015. In comparison to many other lending systems, Kiva stands out for its work with field partners. The field partners' purpose is to help the process along by creating a local presence and advancing funds to the borrowers prior to posting the loan request on the Kiva platform, allowing the borrowers to get a head start on their business.Kiva has made $1.63 billion in loans from over 1.9 million lenders since its inception in 2005. Kiva has managed to keep a 96.2 percent repayment rate.
Considering different criteria, Kiva will decide whether to fund the loan to the borrower.

Data description :
Our data used in this project is obtained from Kiva site. The snapshots of Kiva data are provided in their site “https://www.kiva.org/build/data-snapshots”. We're working with the data in the csv file.Three data tables: loans.csv, lenders.csv, and loans_lenders.csv that maps which lender gives to which project are provided. 
The target variable used for the prediction is “STATUS” which is a nominal data type also called as the dependent variable.The input variables are the ones which plays prominent role in determining the status of the loan.
loans_lenders Data :
Variable names and descriptions of lender and loan characteristics.
LOAN_ID - identification number of the loan.This is unique for each loan. 
LENDERS - list of lenders for a particular loan 

Loans Data :
Variable names and descriptions of loan characteristics.
LOAN_ID -  identification number of the loan.This is unique for each loan. 
LOAN_NAME - name of the person taking loan
ORIGINAL_LANGUAGE - language of the borrower
DESCRIPTION - reason of taking the loan 
DESCRIPTION_TRANSLATED - translated version of the description
FUNDED_AMOUNT - The amount of the loan already funded.
LOAN_AMOUNT - the loan amount requested.
STATUS - status of the loan
IMAGE_ID - id of image
VIDEO_ID - id of video
ACTIVITY_NAME - activity for which loan is taken
SECTOR_NAME - sector for which loan is taken
LOAN_USE - reason for which loan is used
COUNTRY_CODE - code of the borrower country
COUNTRY_NAME - name of the borrower country
TOWN_NAME - town of the borrower 
CURRENCY_POLICY - currency policy representing shared or standard
CURRENCY_EXCHANGE_COVERAGE_RATE - conversion rate of the currency
CURRENCY - name of the currency 
PARTNER_ID - field partner id
POSTED_TIME - loan request posted time
PLANNED_EXPIRATION_TIME - loan expiration time
DISBURSE_TIME - loan pay out time
RAISED_TIME - Time at which the loan amount is allocated
LENDER_TERM - repaying time of loan to the lender
NUM_LENDERS_TOTAL - total number of lenders for one loan id
NUM_JOURNAL_ENTRIES - document number of financial transactions
NUM_BULK_ENTRIES - bulk entry number
TAGS - tags used to identify the loan request reason
BORROWER_NAMES - names of the borrowers
BORROWER_GENDERS - gender of the borrowers
BORROWER_PICTURED -  true/false values
REPAYMENT_INTERVAL - Period of time granted for repayment, in months.Repayment interval as irregular/monthly/bullet
DISTRIBUTION_MODEL - loan distribution model

Lenders data :
Variable names and descriptions of lender characteristics.

PERMANENT_NAME - permanent name/unique name of the lender
DISPLAY_NAME - display name of the lender
MAIN_PIC_ID - image id of the lender
CITY - city of the lender
STATE - state of the lender 
COUNTRY_CODE - country code of the lender MEMBER_SINCE - member since id 
PERSONAL_URL - personal webpage of the lender
OCCUPATION - occupation of the lender
LOAN_BECAUSE - reason for lending loan 
OTHER_INFO - other information given by lender
LOAN_PURCHASE_NUM - The number which describes the purchase of the loan
INVITED_BY-The invited by represents the referred person details
NUM_INVITED- the num_invited represented as 0 or 1.Number of lenders that responded to a particular loan request.
1.Identified research questions :
Descriptive Questions : Descriptive questions describe what the data is.
What is the average loan amount requested?
What is the average loan amount funded
What is the maximum duration of the loan?
What is the max loan amount requested?
What is the min loan amount requested?
Is loan amount correlated with number of total lenders? 
Who has the max number of loan purchases among all the lenders?
Who has the min number of loan purchases among all the lenders?
Which sector has the highest number of loans?

Predictive Questions : Predictive questions intend to predict variable outcomes based on data. We will need to build predictive models to answer these questions. 

What is the chance of loan getting funded ?
What is the prediction of number of new lenders ?
