# A high-performance drop-in replacement to carbon-relay and carbon-cache

This is a SpringBoot application.

This provides a replacement Graphite data store.

https://github.com/salesforce/carbonj

## Where to start?

https://github.com/salesforce/carbonj/blob/1.1.16/carbonj.service/src/main/java/com/demandware/carbonj/service/engine/cfgCarbonJ.java

## Threads to pull on

How do Graphite messages get processed and stored?

https://github.com/salesforce/carbonj/blob/1.1.16/carbonj.service/src/main/java/com/demandware/carbonj/service/engine/LineProtocolHandler.java
