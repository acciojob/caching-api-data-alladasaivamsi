# Scenario: Caching API Data
## Problem: Your web application frequently requests data from a third-party API. To minimize the number of API calls and improve performance, you decide to cache the data. Implement a cache system using JavaScript that stores the API response for a given period and serves it from the cache for subsequent requests within that period.
```'X-RapidAPI-Key': 'c3a9a6b376msh528c0d78a1c317ap1759efjsn28df182c8b4f',
'X-RapidAPI-Host': 'financialmarketdata.p.rapidapi.com'```

## Acceptance criteria
- If an api call is made log in the console that the jsonplaceholder call is made
- If website used cached data and didn’t make call to api then log that call is made from cached data
