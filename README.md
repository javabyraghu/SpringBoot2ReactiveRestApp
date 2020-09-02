# SpringBoot2ReactiveRestApp
Spring Boot 2 Reactive Rest App

## Spring WebFlux
Spring WebFlux is the new reactive web framework that comes with Spring 5. It is not a replacement for Spring MVC but a fully non-blocking, Reactive Streams back pressure supporting framework that is run on servers like Netty, Jetty, Undertow, etc.
Spring WebFlux majorly uses two publishers:
### The Mono
Mono: Returns 0 or 1 element.
The Mono API allows producing only one value.
Mono<String> mono = Mono.just(“Spring Framework”);
Mono<String> mono = Mono.empty();
This is limited to no more than one element.
### The Flux
Flux: Returns 0…N elements.
The Flux can be endless, it can produce multiple values. Here, we have a static stream of the thee elements.
Flux<String> flux = Flux.just(“One”, “Two”, “Three”);
