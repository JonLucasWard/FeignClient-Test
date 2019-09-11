# FeignClient-Test
Non working Feign Client Example

On attempt to launch the FeignClientTest, it fails due to not being able to connect to a Eureka server on US-East.
In spite of the Eureka service running alongside it. If Eureka is not a dependency for that app, it "runs" but is unaccessible and
does not come onto a port.

The Game services and Eureka itself ran fine when I last attempted it (games display a string when accessed, and register with Eureka).

Ideally I want to be able to have the FeignClientTest running at all.
