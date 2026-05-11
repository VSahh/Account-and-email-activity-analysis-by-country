# Account and email activity analysis by country

##Query:
1. Counts the number of accounts by date, country and user parameters.
2. Counts the number of sent, opened and visited emails.
3. Combines data about accounts and messages via UNION ALL.
4. Aggregates general metrics by country, using window functions to count the total number of accounts and messages by country. 
5. Creates a ranking of countries by:
- number of accounts
- number of sent messages.
6. Returns only the TOP-10 countries by these indicators.
7. [Visualization in Looker Studio](https://datastudio.google.com/reporting/01a31440-e830-4fc6-b59b-992a668b5384/page/tEnnC)
