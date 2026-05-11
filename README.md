# Account-and-email-activity-analysis-by-country

Query:
1. Counts the number of accounts by date, country and user parameters.
2. Counts the number of sent, opened and visited emails.
3. Combines data about accounts and messages via UNION ALL.
4. Aggregates general metrics by country.
5. Uses window functions to count the total number of accounts and messages by country.
6. Creates a ranking of countries by:
- number of accounts
- number of sent messages.
7. Returns only the TOP-10 countries by these indicators.
