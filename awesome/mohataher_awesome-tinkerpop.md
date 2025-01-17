# Information comes from [mohataher/awesome-tinkerpop](https://github.com/mohataher/awesome-tinkerpop)
# Awesome TinkerPop [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![alt tag](https://raw.githubusercontent.com/mohataher/awesome-tinkerpop/master/tinkerpop-splash.png)


A curated list of only awesome TinkerPop libraries on Github.

>Apache TinkerPop™ is a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP).

### Table of Contents
* [TinkerPop3](#tinkerpop3)
	- [Implementations](#tinkerpop3-implementations)
	- [Wrappers/Clients](#wrappers)
	- [Query Languages](#qlang)
* [TinkerPop2](#tinkerpop2)
* [Communites](#communites)
* [People to Follow](#people-to-follow)
* [Tutorials and Resources](#tutorials-and-resources)
* [How to Contribute](#contributing)
* [License](#license)

### <A NAME="tinkerpop3"></A>TinkerPop3 Libraries
#### <A NAME="tinkerpop3-implementations"></A>Implementations
* [TinkerPop3 implementation](https://github.com/apache/tinkerpop) - Mirror of Apache TinkerPop. :star:676
* [sqlg](https://github.com/pietermartin/sqlg) - Sqlg is a implementation of TinkerPop3 on a RDBMS. :star:130
* [blazegraph](https://github.com/blazegraph/database) - TinkerPop3 [implementation](https://github.com/blazegraph/tinkerpop3) for Blaze Graph; a high performance graph database. :star:288
* [tinkergraph-js](https://github.com/jbmusso/tinkergraph-js) - A pure JavaScript implementation of TinkerPop's TinkerGraph in-memory graph database. :star:45
* [gremlin-javascript](https://github.com/jbmusso/gremlin-javascript) - JavaScript graph database client for TinkerPop3 Gremlin Server. :star:195
* [Elastic Gremlin](https://github.com/rmagen/elastic-gremlin) - TinkerPop3 implementation on Elasticsearch backend. :star:59
* [Hadoop (Giraph)](http://tinkerpop.apache.org/docs/current/reference/#giraphgraphcomputer) - OLAP graph processor using Giraph.
* [Hadoop (Spark)](http://tinkerpop.apache.org/docs/current/reference/#sparkgraphcomputer) - OLAP graph processor using Spark.
* [IBM Graph](https://console.ng.bluemix.net/catalog/services/ibm-graph/) - OLTP graph database as a service.
* [Neo4j](http://tinkerpop.apache.org/docs/currentg/#neo4j-gremlin) - OLTP graph database.
* [Stardog](http://stardog.com/) - RDF graph database with OLTP and OLAP support.
* [TinkerGraph](http://tinkerpop.apache.org/docs/current/reference/#tinkergraph-gremlin) - In-memory OLTP and OLAP reference implementation.
* [Unipop](https://github.com/rmagen/unipop) - OLTP Elasticsearch and JDBC backed graph. :star:139
* [DuctileDB](https://github.com/PureSolTechnologies/DuctileDB) - Ductile DB is a graph database based on Hadoop/HBase which provides a vast set of features. :star:14
* [hgraphdb](https://github.com/rayokota/hgraphdb) - HBase as a TinkerPop Graph Database. :star:124
* [JanusGraph](https://github.com/JanusGraph/janusgraph) - JanusGraph: an open-source, distributed graph database http://janusgraph.org  :star:1827
* [JanusGraph for DynamoDB (Amazon)](https://github.com/awslabs/dynamodb-janusgraph-storage-backend) - The Amazon DynamoDB storage backend for JanusGraph. :star:372
* [orientdb-gremlin](https://github.com/orientechnologies/orientdb-gremlin) - TinkerPop3 Graph Structure Implementation for OrientDB. :star:67


#### <A NAME="wrappers"></A>Wrappers/Clients
##### C# .NET
*   [Teva Gremlin](https://www.nuget.org/packages/Teva.Common.Data.Gremlin/) (.NET - C#) - A Gremlin Server driver for .NET.

##### Clojure
* [ogre](https://github.com/clojurewerkz/ogre) - Clojure library for querying TinkerPop graphs. :star:104
* [scalajs-gremlin-client](https://github.com/viagraphs/scalajs-gremlin-client) (scala) - A Gremlin-Server client with ad-hoc extensible, reactive, typeclass based API. :star:6

##### Go
* [go-gremlin](https://github.com/go-gremlin/gremlin) - Go graph database client for TinkerPop3 Gremlin Server. :star:56
* [Gremgo](https://github.com/qasaur/gremgo) - A fast, efficient, and easy-to-use Go client for the TinkerPop graph database stack. :star:53

##### Haskell
* [gremlin-haskell](https://github.com/nakaji-dayo/gremlin-haskell) - Haskell graph database client for TinkerPop3 Gremlin Server. :star:6
* [greskell-websocket](https://github.com/debug-ito/greskell) - Haskell client for TinkerPop3 Gremlin Server. :star:4

##### Java
* [gremlin-driver](http://tinkerpop.apache.org/docs/current/reference/#connecting-via-java) (java) - A Gremlin Server driver for Java.
* [neo4j-tinkerpop-api](https://github.com/neo4j-contrib/neo4j-tinkerpop-api) - Apache Licensed Neo4j API for TinkerPop3. :star:5
* [neo4j-gremlin-bolt](https://github.com/SteelBridgeLabs/neo4j-gremlin-bolt) - Allows use of the Apache Tinkerpop Java API with the neo4j server using the BOLT protocol. :star:42
* [Ferma](https://github.com/Syncleus/Ferma) - An ORM / OGM for the TinkerPop graph stack. :star:92

##### Javascript
* [ts-tinkerpop](https://github.com/RedSeal-co/ts-tinkerpop) - Utilities for using TinkerPop3 via the node-java API in Typescript. :star:32
* [gremlin-javascript](https://github.com/jbmusso/gremlin-javascript) (js) - A Gremlin Server driver for JavaScript. :star:195

##### PHP
* [gremlin-php](https://github.com/PommeVerte/gremlin-php) - gremlin-server php driver compatible with TinkerPop3. It will allow you to connect to gremlin-server and it's backends (Neo4J, Titan, etc.). :star:46

##### Python
* [Mogwai](https://github.com/platinummonkey/mogwai) - TinkerPop3 Graph Database Library for Python. :star:37
* [python-gremlin-rest](https://github.com/windj007/python-gremlin-rest) - A REST-based client for Gremlin Server. :star:5
* [gremlinclient](https://github.com/davebshow/gremlinclient) - An asynchronous Python 2/3 client for Gremlin Server that allows for flexible coroutine syntax - Trollius, Tornado, Asyncio. :star:25
* [aiogremlin](https://github.com/davebshow/aiogremlin) (python) - A Python 3 library based on asyncio and aiohttp that uses websockets to communicate with the Gremlin Server. :star:42
* [gremlinrestclient](http://gremlinrestclient.readthedocs.org/en/latest/) (python) - Python 2/3 library that uses HTTP to communicate with the Gremlin Server over REST.
* [goblin](https://github.com/ZEROFAIL/goblin) - OGM for TinkerPop3 Gremlin Server. :star:83
* [goblin 3.5](https://github.com/davebshow/goblin) - A Python 3.5 rewrite of the TinkerPop 3 OGM Goblin. :star:83

##### Reactive
* [reactive-gremlin](https://github.com/coreyauger/reactive-gremlin) (scala) - An Akka HTTP Websocket Connector. :star:28

##### Scala
* [Gremlin Scala](https://github.com/mpollmeier/gremlin-scala) - Scala wrapper for Apache TinkerPop3 Graph DSL. :star:395
* [blueprints-scala](https://github.com/anvie/blueprints-scala) - Tinkerpop Blueprints Scala. :star:79

#### <A NAME="qlang"></A>Query Languages
* [gremlin-py](https://github.com/emehrkay/gremlinpy) - Write pure Python Gremlin that can be sent to Gremlin Server. :star:38
* [gremlin-scala](https://github.com/mpollmeier/gremlin-scala) - A Scala language wrapper for TinkerPop3. :star:395
* [gremlin-template-string](https://github.com/jbmusso/gremlin-template-string) - A Javascript Gremlin language builder. :star:15
* [ipython-gremlin](https://github.com/davebshow/ipython-gremlin) - Gremlin in IPython and Jupyter. :star:25
* [ogre](http://ogre.clojurewerkz.org/) - A Clojure language wrapper for TinkerPop3.
* [Peapod](https://github.com/bayofmany/peapod) - A new object-graph-wrapper for the Tinkerpop3 graph stack. :star:37
* [sparql-gremlin](https://github.com/dkuppitz/sparql-gremlin) - A SPARQL to Gremlin traversal compiler. :star:57
* [sql-gremlin](https://github.com/twilmes/sql-gremlin) - A SQL to Gremlin traversal compiler. :star:53
* [greskell](https://github.com/debug-ito/greskell) - Haskell binding for Gremlin graph query language :star:4
* [Cypher for Gremlin](https://github.com/opencypher/cypher-for-gremlin) -  Cypher for Gremlin adds Cypher support to any Gremlin graph database. :star:68

### <A NAME="tinkerpop2"></A>TinkerPop 2 Libraries
* [Ferma](https://github.com/Syncleus/Ferma) - An ORM / OGM for the TinkerPop graph stack. :star:92
* [Frames](https://github.com/tinkerpop/frames) - An Object to Graph Framework. :star:136
* [Archimedes](https://github.com/clojurewerkz/archimedes) - Clojure library for Blueprints (part of the TinkerPop graph stack). :star:36
* [AccumuloGraph](https://github.com/JHUAPL/AccumuloGraph) - An implementation of TinkerPop Blueprints using Accumulo. :star:29
* [Frontenac](https://github.com/Loupi/Frontenac) - A .NET port of the TinkerPop Stack. :star:25
* [Mogwai](https://github.com/platinummonkey/mogwai) - TinkerPop 2 Graph Database Library for Python. :star:37
* [spring-data-gremlin](https://github.com/gjrwebber/spring-data-gremlin) - Spring data gremlin makes it easier to implement Graph based repositories. This module extends Spring Data to allow support for potentially any Graph database that implements the TinkerPop Blueprints 2.x API. :star:52
* [blueprints-scala](https://github.com/anvie/blueprints-scala) - TinkerPop Blueprints Scala. :star:79

## <A NAME="communites"></A>Communities
* [Gremlin-users](https://groups.google.com/forum/#!forum/gremlin-users) - Mailing list for Gremlin users.
* [Stack Overflow](http://stackoverflow.com/questions/tagged/tinkerpop3) - Stack Overflow has a relatively active community.
* [TinkerPop-dev](http://mail-archives.apache.org/mod_mbox/incubator-tinkerpop-dev/) - Mailing list for TP3 deverlopers.

## <A NAME="people-to-follow"></A>People to Follow 
* [Marko Rodriguez](https://markorodriguez.com/) - Founder of TinkerPop and Aurelius.
* [Stephen Mallette](https://twitter.com/spmallette?lang=en-gb) - Senior developer for Gremlin, TinkerPop and Titan DB.
* [Daniel Kuppitz](https://about.me/daniel.kuppitz) - One of the main developers of Gremlin.
* [Jason Plurad](https://github.com/pluradj) - Senior Developer at IBM. TinkerPop committer and active on the community.

## <A NAME="tutorials-and-resources"></A>Tutorials and Resources
* [Introduction to Gremlin](http://tinkerpop.apache.org/gremlin.html) - Official introduction to the Gremlin language.
* [Datastax Introduction](https://academy.datastax.com/resources/getting-started-tinkerpop-and-gremlin) - A tutorial provided by Datastax to Gremlin and TinkerPop3.
* [TinkerPop Book](http://www.tinkerpopbook.com/) - A long promised book for Tinkeprop but never fulfilled until now. You cans till request a notification.
* [Linux Foundation Presentation](http://events.linuxfoundation.org/sites/events/files/slides/ApacheCon2015TinkerPop3.pdf) - A presentation by Linux Foundation given by David Robinson at IBM aboit Apache TinkerPop3.
* [Getting Started with TinkerPop](http://tinkerpop.apache.org/docs/current/tutorials/getting-started/) - Learn the basics of getting up and going with TinkerPop.
* [The Gremlin Console](http://tinkerpop.apache.org/docs/current/tutorials/the-gremlin-console/) - Discusses uses cases of the Gremlin Console and usage patterns.
* [Gremlin Recipes](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/recipes/) - Reference for common traversal patterns and style.
* [Gremlin Language Variants](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/tutorials/gremlin-language-variants/) - Learn how to embed Gremlin in a host programming language.
* [SQL2Gremlin](http://sql2gremlin.com/) - Learn Gremlin using typical patterns found when querying data with SQL.
* [Getting Started with Graph Databases](https://academy.datastax.com/demos/getting-started-graph-databases) - Compares relational databases to graph databases and SQL to Gremlin.
* [Graph](https://github.com/krlawrence/graph) - Graph Databases, Gremlin and TinkerPop - A Tutorial. :star:202


## <A NAME="contributing"></A>How to Contribute
![alt tag](awesome-tinkerpop.jpg)

Please follow the [guidelines here](contributing.md). Please, make sure your contribution and PR are awesome!

## <A NAME="license"></A>License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@mohataher](https://github.com/mohataher) has waived all copyright and related or neighboring rights to this work.

