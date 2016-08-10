# Exercise 16

## Custom coordinates

Our users have discovered they can customize the location they will visit when traveling to the past!

Allow the `/currency/:date` endpoint to include two optional query parameters: `lat` and `long`.

Make sure to validate their values as such:

- If only one is included, return with an error
- Their values must be in a valid range

If coordinates are not provided, default to your [current location](http://mygeoposition.com/loc/49.2638200,-123.1043210/?zoomLevel=undefined&mapType=undefined).

Make sure the weather recommendation is adjusted to the custom coordinates, if provided.

      