# Exercise 19

## Parse coordinates from the query string

Use [QueryStringBindable](https://www.playframework.com/documentation/2.5.x/ScalaRequestBinders) to parse coordinates from the query string.

**Play! 2.4**: The Play! 2.4.x documentation doesn't have a documentation page for `QueryStringBindable`, but you can find the type in the 2.4.x scaladocs: https://www.playframework.com/documentation/2.4.x/api/scala/index.html#play.api.mvc.QueryStringBindable

This should allow your controller method to have a parameter of type Coordinates (or whatever you called your location related type).
      