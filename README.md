# Fannie Mae Mortgage Data Analysis - R

## Overview
Fannie Mae is one of the largest purchasers of home mortgages from banks and sellers of mortgage-backed
securities (a financial instruments created by bundling and selling mortgages to investors) on the secondary
market in the United States. In exchange for a fee, Fannie Mae guarantees the payments of principal and interest
on the book of loans it sells. As Fannie Mae bears the losses in the event of borrower defaults on a mortgage,
its future profitability is significantly influenced by borrower default rates.

In September 2008, at the peak of the financial crises, Fannie Mae was piling up significant losses. A wave of
mortgage defaults posed a severe threat to Fannie Mae and, consequently, the entire U.S. financial system. To
save the system, the U.S. government stepped in and placed Fannie Mae under conservatorship, a form of
bankruptcy overseen by the Federal Housing Finance Agency (FHFA). This move transformed Fannie Mae
from a government-sponsored entity to a government-owned entity. From 2008 to 2011, the U.S. Treasury
injected $116.1 billion of capital into Fannie Mae. Subsequently, Fannie Mae embarked on a path to recovery.
By mid-2012, it had restored profitability and regained a dominant in the market. In 2022, Fannie Mae reported
an annual net income of $13 billion1, and held the largest market share, accounting for 40% of the issuance of
single-family mortgage-backed securities (MBS).


## Data
The two datasets are small samples randomly drawn from the data
for specific periods, representing approximately 17% and 12% of the entire data for Q4 2007 and Q4 2019,
respectively. 

• “2007Q4.rds” contains information on 50,000 fixed-rate single-family amortizing loans with terms of
30 years or less. These loans were either owned or guaranteed by Fannie Mae during the fourth quarter
of 2007, a period marked by a significant increase in loan defaults5 at Fannie Mae.

• “2019Q4.rds” includes information on 50,000 Fannie Mae loans of the same type as the previous data
file, but specific to the fourth quarter of 2019 – the last quarter before the onset of COVID.


## Analysis
I worked with a smaller subset of the data obtained from Fannie Mae’s data portal. 
