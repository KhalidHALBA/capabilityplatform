This is an implementation of a capability based IoT platform for the simulation of IoT microservices. 
This project contains two microservices : 

- an autonomous vehicle experiment verticle which connects to a UCEF DB containing the outcome of an experiment run. 
- a smart building weather verticle which generates data (temperature, humidity, and particulate matter[air quality]) and publishes it in the event bus.

Both Verticles connect to a hazelcast cluster of verticles which provides the discovery infrastructure.
