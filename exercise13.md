# Exercise 13

## Currency picker

This is the main feature of our TARDIS currency advisor.

Our user has the ability to travel to the past and buy money in other currencies. Our advisor should recommend the best exchange based on the date in order to maximize our investment.

On the currency controller action, use the currency exchange rates from the provided date and today to answer the following question:

**If I were to travel to `date` and could buy money in any currency, in order to come back and sell it in the present, what would be the best currency to invest in?**

When calling `currency/:date`, the user should see a result like this:

_"If you go back to 2001-12-25 you should buy CHF.  You can sell them for a profit when you come back."_

-------------

For bonus points, show both the code and the full name of the currency.
      