# Information comes from [chentsulin/awesome-graphql](https://github.com/chentsulin/awesome-graphql)
# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome list of GraphQL & Relay

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [Specification](#spec)
- [Community](#community)
- [GraphQL Meetups](#meetups)
- [Libraries](#lib)
	- [Javascript](#lib-js)
	- [Typescript](#lib-ts)
	- [Ruby](#lib-rb)
	- [PHP](#lib-php)
	- [Python](#lib-py)
	- [Java](#lib-java)
	- [C/C++](#lib-c)
	- [Go](#lib-go)
	- [Scala](#lib-scala)
	- [Perl](#lib-perl)	
	- [.NET](#lib-dotnet)
	- [Erlang](#lib-erlang)
	- [Elixir](#lib-elixir)
	- [Haskell](#lib-haskell)
	- [SQL](#lib-sql)
	- [Lua](#lib-lua)
	- [Elm](#lib-elm)
	- [Clojure](#lib-clojure)
	- [ClojureScript](#lib-clojurescript)
	- [Swift](#lib-swift)
	- [OCaml](#lib-ocaml)
	- [ReasonML](#lib-reasonml)
	- [Rust](#lib-rust)
	- [R](#lib-r)
	- [Julia](#lib-julia)
	- [Kotlin](#lib-kotlin)
	- [Unity](#lib-unity)
	- [Crystal](#lib-crystal)
	- [Wechat APP](#lib-miniprogram)
- [Tools](#tools)
- [Services](#services)
- [Databases](#databases)
- [Examples](#example)
	- [Javascript](#example-js)
	- [Typescript](#example-ts)
	- [Ruby](#example-rb)
	- [Go](#example-go)
	- [Scala](#example-scala)
	- [Python](#example-python)
	- [Elixir](#example-elixir)
	- [PHP](#example-php)
	- [ReasonML](#example-reasonml)
- [Videos](#video)
- [Blogs](#blogs)
- [Posts](#post)
- [Books](#books)
- [Workshoppers](#workshopper)

<!-- /MarkdownTOC -->

<a name="spec" />

## Specification

* [facebook/graphql](http://facebook.github.io/graphql/) - Working Draft of the Specification for GraphQL created by Facebook.

<a name="community" />

## Community

* [Slack](https://graphql.slack.com/messages/general) - Share and help people on the chat. Get your invite [here](https://graphql-slack.herokuapp.com/)
* [`#graphql` on Freenode](https://webchat.freenode.net/?channels=#graphql) - The official IRC channel for GraphQL
* [Facebook](https://www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing
* [Twitter](https://twitter.com/search?q=%23GraphQL) - Use the hashtag [#graphql](https://twitter.com/search?q=%23GraphQL)
* [StackOverflow](https://stackoverflow.com/questions/tagged/graphql) - Questions and answers. Use the tag [graphql](http://stackoverflow.com/questions/tagged/graphql)
* [GraphQL APIs](https://github.com/APIs-guru/graphql-apis) - A collective list of public GraphQL APIs :star:944
* [GraphQL World](https://graphql-world.com) - The fastest growing community of GraphQL developers

<a name="meetups" />

## GraphQL Meetups

* [Bangalore](https://www.meetup.com/GraphQL-Meetup/)
* [Berlin](https://www.meetup.com/graphql-berlin/)
* [Buenos Aires](https://www.meetup.com/es-ES/GraphQL-BA/)
* [Dallas-Fort Worth](https://www.meetup.com/DFW-GraphQL-Meetup/)
* [Istanbul](https://www.meetup.com/GraphQL-Istanbul/)
* [London](https://www.meetup.com/GraphQL-London/)
* [Manchester](https://www.meetup.com/GraphQL-Manchester/)
* [Melbourne](https://www.meetup.com/GraphQL-Melbourne/)
* [Munich](https://www.meetup.com/GraphQL-Munich/)
* [New York City](https://www.meetup.com/GraphQL-NYC/)
* [San Francisco](https://www.meetup.com/GraphQL-SF/)
* [Sydney](https://www.meetup.com/GraphQL-Sydney/)
* [Tel Aviv](https://www.meetup.com/GraphQL-TLV/)
* [Toronto](https://www.meetup.com/GraphQL-Toronto/)

<a name="lib" />

## Libraries

<a name="lib-js" />

### JavaScript Libraries

##### Clients
* [relay](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications. :star:11581
* [Apollo Client](https://github.com/apollographql/apollo-client) - A well-documented GraphQL client. Has React and Angular bindings. :star:8883
* [aws-amplify](https://github.com/aws/aws-amplify) - A client library developed by Amazon for caching, analytics and more that includes a way to fetch GraphQL queries. :star:3999
* [graphql-request](https://github.com/prismagraphql/graphql-request) - A minimal GraphQL client for Node and browsers. :star:1153
* [FetchQL](https://github.com/gucheen/FetchQL) - A simple GraphQL query client using Fetch. :star:95
* [urql](https://github.com/FormidableLabs/urql) - A simple caching GraphQL client for React. :star:1623
* [micro-graphql-react](https://github.com/arackaf/micro-graphql-react) - A lighweight utility for adding GraphQL to React. components. Includes simple caching and uses GET requests that could additionally be cached through a service-worker.  :star:252
* [Lokka](https://github.com/kadirahq/lokka) - Simple JavaScript client for GraphQL, which you can use anywhere. :star:1370
* [react-reach](https://github.com/kennetpostigo/react-reach) - A library to communicate with Graphql through Redux. :star:127

##### Miscellaneous 

* [GraphQL.js](https://github.com/graphql/graphql-js) - A reference implementation of GraphQL for JavaScript. :star:11876
* [express-graphql](https://github.com/graphql/express-graphql) - GraphQL Express Middleware. :star:3814
* [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware. :star:602
* [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) - Create a GraphQL HTTP server with Hapi. :star:110
* [codemirror-graphql](https://github.com/graphql/codemirror-graphql) - GraphQL mode and helpers for CodeMirror. :star:127
* [graphql-schema](https://github.com/devknoll/graphql-schema) - Create GraphQL schemas with a fluent/chainable interface. :star:130
* [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL. :star:1310
* [graphql-sequelize-crud](https://github.com/Glavin001/graphql-sequelize-crud) - Automatically generate queries and mutations from Sequelize models. :star:118
* [graffiti](https://github.com/RisingStack/graffiti) - Node.js GraphQL ORM. :star:1042
* [graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose) - Mongoose (MongoDB) adapter for graffiti (Node.js GraphQL ORM). :star:396
* [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings. :star:65
* [adrenaline](https://github.com/gyzerok/adrenaline) - React bindings for Redux with Relay in mind. :star:731
* [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models. :star:169
* [graphql-bookshelfjs](https://github.com/weyoss/graphql-bookshelfjs) - A simple bridge between your graphql queries and your bookshelf models, perform batched and optimised queries. :star:24
* [graph.ql](https://github.com/matthewmueller/graph.ql) - Faster and simpler technique for creating and querying GraphQL schemas. :star:592
* [Strapi](http://strapi.io/documentation/graphql) - Open-source Node.js framework that supports "GraphQL" out of the box.
* [GraysQL](https://github.com/larsbs/graysql) - A GraphQL manager and loader. :star:29
* [graysql-orm-loader](https://github.com/larsbs/graysql-orm-loader) - A GraysQL extension to load a GraphQL schema from an ORM. :star:7
* [Annotated GraphQL](https://github.com/almilo/annotated-graphql) - Proof of Concept for annotations in GraphQL (i.e.: transform an existing REST api into a GraphQL endpoint). :star:1
* [graphql-tools](https://github.com/apollographql/graphql-tools) - Tool library for building and maintaining GraphQL-JS servers. :star:2328
* [graphql-anywhere](https://github.com/apollographql/graphql-anywhere) - Run a GraphQL query anywhere, against any data, with no schema. :star:568
* [graphql-tag](https://github.com/apollographql/graphql-tag) - A JavaScript template literal tag that parses GraphQL queries. :star:842
* [modelizr](https://github.com/julienvincent/modelizr) - A library for simplifying the process of writing GraphQL queries, mocking them and normalizing their responses. :star:165
* [vue-apollo](https://github.com/Akryum/vue-apollo) - Vue integration for apollo. :star:2797
* [graphql-thinky](https://github.com/fenos/graphql-thinky) - Build an optimized GraphQL schema from Thinky RethinkDB models. :star:69
* [graphql-pouch](https://github.com/MikeBild/graphql-pouch) - A GraphQL-API runtime on top of PouchDB created by GraphQL shorthand notation as a self contained service with CouchDB synchronization. :star:155
* [gql-tools](https://github.com/almilo/gql-tools) - Tool library with CLI for schema generation and manipulation. :star:17
* [graphql-iso-date](https://github.com/excitement-engineer/graphql-iso-date) - A GraphQL date scalar type to be used with GraphQL.js. This scalar represents a date in the ISO 8601 format YYYY-MM-DD. :star:229
* [graphql-compose](https://github.com/nodkz/graphql-compose) - Tool which allows you to construct flexible graphql schema from different data sources via plugins. :star:433
* [node-graphjoiner](https://github.com/mwilliamson/node-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise. :star:42
* [Join Monster](https://github.com/stems/join-monster) - A GraphQL-to-SQL query execution layer for batch data fetching. :star:1631
* [Create-GraphQL](https://github.com/graphql-community/create-graphql) - Command-line utility to build production-ready servers with GraphQL. :star:423
* [GraphQL-Pokémon](https://github.com/lucasbento/graphql-pokemon) - Get information of a Pokémon with GraphQL! :star:180
* [graphql-factory](https://github.com/graphql-factory) - Create GraphQL types from JSON definitions
* [ChromeiQL](https://chrome.google.com/webstore/detail/chromeiql/fkkiamalmpiidkljmicmjfbieiclmeij) - Chrome extension to use GraphiQL anywhere
* [graphql-auto-mutation](https://github.com/ejoebstl/graphql-auto-mutation) - Automatically generates functions for mutations specified in a GraphQL schema. :star:46
* [GraphiteJS](https://github.com/graphitejs/graphitejs) - Full stack GraphQL framework. :star:83
* [loopback-graphql](https://github.com/tallyb/loopback-graphql) - GraphQL Server for Loopback. :star:199
* [parasprite](https://github.com/octet-stream/parasprite) - Describe your GraphQL schema using chainable interface. :star:4
* [GraphQL.js](https://github.com/f/graphql.js) - JavaScript GraphQL Client for Browser and Node.js Usage :star:1689
* [graphql-sync](https://github.com/arangodb/graphql-sync) - Promise-free wrapper to GraphQL.js for synchronous environments :star:50
* [Spikenail](https://github.com/spikenail/spikenail) - Node.js framework for building GraphQL API almost without coding. :star:350
* [graphql-weaver](https://github.com/AEB-labs/graphql-weaver) - A tool to combine, link and transform GraphQL schemas; combine multiple GraphQL servers into one API. :star:162
* [graphql-lodash](https://github.com/APIs-guru/graphql-lodash) - Data manipulation for GraphQL queries with lodash syntax. :star:536
* [apollo-angular](https://github.com/apollographql/apollo-angular) - Angular integration for Apollo. :star:508
* [graphql-resolvers](https://github.com/lucasconstantino/graphql-resolvers) - Resolver composition library for GraphQL. :star:151
* [apollo-resolvers](https://github.com/thebigredgeek/apollo-resolvers) - Expressive and composable resolvers for Apollo Server and graphql-tools. :star:309
* [apollo-errors](https://github.com/thebigredgeek/apollo-errors) - Machine-readable custom errors for Apollo Server. :star:316
* [graphql-disable-introspection](https://github.com/helfer/graphql-disable-introspection) - Graphql Disable Introspection :star:75
* [mongo-graphql-starter](https://github.com/arackaf/mongo-graphql-starter) - Flexible and robust Mongo based resolvers for Node. :star:272
* [altair-express-middleware](https://github.com/imolorhe/altair) - An express middleware for mounting an instance of Altair GraphQL client. :star:639
* [graphql-cost-analysis](https://github.com/pa-bru/graphql-cost-analysis) - A Graphql query cost analyzer. :star:222
* [gql](https://github.com/Mayank1791989/gql) - Graphql sevice which watches project files and provides validation, autocompletion, get defintion, etc. for GraphQL schema and queries. Works with Relay classic, Relay modern and Apollo, as well as embedded GraphQL queries within any other language such as JS, Golang, Ruby, Cucumber test files, etc. :star:71
* [gql-language-server](https://github.com/Mayank1791989/gql-language-server) - A language-server implementation on top of the [gql](https://github.com/Mayank1791989/gql) library. :star:2

##### Relay Related

* [relay](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications. :star:11581
* [graphql-relay-js](https://github.com/graphql/graphql-relay-js) - A library to help construct a graphql-js server supporting react-relay. :star:1051
* [sequelize-relay](https://github.com/MattMcFarland/sequelize-relay) - Serverside library that connects sequelize and graphql-relay-js together. :star:75
* [babel-plugin-react-relay](https://github.com/graphcool/babel-plugin-react-relay) - Babel Plugin for Relay with support for JSON & graphql-js schemas and URL endpoints. :star:54
* [babel-relay-plugin](https://www.npmjs.com/package/babel-relay-plugin) - Babel Relay Plugin for transpiling GraphQL queries for use with Relay.
* [react-router-relay](https://github.com/relay-tools/react-router-relay) - Relay integration for React Router. :star:564
* [relay-local-schema](https://github.com/relay-tools/relay-local-schema) - Use Relay without a GraphQL server. :star:216
* [relay-sink](https://github.com/acdlite/relay-sink) - Use Relay to fetch and store data outside of a React component. :star:129
* [recompose-relay](https://github.com/acdlite/recompose/tree/master/src/packages/recompose-relay) - Recompose helpers for Relay. :star:12566
* [Graylay](https://github.com/larsbs/graysql#Graylay) - A GraysQL extension to create a Relay compatible Schema. :star:29
* [Apollo Client](https://github.com/apollographql/apollo-client) - A simple alternative to Relay, comes with React and Angular bindings. :star:8883
* [react-relay-network-layer](https://github.com/nodkz/react-relay-network-layer) - A network layer for Relay with query batching and middleware support (urlThunk, retryThunk, auth, defer and other). :star:273
* [relay-subscriptions](https://github.com/edvinerikson/relay-subscriptions) - Subscription support for Relay. :star:184
* [Portfolio Relay Example](https://github.com/alex-cory/portfolio) - An example website that fetches data from various apis and uses Relay and GraphQL to feed the data to React components! :star:10
* [Relay Pokédex](https://github.com/lucasbento/react-relay-pokemon) - Project using GraphQL Pokémon to show how powerful Relay is. :star:61
* [vue-relay](https://github.com/ntkme/vue-relay) - A framework for building GraphQL-driven Vue.js applications. :star:43

<a name="lib-ts" />

### TypeScript Libraries

* [TypeGraphQL](https://github.com/19majkel94/type-graphql) - Create GraphQL schema and resolvers with TypeScript, using classes and decorators! :star:686
* [Vesper](http://vesper-framework.com) - NodeJS framework that helps you to create scalable, maintainable, extensible, declarative and fast GraphQL-based server applications.
* [graphql-strong](https://github.com/calebmer/graphql-strong) - Define your GraphQL schemas with confidence that your values are correct. :star:39
* [graphql-to-typescript](https://github.com/3VLINC/graphql-to-typescript) - Compiles GraphQL files into an importable typescript module with type definitions :star:29
* [graphql-decorator](https://github.com/Quramy/graphql-decorator) - Helps to build GraphQL schema with TypeScript. :star:40
* [graphql-schema-decorator](https://github.com/indigotech/graphql-schema-decorator) - This package makes possible the use of decorators to define a GraphQL schema. :star:34
* [graphql-typescript](https://github.com/vichyssoise/graphql-typescript) - Define and build GraphQL Schemas using typed classes :star:59
* [typegql](https://github.com/prismake/typegql) - Create GraphQL schema with type-safe class decorators. :star:154

<a name="lib-rb" />

### Ruby Libraries

* [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL. :star:3206
* [graphql-parser](https://github.com/Shopify/graphql-parser) - A small ruby gem wrapping the libgraphqlparser C library for parsing GraphQL.
* [graphql-client](https://github.com/github/graphql-client) - A Ruby library for declaring, composing and executing GraphQL queries. :star:634
* [graphql-batch](https://github.com/Shopify/graphql-batch) - A query batching executor for the graphql gem. :star:655
* [batch-loader](https://github.com/exaspark/batch-loader) – A powerful tool to avoid N+1 queries without extra dependencies or primitives.
* [graphql-guard](https://github.com/exAspArk/graphql-guard) - A simple field-level authorization for the graphql gem. :star:296
* [graphql-cache](https://github.com/stackshareio/graphql-cache) - A dead simple caching plugin for graphql-ruby. :star:107

<a name="lib-php" />

### PHP Libraries

* [graphql-php](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation. :star:2590
* [graphql-relay-php](https://github.com/ivome/graphql-relay-php) - Relay helpers for GraphQL & PHP. :star:192
* [API Platform](https://github.com/api-platform/api-platform) - API framework compatible with Symfony having native GraphQL support. :star:3365
* [laravel-graphql](https://github.com/Folkloreatelier/laravel-graphql) - Facebook GraphQL for Laravel 5. :star:1614
* [laravel-graphql-relay](https://github.com/nuwave/laravel-graphql-relay) - A Laravel library to help construct a server supporting react-relay. :star:45
* [graphql-mapper](https://github.com/4rthem/graphql-mapper) - This library allows to build a GraphQL schema based on your model. :star:31
* [graphql-bundle](https://github.com/suribit/GraphQLBundle) - GraphQL Bundle for Symfony 2. :star:37
* [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle) - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay. :star:374
* [GraphQL](https://github.com/Youshido/GraphQL) – Well documented PHP implementation with no dependencies.
* [GraphQL Symfony Bundle](https://github.com/Youshido/GraphQLBundle) – GraphQL Bundle for the Symfony 3 (supports 2.6+).
* [WPGraphQL](https://github.com/wp-graphql/wp-graphql) - WordPress plugin that exposes a Relay compliant GraphQL endpoint :star:847
* [graphql-wp](https://github.com/tim-field/graphql-wp) – a WordPress plugin that exposes a GraphQL endpoint.
* [eZ Platform GraphQL Bundle](https://www.symfony.fi/entry/graphql-bundle-adds-protocol-support-to-ez-platform-symfony-cms) - GraphQL Bundle for the eZ Platform Symfony CMS.
* [GraphQL Middleware](https://github.com/stefanorg/graphql-middleware) - GraphQL Psr7 Middleware :star:9
* [Zend Expressive GraphiQL Extension](https://github.com/stefanorg/zend-expressive-graphiql) - GraphiQL extension for zend expressive :star:1
* [GraphQL for PHP7](https://github.com/digiaonline/graphql-php) - A batteries-included, standard-compliant and easy to work with implementation of the GraphQL specification in PHP7 (based on the reference implementation). :star:133

<a name="lib-py" />

### Python Libraries

* [graphql-parser](https://github.com/tryolabs/graphql-parser) - GraphQL parser for Python. :star:40
* [graphql-core](https://github.com/graphql-python/graphql-core) - GraphQL implementation for Python. :star:301
* [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py) - A library to help construct a graphql-py server supporting react-relay. :star:102
* [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python) - A python wrapper around libgraphqlparser. :star:4
* [graphene](https://github.com/graphql-python/graphene) - A package for creating GraphQL schemas/types in a Pythonic easy way. :star:3803
* [graphene-gae](https://github.com/graphql-python/graphene-gae) - Adds GraphQL support to Google AppEngine (GAE). :star:94
* [flask-graphql](https://github.com/graphql-python/flask-graphql) - Adds GraphQL support to your Flask application. :star:593
* [python-graphql-client](https://github.com/graphcool/python-graphql-client) - Simple GraphQL client for Python 2.7+ :star:46
* [python-graphjoiner](https://github.com/healx/python-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise. :star:41
* [graphene-django](https://github.com/graphql-python/graphene-django) - A Django integration for Graphene. :star:1531

<a name="lib-java" />

### Java Libraries

* [graphql-java](https://github.com/graphql-java/graphql-java) - GraphQL Java implementation. :star:2637
* [graphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator) - Auto-generates types for use with GraphQL Java :star:32
* [schemagen-graphql](https://github.com/bpatters/schemagen-graphql) - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations. :star:36
* [graphql-java-annotations](https://github.com/graphql-java/graphql-java-annotations) - Provides annotations-based syntax for schema definition with GraphQL Java. :star:178
* [spring-graphql-common](https://github.com/oembedler/spring-graphql-common) - Spring Framework GraphQL Library. :star:106
* [graphql-spring-boot](https://github.com/graphql-java/graphql-spring-boot) - GraphQL and GraphiQL Spring Framework Boot Starters. :star:403
* [neo4j-graphql](https://github.com/neo4j-graphql/neo4j-graphql) - GraphQL bindings for Neo4j, generates and runs Cypher. :star:242
* [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - Asynchronous GraphQL service discovery and querying for your microservices. :star:32
* [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader) - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments :star:47
* [LiveGQL](https://github.com/Billy-Bichon/LiveGQL) - GraphQL subscription client in Java. :star:11
* [rdbms-to-graphql](https://github.com/ebridges/rdbms-to-graphql) - A Java CLI program that generates a GraphQL schema from a JDBC data source. :star:33
* [Rejoiner](https://github.com/google/rejoiner) - Generates a GraphQL schema based on one or more gRPC microservices, or any other Protobuf source. :star:1914
* [graphql-spqr](https://github.com/leangen/graphql-spqr) - GraphQL SPQR aims to make it dead simple to add a GraphQL API to any Java project. It works by dynamically generating a GraphQL schema from Java code. :star:268

<a name="lib-c" />

### C/C++ Libraries

* [libgraphqlparser](https://github.com/graphql/libgraphqlparser) - A GraphQL query parser in C++ with C and C++ APIs. :star:597

<a name="lib-go" />

### Go Libraries

* [graphql](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go follows graphql-js :star:3779
* [machinebox/graphql](https://github.com/machinebox/graphql) - Simple low-level GraphQL client for Go :star:268
* [graphql-relay-go](https://github.com/graphql-go/relay) - A Go/Golang library to help construct a server supporting react-relay. :star:281
* [graphql-go](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use. :star:2032
* [c-graphqlparser](https://github.com/tecbot/c-graphqlparser) - Go-gettable version of the libgraphqlparser C library for parsing GraphQL. :star:26
* [tallstreet-graphql](https://github.com/tallstreet/graphql) - GraphQL parser and server for Go that leverages libgraphqlparser :star:14
* [go-graphql](https://github.com/playlyfe/go-graphql) - A powerful GraphQL server implementation for Golang :star:213
* [dataloader](https://github.com/nicksrandall/dataloader) - Implementation of Facebook's DataLoader in Golang :star:302

<a name="lib-scala" />

### Scala Libraries

* [sangria](https://github.com/sangria-graphql/sangria) - Scala GraphQL client and server library. :star:1333
* [sangria-relay](https://github.com/sangria-graphql/sangria-relay) - Sangria Relay Support. :star:74
* [graphql-scala](https://github.com/hrosenhorn/graphql-scala) - An attempt to get GraphQL going with Scala. :star:5

<a name="lib-perl" />

### Perl Libraries

* [Perl6-GraphQL](https://github.com/CurtTilmes/Perl6-GraphQL) - GraphQL for Perl6. :star:14
* [graphql-perl](https://github.com/graphql-perl/graphql-perl) - GraphQL for Perl5. :star:37

<a name="lib-dotnet" />

### .NET Libraries

* [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET. :star:2524
* [Conventions](https://github.com/graphql-dotnet/conventions) - Reflection-based schema generation for .NET. :star:109
* [graphql-net](https://github.com/ckimes89/graphql-net) - GraphQL to IQueryable for .NET :star:644
* [FSharp.Data.GraphQL](https://github.com/fsprojects/FSharp.Data.GraphQL) - FSharp GraphQL. :star:187
* [GraphQL.Client](https://github.com/graphql-dotnet/graphql-client) - GraphQL Client for .NET. :star:101
* [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - GraphQL Server for .net core and .net classic. :star:112

<a name="lib-erlang" />

### Erlang Libraries

* [graphql-erlang](https://github.com/shopgun/graphql-erlang) - Pure Erlang implementation with IDL and pattern-matching. :star:207

<a name="lib-elixir" />

### Elixir Libraries

* [absinthe-graphql](https://github.com/absinthe-graphql/absinthe) - Fully Featured Elixir GraphQL Library. :star:2334
* [graphql-elixir](https://github.com/graphql-elixir/graphql) - GraphQL Elixir. :star:811
* [plug_graphql](https://github.com/graphql-elixir/plug_graphql) - Plug integration for GraphQL Elixir. :star:122
* [graphql_relay](https://github.com/graphql-elixir/graphql_relay) - Relay helpers for GraphQL Elixir. :star:34
* [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - Elixir bindings for [libgraphqlparser](https://github.com/graphql/libgraphqlparser) :star:597
* [graphql](https://github.com/asonge/graphql) - Elixir GraphQL parser. :star:89
* [plot](https://github.com/peburrows/plot) - GraphQL parser and resolver for Elixir. :star:29

<a name="lib-haskell" />

### Haskell Libraries

* [graphql-haskell](https://github.com/jdnavarro/graphql-haskell) - GraphQL AST and parser for Haskell. :star:153

<a name="lib-sql" />

### SQL Libraries

* [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) - GraphQL for Postgres. :star:1000
* [sql-to-graphql](https://github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure. :star:474
* [PostGraphile](https://github.com/graphile/postgraphile) - A GraphQL API created by reflection over a PostgreSQL schema. :star:6175
* [rdbms-to-graphql](https://github.com/ebridges/rdbms-to-graphql) - A Java CLI program that generates a GraphQL schema from a JDBC data source. :star:33
* [Prisma](https://github.com/graphcool/prisma) - Turn your database into a GraphQL API. Prisma lets you design your data model and have a production ready GraphQL API online in minutes. :star:10849
* [tuql](https://github.com/bradleyboy/tuql) - Automatically create a GraphQL server from any sqlite database. :star:278
* [Hasura](https://github.com/hasura/graphql-engine) - Instant realtime GraphQL APIs on Postgres with access control. Works with existing database. :star:4648

<a name="lib-lua" />

### Lua Libraries

* [graphql-lua](https://github.com/bjornbytes/graphql-lua) - GraphQL for Lua. :star:100

<a name="lib-elm" />

### Elm Libraries

* [jamesmacaulay/elm-graphql](https://github.com/jamesmacaulay/elm-graphql) - Client library that lets you build GraphQL queries in Elm. :star:305
* [ghivert/elm-graphql](https://github.com/ghivert/elm-graphql) - Client library that lets you build GraphQL queries in Elm with your own decoders. :star:42
* [jahewson/elm-graphql](https://github.com/jahewson/elm-graphql) - Command-line tool that generates Elm code from queries in .graphql files. :star:315

<a name="lib-clojure" />

### Clojure Libraries

* [graphql-clj](https://github.com/tendant/graphql-clj) - A Clojure library designed to provide GraphQL implementation. :star:249
* [lacinia](https://github.com/walmartlabs/lacinia) - GraphQL implementation in pure Clojure. :star:1037
* [alumbra](https://github.com/alumbra/alumbra) - Simple & Elegant GraphQL for Clojure! :star:120

<a name="lib-clojurescript" />

### ClojureScript Libraries

* [speako](https://github.com/johanatan/speako) - A ClojureScript/NPM compiler for GraphQL Schema Language. :star:8
* [venia](https://github.com/Vincit/venia) - A Clojure(Script) GraphQL query generation :star:144

<a name="lib-swift" />

### Swift Libraries

* [GraphQL](https://github.com/GraphQLSwift/GraphQL) - Build GraphQL APIs with Swift. :star:607
* [Graphiti](https://github.com/GraphQLSwift/Graphiti) - Build Swiftier GraphQL APIs with Swift. :star:119
* [Gryphin](https://github.com/dbart01/Gryphin) - Type-safe GraphQL client for iOS and MacOS written in Swift. :star:19
* [Apollo-iOS](https://github.com/apollographql/apollo-ios) - Strongly typed, code-generating, caching GraphQL client for Swift. :star:1435
* [LiveGQL](https://github.com/florianmari/LiveGQL) - GraphQL Subscription client in Swift. :star:71

<a name="lib-ocaml" />

### OCaml Libraries

* [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server) - GraphQL servers in OCaml. :star:360

<a name="lib-reasonml" />

### ReasonML Libraries

* [reason-apollo](https://github.com/apollographql/reason-apollo) - GraphQL Client (binding to react-apollo). :star:369

<a name="lib-rust" />

### Rust Libraries

* [juniper](https://github.com/mhallin/juniper) - GraphQL server library for Rust. :star:1007
* [graphql-client](https://github.com/tomhoule/graphql-client) - GraphQL client library for Rust with WebAssembly (wasm) support. :star:115
* [graphql-parser](https://github.com/graphql-rust/graphql-parser) - A parser, formatter and AST for the GraphQL query and schema definition language for Rust. :star:56

<a name="lib-r" />

### R Libraries

* [graphql](https://github.com/ropensci/graphql) - Bindings to libgraphqlparser for R. :star:21
* [gqlr](https://github.com/schloerke/gqlr) - GraphQL server package for R. :star:19
* [ghql](https://github.com/ropensci/ghql) - GraphQL client package for R. :star:34

<a name="lib-julia" />

### Julia Libraries

* [Diana.jl](https://github.com/codeneomatrix/Diana.jl) -  Julia client for GraphQL. :star:15

<a name="lib-kotlin" />

### Kotlin Libraries

* [ktq](https://github.com/prestongarno/ktq) - Kotlin gradle plugin SDL type generator & runtime client :star:22

<a name="lib-unity" />

### Unity Libraries

* [graphQL-client-unity](https://github.com/Gazuntype/graphQL-client-unity) - A Unity client for GraphQL. :star:34

<a name="lib-crystal" />

### Crystal Libraries

* [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - A graphql implementation for Crystal :star:128

<a name="tools" />

### Wechat APP Libraries(mini-program)

* [wxapp-graphql](https://github.com/Authing/wxapp-graphql) - GraphQL client for mini-program(wechat app) :star:34

<a name="lib-miniprogram" />

## Tools

* [graphiql](https://github.com/graphql/graphiql) - An in-browser IDE for exploring GraphQL. :star:6863
* [GraphQL Playground](https://github.com/graphcool/graphql-playground) - GraphQL IDE that supports multi-column schema docs, tabs, query history, configuration of HTTP headers and GraphQL Subscriptions. :star:3100
* [GraphiQL.app](https://github.com/skevy/graphiql-app) - A light, Electron-based wrapper around GraphiQL. :star:1692
* [GraphQLviz](https://github.com/Macroz/GraphQLviz) - GraphQLviz marries GraphQL (schemas) with Graphviz. :star:89
* [graphqlviz](https://github.com/sheerun/graphqlviz) - GraphQL API visualizer in Node.js :star:374
* [Graphql for VSCode](https://github.com/kumarharsh/graphql-for-vscode) - VSCode extension for GraphQL schema authoring & consumption. Uses the language server protocol to provide first-class editing capabilities for graphql devs. :star:185
* [Relay Playground](http://facebook.github.io/relay/prototyping/playground.html)
* [GraphQL AST Explorer](http://dferber90.github.io/graphql-ast-explorer/) - Explore the AST of a GraphQL document interactively
* [GraphQLHub](https://www.graphqlhub.com/) - Query public API's schemas (e.g. Reddit, Twitter, Github, etc) using GraphiQL
* [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript. :star:350
* [gdom](https://github.com/syrusakbary/gdom) - DOM Traversing and Scraping using GraphQL. :star:1045
* [Annotated GraphQL Server](https://github.com/almilo/annotated-graphql-server) - Server for annotated GraphQL showing how to transform a REST api into a GraphQL endpoint with annotations. :star:13
* [Model Visualizer](http://nathanrandal.com/graphql-visualizer/) - A small webapp that generates an ERD-like visualization of a GraphQL endpoint from an introspection query.
* [GraphQL Network](https://github.com/Ghirro/graphql-network) - A chrome dev-tools extension for debugging GraphQL network requests. :star:184
* [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) - An ESLint plugin that checks your GraphQL strings against a schema. :star:599
* [AST Explorer](https://astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
* [vim-graphql](https://github.com/jparise/vim-graphql) - A Vim plugin that provides GraphQL file detection and syntax highlighting. :star:173
* [GraphQL CMS](https://github.com/sarkistlt/graphql-auto-generating-cms) - Use your existing GraphQL schema to generate simple for use, fully functional CMS in a couple steps. :star:323
* [graphdoc](https://github.com/2fd/graphdoc) - Static page generator for documenting GraphQL Schema. :star:521
* [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete) - Autocomplete and lint from a GraphQL endpoint in Atom. :star:45
* [GraphQL IDE](https://github.com/redound/graphql-ide) - An extensive IDE for exploring GraphQL API's. :star:749
* [Swagger to GraphQL](https://github.com/yarax/swagger-to-graphql) - GraphQL types builder based on REST API described in Swagger. Allows to migrate to GraphQL from REST for 5 minutes :star:383
* [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager) - Represent any GraphQL API as an interactive graph. :star:3305
* [GraphQL Docs](https://graphql-docs.com) - Instantly create beautiful GraphQL API docs hosted online.
* [GraphQL Faker](https://github.com/APIs-guru/graphql-faker) - 🎲 Mock or extend your GraphQL API with faked data. No coding required. :star:932
* [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) - A language service plugin complete and validate GraphQL query in TypeScript template strings. :star:205
* [Apollo Launchpad](https://launchpad.graphql.com/) - Like JSFiddle for GraphQL server code, write and deploy a GraphQL API directly from your browser.
* [Apollo Tracing](https://github.com/apollographql/apollo-tracing) - GraphQL extension that enables you to easily get resolver-level performance information as part of a GraphQL response. :star:216
* [Altair GraphQL Client](https://github.com/imolorhe/altair) - A beautiful feature-rich GraphQL Client for all platforms. :star:639
* [Apollo Storybook Decorator](https://github.com/abhiaiyer91/apollo-storybook-decorator) - Wrap your React Storybook stories with Apollo Client, provide mocks for isolated UI testing with GraphQL :star:155
* [GraphQL Metrics](https://github.com/Workpop/graphql-utils/tree/master/packages/graphql-metrics) - instrument GraphQL resolvers, logging response times and statuses (if there was an error or not) to the console as well as to InfluxDB. :star:16
* [GraphQL Rover](https://github.com/Brbb/graphql-rover) - GraphQL schema interactive navigation, rearrange nodes, search and explore types and fields. :star:145
* [json-graphql-server](https://github.com/marmelab/json-graphql-server) - Get a full fake GraphQL API with zero coding in less than 30 seconds, based on a JSON data file. :star:481
* [Insomnia](https://insomnia.rest/) – An full-featured API client with first-party GraphQL query editor
* [RAN Toolkit](https://github.com/sly777/ran) - Production-ready toolkit/boilerplate with support for GraphQL, SSR, Hot-reload, CSS-in-JS, caching, and more. :star:1525

<a name="databases" />

## Databases

* [ArangoDB](https://www.arangodb.com/) - Multi-model database that supports GraphQL schemas in JavaScript inside the database.
* [Dgraph](https://dgraph.io/) - Scalable, distributed, low latency, high throughput Graph database with a GraphQL like language (called [GraphQL+](https://docs.dgraph.io/query-language/)) as the query language. Dgrapqh can be queried with graphql by using [dgraphql](https://github.com/dpeek/dgraphql) :star:70

<a name="services" />

## Services

* [GraphCMS](https://graphcms.com/) - GraphQL based Headless Content Management System.
* [Graphcool](https://www.graph.cool/) - Your own GraphQL backend in under 5 minutes. Works with every GraphQL client such as Relay and Apollo.
* [Hasura](https://hasura.io/) - Create tables and get a GraphQL backend in under 60s. Works on top of Postgres that you can directly access. No initial knowledge of graphql required.
* [Reindex](https://www.reindex.io/) - Instant GraphQL Backend for Your React Apps.
* [Scaphold](https://scaphold.io/) - GraphQL as a service that includes API integrations such as Stripe and Mailgun.
* [Tipe](https://tipe.io/) - Next Generation API-first CMS with a GraphQL or REST API. Stop letting your CMS decide how you build your apps.
* [AWS AppSync](https://aws.amazon.com/appsync/) - Serverless GraphQL

<a name="example" />

## Examples

<a name="example-js" />

### JavaScript Examples

* [relay-starter-kit](https://github.com/relayjs/relay-starter-kit) - Barebones starting point for a Relay application. :star:1059
* [react-starter-kit](https://github.com/kriasoft/react-starter-kit) - Isomorphic web app boilerplate (Node.js/Express, GraphQL, React) :star:18409
* [nodejs-api-starter](https://github.com/kriasoft/nodejs-api-starter) - Boilerplate and tooling for authoring data API backends with Node.js and GraphQL :star:1816
* [swapi-graphql](https://github.com/graphql/swapi-graphql) - A GraphQL schema and server wrapping [swapi](http://swapi.co/). :star:666
* [graphql-server](https://github.com/RisingStack/graphql-server) - GraphQL server with Mongoose (MongoDB) and Node.js. :star:815
* [graphql-intro](https://github.com/clayallsopp/graphql-intro) - https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2 :star:85
* [graphql-aws](https://github.com/jonsharratt/graphql-aws) - Amazon AWS GraphQL API Server. :star:66
* [graffiti-todo](https://github.com/RisingStack/graffiti-todo) - Example Relay TodoMVC application using graffiti-mongoose. :star:56
* [devknoll/gist:8b274f1c5d05230bfade](https://gist.github.com/devknoll/8b274f1c5d05230bfade)
* [UniversalRelayBoilerplate](https://github.com/codefoundries/UniversalRelayBoilerplate) :star:577
Boilerplate + examples for React Native (iOS, Android), React (isomorphic, Material-UI), Relay, GraphQL, JWT, Node.js, Apache Cassandra.
* [vslinko/ripster](https://github.com/vslinko/ripster/tree/master/src/graphql) :star:140
* [relay-skeleton](https://github.com/fortruce/relay-skeleton) - React, Relay, GraphQL project skeleton :star:122
* [simple-relay-starter](https://github.com/mhart/simple-relay-starter) - A very simple starter for React Relay using Browserify. :star:163
* [relay-chat](https://github.com/transedward/relay-chat) - an chat example showing Relay with routing and pagination. :star:89
* [relay-todomvc](https://github.com/taion/relay-todomvc) - Relay TodoMVC with routing. :star:144
* [graphql-express-sqlite](https://github.com/mrblueblue/graphql-express-sqlite) - GraphQL server with Sqlite and Express :star:69
* [koa-graphql-relay-example](https://github.com/chentsulin/koa-graphql-relay-example) - Example of [koa-graphql](https://github.com/chentsulin/koa-graphql) :star:602
* [relay-fullstack](https://github.com/lvarayut/relay-fullstack) - Relay Starter Kit integrated with Relay, GraphQL, Express, ES6/ES7, JSX, Webpack, Babel, Material Design Lite, and PostCSS. :star:943
* [serverless-graphql-blog](https://github.com/serverless/serverless-graphql-blog) - A Serverless Blog leveraging GraphQL to offer a REST API with only 1 endpoint :star:746
* [relay-cart](https://github.com/soonlive/relay-cart) - A simple shopping cart example leveraging relay & GraphQL with routing and pagination. :star:19
* [graphql-loader](https://github.com/applification/graphql-loader) - Example project to illustrate GraphQL, Express and Facebook DataLoader to connect to third party REST API :star:46
* [swapi-graphql-lambda](https://github.com/alvinthen/swapi-graphql-lambda) - A GraphQL schema hosted in AWS Lambda wrapping http://swapi.co/ :star:15
* [Apollo Client documentation](http://dev.apollodata.com/react/) - Documentation and example for building GraphQL apps using apollo client
* [Apollo Server tools, products, and libraries documentation](https://www.apollographql.com/docs/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
* [Apollo Link](https://www.apollographql.com/docs/link/) - The official guide for getting started with Apollo Link - a standard interface for modifying control flow of GraphQL requests and fetching GraphQL results.
* [f8-apollo](https://github.com/nnance/f8app-apollo) - Refactored version of the official F8 app of 2016, powered by React Native and the Apollo Stack. :star:110
* [f8app](https://github.com/fbsamples/f8app) - Source code of the official F8 app of 2016, powered by React Native and other Facebook open source projects. [http://makeitopen.com](http://makeitopen.com)
* [Reindex Examples](https://github.com/reindexio/reindex-examples) - Example projects for Reindex with using React Native and React.js for web. :star:165
* [Modelizr Documentation](https://julienvincent.github.io/modelizr/) - Documentation and Usage Examples for modelizr
* [Vue Apollo Example](https://github.com/Akryum/frontpage-vue-app) - Apollo example project for Vue 2.0. :star:70
* [angular2-graphql-rest](https://github.com/kamilkisiela/angular2-graphql-rest) - An example app with REST Api working side by side with GraphQL using Apollo Client with angular2-apollo. Includes step-by-step tutorial how to migrate from REST to GraphQL. :star:28
* [GraphQL-DataLoader-Boilerplate](https://github.com/entria/graphql-dataloader-boilerplate) - Boilerplate to start your GraphQL with DataLoader server :star:340
* [GraphQL-CEP](https://github.com/sibelius/graphql-cep) - Query address by CEP :star:20
* [Apollo React example for Github GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example) - Usage Examples Apollo React for Github GraphQL API with create-react-app :star:79
* [Intuitive GraphQL Resolver Example](https://github.com/xpepermint/graphql-example) - GraphQL application example using [RawModel.js](https://github.com/xpepermint/rawmodeljs). :star:19
* [ReactQL starter kit](https://reactql.org) - Universal React + Apollo + Redux + React Router 4, with SSR-enabled GraphQL, store (de/re)hydration and production code bundling.
* [microhn](https://github.com/stubailo/microhn) - Simple Hacker News client built on top of GraphQLHub :star:76
* [Apollo Web&Mobile Universal Starter Kit with Hot Code Reload](https://github.com/sysgears/apollo-universal-starter-kit) -  Apollo, GraphQL, React, React Native, Expo, Redux, Express, SQL and Twitter Bootstrap. Hot Code Reload of back end & front end using Webpack and Hot Module Replacement. :star:968
* [Building Decoupled Sites and Apps with GraphQL and Next.js](https://malloc.fi/building-decoupled-sites-and-apps-with-graphql-and-next-js)

<a name="example-ts" />

### TypeScript Examples
* [Basic Apollo Server](https://github.com/DxCx/webpack-graphql-server) - Basic Starter for Apollo Server, Using typescript and Webpack. :star:136
* [Apollo Graphql Express Server](https://github.com/FinalDes/apollo-express-ts-server-boilerplate) - Minimal Apollo Graphql Express Server :star:20
* [Prisma/Apollo/React Full-stack Example](https://github.com/KATT/shop) - An e-commerce example project with Prisma, GraphQL API Gateway, React, Apollo, Next.js, SSR, CI, and E2E testing. All TypeScript. :star:145

<a name="example-rb" />

### Ruby Examples

* [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) - Use graphql-ruby to expose a Rails app. :star:213
* [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example) - Example Rails app using GitHub's GraphQL API. :star:241
* [relay-on-rails](https://github.com/nethsix/relay-on-rails) - Barebones starter kit for Relay application with Rails GraphQL server. :star:40
* [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog) - A graphql, relay and standard rails application powered demo weblog. :star:132
* [to_eat_app](https://github.com/jcdavison/to_eat_app) - A sample graphql/rails/relay application with a related 3-part article series. :star:12

<a name="example-go" />

### Go Examples

* [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit) - Barebones starting point for a Relay application with Golang GraphQL server. :star:104
* [golang-graphql-playground](https://github.com/graphql-go/playground) - An example Golang GraphQL server written with graphql-go and graphql-relay-go. Try live demo at: http://golanggraphqlplayground-sogko.rhcloud.com :star:102
* [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend. :star:56

<a name="example-scala" />

### Scala Examples

* [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http and [sangria](http://sangria-graphql.org)
* [sangria-playground](https://github.com/sangria-graphql/sangria-playground) - An example of GraphQL server written with Play and sangria. :star:62

<a name="example-python" />

### Python Examples

* [swapi-graphene](https://github.com/graphql-python/swapi-graphene) - A GraphQL schema and server using [Graphene](http://graphene-python.org) - [View demo online](http://swapi.graphene-python.org).

<a name="example-elixir" />

### Elixir Examples

* [Absinthe tutorial code](https://github.com/absinthe-graphql/absinthe_tutorial) - Example usage of Absinthe GraphQL :star:27
* [hello_graphql_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix - [View demo online](http://playground.graphql-elixir.org). :star:94

<a name="example-php" />

### PHP Examples
* [Siler's GraphQL guide](https://siler.leocavalcante.com/graphql/) - A guide on how to build a PHP GraphQL endpoint.
* [Laravel GraphQL](https://github.com/ardani/laravel-graphql) - A sample integrating GraphQL with Laravel :star:63
* [Adding a GraphQL API to your Symfony Flex application](https://symfony.fi/entry/adding-a-graphql-api-to-your-symfony-flex-app)

<a name="example-reasonml" />

### ReasonML Examples
* [Realtime chat application](https://github.com/apollographql/reason-apollo/tree/master/examples/realtime-chat-application) - Realtime chat application with reason-apollo (Queries, Mutations, Subscriptions). :star:369
* [Todo list example](https://github.com/Gregoirevda/reason-ml-graphql-todo-list) - A todo list integrating GraphQL. :star:80

<a name="video" />

## Videos

* [Zero-config Apollo + GraphQL with Apollo Boost](https://egghead.io/lessons/react-zero-config-apollo-graphql-with-apollo-boost)
* [Zero to GraphQL in 30 Minutes](https://www.youtube.com/embed/UBGzsb2UkeY)
* [Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
* [React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
* [Exploring GraphQL](https://www.youtube.com/watch?v=WQLzZf34FJ8)
* [Creating a GraphQL Server](https://www.youtube.com/watch?v=gY48GW87Feo)
* [GraphQL at The Financial Times](https://www.youtube.com/watch?v=S0s935RKKB4)
* [Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg)
* [Building and Deploying Relay with Facebook](https://www.youtube.com/watch?t=643&v=Pxdgu2XIAAg)
* [Introduction to GraphQL](https://vimeo.com/144817545)
* [Exploring GraphQL@Scale](https://www.youtube.com/watch?v=_9RgHXqH8J0)
* [What's Next for Phoenix by Chris McCord](https://www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be)
* [GraphQL with Nick Schrock](https://www.youtube.com/watch?v=Ed6oJXKt3-M)
* [Build a GraphQL server for Node.js using PostgreSQL/MySQL](https://www.youtube.com/watch?v=DNPVqK_woRQ)
* [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](https://www.youtube.com/watch?v=PHabPhgRUuU)
* [JavaScript Air Episode 023: Transitioning from REST to GraphQL](https://www.youtube.com/watch?v=ENqDNIp1Nd8)
* [GraphQL Future at react-europe 2016](https://www.youtube.com/watch?v=ViXL0YQnioU)
* [GraphQL at Facebook at react-europe 2016](https://www.youtube.com/watch?v=etax3aEe2dA)
* [Building native mobile apps with GraphQL at react-europe 2016](https://www.youtube.com/watch?v=z5rz3saDPJ8)

<a name="blogs" />

## Blogs
* [Official GraphQL blog](http://graphql.org/blog/)
* [Building Apollo](https://dev-blog.apollodata.com/)

<a name="post" />

## Posts

* [Using DataLoader to batch GraphQL requests](http://gajus.com/blog/9/using-dataloader-to-batch-requests)
* [Introducing Relay and GraphQL](https://facebook.github.io/react/blog/2015/02/20/introducing-relay-and-graphql.html)
* [GraphQL Introduction](https://facebook.github.io/react/blog/2015/05/01/graphql-introduction.html)
* [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
* [Your First GraphQL Server](https://medium.com/@clayallsopp/your-first-graphql-server-3c766ab4f0a2)
* [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
* [4 Reasons you should try out GraphQL](https://medium.freecodecamp.com/introduction-to-graphql-1d8011b80159)
* [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
* [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
* [Start using GraphQL with Graffiti](https://blog.risingstack.com/start-using-graphql-with-graffiti/?utm_source=nodeweekly&utm_medium=email)
* [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
* [GraphQL at The Financial Times](https://www.slideshare.net/LondonReact/graph-ql)
* [Relay for visual learners](http://sgwilym.github.io/relay-visual-learners/)
* [Relay and Routing](https://medium.com/@cpojer/relay-and-routing-36b5439bad9)
* [Learn Golang + GraphQL + Relay, Part 1: Your first Golang GraphQL server](https://wehavefaces.net/learn-golang-graphql-relay-1-e59ea174a902)
* [Learn Golang + GraphQL + Relay, Part 2: Your first Relay application](https://wehavefaces.net/learn-golang-graphql-relay-2-a56cbcc3e341)
* [From REST to GraphQL](https://0x2a.sh/from-rest-to-graphql-b4e95e94c26b)
* [GraphQL: A data query language](http://graphql.org/blog/graphql-a-query-language/)
* [Subscriptions in GraphQL and Relay](http://graphql.org/blog/subscriptions-in-graphql-and-relay/)
* [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)
* [GraphQL Shorthand Notation Cheatsheet](https://wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
* [The GitHub GraphQL API](https://githubengineering.com/the-github-graphql-api/)
* [Github GraphQL API React Example](https://medium.com/@katopz/github-graphql-api-react-example-eace824d7b61)
* [Testing a GraphQL Server using Jest](https://medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e)
* [How to implement viewerCanSee in  GraphQL](https://medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464)
* [Introducing Yelp's Local Graph](https://engineeringblog.yelp.com/2017/05/introducing-yelps-local-graph.html)
* [Sharing data in a Microservices Architecture using GraphQL](https://labs.getninjas.com.br/sharing-data-in-a-microservices-architecture-using-graphql-97db59357602)
* [Let's build a node.js GraphQL server for fetching Spotify REST API, in German](https://blog.codecentric.de/2017/09/graphql-mit-spotify-teil-1-server/) |  [in English](https://blog.codecentric.de/en/2017/01/lets-build-spotify-graphql-server/)
* [“Client-side only” realtime web applications with Firebase, GraphQL and apollo-client 2.0](https://medium.com/@pierrecriulanscy/client-side-only-realtime-web-applications-with-firebase-graphql-and-apollo-client-2-0-9606160f7cf8)

<a name="books" />

## Books

* [The GraphQL Guide](https://graphql.guide) by John Resig and Loren Sands-Ramshaw
* [Learning GraphQL](https://www.amazon.com/Learning-GraphQL-Declarative-Fetching-Modern/dp/1492030716/) by Eve Porcello and Alex Banks
* [Fullstack GraphQL](https://www.graphql.college/fullstack-graphql) by Julian Mayorga
* [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) by Bruce Williams and Ben Wilson
* [Learning GraphQL and Relay](https://www.packtpub.com/web-development/learning-graphql-and-relay) by Samer Buna

<a name="workshopper" />

## Tutorials

* [How to GraphQL](https://www.howtographql.com) - Fullstack Tutorial Website with Tracks for all Major Frameworks & Languages including React, Apollo, Relay, JavaScript, Ruby, Java, Elixir and many more
* [learning-graphql](https://github.com/mugli/learning-graphql) - An attempt to learn GraphQL. :star:788
* [Learn Relay](https://www.learnrelay.org/) - A comprehensive introduction to Relay
* [Learn Apollo](https://www.learnapollo.com/) - A hands-on tutorial for Apollo GraphQL Client

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.

