# Information comes from [marmelab/awesome-rest](https://github.com/marmelab/awesome-rest)
# Awesome REST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collaborative list of great resources about RESTful API architecture, development, test, and performance. Feel free to contribute to this on-going list.

* [Design](#design)
* [Standards](#standards)
* [Clients](#clients)
  * [PHP](#php-clients)
  * [Client-side JavaScript](#javascript-clients)
  * [Node.js](#nodejs-clients)
  * [Ruby](#ruby-clients)
  * [Go](#go-clients)
* [Servers](#servers)
  * [Directly On Top Of A RMDB](#directly-on-top-of-a-rmdb)
  * [Node.js](#nodejs)
  * [PHP](#php)
  * [Symfony2](#symfony2)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Go](#go)
  * [Java](#java)
  * [Haskell](#haskell)
* [Testing](#testing)
  * [Querying](#querying)
  * [Mocking](#mocking)
  * [Public REST APIs To Use In Tests](#public-rest-apis-to-use-in-tests)
* [Documentation](#documentation)
* [API Gateway](#api-gateway)
* [SaaS Tools](#saas-tools)
* [Miscellaneous](#miscellaneous)



## Design

* [Architectural Styles and
the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm) - Roy Fielding's dissertation defining REST
* [HTTP API design guide extracted from work on the Heroku Platform API](https://github.com/interagent/http-api-design) :star:12916
* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to design a REST API?](http://blog.octo.com/en/design-a-rest-api/) - Full guide tackling security, pagination, filtering, versioning, partial answers, CORS, etc.
* [Richardson Maturity Model](http://martinfowler.com/articles/richardsonMaturityModel.html) - Explained by Martin Fowler, originally presented by Leonard Richardson at the [QCon 2008](https://www.crummy.com/writing/speaking/2008-QCon/act3.html).
* [Enterprise Integration Using REST](http://martinfowler.com/articles/enterpriseREST.html) - Discusses the constraints and flexibility that you have with nonpublic APIs, and lessons learned from doing large scale RESTful integration across multiple teams.
* [HATEOAS](http://timelessrepo.com/haters-gonna-hateoas) - Clear explanation on what HATEOAS is, and why you should use it.
* [How to GET a cup of coffee](http://www.infoq.com/articles/webber-rest-workflow/)
* [REST API Tutorial](http://www.restapitutorial.com/) - RestApiTutorial.com is dedicated to tracking REST API best practices and making resources available to enable quick reference and self education for the development crafts-person.
* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md#readme) - The Microsoft REST API Guidelines, as a design principle, encourages application developers to have resources accessible to them via a RESTful HTTP interface. :star:9111
* [API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) - Best practices about REST API security :star:11766

## Standards

* [JSON API](http://jsonapi.org/) - Standard for building APIs in JSON.
* [RAML](http://raml.org/) - Simple and succinct way to describe RESTful API.
* [JSend](http://labs.omniti.com/labs/jsend) - Simple specification that lays down some rules for how JSON responses from web servers should be formatted.
* [OData](http://www.odata.org/) - Open protocol to allow the creation and consumption of queryable and interoperable RESTful APIs. Quite complex.
* [HAL](http://stateless.co/hal_specification.html) - Simple format that gives a consistent and easy way to hyperlink between resources in your API (see: [HATEOAS](#hateoas)).
* [JSON-LD](http://json-ld.org/) - Standard for describing Linked Data and hypermedia relations in JSON (W3C).
* [Hydra](http://www.hydra-cg.com/) - Vocabulary for Hypermedia-Driven Web APIs (W3C).
* [Schema.org](http://schema.org) - Collection of schemas describing common data models.
* [OpenAPI](https://openapis.org/) - Formerly known as the Swagger Specification, OpenAPI specifcation is the world’s most popular description format for defining Restful APIs.

## Clients

### PHP Clients

* [Guzzle](http://guzzle.readthedocs.org/en/latest/) - HTTP client and framework for consuming RESTful web services.
* [Buzz](https://github.com/kriswallsmith/buzz) - Another lightweight HTTP client. :star:1532
* [unirest for PHP](https://github.com/Mashape/unirest-php) - Simplified, lightweight HTTP client library. :star:1073

### JavaScript Clients

* [restangular](https://github.com/mgonto/restangular) - AngularJS service to handle REST API properly and easily. :star:8170
* [restful.js](https://github.com/marmelab/restful.js) - JS client for interacting with server-side RESTful resources. :star:950
* [traverson](https://github.com/basti1302/traverson) - A Hypermedia API/HATEOAS Client for Node.js and the Browser :star:294
* [raml-client-generator](https://github.com/mulesoft/raml-client-generator) - Generates static client libs for js. :star:116

### Node.js Clients

 * [restler](https://github.com/danwrong/restler) - REST client library for node.js. :star:1976
 * [unirest for Node.js](https://github.com/Mashape/unirest-nodejs) - Simplified, lightweight HTTP client library. :star:816

### Ruby Clients

* [RESTClient](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions. :star:4497
* [Spyke](https://github.com/balvig/spyke) - Interact with REST services in an ActiveRecord-like manner. :star:523
* [excon](https://github.com/excon/excon) - Usable, fast, simple Ruby HTTP 1.1. It works great as a general HTTP(s) client and is particularly well suited to usage in API clients. :star:905
* [httparty](https://github.com/jnunemaker/httparty) - Makes HTTP fun again! :star:4678
* [Net::HTTP](http://ruby-doc.org/stdlib/libdoc/net/http/rdoc/Net/HTTP.html) - Net::HTTP provides a rich library which can be used to build HTTP user-agents.
* [raml-ruby-client-generator](https://github.com/zlx/raml-ruby-client-generator) - Auto generate API client from a RAML file. :star:2

### Go Clients

* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs. :star:413
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client. :star:1138

## Servers

### Directly On Top Of A RMDB

* [postgrest](https://github.com/begriffs/postgrest) - Serve a fully RESTful API directly from an existing PostgreSQL database. :star:11432
* [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - Simple REST-like / CRUD server for any MySQL database.
* [pREST](https://github.com/prest/prest) - A fully RESTful API from any existing PostgreSQL database written in Go. :star:1849

### Node.js

* [node-restify](https://github.com/restify/node-restify) - Framework specifically meant for REST API. :star:8709
* [Sails.js](http://sailsjs.org/) - Node.js Web framework embedding a command to generate automatically a REST API.
* [mers](https://github.com/jspears/mers) - Express service exposing Mongoose finders as RESTful API. :star:344
* [Baucis](https://github.com/wprl/baucis) - Build scalable REST API based on your Mongoose entities. :star:648
* [flatiron/resourceful](https://github.com/flatiron/resourceful) - Isomorphic Resource engine for JavaScript. :star:358
* [loopback](http://loopback.io/) - Powerful Node.js framework for creating APIs and easily connecting to backend data sources.
* [Feathers](http://feathersjs.com/) - is a real-time, micro-service web framework that gives you control over your data via RESTful resources, sockets and flexible plug-ins.
* [Expressa](https://github.com/thomas4019/expressa) - Express middleware for creating APIs from JSON schemas with a simple admin editor and permissions model. :star:235
* [rest-hapi](https://github.com/JKHeadley/rest-hapi) - Generate RESTful API based on mongoose models that supports relational data. :star:735

### PHP

* [Microrest](https://github.com/marmelab/microrest.php) - Micro-web application providing a REST API on top of any relational database. :star:191
* [Negotiation](https://github.com/willdurand/Negotiation) - Content negotiation library. :star:758
* [Drest](https://github.com/leedavis81/drest) - Library for exposing Doctrine entities as REST resource endpoints. :star:86
* [Restler](https://github.com/Luracast/Restler) - Lightweight framework to expose PHP methods as RESTful web API. :star:1260
* [HAL](https://github.com/blongden/hal) - Hypertext Application Language (HAL) builder library. :star:192
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) - API builder built with Zend Framework 2. :star:478
* [phprest](https://github.com/phprest/phprest) - Specialized REST microframework for PHP. :star:316
* [Hateoas](https://github.com/willdurand/Hateoas) - PHP library to support implementing representations for HATEOAS REST web services. :star:862
* [Fusio](https://github.com/apioo/fusio) - Open source API management platform. :star:571

#### Symfony2

* [REST APIs with Symfony2: the Right Way](http://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - Complete guide to build a state-of-the-art REST API with Symfony2 framework.
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) - Bundle handling view, routing, error handling, etc. for your REST API. :star:1919
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle) - Build a REST API based on Doctrine entities using conventions over configuration. :star:129
* [lakion/Lionframe](http://lakion.com/lionframe) - Glu between several community libraries to ease API development.
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) - Integrate the [Hateoas](https://github.com/willdurand/Hateoas) library into a Symfony2 application. :star:237
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition) - Start with a Symfony2 application with all REST-friendly bundles pre-configured. :star:639
* [NgAdminGeneratorBundle](https://github.com/marmelab/NgAdminGeneratorBundle) - Boostrap ng-admin configuration based on `stanlemon/rest-bundle`. :star:76
* [DunglasApiBundle](https://github.com/dunglas/DunglasApiBundle) - Build a REST API which follow Hydra/JSON-LD specification. :star:850
* [API Platform](https://github.com/api-platform/api-platform) - Specialize Symfony edition for the creation of hypermedia REST APIs. :star:3365
* [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) - Generate documentation for your REST API from annotations. :star:1551

### Python

* [Django REST framework](http://www.django-rest-framework.org/) - Powerful and flexible toolkit that makes it easy to build Web APIs.
* [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* [flask-restful](http://flask-restful.readthedocs.org/) - Extension for Flask that adds support for quickly building REST APIs.
* [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Flask extension for generating ReSTful APIs for database models defined with SQLAlchemy (or Flask-SQLAlchemy).
* [hug](http://www.hug.rest/) - Lightweight and fast API Framework.
* [sandman](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems. :star:2304
* [restless](http://restless.readthedocs.org/en/latest/) - Framework agnostic REST framework based on lessons learned from TastyPie.
* [savory-pie](https://github.com/RueLaLa/savory-pie/) - REST API building library (django, and others). :star:7
* [Python Eve](http://python-eve.org/) - Eve is an open source Python REST API framework designed for human beings. It allows to effortlessly build and deploy highly customizable, fully featured RESTful Web Services.
* [Ramses](https://ramses.readthedocs.org/en/stable/) - Makes RAML files executable by generating production-ready APIs from them at runtime.
* [Flask-Potion](https://github.com/biosustain/potion) - Flask-Potion is a powerful Flask extension for building RESTful JSON APIs. It also provides several Clients for easier access to the API. :star:428
* [apistar](https://github.com/encode/apistar) - A smart Web API framework, designed for Python 3.  :star:4840
* [Falcon](https://github.com/falconry/falcon) - Falcon is a bare-metal Python web API framework for building high-performance microservices, app backends, and higher-level frameworks. :star:5752

### Ruby

* [Grape](http://www.ruby-grape.org) - Opinionated micro-framework for creating REST-like APIs in Ruby.
* [Rails](http://guides.rubyonrails.org/api_app.html) - RailsGuides: Using Rails for API-only applications.

### Go

* [gocrud](https://github.com/manishrjain/gocrud): Go library to simplify creating, updating and deleting arbitrary depth structured data — to make building REST services fast and easy.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Thin layer on top of `net/http` that helps building RESTful APIs easily. :star:3195
* [sleepy](https://github.com/dougblack/sleepy) - RESTful micro-framework written in Go. :star:671
* [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test. :star:49
* [go-relax](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's. :star:153
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go. :star:110
* [go-restful](https://github.com/emicklei/go-restful) - A declarative highly readable framework for building restful API's. :star:2940
* [Goat](https://github.com/bahlo/goat) - Minimalistic REST API server in Go. :star:160
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services. :star:29
* [Zerver](https://github.com/cosiner/zerver) - Zerver is a expressive, modular, feature completed RESTful framework. :star:144

### Java

* [RestExpress](https://github.com/RestExpress/RestExpress) - Netty-based, highly performant, lightweight, container-less, plugin-extensible, framework that is ideal for microservice architectures. :star:855
* [Vertx-Web](https://github.com/vert-x3/vertx-web) - Vert.x-Web is a set of building blocks for building web applications with Vert.x, a toolkit for building reactive applications on the JVM. :star:502
* [Dropwizard](https://github.com/dropwizard/dropwizard) - A framework for developing ops-friendly, high-performance, RESTful web services. :star:6856

### Haskell
* [Rest for Haskell](https://github.com/silkapp/rest) - This package allows you to create REST APIs in Haskell. These APIs can be run in different web frameworks. They can also be used to automatically generate documentation as well as client libraries. :star:381

## Testing

### Querying

* [Hurl.it](https://www.hurl.it/) - Make HTTP requests with a simple web-based HTTP client -- like `curl` in the cloud.
* [httpie](https://github.com/jkbrzt/httpie) - Command line HTTP client, far more dev-friendly than `curl`. :star:37852
* [Postman REST Client](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) - Chrome extension essential to test manually REST API.
* [resty](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines (bash or zsh). :star:2351
* [jq](https://github.com/stedolan/jq) - Command line JSON processor, to use in combination with a command-line HTTP client like cURL. :star:12604
* [HttpMaster](http://www.httpmaster.net) - GUI tool for testing REST APIs and services. Windows OS only.
* [Http-console](https://github.com/cloudhead/http-console) - Command line interface for HTTP that let you *speak HTTP like a local* :star:1333
* [HTTP Prompt](https://github.com/eliangcs/http-prompt) - HTTP Prompt is an interactive command-line HTTP client featuring autocomplete and syntax highlighting, built on HTTPie and prompt_toolkit. :star:6994
* [rest-assured](https://github.com/rest-assured/rest-assured) - Java DSL for easy testing of REST services. :star:3414
* [Insomnia](https://github.com/getinsomnia/insomnia) - Cross-platform HTTP and GraphQL Client :star:8281

### Mocking

* [RequestBin](http://requestb.in/) - Inspect and debug webhook requests sent by your clients or third-party APIs.
* [httpbin](http://httpbin.org) - HTTP request and response service - a/k/a Swiss Army Knife for HTTP.
* [FakeRest](https://github.com/marmelab/FakeRest) - Patch XMLHttpRequest to fake a REST API client-side. :star:277
* [json-server](https://github.com/typicode/json-server) - Serve a REST API from fixture files using quick prototyping. :star:35603
* [Mocky.io](http://www.mocky.io/) - Free online service to create fake HTTP responses.
* [Swagger API Mock](https://github.com/bulkismaslom/swagger-api-mock) - Mock RESTful API based on swagger schema :star:20
* [Request Baskets](https://github.com/darklynx/request-baskets) - Service to collect HTTP requests and inspect them via RESTful API or web UI. :star:40
* [DuckRails](https://github.com/iridakos/duckrails) - Mock quickly & dynamically API endpoints. :star:1509

### Public REST APIs To Use In Tests
* [Deck of Cards API](http://deckofcardsapi.com) - Open API for simulating a deck of cards.
* [ProgrammableWeb](http://www.programmableweb.com/apis/directory) - The world's largest API repository.
* [Public APIS](https://www.publicapis.com/) - Explore The Largest API Directory In The Galaxy.
* [Marvel Comics API](http://developer.marvel.com/) - Query characters, stories, events about Marvel superheroes.
* [JSON Placeholder](http://jsonplaceholder.typicode.com/) - Free online REST service that you can use whenever you need some fake data.
* [APIs.guru](http://APIs.guru) - Wikipedia for Web APIs, each API has OpenAPI/Swagger description.

## Documentation

* [Swagger](http://swagger.io/) - Documentation/querying web interface for REST APIs.
* [API doc](http://apidocjs.com/) - Inline Documentation for RESTful web APIs.
* [raml2html](https://github.com/raml2html/raml2html) - Generates HTML documentation from a RAML file. :star:981
* [ReDoc](https://github.com/Rebilly/ReDoc/) - OpenAPI/Swagger-powered three-panel documentation. :star:3760
* [Slate](https://github.com/lord/slate) - Beautiful and responsive three-panel API documentation using Middleman. :star:24814

## API Gateway

* [Kong](https://github.com/Kong/kong) - Scalable, distributed, and plugin oriented API gateway backed by Nginx. :star:18338
* [Tyk API Gateway](https://github.com/TykTechnologies/tyk) - Lightweight API gateway with analytics logging, written in Go. :star:3886
* [API Umbrella](https://github.com/NREL/api-umbrella) - API management platform for exposing web services, with web interface and analytics, written in Lua. :star:1160
* [WSO2 API Management](https://github.com/wso2/product-apim) - API management tool with lightweight gateway and API lifecycle manangement, written in Java. :star:200

## SaaS Tools

* [Runscope](https://www.runscope.com/) - Automated API Monitoring & Testing.
* [Ping-API](https://ping-api.com/) - Automated API Monitoring & Testing.
* [import.io Magic](https://magic.import.io/) - Create a REST API from any website in one click.
* [Apiary](https://apiary.io/) - Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
* [Amazon API Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
* [Apigee](https://apigee.com) - Apigee is the leading provider of API technology and services for enterprises and developers.
* [3scale](https://www.3scale.net/) - Nginx based API gateway to integrate internal and external API services with 3scale's API Management Platform.
* [Assertible](https://assertible.com) - Continuously test and monitor your APIs after deployments and across environments.
* [Moesif](https://www.moesif.com) - API Analytics for Debugging, Monitoring, and Usage Tracking for RESTful and GraphQL.


## Miscellaneous

* [ng-admin](https://github.com/marmelab/ng-admin) - Add an AngularJS admin GUI to any RESTful API. :star:3918
* [admin-on-rest](https://github.com/marmelab/admin-on-rest) - Add a ReactJS admin GUI to any RESTful API. :star:285
* [swagger-codegen](https://github.com/swagger-api/swagger-codegen) - Auto generation of client libraries or server stubs given an OpenAPI specification (formerly known as the Swagger Specification). :star:7921
* [Lumber](https://github.com/ForestAdmin/lumber) - Generate the admin interface of your application. :star:1727

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

