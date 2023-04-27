# Buncrapcy-prediction
Description The goal of the competition is to predict whether companies went bankrupt or not in 2018 using their financial statements for the year 2017.

# Data 
Data fields
train.csv contains 733271 rows (plus an extra row with headers) and 112 columns for variables. Here's a brief version of what you'll find in the data file:

column 1 - ID_FIRM - company Id;
columns 2-111 - financial statements as of 01.01.2017 and 01.01.2018;
column 112 - BANKR - whether a company went bankrupt or not in 2018 (0 - no bankruptcy, 1 - bankruptcy).
The column names for the financial statements have the following format:

Pcode_[B|E]

where:

code - a 4-digit code from Form 1 or Form 2.
B (begin) and E (end) mean the date of the parameter, namely 01.01.2017 or 01.01.2018.
E.g. P1230_B is parameter 1230 (accounts receivable) as of 01.01.2017, P2400_E is parameter 2400 (net profit / loss) as of 01.01.2018, etc.

test.csv contains 314259 rows (plus an extra row with headers) and 111 columns for variables. In contrast to train.csv, this file does not contain BANKR column.


[Kaggle](https://www.kaggle.com/competitions/hse-m-psmsimmo-p-347795-1-bankruptcy-2018/data)
