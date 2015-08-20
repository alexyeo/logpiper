# logpiper

logpiper is a centralized log collection service to capture application and system log data. It is built in the spirit of Splunk and Loggly, but targeted for deployment in on-premise environments. 

The reality of application development is that there will always be systems that can never be exposed to the Internet or deployed to public clouds. In such situations, SaaS solutions, like Splunk and Loggly, will be unavailable to these categories of applications. Thus, the birth of logpiper.

In fact, logpiper will be similar to [Moonlit Software logFaces](http://www.moonlit-software.com/).

## Design

Protocols supported: UDP, TCP and RESTful
Type: Log4J xml format, NLog ...
