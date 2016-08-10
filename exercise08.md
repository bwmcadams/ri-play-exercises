# Exercise 8

## Throttle access to the currency page

To prevent abuse, we want to avoid any particular user from performing more than N requests per minute (for a configurable value of N).

You can implement this along with the authentication mechanism you've already implemented. Or, if you have time and are curious, consider using Play's [Filter feature](https://www.playframework.com/documentation/2.5.x/ScalaHttpFilters)

**Play! 2.4**: https://www.playframework.com/documentation/2.4.x/ScalaHttpFilters
      