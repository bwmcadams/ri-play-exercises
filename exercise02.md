# Exercise 2

## Enable and configure logging

The Play Scala Seed project you started with already has the logback logging library configured.  All logs goto `./logs/application.log`.  Test the logger by creating a logging a custom `INFO` message when the homepage Action is called.

https://www.playframework.com/documentation/2.5.x/ScalaLogging#Using-Loggers

Moving forward, make sure you use thorough logging.

Hint: The `./conf/logback.xml` default log level is set to `WARN` and will need to be modified.

**Play! 2.4**: The Play! 2.4 seed project is not pre-configured to log to files.  Take the opportunity now to set it up correctly by consulting the documentation:

https://www.playframework.com/documentation/2.4.x/ScalaLogging#Using-Loggers