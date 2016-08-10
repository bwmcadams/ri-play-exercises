# Exercise 18

## Add an /api/currency endpoint

Add an endpoint for `api/currency/:date` with the same behaviour as the existing `/currency` endpoint, but returning a JSON block with the following structure:

```json
{
  "coordinates": {
    "lat": 123.4,
    "long": 32.1
  },
  "recommendation": {
    "code": "GBP",
    "name": "Great British Pounds",
    "expectedProfit": 0.6
  },
  "weatherReminder": ["Sweater", "Umbrella"],
  "triviaFact": "March 11th is the day in 1784 that the signing of the Treaty of Mangalore brings the Second Anglo-Mysore War to an end.",
  "calculatedOn": "2016/03/11 09:01:05"
}
```