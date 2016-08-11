# Exercise 16

## Allow calculating prices in several currencies

Using data from [Fixer.io](http://fixer.io), allow the user to select the currency they want to
get pricing information in.

Try to favour type safety when implementing this feature.

For the easiest solution, just grab the latest exchange rates and store them in a file.
For an added challenge, use the Play Json library to fetch the exchange rate in real time.

If you want to use [`play-json`](https://www.playframework.com/documentation/2.3.x/ScalaJson) then 
you can use the version already included in the scalatrain project.