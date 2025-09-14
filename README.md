# Credit-Card-Approval
A basic data science project showcasing the full data science process.

### Note on the time based columns in the raw data sets
* Time in this data is denoted in terms of negative integers
    * Each integer value represents the number of days/ months/ units that have past since the event took place.
    * e.g. for "DAYS_BIRTH" we count backwards from the current day (0), therefore -1 means yesterday
    * e.g. for "DAYS_EMPLOYED" we count backwards from current day(0). If positive, it means the person is currently unemployed. -10 means that is has been 10 days since the person started their job.

### Note on 'Status' column in credit_record.csv
* This column denotes the status of loans and repayments by the particular individual
    * 0: 1-29 days past due 
    * 1: 30-59 days past due 
    * 2: 60-89 days overdue 
    * 3: 90-119 days overdue 
    * 4: 120-149 days overdue 
    * 5: Overdue or bad debts, write-offs for more than 150 days 
    * C: paid off that month 
    * X: No loan for the month


# Licensing
CC0: Public Domain
Canonical URL  https://creativecommons.org/publicdomain/zero/1.0/