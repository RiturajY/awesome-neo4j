Awesome Neo4j
==============
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/Neueda4j/awesome-neo4j.svg?branch=master)](https://travis-ci.org/Neueda4j/awesome-neo4j)

A curated list of awesome [Neo4j](http://neo4j.com/) resources.  
Inspired by the `awesome-*` trend on GitHub.

The goal is to build a categorized community-driven collection of very well-known resources.  
Sharing, suggestions and contributions are always welcome!

Thanks to all [contributors](https://github.com/Neueda4j/awesome-neo4j/graphs/contributors).

Maintained by [Neueda4j](https://neueda4j.com/).


Table of Contents
=================

  * [Basics](#basics)
  * [Connectors](#connectors)
    * [Bolt](#bolt)
    * [REST API](#rest-api)
      * [Java](#java)
      * [Ruby](#ruby)
      * [Python](#python)
      * [PHP](#php)
      * [Other](#other)
  * [Cloud](#cloud)
  * [Packages](#packages)
  * [Docker](#docker)
  * [Full\-text search](#full-text-search)
  * [Import](#import)
  * [Benchmarking](#benchmarking)
  * [Extensions](#extensions)
  * [Development](#development)
  * [Editors](#editors)
  * [Shell](#shell)
  * [Visualization](#visualization)
  * [Tools](#tools)
  * [Resources](#resources)
    * [Learn](#learn)
    * [Certification](#certification)
    * [Bolt](#bolt-1)
    * [Books](#books)
    * [Miscellaneous](#miscellaneous)
  * [License](#license)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

# Basics

- [Official documentation](http://neo4j.com/docs/stable/)
- [Cypher Refcard](http://neo4j.com/docs/stable/cypher-refcard/)
- [Developer resources](http://neo4j.com/developer/get-started/)
- [Gists](http://graphgist.neo4j.com/) - With Neo4j GraphGists you can describe and model your domain in a simple text file and render it as a rich, interactive page in any browser. Perfect to document a specific domain, use-case, question or graph problem.
- [Neo4j Examples](https://github.com/neo4j-examples) - Examples for Neo4j and Library Usage.
- [Alpha Release Channel](http://alpha.neohq.net/) - This microsite contains links and resources for future product releases.

# Connectors

## Bolt

- [neo4j-java-driver](https://github.com/neo4j/neo4j-java-driver) - [BETA] Java driver for Neo4j binary protocol.
- [neo4j-python-driver](https://github.com/neo4j/neo4j-python-driver) - [BETA] Python driver for Neo4j binary protocol.
- [neo4j-javascript-driver](https://github.com/neo4j/neo4j-javascript-driver) - [BETA] JavaScript driver for Neo4j binary protocol.
- [neo4j-dotnet-driver](https://github.com/neo4j/neo4j-dotnet-driver) - [BETA] .Net driver for Neo4j (Bolt).
- [neo4j-bolt-php](https://github.com/graphaware/neo4j-bolt-php) - [BETA] PHP driver for Neo4j binary protocol.
- [libneo4j-client](https://github.com/cleishm/libneo4j-client) - libneo4j-client is a client library written in C for Neo4j. It is not intended as a complete driver, but rather as a foundation on which basic tools and drivers for various languages may be built. libneo4j-client takes care of all the detail of establishing a session with a Neo4j server, sending statements for evaluation, and retrieving results.

## REST API

### Java

- [neo4j-ogm](https://github.com/neo4j/neo4j-ogm) - Object-Graph Mapping Library for Neo4j.
- [spring-data-neo4j](https://github.com/spring-projects/spring-data-neo4j) - Provides support to increase developer productivity in Java when using the neo4j graph database.
- [neo4j-jdbc](https://github.com/neo4j-contrib/neo4j-jdbc) - Neo4j JDBC driver.
- [jcypher](https://github.com/Wolfgang-Schuetzelhofer/jcypher) - Java access to Neo4J graph databases at multiple levels of abstraction.

### Ruby

- [neo4jrb](https://github.com/neo4jrb/neo4j) - An active model wrapper for the Neo4j Graph Database for Ruby.
- [neography](https://github.com/maxdemarzi/neography) - A thin Ruby wrapper to the Neo4j Rest API.

### Python

- [py2neo](https://github.com/nigelsmall/py2neo) - Py2neo is a comprehensive toolkit for working with Neo4j from within Python applications or from the command line.
- [neomodel](https://github.com/robinedwards/neomodel) - An Object Graph Mapper (OGM) for the neo4j graph database, built on the awesome py2neo.
- [BulbFlow](https://github.com/espeed/bulbs) - A Python persistence framework for graph databases like Neo4j, OrientDB and Titan.

### PHP

- [neo4jphp](https://github.com/jadell/neo4jphp) - PHP wrapper of the Neo4j REST interface.
- [NeoEloquent](https://github.com/Vinelab/NeoEloquent) - A Neo4j ORM - Based on Eloquent.
- [NeoClient](https://github.com/neoxygen/neo4j-neoclient) - A PHP HttpClient for the Neo4j ReST API with MultiDB Support.
- [Spider](https://github.com/spider/spider) - A simple, flexible, and beautiful graph-data abstraction for php.

### Other

- [node-neo4j](https://github.com/thingdom/node-neo4j) - REST API client for Node.
- [Neo4jClient](https://github.com/Readify/Neo4jClient) - .NET client binding.
- [neoism](https://github.com/jmcvetta/neoism) - Client for Golang.
- [neocons](https://github.com/michaelklishin/neocons) - A feature rich idiomatic Clojure client for the REST API.
- [RNeo4j](https://github.com/nicolewhite/RNeo4j) - Driver for R.
- [AnormCypher](https://github.com/AnormCypher/AnormCypher) - Scala library based on Anorm in the Play Framework.

# Cloud

- [GrapheneDB](http://www.graphenedb.com/) - The world's first fully managed
Neo4j graph database.

# Packages

- [Debian Packages](http://debian.neo4j.org/)
- [Yum Repo](http://yum.neo4j.org/)

# Docker

- [docker-neo4j](https://github.com/neo4j/docker-neo4j) - Docker Images for the Neo4j Graph Database.
- [docker-neo4j-cluster](https://github.com/ekino/docker-neo4j-cluster) - Up & Running Neo4j cluster in no time.

# Full-text search

- [neo4j-to-elasticsearch](https://github.com/graphaware/neo4j-to-elasticsearch) - GraphAware Elasticsearch Integration is an enterprise-grade bi-directional integration between Neo4j and Elasticsearch.
- [neo4j-elasticsearch](https://github.com/neo4j-contrib/neo4j-elasticsearch) - Neo4j ElasticSearch Integration.

# Import

- [GraphAware Neo4j Importer](https://github.com/graphaware/neo4j-importer) - Java importer skeleton for complicated, business-logic-heavy high-performance Neo4j imports directly from SQL databases, CSV files, etc.
- [neo4j-csv-firehose](https://github.com/sarmbruster/neo4j-csv-firehose) - Enables Neo4j’s `LOAD CSV` Cypher command to load from other datasources as well.
- [neo4j-rdbms-import](https://github.com/jexp/neo4j-rdbms-import) - An automatic importer for relational databases into Neo4j.
- [Doc manager for Neo4j](https://github.com/neo4j-contrib/neo4j_doc_manager) - The Neo4j Doc Manager takes MongoDB documents and makes it easy to query them for relationships by making them available in a Neo4j graph structure, following the format specified by Mongo Connector.

# Benchmarking

- [neoprofiler](https://github.com/moxious/neoprofiler) - Neo4J database profiling utility.

# Extensions

- [GraphAware Neo4j UUID](https://github.com/graphaware/neo4j-uuid) - GraphAware Runtime Module that assigns a UUID to all nodes in the graph transparently.
- [GraphAware Neo4j ChangeFeed](https://github.com/graphaware/neo4j-changefeed) - A GraphAware Framework Runtime Module allowing users to find out what were the latest changes performed on the graph.
- [GraphAware Neo4j TimeTree](https://github.com/graphaware/neo4j-timetree) - Java and REST APIs for working with time-representing tree in Neo4j.
- [GraphAware Neo4j Recommendation Engine](https://github.com/graphaware/neo4j-reco) - Neo4j-based recommendation engine module with real-time and pre-computed recommendations.
- [GraphAware Neo4j NodeRank](https://github.com/graphaware/neo4j-noderank) - GraphAware Timer-Driven Runtime Module that executes PageRank-like algorithm on the graph.
- [GraphAware Neo4j Algorithms](https://github.com/graphaware/neo4j-algorithms) - Custom graph algorithms for Neo4j with own Java and REST APIs.
- [GraphAware Neo4j Warmup](https://github.com/graphaware/neo4j-warmup) - Simple library that warms up Neo4j caches with a single REST call.
- [GraphAware Neo4j RestTest](https://github.com/graphaware/neo4j-resttest) - GraphAware RestTest is a simple library for testing code that talks to Neo4j running in standalone server mode.
- [Spatial](https://github.com/neo4j-contrib/spatial) - Neo4j Spatial is a library of utilities for Neo4j that faciliates the enabling of spatial operations on data.
- [Graphify](https://github.com/Graphify/graphify) - Graphify is a Neo4j unmanaged extension used for document and text classification using graph-based hierarchical pattern recognition.
- [neo4j-tx-participation](https://github.com/jexp/neo4j-tx-participation) - This is a Neo4j Server Extension to make Neo4j REST-API participate in transactions started by the transactional Cypher endpoint.

# Development

- [Maven repositories](https://m2.neo4j.org/index.html) - Neo4j Maven repositories (releases, snapshots).
- [GraphAware Neo4j Framework](https://github.com/graphaware/neo4j-framework)- GraphAware Framework speeds up development with Neo4j by providing a platform for building useful generic as well as domain-specific functionality, analytical capabilities, (iterative) graph algorithms, etc.
- [cypher-dsl](https://github.com/neo4j-contrib/cypher-dsl) - A Java DSL for the Cypher Query Language and an optional Query DSL mode.
- [Liquigraph](https://github.com/fbiville/liquigraph) - Database migrations management tool, based on how Liquibase works.
- [blueprints](https://github.com/tinkerpop/blueprints) - Blueprints is a collection of interfaces, implementations, ouplementations, and test suites for the property graph data model. Blueprints is analogous to the JDBC, but for graph databases.
- [structr](https://github.com/structr/structr) - Graph Application Platform based on Neo4j.
- [Reco4PHP](https://github.com/graphaware/reco4php) - Neo4j based Recommendation Engine Framework for PHP.

# Editors

- [jetbrains-plugin-cypher](https://github.com/Neueda4j/jetbrains-plugin-cypher) - Cypher plugin for Jetbrains-family IDE's.
- [cypher-vim-syntax](https://github.com/neo4j-contrib/cypher-vim-syntax) - Very basic Vim syntax for Cypher.

# Shell

- [cycli](https://github.com/nicolewhite/cycli) - A Command Line Interface for Cypher.
- [neo4j-shell-tools](https://github.com/jexp/neo4j-shell-tools) - A bunch of import/export tools for the neo4j-shell.

# Visualization

- [neoclipse](https://github.com/neo4j-contrib/neoclipse) - Neoclipse is a tool to view, edit and explore Neo4j databases.
- [Gephi](https://github.com/gephi/gephi) - Gephi is an award-winning open-source platform for visualizing and manipulating large graphs.
- [Linkurious](http://linkurio.us/) - Linkurious helps search and visualize your graph data through a simple web-based interface.

# Tools

- [Graphgen](http://graphgen.graphaware.com) - Graph Generation engine based on the Cypher DSL.
- [store-utils](https://github.com/jexp/store-utils) - Utilities to compact, copy, fix, analyse Neo4j stores.
- [ineo](https://github.com/cohesivestack/ineo)- A simple but useful Neo4j instance manager.

# Resources

- [openCypher](http://www.opencypher.org/) - openCypher is an open source project to bring a new public implementation of the industry’s most widely adopted graph query language: Cypher.

## Learn

- [Getting Started with Neo4j](http://neo4j.com/graphacademy/online-course/)
- [Neo4j in Production](http://neo4j.com/graphacademy/online-course-prod/)
- [Neo4j Koans](https://github.com/jimwebber/neo4j-tutorial) - A koan-style tutorial in Java for Neo4j.

## Certification

- [Neo4j Certification](http://neo4j.com/graphacademy/neo4j-certification/) - Become a Neo4j-Certified Professional.

## Bolt

- [Neo4j Data Protocol, Version 1](http://alpha.neohq.net/docs/server-manual/bolt.html) - This section describes the Neo4j Data Protocol, version 1. It is written primarily for those implementing client drivers as well as those who want to understand the low-level communication details of such interactions.
- [bolt-howto](https://github.com/nigelsmall/bolt-howto) - How to Build a Neo4j Bolt Protocol Driver.

## Books

- [Graph Databases](http://graphdatabases.com/) - The Definitive Book on Graph Databases and Introduction to Neo4j.
- [Learning Neo4j](https://www.packtpub.com/big-data-and-business-intelligence/learning-neo4j-graph-databases) - Run blazingly fast queries on complex graph datasets with the power of the Neo4j graph database.
- [Neo4j High Performance](https://www.packtpub.com/big-data-and-business-intelligence/neo4j-high-performance/)
- [A Programmatic Introduction to Neo4j](http://www.amazon.com/Programmatic-Introduction-Neo4j-Jim-Webber/dp/0321902904) - [NOT YET BEEN RELEASED]

## Miscellaneous

- [Neo4j's Idea board](https://trello.com/b/2zFtvDnV/public-idea-board)
- [Hardware Sizing Calculator](http://neo4j.com/hardware-sizing-calculator/)

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Neueda4j](https://github.com/Neueda4j) has waived all copyright and related or neighboring rights to this work.
