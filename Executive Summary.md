Executive Summary
=================

 

Problem Statement
-----------------

Debt is a large problem in the United States. Many people have fallen into large
amounts of debt much of which have a staggering interest rate attached to it. A
significant number of these people have chosen not to repay this debt. This can
be attributed to any number of reasons (loss of employment, other costs taking
precedence, with the interest being so high they don't see any reduction in the
principle amount, etc…) After a period of time trying to collect on the debt
creditors will write this debt off and sell it in hopes of recouping some of
what is owed. The process by which debt is sold comes in the form of bundles
i.e., a number of different debtors are bound together and sold as a percentage
of the total amount owed. This could me pennies on the dollar, but the amount
paid varies on the amount of information given to the buyer about the debtors
included in the bundle. For instance all statements and correspondence each
debtor has had with the selling creditor. The more data provided the more the
bundle will cost, however the more data you have the better you will be able to
predict if someone will eventually repay what is owed.

 

Getting people who have a demonstrated propensity of ignoring their debts to pay
is the key to success when purchasing bundles of debt. How then do we do this?
It is our belief that for the most part people in this position would like a way
out. Either to just have the load of the debt off their shoulders, or to get the
credit back so they my buy a house, car, etc… What has was implemented
successfully in this bundle was to reduce the interest rate to prime plus 3 for
debtors meeting the following criteria:

-   Debt must be in Colorado

-   Amount must be less then or equal to \$15,000

 

Can we accurately predict if debtor will repay loan. We have a bundle of debt
that was purchased in 2008. This bundle is comprised of 42 debtors with a total
debt amount of \$182,222.36. The cost of the bundle was \$6,000. We also know
who in fact accepted the deal to repay.

### People who paid

-   Claudia Rendon paid \$571.54 

    -   Enrique Ochoa paid \$2135.20

    -   Liseth Pena paid \$984.34

    -   Andy packer paid 25,500.00

    -   Olivia Aragon paid 800.00

 

 

Data Gather Data
----------------

The data came in the form of two paper spreadsheets. I used Abbyy FineReader,
which is an optical character recognition (OCR) piece of software that allowed
me to read the paper documents into a .csv file. From there I needed to separate
several columns that the software merged together because of several reasons;
some of the cells were highlighted, the pages were taped together so that the
rows could be seen with all the columns. I also needed to fix several of the
date, name, and address fields for the same reasons as above.

 

Exploratory Data Analysis (EDA)
-------------------------------

Upon the initial look at the two spreadsheets it became clear that they were the
same group of accounts. When the bundle was purchased two people were doing the
analysis. I’m guessing that the two spreadsheets were each individuals work
product.

 

The first data set had less missing data

### Data Dictionary

42 entries with 28 columns

Account Number         int64  
PortID                        object  
Remaining Balance      float64  
interests Fees             float64  
Date Opened              datetime64[ns]  
Charge Off Date         datetime64[ns]  
Last Pay Date             datetime64[ns]  
Last Pay Amount        float64  
Last Activity Date       datetime64[ns]  
Interest Rate %         float64  
Issuer                       object  
Merchant                   object  
FCFRA Date              datetime64[ns]  
OOS Date                  datetime64[ns]  
Account Type             object  
Last Name                object  
First Name               object  
Middle Name             object  
Address                     object  
City                          object  
State                       object  
Zip                           object  
County                     object  
SSN                         float64  
Home Phone             float64  
Employer Phone        float64  
Cycle                        object  
Paid                         int64

 

Model The Data
--------------

 

 

Evaluate The Model
------------------

 

 

Answer The Problem
------------------

 
