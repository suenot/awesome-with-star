# Information comes from [vert-x3/vertx-awesome](https://github.com/vert-x3/vertx-awesome)
# Awesome Vert.x [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="logo-sm.png" align="right" width="250">](http://vertx.io)

*Awesome Vert.x* is a list of awesome frameworks, libraries or other components for use with or that use
[Vert.x](https://github.com/eclipse/vert.x) version 3.

If you want your component to appear here send a pull request to this repository to add it.

Please note that we can't vouch for the stability or production-worthiness of everything on this list unless it has
the icon <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px">
next to it. This icon means the component is part of the official
[Vert.x stack](https://vertx.io/docs/).

For Vert.x version 2 check [this page](./vert-x2.md).

## Contents

- [Books](#books)
- [Build tools](#build-tools)
- [Web Frameworks](#web-frameworks)
- [Authentication Authorisation](#authentication-authorisation)
- [Database Clients](#database-clients)
- [Integration](#integration)
- [Middleware](#middleware)
- [Language Support](#language-support)
- [Reactive](#reactive)
- [Sync Thread Non Block](#sync-thread-non-block)
- [Vert.x Event Bus Clients](#vertx-event-bus-clients)
- [Cluster Managers](#cluster-managers)
- [Cloud Support](#cloud-support)
- [Docker](#docker)
- [Microservices](#microservices)
- [Search Engines](#search-engines)
- [Service Factory](#service-factory)
- [Config](#config)
- [Dependency Injection](#dependency-injection)
- [Testing](#testing)
- [Development Tools](#development-tools)
- [Miscellaneous](#miscellaneous)
- [Distribution](#distribution)
- [Examples](#examples)
- [Deployment](#deployment)
- [Utilities](#utilities)
- [Front-End](#front-end)

## Books

* [A gentle guide to asynchronous programming with Eclipse Vert.x for Java developers](http://vertx.io/docs/guide-for-java-devs/) by Julien Ponge, Thomas Segismont and Julien Viet
* [Building Reactive Microservices in Java](https://developers.redhat.com/promotions/building-reactive-microservices-in-java/) by Clément Escoffier

## Build tools

* [Vert.x Maven plugin](https://github.com/fabric8io/vertx-maven-plugin) :star:24
* [Vert.x Gradle plugin](https://plugins.gradle.org/plugin/io.vertx.vertx-plugin)

## Web Frameworks

* [Vert.x Web](https://github.com/vert-x3/vertx-web)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Full featured web toolkit for Vert.x.
* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) - Create JAX-RS [Jersey](https://jersey.java.net/) resources in Vert.x. :star:138
* [Kovert](https://github.com/kohesive/kovert) - Invisible REST framework for Kotlin + Vert.x Web. :star:115
* [Handlers](https://github.com/spriet2000/vertx-handlers-http) - Open web framework for Vert.x. :star:8
* [QBit](https://github.com/advantageous/qbit) - REST and WebSocket method call marshaling and reactive library. :star:638
* [vertx-rest-storage](https://github.com/swisspush/vertx-rest-storage) - Persistence for REST resources in the filesystem or a redis database. :star:14
* [Jubilee](https://github.com/isaiah/jubilee) - A rack compatible Ruby HTTP server built on Vert.x 3. :star:336
* [Knot.x](https://github.com/Cognifide/knotx) - Efficient & high-performance integration platform for modern websites built on Vert.x 3. :star:97
* [Vert.x Jspare](https://github.com/jspare-projects/vertx-jspare) - Improving your Vert.x 3 experience with Jspare Framework. :star:10
* [Irked](https://github.com/GreenfieldTech/irked) - Annotations-based configuration for Vert.x 3 Web and controller framework. :star:12
* [REST.VertX](https://github.com/zandero/rest.vertx) - Lightweight JAX-RS (RestEasy) like annotation processor for Vert.x verticals. :star:68
* [Atmosphere Vert.x](https://github.com/Atmosphere/atmosphere-vertx) - Realtime Client Server Framework for the JVM, supporting WebSockets and Server Sent Events with Cross-Browser Fallbacks. :star:33
* [Vert.x Vaadin](https://github.com/mcollovati/vertx-vaadin) - Run Vaadin applications on Vert.x. :star:5

## Authentication Authorisation

* [Vert.x Auth JDBC](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-jdbc)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x authentication/authorisation JDBC based.
* [Vert.x Auth JWT](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-jwt)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation based on JSON Web Tokens.
* [Vert.x Auth Shiro](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-shiro)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x AuthN/AuthZ based on [Apache Shiro](http://shiro.apache.org/).
* [Vert.x Auth htdigest](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-htdigest)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [Apache htdigest](https://httpd.apache.org/docs/2.4/programs/htdigest.html).
* [Vert.x Auth Mongo](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-mongo)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [MongoDB](https://www.mongodb.com/).
* [Vert.x Auth OAuth2](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-oauth2) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [OAuth 2](https://oauth.net/2/).
* [Vert.x Auth htpasswd](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-htpasswd) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [htpasswd](https://httpd.apache.org/docs/2.4/programs/htpasswd.html).

* [Vert.x-Pac4j](https://github.com/pac4j/vertx-pac4j) - Vert.x authentication/authorisation implemented using [pac4j](http://www.pac4j.org/). :star:85

## Database Clients

*Clients for connecting to databases*

* Relational Databases
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous interface around a JDBC datasource.
  * [MySQL / PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous Client for MySQL/PostgreSQL.
  * [PostgreSQL](https://github.com/vietj/reactive-pg-client) - Reactive PostgreSQL Client. :star:2
  * [database](https://github.com/susom/database) - Client for Oracle, PostgreSQL, SQL Server, HyperSQL, etc. designed for security, correctness, and ease of use. :star:26
  * [jOOQ](https://github.com/jklingsporn/vertx-jooq) - Doing typesafe, asynchronous SQL and generate code using jOOQ. :star:120

* NoSQL Databases
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - An asynchronous client for interacting with a MongoDB database.
  * [Redis](https://github.com/vert-x3/vertx-redis-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous API to interact with Redis.
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) - Asynchronous API to interact with Cassandra and Cassandra Mapping. :star:38
  * [OrientDB](https://github.com/cstamas/vertx-orientdb) - Non-blocking OrientDB server integration. :star:7
  * [Bitsy](https://github.com/cstamas/vertx-bitsy) - Non-blocking Bitsy Graph server integration. :star:1
  * [MarkLogic](https://github.com/etourdot/vertx-marklogic) - Asynchronous client for Marklogic Database Server. :star:2

* [vertx-pojo-mapper](https://github.com/BraintagsGmbH/vertx-pojo-mapper) - Non-blocking POJO mapping for MySQL and MongoDB. :star:42
* [vertx-mysql-binlog-client](https://github.com/guoyu511/vertx-mysql-binlog-client) - A Vert.x client for tapping into MySQL replication stream. :star:13
* [vertx-mongo-streams](https://github.com/st-h/vertx-mongo-streams) - Helpers to pump Vert.x streams to/from MongoDB GridFS using the MongoDB async driver. :star:4

## Integration

* Server-Sent Events
  * [jEaSSE](https://github.com/mariomac/jeasse) - Java Easy SSE. A simple, lightweight implementation of SSE. :star:38
  * [vertx-sse](https://github.com/aesteve/vertx-sse) - Vert.x SSE implementation + event-bus SSE bridge. :star:19

* Mail
  * [SMTP](https://github.com/vert-x3/vertx-mail-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Async SMTP client.
  * [vertx-smtp-server](https://github.com/cinterloper/vertx-smtp-server) - SMTP server bridging to EventBus. :star:3

* REST
  * [Vertx REST Client](https://github.com/hubrick/vertx-rest-client) - A REST client for vertx with support for RxJava and request caching. :star:33
  * [Retrofit adapter for Vert.x](https://github.com/vietj/retrofit-vertx) - A highly scalable adapter for Retrofit with Vert.x. :star:21

* Messaging
  * [AMQP 1.0](https://github.com/vert-x3/vertx-amqp-bridge) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Interact with AMQP 1.0 servers using the Vert.x Producer and Consumer APIs.
  * [MQTT](https://github.com/vert-x3/vertx-mqtt) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Provides two different components : an MQTT server for handling all the MQTT communication and messages exchanges with clients and an MQTT client for sending and receiving messages against an MQTT broker.
  * [RabbitMQ](https://github.com/vert-x3/vertx-rabbitmq-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A RabbitMQ client (AMQP 0.9.1).
  * [Kafka Client](https://github.com/vert-x3/vertx-kafka-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A Kafka client.
  * [kafka](https://github.com/cyngn/vertx-kafka) - Kafka client for consuming and producing messages. :star:27
  * [Kafka Service](https://github.com/hubrick/vertx-kafka-service) - Kafka producer and consumer with retry logic. :star:23
  * [SaltStack](https://github.com/cinterloper/vertx-salt) - A bi-directional bridge between the SaltStack event system and the Vert.x event bus. :star:2
  * [STOMP](https://github.com/vert-x3/vertx-stomp) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A Kafka client and server.
  * [ZeroMQ](https://github.com/dano/vertx-zeromq) - ZeroMQ Event Bus bridge. :star:5
  * [MQTT Broker](https://github.com/GruppoFilippetti/vertx-mqtt-broker) - MQTT Broker (MQTT ver. 3.1.1 and 3.1 compliant). :star:140
  * [Azure ServiceBus](https://github.com/TextBack/vertx-azure-servicebus) - Azure [ServiceBus](https://azure.microsoft.com/en-us/services/service-bus/) producer and consumer (fully async, doesn't use Microsoft Azure SDK).
  * [AMQP 1.0 - Kafka bridge](https://github.com/rhiot/amqp-kafka-bridge) - Bridge for sending/receiving messages to/from Apache Kafka using the AMQP 1.0 protocol. :star:54
  * [Vertx Kafka Client](https://github.com/vert-x3/vertx-kafka-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Apache Kafka client for reading and sending messages from/to an Apache Kafka cluster.

* JavaEE
  * [JCA adaptor](https://github.com/vert-x3/vertx-jca) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Java Connector Architecture Adaptor for the Vert.x event bus.
  * [Weld](https://github.com/weld/weld-vertx) - Brings the CDI programming model into the Vert.x ecosystem (register CDI observer methods as Vert.x message consumers, CDI-powered Verticles, define routes in a declarative way, etc.). :star:42

* Meteor
  * [Meteor](https://github.com/jmusacchio/vertxbus/) - Meteor integration support through Vert.x event bus. :star:17

* Metrics
  * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) - [Hawkular](http://www.hawkular.org/) implementation of the Vert.x Metrics SPI. :star:5
  * [DropWizard metrics](https://github.com/vert-x3/vertx-dropwizard-metrics) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Metrics implementation using DropWizard metrics.
  * [Micrometer metrics](https://github.com/vert-x3/vertx-micrometer-metrics) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Metrics implementation using Micrometer metrics.
  * [OpenTsDb Metrics](https://github.com/cyngn/vertx-opentsdb) - [OpenTsDb](http://opentsdb.net/) metrics client for Vert.x. :star:9
  * [Bosun Monitoring](https://github.com/cyngn/vertx-bosun) - [Bosun](https://bosun.org/) client library for Vert.x. :star:3

* Netflix - Hystrix
  * [Hystrix Metrics Stream](https://github.com/kennedyoliveira/hystrix-vertx-metrics-stream.git) - Emits metrics for Hystrix Dashboard from a Vertx application with [Hystrix](https://github.com/Netflix/Hystrix). :star:13

* Dart
  * [Vert.x Dart SockJS](https://github.com/wem/vertx-dart-sockjs) - [Dart](https://www.dartlang.org/) integration for [Vert.x SockJS bridge](http://vertx.io/docs/vertx-web/java/#_sockjs_event_bus_bridge) and plain SockJS with use of dart:js.

* Push Notifications
  * [Onesignal](https://github.com/jklingsporn/vertx-push-onesignal) - Send push notifications to (mobile/web) apps from your Vertx application with [OneSignal](https://onesignal.com/). :star:10

## Middleware

* [Apache Camel](https://github.com/apache/camel/blob/master/components/camel-vertx/src/main/docs/vertx-component.adoc) - [Apache Camel](http://camel.apache.org/) component for bridging Camel with the Vert.x event bus. :star:2167
* [Gateleen](https://github.com/swisspush/gateleen) - Middleware library based on Vert.x to build advanced JSON/REST communication servers. :star:53
* [Gravitee.io](https://gravitee.io) - An OSS API Platform including an API Gateway and an OAuth2 / OIDC authorization server based on Vert.x Core / Vert.x Web and other modules.

## Language Support

*Programming language support for Vert.x*

* [Ceylon](https://github.com/vert-x3/vertx-lang-ceylon) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ceylon support.
* [Groovy](https://github.com/vert-x3/vertx-lang-groovy) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Groovy support.
* [Java](https://github.com/eclipse/vert.x) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x main repository (including the Java API).
* [JavaScript](https://github.com/vert-x3/vertx-lang-js) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - JavaScript support.
* [Python](https://github.com/vert-x3/vertx-lang-python) - Python support. :star:7
* [Ruby](https://github.com/vert-x3/vertx-lang-ruby) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ruby support.
* [Scala](https://github.com/vert-x3/vertx-lang-scala) - <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Scala support. :star:70
* [Kotlin](https://github.com/vert-x3/vertx-lang-kotlin) - <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Kotlin support. :star:98
* [TypeScript](https://github.com/michel-kraemer/vertx-lang-typescript) - TypeScript support. :star:49

*Language extensions*

* [Grooveex](https://github.com/aesteve/grooveex) - Syntactic sugar + utilities (DSL builders, etc.) on top of [vertx-lang-groovy](https://github.com/vert-x3/vertx-lang-groovy). :star:11

## Reactive

* [Reactive Streams](https://github.com/vert-x3/vertx-reactive-streams) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Reactive Streams.
* [Vert.x Rx](https://github.com/vert-x3/vertx-rx) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Reactive Extensions.
* [Vert.x Sync](https://github.com/vert-x3/vertx-sync) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x fiber support.
* [Kotlin coroutines](https://github.com/vert-x3/vertx-lang-kotlin/tree/master/vertx-lang-kotlin-coroutines) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x support for kotlin coroutines.
* [vertx-util](https://github.com/cyngn/vertx-util) - Light weight promises & latches for Vert.x. :star:17
* [QBit](https://github.com/advantageous/qbit) - Async typed actor-like lib that runs easily in Vert.x Async Callbacks. Callback management. :star:638
* [VxRifa](https://nsforth.github.io/vxrifa) - Utility library for Vert.X that allows using strong-typed interfaces in communication through EventBus.

## Sync Thread Non Block

* [Sync](https://github.com/vert-x3/vertx-sync) - Synchronous but non-OS-thread-blocking verticles. :star:66

## Vert.x Event Bus Clients

*Clients to connect applications to the Vert.x event bus*

* [JavaScript](https://www.npmjs.com/package/vertx3-eventbus-client) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - JavaScript event bus client.
* [C++11](https://github.com/julien3/vertxbuspp) - C++11 event bus client. :star:10
* [Java](https://github.com/saffron-technology/vertx-eventbusbridge) - Java implementation of vertxbus.js. :star:16
* [Java](https://github.com/abdlquadri/vertx-eventbus-java) - Java and Android Event Bus Client. :star:15
* [Java](https://github.com/danielstieger/javaxbus) - Simple Java Event Bus Client using plain TCP socket I/O. :star:7
* [CLI](https://github.com/cinterloper/vxc) - Command-line binary client for Vert.x event bus - pipe in JSON, emit JSON. :star:2
* [Swift](https://github.com/tobias/vertx-swift-eventbus) - Event bus client for [Apple's Swift](https://swift.org) using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge). :star:5
* [Python](https://github.com/jaymine/TCP-eventbus-client-Python) - Event bus client for Python using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge). :star:8
* [C#](https://github.com/jaymine/TCP-eventbus-client-C-Sharp) - Event bus client for C# using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C](https://github.com/jaymine/TCP-eventbus-client-C) - Event bus client for C99 using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge). :star:3
* [Go](https://github.com/jponge/vertx-go-tcp-eventbus-bridge)- Event bus client for Go-lang using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Smalltalk](https://github.com/mumez/VerStix)- Event bus client for [Pharo Smalltalk](http://pharo.org/) using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Java](https://github.com/nielsbaloe/vertxui/tree/master/vertxui-core/src/main/java/live/connector/vertxui/client/transport) - Event bus support in JavaScript through Java code. :star:92

## Cluster Managers

*Implementations of the Vert.x cluster manager SPI*

* [Hazelcast Cluster Manager](https://github.com/vert-x3/vertx-hazelcast) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Hazelcast cluster manager.
* [Ignite Cluster Manager](https://github.com/vert-x3/vertx-ignite) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ignite cluster manager.
* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) - JGroups cluster manager. :star:5
* [Zookeeper Cluster Manager](https://github.com/vert-x3/vertx-zookeeper) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Zookeeper cluster manager.
* [Atomix Cluster Manager](https://github.com/atomix/atomix-vertx) - An [Atomix](http://atomix.io) based cluster manager implementation for Vert.x 3. :star:21
* [Infinispan Cluster Manager](https://github.com/vert-x3/vertx-infinispan) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Infinispan cluster manager.

## Cloud Support

* [OpenShift DIY cartridge](https://github.com/vert-x3/vertx-openshift-diy-quickstart) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - OpenShift DIY Cartridge using Vert.x.
* [OpenShift Vert.x cartridge](https://github.com/vert-x3/vertx-openshift-cartridge) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - OpenShift Vert.x Cartridge using Vert.x.
* [S3](https://github.com/hubrick/vertx-s3-client) - A fully functional Vert.x client for S3. :star:18

## Docker

* [Docker images](https://github.com/vert-x3/vertx-stack/tree/master/stack-docker) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Docker images for Vert.x.

## Microservices

* [Service Discovery](https://github.com/vert-x3/vertx-service-discovery) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery" height="16px"> - Vert.x Service Discovery.
* [Circuit Breaker](https://github.com/vert-x3/vertx-circuit-breaker) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Circuit Breaker" height="16px"> - Vert.x Circuit Breaker.
* [Service Discovery - Consul](https://github.com/vert-x3/vertx-service-discovery) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Consul" height="16px"> - [Consul](https://www.consul.io/) extension to Vert.x Service Discovery.
* [Service Discovery - Docker links](https://github.com/vert-x3/vertx-service-discovery) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Docker Links" height="16px"> - [Docker](https://www.docker.com/) extension to Vert.x Service Discovery.
* [Service Discovery - Kubernetes](https://github.com/vert-x3/vertx-service-discovery) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Kubernetes" height="16px"> - [Kubernetes](http://kubernetes.io/) extension to Vert.x Service Discovery.
* [Service Discovery - Redis backend](https://github.com/vert-x3/vertx-service-discovery) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Redis backend" height="16px"> - [Redis](http://redis.io/) storage backend for Vert.x Service Discovery.
* [Vert.x GraphQL Service Discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - [GraphQL](http://graphql.org/) service discovery and querying for your Vert.x microservices. :star:32
* [HTTP Request Multiplexer - Kalfor](https://github.com/derveloper/kalfor) - Combine multiple HTTP GET requests into a single POST. A dead simple alternative to Facebook's [GraphQL](http://graphql.org/) and Netflix's [Falcor](http://netflix.github.io/falcor/). :star:7
* [Resilience4j](https://github.com/resilience4j/resilience4j) - Resilience4j is a fault tolerance library designed for Java8 and functional programming. Resilience4j provides modules for Circuit Breaking, Rate Limiting, Bulkheading, Automatic retrying, Response caching and Metric measuring. :star:1096

## Search Engines

* [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) - Vert.x 3 [Elasticsearch](https://www.elastic.co/) service with event bus proxying. :star:53
* [Vert.x Elasticsearch Service (redesign)](https://github.com/hubrick/vertx-elasticsearch-service) - Vert.x 3 [Elasticsearch](https://www.elastic.co/) service with event bus proxying. Redesign of the [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service). Heavy usage of DTOs over eventbus and no more JsonObjects. Added support for ES plugins. :star:17
* [Vert.x Solr Service](https://github.com/englishtown/vertx-solr-service) - Vert.x 3 Solr service with event bus proxying. :star:5

## Service Factory

* [Service Factory](https://github.com/vert-x3/vertx-service-factory) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Service Factory.
* [Maven Service Factory](https://github.com/vert-x3/vertx-maven-service-factory) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Maven Vert.x Service Factory.
* [HTTP Service Factory](https://github.com/vert-x3/vertx-http-service-factory) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x HTTP Service Factory.
* [Node.js Service Factory](https://github.com/mellster2012/vertx-nodejs-service-factory) - Vert.x Node.js Service Factory. :star:3
* [Eclipse SISU Service Factories](https://github.com/cstamas/vertx-sisu) - Vert.x integration with [Eclipse SISU](https://www.eclipse.org/sisu/) DI container offering alternatives for `vertx-service-factory` and `vertx-maven-service-factory`. :star:2

## Config

* [Vertx Config AWS SSM Store](https://github.com/Finovertech/vertx-config-aws-ssm) - A [config store](http://vertx.io/docs/vertx-config/java/) implementation for retrieving configuration values from the [AWS EC2 SSM Parameter Store](https://aws.amazon.com/ec2/systems-manager/parameter-store/).
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - Deploying verticles from a HOCON configuration. :star:19

## Dependency Injection

* [Vert.x Guice](https://github.com/englishtown/vertx-guice) - Vert.x verticle factory for Guice dependency injection. :star:48
* [Vert.x HK2](https://github.com/englishtown/vertx-hk2) - Vert.x verticle factory for HK2 dependency injection. :star:22
* [Spring Vert.x Extension](https://github.com/amoAHCP/spring-vertx-ext) - Vert.x verticle factory for Spring DI injection. :star:42
* [Vert.x Beans](https://github.com/rworsnop/vertx-beans) - Inject Vert.x objects as beans into your Spring application. :star:14
* [QBit](https://github.com/advantageous/qbit) - QBit works with Spring DI and Spring Boot (and of course Vertx). Allows you to use QBit, Vertx, Spring DI and Spring Boot in the same application. :star:638
* [Vert.x Eclipse SISU](https://github.com/cstamas/vertx-sisu) - Vert.x integration with [Eclipse SISU](https://www.eclipse.org/sisu/) DI container. :star:2
* [Vert.x Spring Verticle Factory](https://github.com/juanavelez/vertx-spring-verticle-factory) - A Vert.x Verticle Factory that makes use of Spring to obtain and configure Verticles. :star:3

## Testing

* [Vert.x Unit](https://github.com/vert-x3/vertx-unit) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Async polyglot unit testing for Vert.x.

## Development Tools

* [Vert.x shell](https://github.com/vert-x3/vertx-shell)  <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Allows for interaction with Vert.x from the command line.
* [Vert.x health check](https://github.com/vert-x3/vertx-health-check) - Allows for remote health checking in Vert.x projects. :star:4
* [Vert.x Hot](https://github.com/dazraf/vertx-hot) - A Maven plugin for the hot-deploy of Maven Vert.x projects. :star:40
* [slush-vertx](https://www.npmjs.com/package/slush-vertx) - A template driven Vert.x project generator for different languages and build tools.
* [Vert.x for Visual Studio Code](https://github.com/pmlopes/VertxSnippet) - A Visual Studio Code (polyglot) plugin for Vert.x. Also available from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=pmlopes.vertxsnippet). :star:1
* [Vert.x Starter](http://www.jetdrone.xyz/vertx-starter/) - A browser-based project starter and project templates for Vert.x applications.
* [Vert.x LiveReload](https://github.com/ybonnel/vertx-livereload) - A simple livereload server for Vert.x applications. :star:8

## Miscellaneous

* [Vert.x Child Process](https://github.com/vietj/vertx-childprocess) - Spawn child process from Vert.x. :star:29
* [vertx-redisques](https://github.com/swisspush/vertx-redisques) - A highly scalable redis-persistent queuing system for Vert.x. :star:11
* [Simple File Server](https://github.com/pitchpoint-solutions/sfs) - An OpenStack Swift compatible distributed object storage server that can serve and securely store billions of large and small files using minimal resources implemented using Vert.x. :star:44
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - Deploying verticles from a HOCON configuration. :star:19
* [GDH](https://github.com/maxamel/GDH) - Generalized Diffie-Hellman key exchange Java library built on top of Vert.x. :star:29

## Distribution

* [Vert.x Stack](https://github.com/vert-x3/vertx-stack) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x + the endorsed modules.

## Examples

* [Vert.x blueprint - Microservice application](https://github.com/sczyh30/vertx-blueprint-microservice) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a complex microservice application.
* [Vert.x blueprint - Job Queue](https://github.com/sczyh30/vertx-blueprint-job-queue) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a distributed job processing application.
* [Vert.x blueprint - TODO backend](https://github.com/sczyh30/vertx-blueprint-todo-backend) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a backend for a TODO application.
* [Vert.x examples](https://github.com/vert-x3/vertx-examples) <img src="https://rawgit.com/vert-x3/vertx-awesome/d93d327/vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x examples including web examples, how to use the official database clients, etc.
* [Vert.x feeds](https://github.com/aesteve/vertx-feeds) - Example of an RSS aggregator built using Vert.x, Gradle, MongoDB, Redis, Handlebars templates, AngularJS, the event bus and SockJS. :star:110
* [Vert.x Markdown service](https://github.com/aesteve/vertx-markdown-service) - Example on how to use [service-proxy](https://github.com/vert-x3/vertx-service-proxy) with Gradle. :star:6
* [Example using event bus and service proxies to connect vertx and node](https://github.com/advantageous/vertx-node-ec2-eventbus-example) - Step by step example with wiki description showing how to connect Vert.x and Node using event bus and service proxies. :star:40
* [Vert.x Todo-Backend implementation](https://github.com/aesteve/todo-backend-vertx) - Pure Java 8 implementation of the Todo MVC backend. Uses a Vert.x LocalMap for storage. :star:3
* [Kotlin Todo-Backend implementation](https://github.com/aesteve/vertx-kotlin-todomvc) - Kotlin implementation of the Todo MVC backend. :star:7
* [Scala Todo-Backend implementation](https://github.com/aesteve/vertx-scala-todomvc) - Scala implementation of the Todo MVC backend. :star:1
* [Grooveex Todo-Backend implementation](https://github.com/aesteve/todo-backend-grooveex) - Todo MVC backend implementation with Vert.x + Groovy + some syntactic sugar + DSL routing facilities.
* [Vert.x Gradle Starter](https://github.com/yyunikov/vertx-gradle-starter) - Java 8 starter application with example of using Vert.x with Gradle build system, profiles configuration and SLF4J. :star:6
* [Vert.x Gentics Mesh Example](https://github.com/gentics/mesh-vertx-example) - Example on how to build a template-based web server with Gentics Mesh and handlebars. :star:10
* [HTTP/2 showcase](https://github.com/aesteve/http2-showcase) - A simple demo, showing how HTTP/2 can drastically improve user experience when a huge latency is involved. :star:7
* [Vert.x Music Store](https://github.com/tsegismont/vertx-musicstore) - An example application on how to build Vert.x applications with RxJava. :star:38
* [Crabzilla](https://github.com/crabzilla/crabzilla) - Yet another Event Sourcing experiment. A project exploring Vert.x to develop Event Sourcing / CQRS applications. :star:23
* [Vert.x PostgreSQL Starter](https://github.com/BillyYccc/vertx-postgresql-starter) - A starter to build a monolithic CRUD RESTful Web Service with Vert.x stack and PostgreSQL. :star:14
* [Cloud Foundry](https://github.com/amdelamar/vertx-cloudfoundry) - An example Vert.x for deploying to a [Cloud Foundry](https://www.cloudfoundry.org/) service provider. :star:1

## Deployment

* [Vert.x Deploy Application](https://github.com/msoute/vertx-deploy-tools) - (Seamless) deploy to AWS based Vert.x application clusters. :star:43

## Utilities

* [Chime](https://github.com/LisiLisenok/Chime) - Time scheduler working on Vert.x event bus allowing for scheduling with _cron-style_ and _interval_ timers. :star:18
* [Vert.x Cron](https://github.com/diabolicallabs/vertx-cron) - Schedule events with cron specifications. Has event bus and Observable versions. :star:31
* [Vert.x POJO config](https://github.com/aesteve/vertx-pojo-config) - Allows for mapping between standard JSON configuration and a (type-safe) configuration Java bean. Also allows the configuration bean to be validated through JSR 303. :star:3
* [Vert.x Async](https://github.com/gchauvet/vertx-async) - Portage of caolan/async nodejs module to Vert.x framework that provides helpers methods for common async patterns. :star:13
* [Vert.x JOLT](https://github.com/lusoalex/vertx-jolt) - JSON to JSON transformation tool based on the original bazaarvoice JOLT project. Helpful to transform different json structure into an expected json format. :star:4
* [Vert.x Dependent Verticle Deployer](https://github.com/juanavelez/vertx-dependent-verticle-deployer) - A Vert.x Verticle intended to deploy verticles and their dependent verticles. :star:4
* [Vert.x Dataloader](https://github.com/engagingspaces/vertx-dataloader) - Java port of Facebook Dataloader for Vert.x. Efficient batching and caching for your data layer. :star:47
* [Vert.x Util](https://github.com/juanavelez/vertx-util) - A collection of Vert.x utility methods. :star:2
* [Vert.x Web Accesslog](https://github.com/romanpierson/vertx-web-accesslog) - Just a simple handler to be used in Vert.x Web to generate access logs. :star:13
* [Vert.x GraphQL Utils](http://github.com/tibor-kocsis/vertx-graphql-utils) - A route handler and Vert.x compatible interfaces to handle GraphQL queries in Vert.x and Vert.x Web. :star:15
* [Nannoq-Tools](https://noriginmedia.github.io/nannoq-tools/) - Nannoq-Tools is a toolkit for constructing robust, scalable and distributed applications leveraging Vert.x including modules for authentication, cluster management, Firebase Cloud Messaging, DynamoDB, fully generic queries, REST, and more.

## Community

- [User Group](https://groups.google.com/forum/?fromgroups#!forum/vertx) - Discuss all user issues related to *using* Vert.x.
- [Developer Group](https://groups.google.com/forum/?fromgroups#!forum/vertx-dev) - A group for Vert.x core *developers* and *contributors*.
- [Gitter chat](https://gitter.im/eclipse-vertx/vertx-users) general chat for Vert.x releated chat.
- [Issues](https://github.com/vert-x3/issues/issues) - Vert.x core issue tracker. :star:29
- [Wiki](https://github.com/vert-x3/wiki/wiki) - Contains useful information about Vert.x. :star:120
- [Learning Materials](http://vertx.io/materials/) - A list of articles and presentations on Vert.x.
- [Blog](http://vertx.io/blog/) - The official Vert.x blog containing many tutorials and other information.
- [2017 Events](https://github.com/vert-x3/wiki/wiki/Vert.x-2017-Events) - A list of 2017 Vert.x talks and presentations. :star:120

## Social events / Meetups

- [Amsterdam/The Netherlands](https://www.meetup.com/Vert-x-NL)
- [Paris](https://www.meetup.com/Paris-vert-x-Meetup/)

## Front-End

* [VertxUI](https://github.com/nielsbaloe/vertxui) - A pure Java front-end toolkit with descriptive fluent views-on-models, POJO traffic, JUnit testing on the virtual DOM or mixed-language on a real DOM, and more. :star:92

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

