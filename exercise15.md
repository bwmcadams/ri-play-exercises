# Exercise 15

## Weather recommendation

Now that the user knows what date she's visiting, we should make a recommendation about appropriate clothing for the weather.

Use the [Forecast.io](https://developer.forecast.io/docs/v2#forecast_call) web service to gather information about the weather on the date the user will visit.

When calling `/currency/:date`, the response should now look like this:

_"If you go back to 2001-12-25 you should buy CHF.  You can sell them for an expected profit of 35.278% when you come back.  Don't forget to bring your Winter Coat."_

Where recommendation is one of:

- **Shorts** if temperature was above 20 degrees
- **Sweater** if temperature was between 10 and 20 degrees
- **Winter Coat** if temperatures was below 10 degrees
- **Umbrella** if it was raining

Assume we are stationary in space and located in central London at the Latitude/Longitude coordinates of `51.5285582,-0.2416781`.

-----------

**NOTE**: you'll need to get an API key, which is free for < 1000 calls per day. Make sure your tests are not overusing this call, or you'll run through your quota too quickly.