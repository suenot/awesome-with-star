# Information comes from [mark-rushakoff/awesome-influxdb](https://github.com/mark-rushakoff/awesome-influxdb)
# awesome-influxdb [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome projects, libraries, tools, etc. related to [InfluxDB](https://www.influxdata.com/).
This list focuses on libraries, tools, etc. supporting InfluxDB version 1.0 and up.

Want to make this list better?
Take a look at our page on [contributing](CONTRIBUTING.md) and then open a pull request!

## Reference material

If you know of any particularly useful blog posts, talks, slides, etc. that belong in this list, please open a pull request!

* [Official documentation](https://docs.influxdata.com/influxdb/latest/)
* InfluxDB in IoT world. [Part 1: Introduction](https://www.easyitblog.info/2017/11/10/influxdb-and-grafana-fighting-together-with-iot-data-attack/) | [Part 2: Hosting and scaling on AWS](https://www.easyitblog.info/2017/11/14/influxdb-in-iot-world-aws-part-2/) | [Part 3: Plotting graphs using Grafana](https://www.easyitblog.info/2017/11/26/influxdb-in-iot-world-making-it-production-ready-part-3/)

## Client libraries

### Official

* [C#](https://github.com/influxdata/influxdb-csharp) - A .NET library for efficiently sending points to InfluxDB :star:113
* [Go](https://github.com/influxdata/influxdb/tree/master/client) - Go client for InfluxDB, contained as package within main InfluxDB repo :star:14615
* [Java](https://github.com/influxdata/influxdb-java) - Java client for InfluxDB :star:562
* [PHP](https://github.com/influxdata/influxdb-php) - PHP client for InfluxDB :star:244
* [Python](https://github.com/influxdata/influxdb-python) - Python client for InfluxDB :star:911
* [Rails](https://github.com/influxdata/influxdb-rails) - Ruby on Rails bindings to automatically write metrics into InfluxDB :star:98
* [Ruby](https://github.com/influxdata/influxdb-ruby) - Ruby client for InfluxDB :star:299

### Unofficial

* [capacitor](https://github.com/olauzon/capacitor) - A Clojure client for InfluxDB :star:65
* [cl-influxdb](https://github.com/mmaul/cl-influxdb) - Common Lisp interface to the Time Series Database InfluxDB :star:13
* [erflux](https://github.com/gossiperl/erflux) - InfluxDB client for Erlang :star:22
* [fluxter](https://github.com/lexmag/fluxter) - An InfluxDB writer for Elixir :star:75
* [influent](https://github.com/gobwas/influent) - InfluxDB Javascript driver :star:34
* [influent.rs](https://github.com/gobwas/influent.rs) - InfluxDB Rust driver :star:35
* [InfluxDB-Client-LabVIEW](https://github.com/johanvandenbroek/InfluxDB-Client-LabVIEW) - LabVIEW client for InfluxDB :star:3
* [influxdb-cpp-rest](https://github.com/d-led/influxdb-cpp-rest) - A C++ InfluxDB client with a batching async interface :star:15
* [influxdb-haskell](https://github.com/maoe/influxdb-haskell) - Haskell client library for InfluxDB :star:46
* [InfluxDB.NET](https://github.com/ziyasal/InfluxDB.Net) - .NET client for InfluxDB :star:126
* [InfluxDB PHP SDK](https://github.com/corley/influxdb-php-sdk) - UDP/IP or HTTP adapters for read and write data :star:85
* [influxdbr](https://github.com/dleutnant/influxdbr) - R library for InfluxDB :star:48
* [instream](https://github.com/mneudert/instream) - InfluxDB driver for Elixir :star:132
* [node-influx](https://github.com/node-influx/node-influx) - InfluxDB Node.js Client :star:595
* [node-influx-udp](https://github.com/mediocre/node-influx-udp) - Write to InfluxDB using its UDP interface :star:17
* [scala-influxdb-client](https://github.com/paulgoldbaum/scala-influxdb-client) - Asynchronous InfluxDB client for Scala :star:101

## Collecting data into InfluxDB

### Projects

#### Dedicated

Tools whose primary or sole purpose is to feed data into InfluxDB.

* [accelerometer2influx](https://github.com/CorpGlory/accelerometer2influx) - Android application that takes the x-y-z axis metrics from your phone accelerometer and sends the data to InfluxDB. :star:1
* [agento](https://github.com/abrander/agento) - Client/server collecting near realtime metrics from Linux hosts :star:20
* [aggregateD](https://github.com/ccpgames/aggregateD) - A [dogstatsD](https://docs.datadoghq.com/guides/dogstatsd/) inspired metrics and event aggregation daemon for InfluxDB :star:15
* [aprs2influxdb](https://github.com/FaradayRF/aprs2influxdb) - Interfaces ham radio APRS-IS servers and saves packet data into an influxdb database :star:14
* [Charmander](https://github.com/att-innovate/charmander) - Charmander is a lab environment for measuring and analyzing resource-scheduling algorithms :star:58
* [gopherwx](https://github.com/chrissnell/gopherwx) - a service that pulls live weather data from a Davis Instruments Vantage Pro2 station and stores it in InfluxDB :star:9
* [grade](https://github.com/influxdata/grade) - Track Go benchmark performance over time by storing results in InfluxDB :star:27
* [Influx-Capacitor](https://github.com/poxet/Influx-Capacitor) - Influx-Capacitor collects metrics from windows machines using Performance Counters. Data is sent to influxDB to be viewable by grafana :star:39
* [Influxdb-Powershell](https://github.com/vsavornin/Influxdb-Powershell) - Powershell script to send Windows Performance counters to an InfluxDB Server :star:4
* [influxdb-logger](https://github.com/codersaur/SmartThings/tree/master/smartapps/influxdb-logger) - SmartApp to log [SmartThings](https://www.smartthings.com/) device attributes to an InfluxDB database :star:143
* [influxdb-sqlserver](https://github.com/zensqlmonitor/influxdb-sqlserver) - Collect Microsoft SQL Server metrics for reporting to InfluxDB and visualize them with Grafana :star:45
* [k6](https://github.com/loadimpact/k6) - A modern load testing tool, using Go and JavaScript :star:4298
* [marathon-event-metrics](https://github.com/Wikia/marathon-event-metrics) - a tool for reporting [Marathon](https://mesosphere.github.io/marathon/) events to InfluxDB :star:1
* [mesos-influxdb-collector](https://github.com/kpacha/mesos-influxdb-collector) - Lightweight [mesos](https://mesos.apache.org/) stats collector for InfluxDB :star:15
* [mqforward](https://github.com/shirou/mqforward) - [MQTT](http://mqtt.org/) to influxdb forwarder :star:52
* [node-opcua-logger](https://github.com/coussej/node-opcua-logger) - Collect industrial data from OPC UA Servers  :star:33
* [ntp_checker](https://github.com/fss1/ntp_checker) - compares internal NTP sources and warns if the offset between servers exceeds a definable (fraction of) seconds :star:3
* [proc_to_influxdb](https://github.com/d-led/proc_to_influxdb) - Console app to observe Windows process starts and stops via InfluxDB :star:1
* [pysysinfo_influxdb](https://github.com/nagylzs/pysysinfo_influxdb) - Periodically send system information into influxdb (uses python3 + psutil, so it also works under Windows) :star:1
* [sysinfo_influxdb](https://github.com/novaquark/sysinfo_influxdb) - Collect and send system (linux) info to InfluxDB :star:95
* [snmpcollector](https://github.com/toni-moreno/snmpcollector) - A full featured Generic SNMP data collector with Web Administration Interface for InfluxDB :star:114
* [Telegraf](https://github.com/influxdata/telegraf) - (Official) plugin-driven server agent for reporting metrics into InfluxDB :star:5729
* [tesla-streamer](https://github.com/timdorr/tesla-trip/blob/master/lib/tesla_stream_reader.rb) - Streams data from Tesla Model S to InfluxDB ([rake task](https://github.com/timdorr/tesla-trip/blob/master/lib/tasks/tesla.rake#L12-L16)) :star:5
* [traffic_stats](http://traffic-control-cdn.readthedocs.io/en/latest/overview/traffic_stats.html) - Acquires and stores statistics about CDNs controlled by [Apache Traffic Control](https://trafficcontrol.apache.org/)
* [vsphere-influxdb-go](https://github.com/Oxalide/vsphere-influxdb-go) - Collect VMware vSphere, vCenter and ESXi performance metrics and send them to InfluxDB :star:164

#### Non-dedicated

Tools that generate data that feed into multiple backends, InfluxDB included.

* [cAdvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers :star:8118
* [Centreon](https://github.com/centreon/centreon) - A network, system, applicative supervision and monitoring tool :star:246
* [cernan](https://github.com/postmates/cernan) - A telemetry and logging aggregation server :star:251
* [cloudwatch-sender](https://github.com/BBC-News/cloudwatch-sender) - Send metrics to InfluxDB/Graphite from [Amazon Cloudwatch](https://aws.amazon.com/cloudwatch/)
* [crankshaftd](https://github.com/fullcontact/crankshaftd) - Simple Go agent to ingest streaming data from [Turbine](https://github.com/Netflix/Turbine) via SSE and push it into StatsD as a gauge or to InfluxDB :star:6
* [Domoticz](https://www.domoticz.com) - Open source Home Automation System
* [gatling](https://github.com/gatling/gatling) - Async Scala-Akka-Netty based Stress Tool :star:3859
* [Glances](https://github.com/nicolargo/glances) - Glances an Eye on your system :star:12070
* [Graphios](https://github.com/shawn-sterling/graphios) - A program to send nagios perf data to graphite (carbon) / statsd / librato / influxDB :star:282
* [heapster](https://github.com/kubernetes/heapster) - Monitor container resource usage of a [Kubernetes](https://kubernetes.io/) cluster :star:2353
* [heka](https://github.com/mozilla-services/heka) - General purpose data collection and processing tool :star:3352
* [internet_data_usage](https://github.com/precurse/internet_data_usage) - Python based application to pull data plan usage for different carriers such as Telus and Koodo :star:2
* [ioBroker](http://www.iobroker.net/) - Homeautomation / IoT Platform uses Influxdb to store [history data](https://github.com/ioBroker/ioBroker.influxdb/blob/master/README.md) :star:7
* [jmxtrans](https://github.com/jmxtrans/jmxtrans) - Effectively the missing connector between speaking to a JVM via JMX on one end and whatever logging / monitoring / graphing package that you can dream up on the other end. :star:1419
* [Apache JMeter](https://jmeter.apache.org/usermanual/realtime-results.html) - Popular load testing tool, you can get real-time results sent to a backend through the InfluxDBBackendListenerClient which allows you to send metrics (active threads, response time ...) to an InfluxDB Backend using UDP or HTTP protocols
* [logary](https://github.com/logary/logary) - High performance, multi-target logging, metric and health-check library for mono and .Net :star:378
* [metrics.sh](https://github.com/pstadler/metrics.sh) - Collect and forward metrics using portable shell scripts :star:75
* [OpenHAB](https://www.openhab.org/) - A universal integration platform for all things around home automation
* [Riemann](https://github.com/riemann/riemann) - A network event stream processing system, in Clojure :star:3658
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler) - Simple JVM Profiler Using StatsD :star:296
* [statsite](https://github.com/statsite/statsite) - C implementation of statsd :star:1672

### Libraries

Libraries to collect data and feed into InfluxDB.

* [crow-metrics](https://github.com/robey/crow-metrics) - small metrics collector for node servers :star:18
* [django-influxdb-metrics](https://github.com/bitlabstudio/django-influxdb-metrics) - A reusable Django app that sends metrics about your project to InfluxDB :star:66
* [go-runtime-metrics](https://github.com/tevjef/go-runtime-metrics) - Collect golang runtime Metrics, outputting to InfluxDB or through Telegraf :star:182
* [lua-resty-influx](https://github.com/p0pr0ck5/lua-resty-influx) - [OpenResty](https://openresty.org/en/) client for InfluxDB :star:14
* [metrics](https://github.com/beberlei/metrics) - (PHP) Simple library that abstracts different metrics collectors. "I find this necessary to have a consistent and simple metrics (functional) API that doesn't cause vendor lock-in" :star:259
* [pyVsphereInflux](https://github.com/fennm/pyVsphereInflux) - A library and supporting script for pulling data from [vSphere](https://www.vmware.com/products/vsphere.html) and inserting it into InfluxDB :star:3
* [telemetry](https://github.com/arussellsaw/telemetry) - metric reporting for Go applications :star:79

#### Hooks

Hooks for other logging libraries to output to InfluxDB.

* [go-metrics-influxdb](https://github.com/vrischmann/go-metrics-influxdb) - A reporter for the [go-metrics library](https://github.com/rcrowley/go-metrics) which will post the metrics to InfluxDB :star:49
* [logrus_influxdb](https://github.com/Abramovic/logrus_influxdb) - InfluxDB Hook for [Logrus](https://github.com/Sirupsen/logrus) :star:8729

### Plugins

Plugins to allow other standalone tools to send their data into InfluxDB.

* [embulk-output-influxdb](https://github.com/joker1007/embulk-output-influxdb) - InfluxDB output plugin for [Embulk](https://github.com/embulk/embulk) :star:1157
* [exometer_influxdb](https://github.com/travelping/exometer_influxdb) - [Exometer](https://github.com/Feuerlabs/exometer) reporter for InfluxDB :star:29
* [fluent-plugin-influxdb](https://github.com/fangli/fluent-plugin-influxdb) - A buffered output plugin for [fluentd](https://www.fluentd.org/) and InfluxDB :star:93
* [influx-nagios-plugin](https://github.com/shaharke/influx-nagios-plugin) - [Nagios](https://www.nagios.org/) plugin for querying monitoring stats from InfluxDB :star:29
* [jenkinsci/influxdb-plugin](https://github.com/jenkinsci/influxdb-plugin) - [Jenkins](https://jenkins.io/index.html) plugin to send build metrics into InfluxDB :star:19
* [kafka-influxdb](https://github.com/mre/kafka-influxdb) - A [Kafka](https://kafka.apache.org/) consumer for InfluxDB written in Python :star:151
* [logstash-output-influxdb](https://github.com/logstash-plugins/logstash-output-influxdb) - Community-maintained [Logstash](https://www.elastic.co/products/logstash) plugin to output metrics to InfluxDB :star:39
* [metrics-influxdb](https://github.com/davidB/metrics-influxdb) - A reporter for [dropwizard](https://www.dropwizard.io/0.9.1/docs/) metrics which announces measurements to an InfluxDB server :star:232
* [mod-influxdb](https://github.com/savoirfairelinux/mod-influxdb) - [Shinken](http://www.shinken-monitoring.org/) module for exporting data to InfluxDB :star:13
* [sensu-plugins-influxdb](https://github.com/sensu-plugins/sensu-plugins-influxdb) - [Sensu](https://sensu.io/) InfluxDB Plugins :star:13
* [sidekiq-influxdb](https://github.com/vassilevsky/sidekiq-influxdb) - A [Sidekiq](https://sidekiq.org/) middleware to send job execution metrics to InfluxDB :star:6
* [snap-plugin-publisher-influxdb](https://github.com/intelsdi-x/snap-plugin-publisher-influxdb) - Publishes [snap](http://www.snap-telemetry.io/) metrics to InfluxDB :star:8
* [statsd-influxdb-backend](https://github.com/bernd/statsd-influxdb-backend) - A naive InfluxDB backend for StatsD :star:163

### Import tools

Tools to import a fixed set of data into InfluxDB.

* [nmon2influxdb](https://github.com/adejoux/nmon2influxdb) - Import [nmon](http://nmon.sourceforge.net/pmwiki.php) file into InfluxDB :star:48

## Consuming data from InfluxDB

### Dashboards and visualization

* [Chronograf](https://github.com/influxdata/chronograf) - Official InfluxDB data visualization tool :star:761
* [facette](https://github.com/facette/facette) - Time series data visualization and graphing software :star:1028
* [FluxDash](https://github.com/vrecan/FluxDash) - Terminal based InfluxDB dashboard :star:28
* [grafana](https://github.com/grafana/grafana) - Gorgeous metric viz, dashboards & editors for Graphite, InfluxDB & OpenTSDB :star:24468
* [InfluxGraph](https://github.com/InfluxGraph/influxgraph) - Graphite InfluxDB storage finder for Graphite-API :star:75
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB :star:157
* [InfluxDB Studio](https://github.com/CymaticLabs/InfluxDBStudio) - InfluxDB Studio is a UI management tool, its inspiration comes from other similar SQL database management tools (use InfluxData.Net run on MS Windows) :star:170

### Other tools

* [hubot-influxdb-alerts](https://github.com/amwelch/hubot-influxdb-alerts) - Create and manage alerts in your chatroom using [hubot](https://hubot.github.com/) and influxdb :star:11
* [influx-alert](https://github.com/joshrendek/influx-alert) - A tool to query InfluxDB and send alerts based on a YAML config :star:27
* [influxdb_google_sheets](https://github.com/HormyAJP/influxdb_google_sheets) - Google Sheets script for fetching and formatting InfluxDB data :star:8
* [Morgoth](https://github.com/nathanielc/morgoth) - Metric anomaly detection :star:250

## Provisioning InfluxDB

Tools, libraries, etc. to help you get InfluxDB running without installing it by hand.

* [chef-influxdb](https://github.com/bdangit/chef-influxdb) - Chef cookbook for InfluxDB :star:53
* [golja-influxdb](https://github.com/dgolja/golja-influxdb) - Puppet module for InfluxDB :star:19
* [influxdb-formula](https://github.com/saltstack-formulas/influxdb-formula) - Installs and configures the InfluxDB timeseries database :star:6
* [influxdb-release](https://github.com/pivotal-cf-experimental/influxdb-release) - Experimental BOSH release for InfluxDB :star:2
* [puppet-telegraf](https://forge.puppet.com/datacentred/telegraf/readme) - Puppet module for Telegraf
* [rossmcdonald/influxdb](https://github.com/rossmcdonald/influxdb) - Ansible role for installing, configuring, and maintaining InfluxDB :star:19
* [tutum-docker-influxdb](https://github.com/tutumcloud/influxdb) - Docker image to run an out-of-the-box InfluxDB server :star:232

## Queries

* [dbal-influxdb](https://github.com/corley/dbal-influxdb) - Doctrine DBAL for InfluxDB :star:10
* [Influxdb::Arel](https://github.com/undr/influxdb-arel) - Influxdb::Arel is a SQL AST manager for InfluxDB dialect. It simplifies the generation of complex SQL queries :star:9
* [influxer](https://github.com/palkan/influxer) - InfluxDB ActiveRecord-style :star:83

## Hosting of InfluxDB / SaaS

* [InfluxCloud](https://cloud.influxdata.com/plan-picker) - From the creators of InfluxDB
* [Aiven](https://aiven.io/influxdb) - Provides a choice of host (AWS, Google, DigitalOcean, etc.), geographic location, and server specs
* [Scalingo](https://scalingo.com/databases/influxdb) - Provides a choice of server specs
* [HostedMetrics](https://hostedmetrics.com/product/influxdb/) - Geared towards custom application monitoring by hosting the combination of InfluxDB, Grafana, and StatsD


## Miscellaneous

Projects that don't seem to fit in any other category.

* [influx-protector](https://github.com/ve-global/influx-protector) - proxy to prevent dangerous queries getting to influxdb :star:8
* [influxdb-schema-updater](https://github.com/open-ch/influxdb-schema-updater) - A small DevOps tool to manage the schema of an InfluxDB instance with a set of configuration files :star:3
* [influx-prompt](https://github.com/RPing/influx-prompt) - An interactive command-line InfluxDB cli with auto completion :star:24

## Other awesome lists

### Awesome lists that include links to InfluxDB

* [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata) :star:6646
* [awesome-dashboard](https://github.com/obazoud/awesome-dashboard) :star:640
* [awesome-data-engineering](https://github.com/igorbarinov/awesome-data-engineering) :star:1855
* [awesome-db](https://github.com/numetriclabz/awesome-db) :star:662
* [awesome-go](https://github.com/avelino/awesome-go) :star:36347
* [awesome-home-assistant](https://github.com/frenck/awesome-home-assistant) :star:764
* [awesome-microservices](https://github.com/mfornos/awesome-microservices) :star:6769
* [awesome-sysadmin](https://github.com/kahun/awesome-sysadmin) :star:17764

### Lists of awesome lists that include awesome-influxdb

* [awesome](https://github.com/sindresorhus/awesome) :star:94843
* [lists](https://github.com/jnv/lists) :star:5331

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors and contributors have waived all copyright and related or neighboring rights to awesome-influxdb.

