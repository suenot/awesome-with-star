# Information comes from [lauris/awesome-scala](https://github.com/lauris/awesome-scala)

Awesome Scala [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
=============

A community driven list of useful Scala libraries, frameworks and software. This is not a catalog of all the libraries, just a starting point for your explorations. Inspired by [awesome-python](https://github.com/vinta/awesome-python). Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

Also awesome is [Scaladex](https://index.scala-lang.org/), the searchable, tagged, and centralized index of Scala libraries.

Projects with over 500 stargazers are in bold.

## Table of Contents

- [Learning Scala](#learning-scala)
- [Projects](#projects)
    - [Android](#android)
    - [Artificial Intelligence](#artificial-intelligence)
    - [Authentication](#authentication)
    - [Authorization](#authorization)
    - [Big Data](#big-data)
    - [Cryptography](#cryptography)
    - [CSV](#csv)
    - [Data Binding and Validation](#data-binding-and-validation)
    - [Database](#database)
    - [DevOps](#devops)
    - [Distributed Systems](#distributed-systems)
    - [Extensions](#extensions)
    - [Functional Reactive Programming](#functional-reactive-programming)
    - [Geospatial](#geospatial)
    - [Graphical User Interfaces](#graphical-user-interfaces)
    - [HTTP](#http)
    - [i18n](#i18n)
    - [Image processing and image analysis](#image-processing-and-image-analysis)
    - [JavaScript](#javascript)
    - [JSON](#json)
    - [Markdown](#markdown)
    - [Metrics and Monitoring](#metrics-and-monitoring)
    - [Misc](#misc)
    - [Modularization and Dependency Injection](#modularization-and-dependency-injection)
    - [Parsing](#parsing)
    - [Reactive Web Frameworks](#reactive-web-frameworks)
    - [Sbt plugins](#sbt-plugins)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Scheduling](#scheduling)
    - [Semantic Web](#semantic-web)
    - [Serialization](#serialization)
    - [Templating](#templating)
    - [Testing](#testing)
    - [Tools](#tools)
    - [Web Frameworks](#web-frameworks)
    - [XML / HTML](#xml--html)
    - [YAML](#yaml)
- [Resources](#resources)
    - [Newsletters](#newsletters)
    - [Podcasts](#podcasts)
- [Contributing](#contributing)

## Artificial Intelligence

* [CIlib ★ 82](https://github.com/cirg-up/cilib) - Typesafe, purely functional Computational Intelligence. :star:86
* [CIlib-tutorial ★ 2](https://github.com/cirg-up/cilib-tutorial) - A tutorial book for cilib. :star:3

## Database

*Database access libraries in Scala.*

* [Anorm ★ 135](https://github.com/playframework/anorm) - Simple SQL data access. :star:162
* [Casbah](http://mongodb.github.io/casbah/) ([repo](https://github.com/mongodb/casbah)) - Officially supported Scala driver for MongoDB :star:540
* [CouchDB-Scala ★ 59 ⧗ 21](https://github.com/beloglazov/couchdb-scala) - Purely functional Scala client for CouchDB :star:62
* **[doobie ★ 812 ⧗ 0](https://github.com/tpolecat/doobie)** - Pure functional JDBC layer for Scala.
* **[Elastic4s ★ 1049 ⧗ 0](https://github.com/sksamuel/elastic4s)** - A scala DSL / reactive client for Elasticsearch
* [Finagle ★ 42 ⧗ 71](https://github.com/finagle/finagle-postgres) - PostgreSQL protocol support for Finagle :star:62
* [longevity ★ 78 ⧗ 21](https://github.com/longevityframework/longevity) - A Persistence Framework for Scala and NoSQL with a Domain Driven Design Orientation :star:96
* [lucene4s ★ 3 ⧗ 56](https://github.com/outr/lucene4s) - Light-weight convenience wrapper around Lucene to simplify complex tasks and add Scala sugar. :star:20
* [MapperDao ★ 12 ⧗ 36](https://github.com/kostaskougios/mapperdao) - An ORM library for oracle, mysql, mssql, and postgresql :star:10
* [Memcontinuationed ★ 51 ⧗ 245](https://github.com/Atry/memcontinuationed) - Memcached client for Scala. :star:50
* [Morpheus ★ 104 ⧗ 0](https://github.com/outworkers/morpheus) - Reactive type safe Scala Driver for MySQL/Postgres. :star:103
* [neo4akka ★ 6 ⧗ 117](https://github.com/outr/neo4akka) - Neo4j Scala client using Akka HTTP with compile-time query interpolation, case class support, true non-blocking IO, and much more. :star:14
* **[Phantom ★ 903 ⧗ 5](https://github.com/outworkers/phantom)** - Reactive typed Scala driver for Apache Cassandra.
* **[PostgreSQL and MySQL async ★ 983 ⧗ 0](https://github.com/mauricio/postgresql-async)** - Async database drivers to talk to PostgreSQL and MySQL in Scala.
* [Pulsar4s ★ 15](https://github.com/sksamuel/pulsar4s) - Scala client for Apache Pulsar. :star:73
* **[Quill ★ 865 ⧗ 0](https://github.com/getquill/quill)** - Compile-time Language Integrated Query for Scala
* [ReactiveCouchbase](http://reactivecouchbase.org/) - Reactive Scala Driver for Couchbase. Also includes a Play plug-in. An official plug-in is also in development.
* **[ReactiveMongo ★ 704 ⧗ 8](https://github.com/ReactiveMongo/ReactiveMongo)** - Reactive Scala Driver for MongoDB.
* **[rediscala ★ 642 ⧗ 0](https://github.com/etaty/rediscala)** - Non-blocking, Reactive Redis driver for Scala (with Sentinel support)
* [Relate ★ 110 ⧗ 7](https://github.com/lucidsoftware/relate) - Lightweight, blazing-fast database access layer for Scala that abstracts the idiosyncricies of the JDBC while keeping complete control over the SQL. :star:152
* [Salat ★ 490 ⧗ 9](https://github.com/salat/salat/) - ORM for MongoDB. A related Play-plugin is also available. :star:501
* [Scala ActiveRecord ★ 297 ⧗ 3](https://github.com/aselab/scala-activerecord) - ORM library for scala, inspired by ActiveRecord of Ruby on Rails. :star:314
* [Scala-Forklift ★ 91 ⧗ 1](https://github.com/lastland/scala-forklift) - Type-safe database migration for Slick, Git, etc. :star:147
* **[scala-redis ★ 739 ⧗ 1](https://github.com/debasishg/scala-redis)** - A Scala library for connecting to a redis server, with clustering support
* [scala-sql ★ 14 ⧗ 34](https://github.com/wangzaixiang/scala-sql) - Yet another SQL-based DB access library for scala language :star:43
* [ScalaRelational ★ 51 ⧗ 1](https://github.com/outr/scalarelational) - Type-Safe framework for defining, modifying, and querying SQL databases. :star:52
* **[ScalikeJDBC ★ 746 ⧗ 1](https://github.com/scalikejdbc/scalikejdbc)** - A tidy SQL-based DB access library for Scala developers.
* [Scanamo ★ 92 ⧗ 1](https://github.com/guardian/scanamo) - A library to make using DynamoDB with Scala simpler and less error-prone. :star:190
* [scredis ★ 149 ⧗ 29](https://github.com/Livestream/scredis) - Non-blocking Redis client built on top of Akka IO (used by Livestream) :star:151
* [Shade ★ 82 ⧗ 32](https://github.com/alexandru/shade) - Memcached client for Scala, based on Spymemcached :star:96
* **[Slick ★ 1795 ⧗ 0](https://github.com/slick/slick)** - Modern database query and access library for Scala.
* [Sorm ★ 239 ⧗ 2](https://github.com/sorm/sorm) - A functional boilerplate-free Scala ORM. :star:239
* [Squeryl ★ 484 ⧗ 1](https://github.com/squeryl/squeryl) - A Scala DSL for talking with databases with minimum verbosity and maximum type safety. :star:512
* [Tepkin ★ 86 ⧗ 251](https://github.com/fehmicansaglam/tepkin) - Reactive MongoDB Driver for Scala built on top of Akka IO and Akka Streams. :star:83

## Messaging

* [Op-Rabbit ★ 153 ⧗ 2](https://github.com/SpinGo/op-rabbit) - High-level messaging library for Akka and Op-Rabbit. :star:219

## Graphical User Interfaces

*Libraries for creation of graphical user interfaces*

* [ScalaFX](http://www.scalafx.org/) - Scala DSL for creating Graphical User Interfaces that sits on top of JavaFX.

## Web Frameworks

*Scala frameworks for web development.*

* [Analogweb](https://github.com/analogweb/analogweb-scala) - Tiny, simple, and pluggable web framework in Scala. :star:10
* [Chaos ★ 220 ⧗ 27](https://github.com/mesosphere/chaos) - A lightweight framework for writing REST services in Scala. :star:225
* **[Colossus ★ 811 ⧗ 70](http://tumblr.github.io/colossus/)** - lightweight framework for building high-performance applications in Scala that require non-blocking network I/O.
* **[Finatra ★ 1558 ⧗ 0](https://github.com/twitter/finatra)** - A sinatra-inspired web framework for scala, running on top of Finagle.
* **[Lift ★ 1069 ⧗ 0](https://github.com/lift/framework)** - Secure and powerful full stack web framework ([discussion](https://github.com/lauris/awesome-scala/pull/19)).
* [peregine ★ 11 ⧗ 40](https://github.com/dvarelap/peregrine) - A simple and async lightweight Scala web framework. :star:12
* **[Play ★ 9229 ⧗ 0](https://github.com/playframework/playframework)** - Makes it easy to build scalable, fast and real-time web applications with Java & Scala.
* [Play Pagelets ★ 47 ⧗ 11](https://github.com/splink/pagelets) - A Module for the Play Framework to build resilient and modular Play applications in an elegant and concise manner. :star:71
* [Reactive ★ 194 ⧗ 6](https://github.com/nafg/reactive) - FRP and web abstractions, which can be plugged into any web framework (currently only has bindings for Lift). :star:201
* **[Scalatra ★ 2146 ⧗ 0](https://github.com/scalatra/scalatra)** - Tiny Scala high-performance, async web framework, inspired by Sinatra.
* **[Skinny Framework ★ 621 ⧗ 1](https://github.com/skinny-framework/skinny-framework)** - A full-stack web app framework upon Scalatra for rapid Development in Scala.
* [suzaku](https://github.com/suzaku-io/suzaku) - Suzaku web UI framework for Scala :star:102
* **[Unfiltered ★ 673 ⧗ 6](https://github.com/unfiltered/unfiltered)** - A modular set of unopinionated primitives for servicing HTTP and WebSocket requests in Scala.
* [Xitrum](http://xitrum-framework.github.io/) - An async and clustered Scala web framework and HTTP(S) server fusion on top of Netty, Akka, and Hazelcast.
* [youi ★ 81 ⧗ 12](https://github.com/outr/youi) - Next generation user interface framework and server engine for Scala and Scala.js. :star:142

## Reactive Web Frameworks

*Scala libraries for Reactive Web development*

* **[Binding.scala ★ 935 ⧗ 0](https://github.com/ThoughtWorksInc/Binding.scala)** - A reactive web framework. It enables you use native XML literal syntax to create reactive DOM nodes, which are able to automatically change whenever the data source changes.
* [Korolev](http://github.com/fomkin/korolev/) - Modern single-page applications running on the server side :star:266
* [Udash](http://udash.io/) - a web framework based on Scala.js with support for property bindings, frontend routing, i18n and much more. It also provides strongly typed client<->server RPC system based on WebSockets.
* [Widok](https://widok.github.io/) - Reactive web framework for the JVM and Scala.js
* [Vert.x Web](http://vertx.io/docs/vertx-web/scala/) - Toolkit to build Reactive web applications..

## Data Binding and Validation

*Scala libraries for data binding and validation*

* [Accord ★ 379 ⧗ 0](https://github.com/wix/accord) - A sane validation library for Scala :star:448
* [form-binder ★ 17 ⧗ 29](https://github.com/tminglei/form-binder) - A micro data binding and validating framework, very easy to use and hack :star:20
* [Monkeytail ★ 55](https://github.com/sksamuel/monkeytail) - A set of validation macros and helpers for cats.Validated :star:80
* [Octopus ★ 15](https://github.com/krzemin/octopus) - Scala library for boilerplate-free validation :star:50

## i18n

*Scala libraries for i18n.*

* [scala-xgettext ★ 19 ⧗ 99](https://github.com/xitrum-framework/scala-xgettext) - A compiler plugin that acts like GNU xgettext command to extract i18n strings in Scala source code files to Gettext .po file. :star:20
* [Scaposer ★ 30 ⧗ 99](https://github.com/xitrum-framework/scaposer) - GNU Gettext .po file loader for Scala. :star:33

## Authentication

*Libraries for implementing authentications schemes.*

* [akka-http-session ★ 268 ⧗ 11](https://github.com/softwaremill/akka-http-session) - Web&mobile client-side sessions for akka-http based applications, with optional JWT support :star:371
* [AWS Request Signer ★ 4 ⧗ 43](https://github.com/ticofab/aws-request-signer) - Helper to evaluate the signing headers for HTTP requests to Amazon Web Services. :star:17
* [OAuth2-mock-play ★ 16 ⧗ 23](https://github.com/zalando/OAuth2-mock-play) - Implementation of an OAuth2 server designed for mocking/testing and configurable by environment variables (by use of the Typesafe config). :star:21
* [Play Google Auth Module ★ 17 ⧗ 76](https://github.com/guardian/play-googleauth) - A very simple implementation of Google OpenID Connect authentication for Play 2 applications. :star:26
* [play-pac4j ★ 255 ⧗ 0](https://github.com/pac4j/play-pac4j) - Security library managing authentication (CAS, OAuth, OpenID, SAML, LDAP, SQL, JWT...), authorizations and logout for Play 2.x in Java and Scala. :star:337
* **[play-silhouette ★ 600 ⧗ 1](https://github.com/mohiva/play-silhouette)** - Authentication library for Play Framework applications that supports several authentication methods, including OAuth1, OAuth2, OpenID, Credentials or custom authentication schemes.
* **[play2-auth ★ 617 ⧗ 4](https://github.com/t2v/play2-auth)** - Play2.x Authentication and Authorization module.
* [scala-oauth2-provider ★ 419 ⧗ 7](https://github.com/nulab/scala-oauth2-provider) - OAuth 2.0 server-side implementation written in Scala. :star:478
* **[SecureSocial ★ 1210 ⧗ 1](https://github.com/jaliss/securesocial)** - A module that provides OAuth, OAuth2 and OpenID authentication for Play Framework applications.

## Authorization

*Libraries for implementing authorization strategies.*

* [deadbolt-2 ★ 467 ⧗ 3](https://github.com/schaloner/deadbolt-2) - A Play 2.x module supporting role-based and proprietary authorization; idiomatic APIs for Scala and Java APIs are provided. :star:495

## Cryptography

*Cryptography and Encryption Libraries.*

* [Scrypto ★ 50 ⧗ 4](https://github.com/ScorexProject/scrypto) - All-purpose cryptographic framework. :star:150
* [TSec ★ 27 ⧗ 0](https://github.com/jmcardon/tsec) - Type-safe, functional, general-cryptography library :star:203

## Testing

*Libraries for code testing.*

* [cornichon ★ 109 ⧗ 3](https://github.com/agourlay/cornichon) - Scala DSL for testing HTTP JSON API. :star:161
* [Gatling](http://gatling.io) - Async Scala-Akka-Netty based Stress Tool.
* **[ScalaCheck ★ 1196 ⧗ 6](https://github.com/rickynils/scalacheck)** - Property-based testing for Scala.
* [Minitest](https://github.com/monix/minitest) - A testing framework with a focus on simplicity. :star:118
* [ScalaMeter](https://scalameter.github.io/) - Performance &  memory footprint measuring, regression testing.
* [ScalaMock](http://scalamock.org) - Scala native mocking framework
* [scalaprops ★ 171 ⧗ 5](https://github.com/scalaprops/scalaprops) - Another property based testing library for Scala :star:215
* **[ScalaTest ★ 532 ⧗ 5](https://github.com/scalatest/scalatest)** - A testing tool for Scala and Java developers.
* [Scalive ★ 187 ⧗ 20](https://github.com/xitrum-framework/scalive) - Connect a Scala REPL to running JVM processes without any prior setup; this library is used for inspecting systems in production mode. :star:198
* **[Specs2 ★ 570 ⧗ 1](https://github.com/etorreborre/specs2)** - Software Specifications for Scala.
* [µTest ★ 197 ⧗ 0](https://github.com/lihaoyi/utest) - A tiny, portable testing library for Scala. :star:323
* [testcontainers-scala ★ 52 ⧗ 2](https://github.com/testcontainers/testcontainers-scala) - Docker containers for testing in Scala. :star:118
* [Stryker4s ★ 21](https://github.com/stryker-mutator/stryker4s) - Test your tests with mutation testing. :star:36

## JSON

*Libraries for work with json.*

* [uJson](http://www.lihaoyi.com/upickle/#uJson) - fast, flexible and intuitive JSON for Scala
* [argonaut](http://argonaut.io/) - Purely Functional JSON in Scala.
* **[circe ★ 824 ⧗ 2](https://github.com/travisbrown/circe)** - JSON library based on Argonaut, depends on Cats
* [diffson ★ 94 ⧗ 14](https://github.com/gnieh/diffson) - A scala diff/patch library for Json :star:172
* [jackson-module-scala ★ 313 ⧗ 8](https://github.com/FasterXML/jackson-module-scala) - Add-on module for Jackson to support Scala-specific datatypes. :star:366
* [jawn ★ 252 ⧗ 4](https://github.com/non/jawn) - Fast json parser (According to them, competetive with java gson/jackson speed). :star:325
* **[json4s ★ 877 ⧗ 0](https://github.com/json4s/json4s)** - Project aims to provide a single AST to be used by other scala json libraries.
* [jsoniter-scala ★ 47 ⧗ 7](https://github.com/plokhotnyuk/jsoniter-scala) - Scala macros for compile-time generation of ultra-fast JSON codecs. :star:176
* [persist-json ★ 9 ⧗ 49](https://github.com/nestorpersist/json) - Fast json parser. :star:9
* [play-json ★ 39 ⧗ 7](https://github.com/playframework/play-json) - Flexible and powerful JSON manipulation, validation and serialization, with no reflection at runtime. :star:176
* [Pushka ★ 75 ⧗ 21](https://github.com/fomkin/pushka) - Scala JSON serialization library with annotations. :star:80
* [qbproject](https://github.com/qb-project/qbproject) - Scala Libs around JSON and API developement for Play Framework.
* [rapture-json](https://github.com/propensive/rapture/blob/dev/doc/json.md) - Clean, intuitive, unintrusive, boilerplate-free Scala API :star:193
* [scala-jsonapi ★ 95 ⧗ 240](https://github.com/scala-jsonapi/scala-jsonapi) - Support library for integrating the JSON API spec with Scala and Spray JSON, Play! JSON or Circe. :star:104
* [scalajack ★ 81 ⧗ 35](https://github.com/gzoller/ScalaJack) - Fast 'n easy JSON serialization with optional MongoDB support.  Uses Jackson under the hood. :star:85
* **[spray-json ★ 606 ⧗ 2](https://github.com/spray/spray-json)** - Lightweight, clean and efficient JSON implementation in Scala.
* [sbt-json](https://github.com/battermann/sbt-json) - sbt plugin that generates Scala case classes for easy, statically typed and implicit access of JSON documents :star:29

## YAML

*Libraries for work with YAML.*

* [MoultingYAML ★ 43 ⧗ 2](https://github.com/jcazevedo/moultingyaml) - Type-class based YAML serialization and deserialization on top of SnakeYAML. :star:64

## CSV

*Libraries for work with CSV.*

* [kantan.csv ★ 143 ⧗ 24](https://github.com/nrinaudo/kantan.csv) - CSV handling library for Scala with multiple backends. :star:230
* [Scala-CSV ★ 365 ⧗ 1](https://github.com/tototoshi/scala-csv) - CSV Reader/Writer for Scala. :star:491
* [fm-flatfile ★ 1 ⧗ 1](https://github.com/frugalmechanic/fm-flatfile) - Very flexible, Flat File (CSV, TSV, Excel, etc) Reader for Scala. :star:6


## Serialization

*Libraries for serializing and deserializing data for storage or transport.*

* [avro-codegen ★ 24 ⧗ 23](https://github.com/Nitro/avro-codegen) - Code generation from avro schemas to serialize/deserialize avro messages, no runtime reflection.
* [Chill ★ 378 ⧗ 4](https://github.com/twitter/chill) - Extensions for the Kryo serialization library to ease configuration in systems like Hadoop and Storm. :star:467
* [msgpack ★ 75 ⧗ 57](https://github.com/msgpack/msgpack-scala) - A efficient binary serialization library. :star:85
* **[Pickling ★ 808 ⧗ 0](https://github.com/scala/pickling)** - Fast, customizable, boilerplate-free pickling support.
* [ScalaBuff ★ 218 ⧗ 1](https://github.com/SandroGrzicic/ScalaBuff) - a Scala Protocol Buffers (protobuf) compiler :star:224
* **[ScalaPB ★ 705 ⧗ 51](https://scalapb.github.io/)** - Protocol Buffers and gRPC support for Scala
* [scodec ★ 474 ⧗ 10](https://github.com/scodec/scodec) - A combinator library for working with binary data. :star:569
* [Scrooge](http://twitter.github.io/scrooge/) - An Apache Thrift code generator for Scala.
* [validation ★ 177 ⧗ 3](https://github.com/jto/validation) - Advanced validation & serialization for JSON, HTML form data, etc, with no reflection at runtime. :star:190
* [µPickle](http://lihaoyi.github.io/upickle/) - A lightweight serialization library for Scala that works in ScalaJS, allowing transfer of structured data between the JVM and JavaScript.

## Science and Data Analysis

*Libraries for scientific computing, data analysis and numerical processing.*

* **[Algebird ★ 1478 ⧗ 0](https://github.com/twitter/algebird)** - Abstract Algebra for Scala.
* [Axle ★ 51 ⧗ 9](https://github.com/axlelang/axle) - A Spire-based DSL for scientific cloud computing. :star:60
* **[BigDL ★ 1662 ⧗ 0](https://github.com/intel-analytics/BigDL)** - BigDL is a distributed deep learning library for Apache Spark.
* **[Breeze ★ 2028 ⧗ 0](https://github.com/scalanlp/breeze)** - Breeze is a numerical processing library for Scala.
* [Chalk ★ 231 ⧗ 6](https://github.com/scalanlp/chalk) - Chalk is a natural language processing library. :star:261
* [FACTORIE ★ 486 ⧗ 7](https://github.com/factorie/factorie) - A toolkit for deployable probabilistic modeling, implemented as a software library in Scala. :star:537
* [Figaro ★ 461 ⧗ 0](https://github.com/p2t2/figaro) - Figaro is a probabilistic programming language that supports development of very rich probabilistic models. :star:647
* [Libra ★ 142](https://github.com/to-ithaca/libra) - Libra is a dimensional analysis library based on shapeless, spire and singleton-ops. It contains out of the box support for SI units for all numeric types. :star:162
* [MGO ★ 37 ⧗ 55](https://github.com/openmole/mgo) - Modular multi-objective evolutionary algorithm optimization library enforcing immutability. :star:53
* [MLLib](https://spark.apache.org/mllib/) - Machine Learning framework for Spark
* [ND4S ★ 201 ⧗ 0](https://github.com/deeplearning4j/nd4s) - N-Dimensional arrays and linear algebra for Scala with an API similar to Numpy.  ND4S is a scala wrapper around [ND4J](http://nd4j.org/). :star:298
* [Numsca ★ 8 ⧗ 0](https://github.com/botkop/numsca) - Numsca is Numpy for Scala. :star:45
* [OpenMOLE ★ 65 ⧗ 5](https://github.com/openmole/openmole) - OpenMOLE (Open MOdeL Experiment) is a workflow engine designed to leverage the computing power of distributed execution environments for naturally parallel processes. :star:88
* [OscaR](https://bitbucket.org/oscarlib/oscar/wiki/Home) - a Scala toolkit for solving Operations Research problems
* [Persist-Units ★ 9 ⧗ 40](https://github.com/nestorpersist/units) - Type check units of measure in Scala. :star:9
* **[PredictionIO ★ 10105 ⧗ 0](https://github.com/PredictionIO/PredictionIO)** - machine learning server for developers and data scientists. Built on Apache Spark, HBase and Spray
* [Rings ★ 3 ⧗ 0](https://github.com/PoslavskySV/rings) - An efficient library for polynomial rings. Commutative algebra, polynomial GCDs, polynomial factorization and other sci things at a really high speed. :star:30
* [Saddle ★ 428 ⧗ 2](https://github.com/saddle/saddle) - A minimalist port of Pandas to Scala :star:487
* [Smile](http://haifengl.github.io/smile/) - Statistical Machine Intelligence and Learning Engine. Smile is a fast and comprehensive machine learning system.
* [doddle-model](https://github.com/picnicml/doddle-model) - An in-memory machine learning library built on top of Breeze. It provides immutable objects and exposes its functionality through a scikit-learn-like API. :star:74
* **[Spark Notebook ★ 1896 ⧗ 0](https://github.com/andypetrella/spark-notebook)** - Scalable and stable Scala and Spark focused notebook bridging the gap between JVM and Data Scientists (incl. extendable, typesafe and reactive charts).
* **[Spire ★ 1152 ⧗ 3](https://github.com/non/spire)** - Powerful new number types and numeric abstractions for Scala.
* [Squants ★ 388 ⧗ 1](https://github.com/garyKeorkunian/squants) - The Scala API for Quantities, Units of Measure and Dimensional Analysis. :star:556
* [SwiftLearner ★ 20 ⧗ 5](https://github.com/valdanylchuk/swiftlearner) - Simply written algorithms to help study Machine Learning or write your own implementations. :star:31
* [Tensorflow_scala](https://github.com/eaplatanios/tensorflow_scala) - TensorFlow API for the Scala Programming Language :star:494
* [Tyche ★ 89 ⧗ 17](https://github.com/neysofu/tyche) - Probability distributions, stochastic & Markov processes, lattice walks, simple random sampling. A simple yet robust Scala library. :star:91
* [Zeppelin](http://zeppelin-project.org/) - Scala and Spark Notebook (like IPython Notebook)

## Big Data

* **[BIDMach ★ 745 ⧗ 0](https://github.com/BIDData/BIDMach)** - CPU and GPU machine learning library, using JNI for GPU computation.
* **[Flink ★ 2414 ⧗ 0](https://github.com/apache/flink)** - Processing framework with powerful stream- and batch-processing capabilities.
* **[Gearpump ★ 619 ⧗ 5](https://github.com/apache/incubator-gearpump)** - Lightweight real-time big data streaming engine
* [GridScale ★ 15 ⧗ 5](https://github.com/openmole/gridscale) - A Scala API for computing clusters and grids. :star:16
* **[Kafka ★ 5035 ⧗ 0](https://github.com/apache/kafka)** - Kafka is a message broker project and aims to provide a unified, high-throughput, low-latency platform for handling real-time data feeds.
* **[Reactive-kafka ★ 753 ⧗ 0](https://github.com/akka/reactive-kafka)** - Reactive Streams API for Apache Kafka.
* **[Scalding ★ 2783 ⧗ 2](https://github.com/twitter/scalding)** - A Scala binding for the Cascading abstraction of Hadoop MapReduce.
* [Schemer](https://github.com/indix/schemer) - Schema registry for CSV, TSV, JSON, AVRO and Parquet schema. Supports schema inference and GraphQL API. :star:50
* [Scio](https://github.com/spotify/scio) - A Scala API for [Apache Beam](https://beam.apache.org/) and [Google Cloud Dataflow](https://cloud.google.com/dataflow/) - None
* [Scrunch](http://crunch.apache.org/scrunch.html) - A Scala wrapper for [Apache Crunch](http://crunch.apache.org/index.html) which provides a framework for writing, testing, and running MapReduce pipelines.
* [Spark](http://spark.apache.org/) - Lightning fast cluster computing — up to 100x faster than Hadoop for iterative algorithms (memory caching) and up to 10x faster than Hadoop for single-pass MapReduce jobs. Compatible with YARN-enabled Hadoop clusters, can run on Mesos and in stand-alone mode as well.
* [spark-deployer ★ 69 ⧗ 29](https://github.com/KKBOX/spark-deployer) - A sbt plugin which helps deploying Apache Spark stand-alone cluster and submitting job on cloud system like AWS EC2. :star:77
* [Sparkta ★ 320 ⧗ 1](https://github.com/Stratio/sparkta) - Real Time Aggregation based on Spark Streaming. :star:453
* [Sparkplug ★ 4 ⧗ 1](https://github.com/indix/sparkplug) - Spark package to "plug" holes in data using SQL based rules :star:17
* **[Summingbird ★ 1841 ⧗ 1](https://github.com/twitter/summingbird)** - An implementation of the “lambda architecture” as a software abstraction — a single API for Hadoop and Storm.
* [Vegas](https://github.com/vegas-viz/Vegas) - The missing MatPlotLib for Scala + Spark :star:498

## Image processing and image analysis

*2D and 3D image processing and image analysis*

* [scalismo ★ 45 ⧗ 9](https://github.com/unibas-gravis/scalismo) - Shape modelling and  model-based image analysis. :star:111
* [scrimage ★ 476 ⧗ 0](https://github.com/sksamuel/scrimage) - Image io, resize, manipulation and thumbnails. :star:636

## Sound processing and music

* [ScalaCollider ★ 121 ⧗ 5](https://github.com/Sciss/ScalaCollider) - Sound synthesis and signal processing client for SuperCollider. :star:146

## Functional Reactive Programming

*Event streams, signals, observables, etc.*

* **[Monix ★ 754 ⧗ 0](https://github.com/monifu/monix)** - Extensions to Scala’s standard library for multi-threading primitives and functional reactive programming. Scala.js compatible.
* [Reactive Collections ★ 2 ⧗ 165](https://github.com/storm-enroute/reactors) - A library that incorporates event streams and signals with specialized collections called reactive containers, and expresses concurrency using isolates and channels. :star:3
* **[RxScala ★ 644 ⧗ 0](https://github.com/ReactiveX/RxScala)** - Reactive Extensions for Scala – a library for composing asynchronous and event-based programs using observable sequences
* [scala.frp ★ 21 ⧗ 101](https://github.com/dylemma/scala.frp) - Functional Reactive Programming for Scala (event streams). :star:22
* **[Scala.Rx ★ 771 ⧗ 4](https://github.com/lihaoyi/scala.rx)** - An experimental library for Functional Reactive Programming in Scala (reactive variables). Scala.js compatible.
* [SynapseGrid ★ 109 ⧗ 1](https://github.com/Primetalk/SynapseGrid) - an FRP framework for constructing reactive real-time immutable data flow systems. It implements an original way of running and organizing event-driven systems based on Petri nets. The topology can be viewed as a .dot graph. The library is compatible with Akka and can seamlessly communicate with other actors. :star:121
* [Vert.x](http://vertx.io/) - A polyglot reactive application platform for the JVM which aims to be an alternative to node.js. Its concurrency model resembles actors. It supports [Scala](http://vertx.io/docs/vertx-core/scala/), Clojure, Java, Javascript, Ruby, Groovy and Python.
* [REScala](http://www.rescala-lang.com/) - REScala is a library for functional reactive programming on the JVM and the Web. It provides a rich API for event stream transformations and signal composition with managed consistent up-to-date state and minimal syntactic overhead.

## Modularization and Dependency Injection

*Modularization of applications, dependency injection, etc.*

* [Airframe ★ 25 ⧗ 13](https://github.com/wvlet/airframe) - Dependency injection library tailored to Scala. :star:225
* [Cableguy ★ 1 ⧗ 269](https://github.com/akozhemiakin/cableguy) - Macro based compile time Dependency Injection library. :star:1
* [DIStage ★ 13 ⧗ 0](https://github.com/pshirshov/izumi-r2) - Staged Dependency Injection with higher-kinded polymorphism. :star:27
* [Grafter ★ 148 ⧗ 0](https://github.com/zalando/grafter) - Grafter is a library to configure and wire Scala applications. :star:237
* **[MacWire ★ 661 ⧗ 0](https://github.com/adamw/macwire)** - Scala Macro to generate wiring code for class instantiation. DI container replacement.
* [Scala-Guice ★ 211 ⧗ 10](https://github.com/codingwell/scala-guice) - Scala extensions for Google Guice :star:274
* [Scaldi ★ 252 ⧗ 1](https://github.com/scaldi/scaldi) - Lightweight Scala Dependency Injection Library. :star:271
* [Sclasner ★ 9 ⧗ 130](https://github.com/xitrum-framework/sclasner) - Scala classpath scanner. :star:9
* [SubCut ★ 403 ⧗ 9](https://github.com/dickwall/subcut) - Scala Uniquely Bound Classes Under Traits. :star:402

## Distributed Systems

*Libraries and frameworks for writing distributed applications.*

* [Akka](http://akka.io/) - A toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications.
* [Akka-tracing ★ 252 ⧗ 2](https://github.com/levkhomich/akka-tracing) - A distributed tracing extension for Akka. Provides integration with Play framework, Spray and Akka HTTP. :star:304
* [autobreaker ★ 6 ⧗ 93](https://github.com/lucastorri/autobreaker) - Automatically wrap classes that return Futures with a [Circuit Breaker](http://martinfowler.com/bliki/CircuitBreaker.html). :star:10
* [Clump](http://getclump.io) - A library for expressive and efficient service composition
* [CurioDB ★ 459 ⧗ 4](https://github.com/stephenmcd/curiodb) - Distributed & Persistent Redis Clone built with Scala & Akka. :star:498
* [Finagle](https://twitter.github.io/finagle/) - An extensible, protocol-agnostic RPC system designed for high performance and concurrency.
* [Glokka ★ 46 ⧗ 148](https://github.com/xitrum-framework/glokka) - Library to register and lookup actors by names in an Akka cluster. :star:51
* [Lagom](https://www.lightbend.com/lagom) - Framework for creating microservice-based systems.
* [Reactors](http://reactors.io/) - Foundational framework for distributed computing that fuses functional reactive programming and traditional actors.

## Extensions

*Scala extensions.*

* [Squid ★ 88 ⧗ 9](https://github.com/epfldata/squid) - Type-safe metaprogramming framework with typed, hygienic quasiquotes. :star:126
* [Ammonite-Ops](http://lihaoyi.github.io/Ammonite/#Ammonite-Ops) - Safe, easy, filesystem operations in Scala as convenient as in the Bash shell.
* **[better-files ★ 824 ⧗ 0](https://github.com/pathikrit/better-files)** - Simple, safe and intuitive Scala I/O. better-files is a dependency-free pragmatic thin Scala wrapper around Java NIO.
* **[Cassovary ★ 881 ⧗ 0](https://github.com/twitter/cassovary)** - A Scala library that is designed from the ground up for space efficiency, handling graphs with billions of nodes and edges.
* **[cats ★ 1697 ⧗ 0](https://github.com/typelevel/cats)** - Lightweight, modular, and extensible library for functional programming.
* [Chimney ★ 92 ⧗ 5](https://github.com/scalalandio/chimney) - Scala library for boilerplate-free data transformations. :star:286
* [Each ★ 146 ⧗ 0](https://github.com/ThoughtWorksInc/each) - A macro library that converts native imperative syntax to [Scalaz](https://github.com/scalaz/scalaz)'s monadic expressions. :star:208
* [Eff ★ 220 ⧗ 6](https://github.com/atnos-org/eff) - Extensible effects are an alternative to monad transformers for computing with effects in a functional way. :star:371
* [enableIf.scala ★ 40 ⧗ 25](https://github.com/ThoughtWorksInc/enableIf.scala) - A library that switches Scala code at compile-time, like `#if` in C/C++. :star:46
* [Enumeratum ★ 374 ⧗ 0](https://github.com/lloydmeta/enumeratum) - A macro to replace Scala enumerations with a sealed family of case objects. This allows additional checks for the compiler, e.g. for missing cases in a match statement. Has additinal support for Json libraries and the Play framework. :star:672
* [Freasy-Monad ★ 90 ⧗ 14](https://github.com/Thangiee/Freasy-Monad) - Easy way to create Free Monad for Cats and Scalaz using Scala macros with first-class Intellij support. :star:111
* [Freedsl ★ 25 ⧗ 5](https://github.com/ISCPIF/freedsl) - A library to implement composable side effects, weaving typeclasses on a wrapping type and the free monad. :star:33
* [Freestyle ★ 430 ⧗ 0](https://github.com/frees-io/freestyle) - A cohesive & pragmatic framework of FP centric Scala libraries. :star:548
* [Hamsters ★ 216 ⧗ 0](https://github.com/scala-hamsters/hamsters) - A mini Scala utility library. Compatible with functional programming beginners. Featuring validation, monad transformers, HLists, Union types. :star:266
* [idid ★ 4 ⧗ 43](https://github.com/lucastorri/idid) - A library to define common interfaces for different Id types. :star:12
* [Lamma ★ 70 ⧗ 8](https://github.com/maxcellent/lamma) - A Scala date library for date and schedule generation. :star:82
* [LArray ★ 225 ⧗ 25](https://github.com/xerial/larray) - Large off-heap arrays (> 2GB) and mmap files. :star:304
* [Log4s](http://www.log4s.org/) - Fast, Scala-friendly logging bindings on top of [SLF4J](http://slf4j.org/). Uses macros for extreme performance.
* [LogStage ★ 13 ⧗ 0](https://github.com/pshirshov/izumi-r2) - Zero-cost structural logger for Scala with [SLF4J] integration. :star:27
* **[Monocle ★ 757 ⧗ 0](https://github.com/julien-truffaut/Monocle)** - An Optics/Lens library for purely functional manipulation of immutable objects.
* **[n-scala ★ 662 ⧗ 3](https://github.com/nscala-time/nscala-time)** - Scala wrapper for Joda Time.
* [chronoscala ★ 38 ⧗ 0](https://github.com/opt-tech/chronoscala) - Scala wrapper for Java Date/Time API. :star:50
* [Persist-Logging ★ 33 ⧗ 48](https://github.com/nestorpersist/logging) - Comprehensive logging library for Scala. :star:35
* [Quicklens ★ 245 ⧗ 0](https://github.com/adamw/quicklens) - modify deeply nested case class fields with an elegant API :star:433
* [Rapture](http://rapture.io/) ([repo](https://github.com/propensive/rapture)) - a collection of libraries for common, everyday programming tasks (I/O, JSON, i18n, etc.) :star:193
* [Records for Scala ★ 125 ⧗ 55](https://github.com/scala-records/scala-records) - Labeled records for Scala based on structural refinement types and macros. :star:141
* [refined ★ 447 ⧗ 3](https://github.com/fthomas/refined) - Simple refinement types with compile- and runtime checking :star:774
* [Resolvable ★ 0 ⧗ 94](https://github.com/stanch/resolvable) - A library to optimize fetching immutable data structures from several endpoints in several formats. :star:3
* **[Scala Async ★ 778 ⧗ 0](https://github.com/scala/async)** - An asynchronous programming facility for Scala.
* [Scala Graph](http://www.scala-graph.org/) - A Scala library with basic graph functionality that seamlessly fits into the Scala standard collections library.
* [scala.meta](http://scalameta.org/) - A clean-room implementation of a metaprogramming toolkit for Scala.
* [Scalactic](http://www.scalactic.org/) - Small library of utilities related to quality that helps keeping code clear and correct.
* **[Scalaz ★ 3045 ⧗ 0](https://github.com/scalaz/scalaz)** - An extension to the core Scala library for functional programming.
* [scribe ★ 36 ⧗ 3](https://github.com/outr/scribe) - Practical logging framework that doesn't depend on any other logging framework and can be completely configured programmatically. :star:180
* **[Shapeless ★ 2002 ⧗ 0](https://github.com/milessabin/shapeless)** - A type class and dependent type based generic programming library for Scala.
* [Simulacrum ★ 484 ⧗ 2](https://github.com/mpilquist/simulacrum) - First class syntax support for type classes in Scala. :star:709
* [Stateless Future ★ 165 ⧗ 35](https://github.com/qifun/stateless-future) - Asynchronous programming in fully featured Scala syntax. :star:178
* **[Twitter Util ★ 1809 ⧗ 1](https://github.com/twitter/util)** - General-purpose Scala libraries, including a future implementation and other concurrency tools.
* [wvlet-log ★ 43 ⧗ 13](https://github.com/wvlet/log) - A library for enhancing your application logs with colors and source code locations. :star:57

## Misc

*Projects that don't fit into any specific category.*

* [Agora](https://gitlab.com/aossie/Agora/) - Library of vote-counting algorithms for elections.
* [Ammonite-REPL](http://lihaoyi.github.io/Ammonite/#Ammonite-REPL) - An improved Scala REPL: syntax highlighting, output formatting, multi-line input, and more.
* [BootZooka ★ 331 ⧗ 5](https://github.com/softwaremill/bootzooka) - Simple project to quickly start developing a web application using AngularJS and Akka HTTP, without the need to write login, user registration etc. :star:378
* [Eclair ★ 469](https://github.com/ACINQ/eclair) - ACINQ's Lightning Network implementation written in Scala.  Lightning Network is a second layer protocol built on top of bitcoin to address scalability, privacy, confirmation time and many other issues. :star:677
* [Fansi ★ 96 ⧗ 15](https://github.com/lihaoyi/fansi) - Scala/Scala.js library for manipulating Fancy Ansi colored strings :star:137
* [GoogleApiScala ★ 5 ⧗ 3](https://github.com/EckerdCollege/google-api-scala) - A simple scala library offering control of Google Drive, Calendar, and the Admin SDK. :star:15
* [mailgun4s ★ 7 ⧗ 4](https://github.com/outr/mailgun4s) - Scala wrapper around the Mailgun API :star:11
* [media4s ★ 5 ⧗ 3](https://github.com/outr/media4s) - Scala command-line wrapper around ffmpeg, ffprobe, ImageMagick, and other tools relating to media. :star:14
* [Miniboxing](https://github.com/miniboxing/miniboxing-plugin) - A Scala compiler plugin that improves program performance -- [see the project web site](http://scala-miniboxing.org) - Less boxes
* [Openquant ★ 73 ⧗ 0](https://github.com/openquant) - A Scala open source quantitative trading platform
* [Ostinato ★ 27 ⧗ 7](https://github.com/marianogappa/ostinato) - A chess library that runs on the server (Scala) and on the browser (ScalaJS) :star:33
* [pdf4s ★ 3 ⧗ 3](https://github.com/outr/pdf4s) - Simplified wrapper to create PDFs in Scala. :star:4
* [Play Swagger ★ 174 ⧗ 3](https://github.com/iheartradio/play-swagger) - Automatically create Swagger documentation for your Play REST API :star:266
* [powerscala ★ 11 ⧗ 80](https://github.com/outr/powerscala) - Powerful framework providing many useful utilities and features on top of the Scala language. :star:14
* [pprint](https://github.com/lihaoyi/pprint) - Pretty-printer for Scala values and types for easier reading and debugging :star:63
* [PureConfig ★ 337 ⧗ 2](https://github.com/melrief/pureconfig) - A boilerplate-free Scala library for loading configuration files. :star:692
* [REPLesent ★ 319 ⧗ 5](https://github.com/marconilanna/REPLesent) - A presentation tool built inside the Scala REPL. Runs code straight from your slides with a single keystroke. :star:367
* [scala-debugger ★ 52 ⧗ 18](https://github.com/ensime/scala-debugger) - Scala libraries and tooling utilizing the Java Debugger Interface. :star:82
* [scala-ssh ★ 186 ⧗ 6](https://github.com/sirthias/scala-ssh) - Remote shell access via SSH for your Scala applications :star:213
* [Scalan ★ 81 ⧗ 67](https://github.com/scalan/scalan) - A framework for development of domain-specific compilers in Scala :star:90
* [ScalaSTM](https://nbronson.github.io/scala-stm/) - Software Transaction Memory for Scala
* [Scavenger](https://gitlab.com/aossie/Scavenger) - An experimental automated theorem prover.
* [settler ★ 4 ⧗ 171](https://github.com/lucastorri/settler) - Boilerplate-free typed settings generation in Scala. :star:8
* [Simple Scala Config ★ 43 ⧗ 5](https://github.com/ElderResearch/ssc) - Thin, idiomatic Scala wrapper around [Typesafe Config](https://github.com/typesafehub/config) with custom `Reader[T]` suppport. :star:47
* [YahooFinanceScala ★ 15 ⧗ 2](https://github.com/openquant/YahooFinanceScala) - Get stock data from Yahoo Finance using Akka http. :star:16

## Android

*Scala libraries and wrappers for Android development.*

* **[Android SDK Plugin for SBT ★ 609 ⧗ 1](https://github.com/pfn/android-sdk-plugin)** - An sbt plugin that adds tasks for developing Android applications.
* [Gradle Android Scala Plugin ★ 318 ⧗ 20](https://github.com/saturday06/gradle-android-scala-plugin) - A gradle plugin that allows you to use Scala with Android :star:340
* **[Macroid ★ 511 ⧗ 3](https://github.com/47deg/macroid)** - A modular functional UI language for Android.
* **[Scaloid ★ 2065 ⧗ 0](https://github.com/pocorall/scaloid)** - Less painful Android development with Scala.

## HTTP

*Scala libraries and wrappers for HTTP clients.*

* [Akka HTTP ★ 306 ⧗ 1](https://github.com/akka/akka-http) - The Streaming-first HTTP server/module of [Akka](https://github.com/akka/akka). :star:786
* [Dispatch ★ 366 ⧗ 6](https://github.com/dispatch/reboot) - Library for asynchronous HTTP interaction. It provides a Scala vocabulary for Java’s [async-http-client](https://github.com/AsyncHttpClient/async-http-client). :star:415
* **[Finch.io ★ 1005 ⧗ 3](https://github.com/finagle/finch)** - Purely Functional REST API atop of [Finagle](https://github.com/twitter/finagle).
* [Fintrospect ★ 37 ⧗ 0](http://fintrospect.io) - Implement fast, type-safe HTTP webservices for [Finagle](https://github.com/twitter/finagle).
* **[Http4s ★ 732 ⧗ 3](https://github.com/http4s/http4s)** - A minimal, idiomatic Scala interface for HTTP.
* [jefe ★ 2 ⧗ 105](https://github.com/outr/jefe) - Manages installation, updating, downloading, launching, error reporting, proxying, multi-server management, and much more for your stand-alone and web applications. :star:4
* [lolhttp ★ 64 ⧗ 10](https://github.com/criteo/lolhttp) An HTTP & HTTP/2 Server and Client library for Scala.
* [RösHTTP ★ 79 ⧗ 9](https://github.com/hmil/RosHTTP) - A lightweight asynchronous HTTP API built with Scala.js in mind. Supports the JVM and Node.js runtimes as well as most browsers. :star:118
* **[scalaj-http ★ 580 ⧗ 0](https://github.com/scalaj/scalaj-http)** - Simple scala wrapper for HttpURLConnection (including OAuth support).
* [Scalaxb ★ 235 ⧗ 18](https://github.com/eed3si9n/scalaxb) - An XML data-binding tool for Scala that supports W3C XML Schema (xsd) and Web Services Description Language (wsdl) as the input file. :star:263
* [Spray](http://spray.io/) - Actor-based library for http interaction.
* [sttp](https://github.com/softwaremill/sttp) - The Scala HTTP client you always wanted! :star:596
* [Tubesocks ★ 12 ⧗ 174](https://github.com/softprops/tubesocks) - Library supporting bi-directional communication with websocket servers. :star:12

## Semantic Web

*Scala libraries for interactions with the Web of Data, and other RDF tools.*

* [Banana-RDF ★ 207 ⧗ 26](https://github.com/banana-rdf/banana-rdf) - Scala-friendly abstractions for RDF and Linked Data technologies. Supports Jena, Sesame and native Scala. :star:244
* [rdfp ★ 4 ⧗ 50](https://github.com/jannvck/rdfp) - RDF stream processing framework in Scala :star:5
* [Scowl ★ 16 ⧗ 36](https://github.com/phenoscape/scowl) - Scala DSL allowing a declarative approach to composing OWL expressions and axioms using the OWL API. :star:28

## Metrics and Monitoring

*Scala libraries for gathering metrics and monitoring applications.*

* [Kamon](http://kamon.io) - Gathering metrics from applications built with Akka, Spray and Play! with support for user metrics as well.
* [Metrics-Scala ★ 335](https://github.com/erikvanoosten/metrics-scala) - Scala API for Dropwizard's Metrics library. :star:369

## Parsing

*Scala libraries for creating parsers.*

* [atto ★ 148 ⧗ 1](https://github.com/tpolecat/atto) - Pure functional incremental text parsing library for Scala, based on Attoparsec. :star:233
* [CLIST ★ 43 ⧗ 24](https://github.com/backuity/clist) - Command Line Interface Scala Toolkit :star:75
* [decline ★ 101](https://github.com/bkirwi/decline) - composable command-line parser for Scala, built on Cats :star:167
* [Fast Parse ★ 467 ⧗ 1](https://github.com/lihaoyi/fastparse) - Fast to write, Fast running Parsers in Scala :star:697
* **[Parboiled2 ★ 502 ⧗ 7](https://github.com/sirthias/parboiled2)** - A Fast Parser Generator for Scala 2.10.3+.
* [Scala Parser Combinators ★ 221 ⧗ 0](https://github.com/scala/scala-parser-combinators) - Scala Standard Parser Combinator Library. :star:354
* **[Scopt ★ 678 ⧗ 0](https://github.com/scopt/scopt)** - Simple scala command line options parsing.

## Sbt plugins

*Sbt plugins to make your life easier.*

* **[coursier ★ 847 ⧗ 0](https://github.com/alexarchambault/coursier)** - A Scala library to fetch dependencies from Maven / Ivy repositories
* [sbt-api-mappings ★ 38 ⧗ 67](https://github.com/ThoughtWorksInc/sbt-api-mappings) - A Sbt plugin that resolves external API links to common Scala libraries. :star:60
* [sbt-buildinfo ★ 274 ⧗ 1](https://github.com/sbt/sbt-buildinfo) - Generates Scala source from build definition. :star:396
* [sbt-classfinder ★ 3 ⧗ 39](https://github.com/ruippeixotog/sbt-classfinder) - Retrieves runtime information about the classes and traits in a project. :star:3
* **[sbt-dependency-graph ★ 731 ⧗ 1](https://github.com/jrudolph/sbt-dependency-graph)** - Create a dependency graph for your project.
* [sbt-docker ★ 422 ⧗ 3](https://github.com/marcuslonnberg/sbt-docker) - Create Docker images directly from sbt :star:593
* [sbt-doctest ★ 148](https://github.com/tkawachi/sbt-doctest) - Plugin for sbt that generates tests from examples in ScalaDoc. :star:155
* [sbt-ensime ★ 197 ⧗ 11](https://github.com/ensime/ensime-sbt) - Generates .ensime config files for SBT projects [http://ensime.org/build_tools/sbt](http://ensime.org/build_tools/sbt)
* [sbt-groll ★ 87 ⧗ 10](https://github.com/sbt/sbt-groll) - sbt plugin to roll the Git history. :star:119
* [sbt-haxe ★ 9 ⧗ 274](https://github.com/qifun/sbt-haxe) - A Sbt plugin to compile Haxe sources. :star:9
* [sbt-ide-settings ★ 32 ⧗ 27](https://github.com/Jetbrains/sbt-ide-settings) - SBT plugin for tweaking various IDE settings :star:41
* **[sbt-native-packager ★ 811 ⧗ 3](https://github.com/sbt/sbt-native-packager)** - Bundle up Scala software for native packaging systems, like deb, rpm, homebrew, msi..
* [sbt-pack ★ 284 ⧗ 7](https://github.com/xerial/sbt-pack) - A sbt plugin for creating distributable Scala packages. :star:361
* [sbt-pantarhei ★ 3 ⧗ 0](https://github.com/kolov/sbt-pantarhei) - SBT plugin to generate release notes from the pull requests and git commits in GitHub. :star:10
* **[sbt-revolver ★ 519 ⧗ 0](https://github.com/spray/sbt-revolver)** - Fork & Stop processes from sbt.
* [sbt-robovm ★ 107 ⧗ 17](https://github.com/roboscala/sbt-robovm) - An sbt plugin for iOS development in Scala :star:111
* [sbt-scala-js-map ★ 12 ⧗ 2](https://github.com/ThoughtWorksInc/sbt-scala-js-map) - A sbt plugin that configures source mapping for Scala.js projects hosted on Github :star:19
* [sbt-sublime ★ 145 ⧗ 38](https://github.com/orrsella/sbt-sublime) - Create Sublime Text projects with library dependencies sources :star:139
* [sbt-updates ★ 316 ⧗ 3](https://github.com/rtimush/sbt-updates) - Shows sbt project's dependency updates. :star:491
* [sbt-versions ★ 14 ⧗ 167](https://github.com/sksamuel/sbt-versions) - Plugin that checks for updated versions of your project's dependencies. :star:16
* [sbt-view ★ 7 ⧗ 18](https://github.com/nestorpersist/sbt-view) - View ScalaDoc/JavaDoc in browser window. :star:7
* **[sbteclipse ★ 632 ⧗ 0](https://github.com/typesafehub/sbteclipse)** - Create Eclipse project definitions from sbt builds.
* [scala-clippy ★ 211 ⧗ 5](https://github.com/softwaremill/scala-clippy) - Good advice and coloring for Scala compiler errors :star:276
* [ScalaKata2 ★ 79 ⧗ 0](https://github.com/MasseGuillaume/ScalaKata2) - Scala playground & Documentation tool. :star:93
* [tut ★ 364 ⧗ 2](https://github.com/tpolecat/tut) - Tool for writing documentation with typechecked examples. :star:518
* [xsbt-web-plugin ★ 334 ⧗ 1](https://github.com/earldouglas/xsbt-web-plugin) - Build enterprise J2EE Web applications in Scala. :star:370
* [sbt-hepek ★ 5 ⧗ 0](https://github.com/sake92/sbt-hepek) - Make static websites in Scala code (render `object` to file!). :star:13
* [splain ★ 234 ⧗ 0](https://github.com/tek/splain) - Better implicit errors for Scala. :star:238

## XML / HTML

*XML and HTML generation and processing*

* [scala-scraper ★ 316 ⧗ 1](https://github.com/ruippeixotog/scala-scraper) - A library for scraping content from HTML pages. :star:499
* [xs4s ★ 29 ⧗ 47](https://github.com/ScalaWilliam/xs4s) - XML Streaming for Scala for processing large (gigabytes and over) XML files. :star:32

## Markdown

* [Laika ★ 161](https://github.com/planet42/Laika) - Text Markup Transformer for sbt and Scala applications, transforming Markdown and reStructuredText to HTML and PDF. :star:184

## Learning Scala

*Nice books, blogs and other resources to learn Scala*

* **[Demos and Examples in Scala (Chinese) ★ 525 ⧗ 2](https://github.com/jacksu/utils4s)** - repo of sample Scala library usage, written in Chinese
* [A Tour of Scala](http://docs.scala-lang.org/tour/tour-of-scala.html) - Bite-sized introductions to some of the core language concepts.
* [Deploying Scala libraries to Sonatype for dummies ★ 23 ⧗ 25](https://github.com/larroy/deployingScalaLibrariesToSonatype) - None :star:21
* [Programming Community Curated Resources for Learning Scala](https://hackr.io/tutorials/learn-scala)
* [Functional Programming in Scala](https://www.coursera.org/specializations/scala) - Coursera Specialization (5 courses) created by  Martin Odersky et al. at the EPFL (Ecole polytechnique fédérale de Lausanne).
* [Reactive Programming with Scala and Akka](http://www.foxebook.net/reactive-programming-with-scala-and-akka/) - Use the concepts of reactive programming to build distributed systems running on multiple nodes
* [Scala Collections Cookbook](http://colobu.com/ScalaCollectionsCookbook/) - Scala collections introduction. written in Chinese.
* [Scala Exercises](http://scala-exercises.47deg.com/) - Brings the popular Scala Koans to the web. Offering hundreds of solvable exercises organized into 42 categories covering the basics of the Scala language.
* [Exercism - Scala Exercises](http://exercism.io/languages/scala/exercises) - Community-driven Scala exercises.
* [Scala With Cats](https://underscore.io/books/scala-with-cats/) - Learn system architecture and design using the techniques of modern functional programming with [Cats](https://typelevel.org/cats/)
* [Scala in Depth](https://www.manning.com/books/scala-in-depth) - None
* [Scala school](https://twitter.github.io/scala_school/) - Scala school started as a series of lectures at Twitter to prepare experienced engineers to be productive Scala programmers.
* [Essential Scala](https://underscore.io/books/essential-scala/) - None
* [Scalera Blog](http://www.scalera.es) - Blog about Scala language and its environment (howto's, good practices, tips,...). Weekly posts written in both spanish and english
* [The Neophyte's Guide to Scala](http://danielwestheide.com/scala/neophytes.html) - None
* Resources by [Dr. Mark Lewis](http://www.cs.trinity.edu/~mlewis/) >> [Website](http://www.programmingusingscala.net/) | [Youtube Playlists](https://www.youtube.com/user/DrMarkCLewis/playlists)
* [Functional Programming for Mortals](https://leanpub.com/fpmortals/read) - None
* [The Type Astronaut's Guide to Shapeless](https://underscore.io/books/shapeless-guide/) - None
* [Learn-by-doing functional programming course on Scala](https://github.com/dehun/learn-fp/) - Covers type classes, functors, applicatives, monads, monad transformers, free monad :star:429
* [Get Programming with Scala](https://www.manning.com/books/get-programming-with-scala) - Tutorial-driven introduction to Scala
* [Introduction to programming with dependent types in Scala](https://stepik.org/course/2294/) - Video Course by Dmytro Mitin
* [Functional Works / Learn](https://functional.works-hub.com/learn/) - Quality resources maintained by functional works
* [Scala for the Impatient 2nd Edition](https://horstmann.com/scala/) - Covers most Scala features with short and easy to understand explainations.

## JavaScript

*JavaScript generation and interop libraries.*

* [scala-js-fiddle](http://www.scala-js-fiddle.com/) ([repo](https://github.com/lihaoyi/scala-js-fiddle)) - Browser-based Scala.js playground :star:84
* [Scala.js](http://www.scala-js.org/) ([repo](https://github.com/scala-js/scala-js)) - Scala to JavaScript compiler :star:3492

## Scheduling

* [akka-quartz-scheduler ★ 365](https://github.com/enragedginger/akka-quartz-scheduler) - Quartz Extension and utilities for cron-style scheduling in Akka. :star:432

## Templating

*Web templating engines.*

* [Beard ★ 67 ⧗ 3](https://github.com/zalando/beard) - lightweight logicless templating engine inspired by Mustache :star:94
* [Scalatags ★ 492 ⧗ 3](https://github.com/lihaoyi/scalatags) - Write html as scala code and have your IDE syntax check it. :star:559
* [Scalate ★ 517](https://github.com/scalate/scalate) - Scala based template engine which supports HAML, Mustache and JSP, Erb and Velocity style syntaxes :star:517
* [Twirl ★ 324 ⧗ 3](https://github.com/playframework/twirl) - The Play Scala Template Compiler :star:415

## Tools

* [Mill](http://www.lihaoyi.com/mill/) - A better Scala build tool
* [Scalafix]https://github.com/scalacenter/scalafix) - Refactoring and linting tool
* [Codacy](https://www.codacy.com/) - Automated Code Reviews for Scala
* [Fastring ★ 97 ⧗ 2](https://github.com/Atry/fastring) - Extremely fast string formatting :star:109
* [fast-string-interpolator ★ 24 ⧗ 0](https://github.com/Sizmek/fast-string-interpolator) - Scala macro that generates ultra-fast string interpolators :star:50
* **[Gitbucket ★ 6296 ⧗ 0](https://github.com/gitbucket/gitbucket)** - The easily installable GitHub clone powered by Scala
* [sbt](http://www.scala-sbt.org/) ([repo](https://github.com/sbt/sbt)) - The interactive build tool for Scala :star:3671
* [Scala @LibHunt](https://scala.libhunt.com) - The go-to Scala Toolbox.
* [scala-trace-debug ★ 80 ⧗ 14](https://github.com/JohnReedLOL/scala-trace-debug) - Multithreaded print debug tool :star:112
* [Scalariform ★ 116 ⧗ 47](https://github.com/daniel-trinh/scalariform) - Scala source code formatter :star:116
* [Scalastyle ★ 463 ⧗ 1](https://github.com/scalastyle/scalastyle) - Scala style checker. :star:582
* [Scalatex ★ 236 ⧗ 12](https://github.com/lihaoyi/Scalatex) - Programmable, Typesafe Document Generation :star:265
* [Scapegoat ★ 230 ⧗ 6](https://github.com/sksamuel/scapegoat) - Scala compiler plugin for static code analysis :star:279
* [Scaps](http://scala-search.org/) ([repo](https://github.com/scala-search/scaps)) - A search engine for Scala libraries :star:34
* [Scoverage](https://github.com/scoverage) - Scala Code Coverage tool
* **[Wartremover ★ 662 ⧗ 1](https://github.com/puffnfresh/wartremover)** - Wartremover a flexible Scala code linting tool
* [Giter8](http://www.foundweekends.org/giter8/) command line tool to generate files and directories from templates published on Github

## Geospatial

*Libraries to aid with geospatial calculations and artifacts.*

* **[Geotrellis ★ 553 ⧗ 0](https://github.com/locationtech/geotrellis)** - Scalable raster toolkit for GIS processing
* [osm4scala ★ 8 ⧗ 40](https://github.com/angelcervera/osm4scala) - OpenStreetMap PBF2 file parser :star:24
* [rtree2d ★ 27 ⧗ 1](https://github.com/Sizmek/rtree2d) - RTree2D is a 2D immutable R-tree with STR (Sort-Tile-Recursive) packing for ultra-fast nearest and intersection queries on plane and spherical surfaces :star:35
* [sfcurve ★ 20 ⧗ 1](https://github.com/locationtech/sfcurve) - Space filling curves in Scala for geospatial indexing and query :star:32

## Devops

*DevOps related tools and libraries.*

* [Skuber ★ 85 ⧗ 0](https://github.com/doriordan/skuber) - Kubernetes client in Scala :star:146

# Resources

Where to discover new Scala libraries.

## Podcasts

* [CoRecursive Interviews](https://corecursive.com/) - In-depth Interviews with software developers, often on the subject of scala libraries and functional programming.

## Newsletters

* [Scala Times](https://scalatimes.com/) - Weekly newsletter about scala

# Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new framework, library or software to the list. Do not submit a project that hasn’t been updated in the past 6 months or is not awesome.

