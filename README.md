# zipkin-server

 Zipkin is a distributed tracing system. It helps gather timing data needed to troubleshoot latency problems in service architectures.Performance issue and where request is getting failed in multiple microservice call can easily deteced with the help of zipkin.
 
 Zipkin is an open source project that provides mechanisms for sending, receiving, storing, and visualizing traces. This allows us to correlate activity between servers and get a much clearer picture of exactly what is happening in our services.
 
 **To Implement Zipkin Server we need below steps:**
 
* Need to add Zipkin autoconfigure ui and Zipkin server dependency.
* In main class add @EnableZipkinServer.
* Set the port. 9411 is default.
