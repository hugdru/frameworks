# Collection of frameworks and libraries

Frameworks and Libraries for the development

## Event Sourcing

- [Event Store](https://www.eventstore.com/): an industrial-strength database technology used as the central data store for event-sourced systems. It is available open-source to run locally on most platforms or as SaaS through Event Store Cloud.
- [Lagom](https://www.lagomframework.com/): n open source framework for building systems of Reactive microservices in Java or Scala. Lagom builds on Akka and Play, proven technologies that are in production in some of the most demanding applications today.
- [Axon](https://axoniq.io/)
- [Eventuate](https://eventuate.io/): a platform that solves the distributed data management problems inherent in a microservice architecture enabling you focus on your business logic.

## Security

- [Keycloak](https://www.keycloak.org/): add authentication to applications and secure services with minimum fuss. No need to deal with storing users or authenticating users. It's all available out of the box.
- [Shiro](https://shiro.apache.org/): a powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management. With Shiro’s easy-to-understand API, you can quickly and easily secure any application – from the smallest mobile applications to the largest web and enterprise applications.
- [Spring Security](https://spring.io/projects/spring-security): a powerful and highly customizable authentication and access-control framework. It is the de-facto standard for securing Spring-based applications.
- [Passport](http://www.passportjs.org/): an authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application. A comprehensive set of strategies support authentication using a username and password, Facebook, Twitter, and more.

## API Gateways

- [Kong Gateway](https://konghq.com/kong/): a popular API gateway. Built for hybrid and multi-cloud, optimized for microservices and distributed architectures.
- [Netflix Zuul](https://github.com/Netflix/zuul): a gateway service that provides dynamic routing, monitoring, resiliency, security, and more.
- [Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway): Gateway built on Spring Framework 5.x and Spring Boot 2.x providing routing and more.
- [Apollo GraphQL](https://www.apollographql.com/): n open-source, spec-compliant GraphQL server that's compatible with any GraphQL client, including Apollo Client. It's the best way to build a production-ready, self-documenting GraphQL API that can use data from any source.

## Forecast

- [Greykite](https://github.com/linkedin/greykite): a flexible, intuitive and fast forecasting library
- [Prophet](https://facebook.github.io/prophet/):  a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

## Messaging

- [RabbitMQ](https://www.rabbitmq.com/): popular open source message broker
- [RocketMQ](https://github.com/alibaba/spring-cloud-alibaba/wiki/RocketMQ-en): an open-source distributed message system. It is based on highly available distributed cluster technologies and provides message publishing and subscription service with low latency and high stability
- [ActiveMQ Artemis](https://activemq.apache.org/): an open source project to build a multi-protocol, embeddable, very high performance, clustered, asynchronous messaging system
- [Kafka](https://kafka.apache.org/): a distributed streaming platform
- [Pulsar](https://pulsar.apache.org/): an open-source distributed pub-sub messaging system originally created at Yahoo and now part of the Apache Software Foundation
- [NATS.io](https://nats.io/):  an open source, lightweight, high-performance cloud native infrastructure messaging system.


## Streaming

- [Flink](https://flink.apache.org/): a framework and distributed processing engine for stateful computations over unbounded and bounded data streams
- [Spark](https://spark.apache.org/): a unified analytics engine for large-scale data processing
- [Storm](https://storm.apache.org/): a free and open source distributed realtime computation system
- [Spring Cloud Stream](https://spring.io/projects/spring-cloud-stream):  framework for building highly scalable event-driven microservices connected with shared messaging systems
- [Apache Samze](https://samza.apache.org/): a distributed stream processing framework
- [Google Dataflow](https://cloud.google.com/dataflow/): unified stream and batch data processing that's serverless, fast, and cost-effective.
- [Apache Beam](https://beam.apache.org/): implement batch and streaming data processing jobs that run on any execution engine.

## Serverless

- [Flink Statefun](https://flink.apache.org/stateful-functions.html): an API that simplifies building distributed stateful applications. It’s based on functions with persistent state that can interact dynamically with strong consistency guarantees.
- [Cloudstate](https://cloudstate.io/): allows developers to rapidly build stateful, highly scalable serverless applications.
- [Dapr](https://github.com/dapr/dapr): a portable, serverless, event-driven runtime that makes it easy for developers to build resilient, stateless and stateful microservices that run on the cloud and edge and embraces the diversity of languages and developer frameworks.
- [Argo](https://argoproj.github.io/): open source Kubernetes native workflows, events, CI and CD
- [TriggerMesh](https://triggermesh.com/): provides a real-time cloud native integration platform that allows you to connect services together to automate workflows and accelerate the flow of information across your organization.
- [Nats](https://nats.io/): a simple, secure and high performance open source messaging system for cloud native applications, IoT messaging, and microservices architectures.

## Protocol

### Misc

- [RSocket](https://rsocket.io/): Application protocol providing Reactive Streams semantics
- [Aeron](https://github.com/real-logic/aeron): efficient reliable UDP unicast, UDP multicast, and IPC message transport. Java and C++ clients are available in this repository, and a .NET client is available from a 3rd party. 


### RPC

- [Finagle](https://github.com/twitter/finagle):  an extensible RPC system for the JVM, used to construct high-concurrency servers
- [Dubbo](https://dubbo.apache.org/): a high-performance, java based open source RPC framework
- [gRPC](https://grpc.io/): a high-performance, open source universal RPC framework

## Python

- [Django](https://www.djangoproject.com/):  a high-level Python Web framework that encourages rapid development and clean, pragmatic design. 
- [Flask](https://flask.palletsprojects.com/): a Python web framework built with a small core and easy-to-extend philosophy.
- [FastAPI](https://fastapi.tiangolo.com/): a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
- [Pyctuator](https://github.com/SolarEdgeTech/pyctuator): monitor Python web apps using Spring Boot Admin
- [Tornado](https://www.tornadoweb.org/en/stable/): a Python web framework and asynchronous networking library, originally developed at FriendFeed. By using non-blocking network I/O, Tornado can scale to tens of thousands of open connections, making it ideal for long polling, WebSockets, and other applications that require a long-lived connection to each user.
- [aiohttp](https://docs.aiohttp.org/en/stable/): asynchronous HTTP Client/Server for asyncio and Python.

### Misc

- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/): provides a few simple methods and Pythonic idioms for navigating, searching, and modifying a parse tree
- [Scrapy](https://github.com/scrapy/scrapy): a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages
- [Requests](https://github.com/psf/requests): a simple, yet elegant HTTP library.
- [Pillow](https://pillow.readthedocs.io/en/stable/): the Python Imaging Library adds image processing capabilities to your Python interpreter.

### Package Manager

- [Poetry](https://github.com/python-poetry/poetry): helps you declare, manage and install dependencies of Python projects, ensuring you have the right stack everywhere.
- [pip](https://pip.pypa.io/en/stable/): the package installer for Python. You can use pip to install packages from the Python Package Index and other indexes.

## Java & Kotlin

### JDK

- [Amazon Corretto](https://aws.amazon.com/corretto): a no-cost, multiplatform, production-ready distribution of the Open Java Development Kit (OpenJDK)
- [AdaptOpenJDK](https://adoptopenjdk.net/): AdoptOpenJDK uses infrastructure, build und test scripts to produce prebuilt binaries from OpenJDK™ class libraries and a choice of either OpenJDK or the Eclipse OpenJ9 VM.
- [OpenJDK](https://github.com/openjdk): open-source JDK

### Injection

- [Dagger](https://github.com/google/dagger): a fast dependency injector for Java and Android.
- [Guice](https://github.com/google/guice): alleviates the need for factories and the use of new in your Java code.  

### HTTP Clients

- [Retrofit](https://github.com/square/retrofit): a type-safe HTTP client for Android and Java.
- [OkHttp](https://square.github.io/okhttp/): an HTTP client that’s efficient by default

### MicroServer

- [Open Liberty](https://openliberty.io/): a lightweight open framework for building fast and efficient cloud-native Java microservices.
- [ActiveJ](https://activej.io/): an alternative Java platform built from the ground up as a replacement of Spring, Spark, Quarkus, Micronauts, and other solutions.
- [Helidon](https://helidon.io/#/): reactive WebServer provides a modern functional programming model and runs on top of Netty. From Oracle
- [Quarkus](https://quarkus.io/):  Kubernetes Native Java stack tailored for OpenJDK HotSpot and GraalVM, crafted from the best of breed Java libraries and standards. From RedHat
- [Micronaut](https://micronaut.io/): a modern, JVM-based, full-stack framework for building modular, easily testable microservice and serverless applications
- [Javalin](https://javalin.io/): a simple web framework for Java and Kotlin
- [Jooby](https://jooby.io/): is a modern, performant and easy to use web framework for Java and Kotlin built on top of your favorite web server.
- [Spark](http://sparkjava.com/): a micro framework for creating web applications in Kotlin and Java 8 with minimal effort
- [Spring Boot](https://spring.io/projects/spring-boot): Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run".
- [Vert.x](https://vertx.io/): a tool-kit for building reactive applications on the JVM
- [Ratpack](https://ratpack.io/): a set of Java libraries for building scalable HTTP applications
- [JHipster](https://www.jhipster.tech/): a development platform to quickly generate, develop, & deploy modern web applications & microservice architectures.
- [http4k](https://www.http4k.org/): a lightweight but fully-featured HTTP toolkit written in pure Kotlin
- [Ktor](https://ktor.io/): a framework for building asynchronous servers and clients in connected systems using the powerful Kotlin programming language
- [Dropwizard](https://www.dropwizard.io/en/latest/): pulls together stable, mature libraries from the Java ecosystem into a simple, light-weight package that lets you focus on getting things done


### Serializer

- [Kryo](https://github.com/EsotericSoftware/kryo): a fast and efficient binary object graph serialization framework for Java
- [Avro](https://avro.apache.org/): a data serialization system.
- [Protocol Buffers](https://developers.google.com/protocol-buffers): Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data 
- [Jackson](https://github.com/FasterXML)
- [Boon](https://github.com/boonproject/boon/wiki/Boon-JSON-in-five-minutes): is the probably the fastest way to serialize and parse JSON in Java so far for your project
- [Gson](https://github.com/google/gson): a Java library that can be used to convert Java Objects into their JSON representation
- [fast-serialization](https://github.com/RuedigerMoeller/fast-serialization): up to 10 times faster 100% JDK Serialization compatible drop-in replacement
- [MicroStream](https://microstream.one/serialization): Next Generation Java Serialization
- [Thrift](http://thrift.apache.org/): scalable cross-language services development, combines a software stack with a code generation engine to build services that work efficiently and seamlessly between C++, Java, Python, PHP, Ruby, Erlang, Perl, Haskell, C#, Cocoa, JavaScript, Node.js, Smalltalk, OCaml and Delphi and other languages.
- [JsonPath](https://github.com/json-path/JsonPath): a Java port of Stefan Goessner JsonPath implementation.
- [protostuff](https://github.com/protostuff/protostuff): a java serialization library with built-in support for forward-backward compatibility (schema evolution) and validation.

### Mapping

- [MapStruct](https://mapstruct.org/): a code generator that greatly simplifies the implementation of mappings between Java bean types based on a convention over configuration approach
- [Orika](https://github.com/orika-mapper/orika): a Java Bean mapping framework that recursively copies (among other capabilities) data from one object to another
- [fastJson](https://github.com/alibaba/fastjson): a Java library that can be used to convert Java Objects into their JSON representation. It can also be used to convert a JSON string to an equivalent Java object
- [Apache Cayenne](https://cayenne.apache.org/): an open source Java object-to-relational mapping framework

### Docker Pluins

- [jib](https://github.com/GoogleContainerTools/jib): builds optimized Docker and OCI images for your Java applications without a Docker daemon - and without deep mastery of Docker best-practices
- [Docker Gralde Plugin](https://github.com/palantir/gradle-docker): three Gradle plugins for working with Docker containers
- [Docker Maven Plugin](https://github.com/fabric8io/docker-maven-plugin): a Maven plugin for building Docker images and managing containers for integration tests
- [Gradle Docker Plugin](https://github.com/bmuschko/gradle-docker-plugin): Gradle plugin for managing Docker images and containers using the Docker remote API

### Misc

- [vavr](https://www.vavr.io/): vavr core is a functional library for Java. It helps to reduce the amount of code and to increase the robustness. 
- [Eclipse Collections](https://www.eclipse.org/collections/): the best Java collections framework ever that brings happiness to your Java development.
- [Caffeine](https://github.com/ben-manes/caffeine): a high performance, near optimal caching library based on Java 8
- [HikariCP](https://github.com/brettwooldridge/HikariCP): a "zero-overhead" production ready JDBC connection pool. At roughly 130Kb, the library is very light
- [Bouny Castle](https://www.bouncycastle.org/): crypto library
- [JavaLite](https://javalite.io/): a cohesive collection of frameworks designed from ground up to add pleasure back to your daily life
- [Jsoup](https://jsoup.org/): a Java library for working with real-world HTML.
- [Immutables](http://immutables.github.io/): Java annotation processors to generate simple, safe and consistent value objects.
- [picocli](https://picocli.info/): a mighty tiny command line interface
- [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap): compressed bitmaps which tend to outperform conventional compressed bitmaps such as WAH, EWAH or Concise.
- [Antora](https://antora.org/): a multi-repository documentation site generator for tech writers who loves writing in AsciiDoc.
- [Google Auto](https://github.com/google/auto): a collection of source code generators for Java.

### Scheduler

- [ShedLock ](https://github.com/lukas-krecan/ShedLock): hedLock makes sure that your scheduled tasks are executed at most once at the same time. 
- [Quartz ](http://www.quartz-scheduler.org/): open source job scheduling library that can be integrated within virtually any Java application - from the smallest stand-alone application to the largest e-commerce system.

### Query Languages

#### SQL

- [jOOQ](https://www.jooq.org/): generates Java code from your database and lets you build type safe SQL queries through its fluent API
- [Liquibase](https://www.liquibase.org/): an open source project that helps millions of developers rapidly manage database schema changes
- [Flyway](https://flywaydb.org/): Version control for your database. Robust schema evolution across all your environments
- [Hikari](https://github.com/brettwooldridge/HikariCP): a "zero-overhead" production ready JDBC connection pool.

#### Misc

- [GraphQL](https://graphql.org/): a query language for APIs and a runtime for fulfilling those queries with your existing data
- [Cipher](https://neo4j.com/developer/cypher-basics-i/): Query language for Neo4j 

### Reactive

- [SmallRye Mutiny](https://smallrye.io/smallrye-mutiny/): a reactive programming library
- [Project Reactor](https://projectreactor.io/): a fourth-generation reactive library, based on the Reactive Streams
specification, for building non-blocking applications on the JVM
- [akka](https://akka.io/): a toolkit for building highly concurrent, distributed, and resilient message-driven applications for Java and Scala
- [RxJava](https://github.com/ReactiveX/RxJava): a Java VM implementation of Reactive Extensions: a library for composing asynchronous and event-based programs by using observable sequences

### Testing

- [AssertJ](https://assertj.github.io/doc/): fluent assertions java library
- [Mockito](https://site.mockito.org/): mocking framework for unit tests in Java
- [JUnit 5](https://junit.org/junit5/): the next generation of JUnit
- [Togglz](https://www.togglz.org/): Feature Flags for the Java platform
- [jQAssistant](https://jqassistant.org/):  a QA tool, which allows the definition and validation of project specific rules on a structural level. 
- [Sotograph](https://www.hello2morrow.com/products/sotograph): detects a wide range of potential problems and gathers information about many quality aspects. 
- [ArchUnit](https://www.archunit.org/): a free, simple and extensible library for checking the architecture of your Java code using any plain Java unit test framework.
- [JBehave](https://jbehave.org/): a framework for Behaviour-Driven Development (BDD). 
- [Gauge](https://gauge.org/): a free and open source test automation framework that takes the pain out of acceptance testing 
- [FitNesse](http://docs.fitnesse.org/FrontPage): fully integrated standalone wiki and acceptance testing framework
- [JUnit Pioneer](https://github.com/junit-pioneer/junit-pioneer): a melting pot for all kinds of extensions to JUnit 5, particular to its Jupiter API.
- [Karate](https://github.com/intuit/karate): the only open-source tool to combine API test-automation, mocks, performance-testing and even UI automation into a single, unified framework. 
- [ClueCumber](https://github.com/trivago/cluecumber-report-plugin): aggregated test reports from Cucumber compatible JSON files that are generated by Cucumber BDD, Karate and other frameworks.
- [PIT ](https://pitest.org/): state of the art mutation testing system, providing gold standard test coverage for Java and the jvm.
- [Mockneat ](https://github.com/nomemory/mockneat): a simple but powerful (fluent) API that enables developers to create json, xml, csv and sql data programatically.
- [Spock](https://github.com/spockframework/spock): a BDD-style developer testing and specification framework for Java and Groovy applications.
- [Awaitility](https://github.com/awaitility/awaitility): small Java DSL for synchronizing asynchronous operations

### Integration Tests

- [Pact](https://docs.pact.io/): a code-first tool for testing HTTP and message integrations using contract tests.
- [Spring Cloud Contract](https://spring.io/projects/spring-cloud-contract): a tool that enables Consumer Driven Contract (CDC) development of JVM-based applications. It is shipped with Contract Definition Language (DSL) written in Groovy or YAML.
- [REST Assured](https://rest-assured.io/): brings the simplicity of using these languages into the Java domain.
- [WireMock](http://wiremock.org/): a simulator for HTTP-based APIs. Some might consider it a service virtualization tool or a mock server. 
- [MockServer](https://www.mock-server.com/): easy mocking of any system you integrate with via HTTP or HTTPS
- [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver): a scriptable web server for testing HTTP clients (super easy to use with Spring Boot)
- [Testcontainers](https://www.testcontainers.org/): a Java library that supports JUnit tests, providing lightweight, throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.

### Resilience

- [Failsafe](https://github.com/jhalterman/failsafe):  a lightweight, zero-dependency library for handling failures in Java 8+, with a concise API for handling everyday use cases and the flexibility to handle everything else. 
- [Resilience4j](https://github.com/resilience4j/resilience4j): a lightweight fault tolerance library inspired by Netflix Hystrix, but designed for Java 8 and functional programming. 
-[Bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j): Java rate-limiting library based on token-bucket algorithm 
- Guava Ratelimiter

### Security Tests

- [ZAP](https://www.zaproxy.org/):  a free, open-source penetration testing tool being maintained under the umbrella of the Open Web Application Security Project (OWASP).

### UI

- [PrimeFace](https://www.primefaces.org/): a lightweight library with one jar, zero-configuration and no required dependencies
- [Wicket](https://wicket.apache.org/): open source Java web framework servicing websites and applications 

### API

- [Problem](https://github.com/zalando/problem): a library that implements application/problem+json. It comes with an extensible set of interfaces/implementations as well as convenient functions for every day use
- [HAL Explorer](https://github.com/toedter/hal-explorer): you can browse and explore HAL and HAL-FORMS based RESTful Hypermedia APIs


### Template Engines

- [Rocker](https://github.com/fizzed/rocker): a Java 8 optimized (runtime compat with 6+), near zero-copy rendering, speedy template engine that produces statically typed, plain java object templates that are compiled along with the rest of your project.
- [Thymeleaf](https://www.thymeleaf.org/): a modern server-side Java template engine for both web and standalone environments.
- [Freemarker](https://freemarker.apache.org/): a Java library to generate text output (HTML web pages, e-mails, configuration files, source code, etc.) based on templates and changing data
- [Velocity](https://velocity.apache.org/): a Java-based template engine. It permits anyone to use a simple yet powerful template language to reference objects defined in Java code.
- [jte](https://jte.gg/): a fast and lightweight template engine for Java (!)

### ByteCode / CodeGeneration

- [ByteBuddy](https://bytebuddy.net/#/): a code generation and manipulation library for creating and modifying Java classes during the runtime of a Java application and without the help of a compiler
- [ASM](https://asm.ow2.io/): an all purpose Java bytecode manipulation and analysis framework
- [JavaPoet](https://github.com/square/javapoet):  a Java API for generating .java source files

### MS-Office

- [Apache POI](https://poi.apache.org/): Excel
- [docx4j](https://www.docx4java.org/trac/docx4j): Word
- [fastexcel](https://github.com/dhatim/fastexcel) 

## JavaScript

### Misc

- [Leafletjs](https://leafletjs.com/): an open-source JavaScript library for mobile-friendly interactive maps
- [fullPage](https://alvarotrigo.com/fullPage/): open-source library helps you create full-screen scrolling websites
- [anime](https://animejs.com/): a lightweight JavaScript animation library with a simple, yet powerful API
- [screenfull](https://github.com/sindresorhus/screenfull.js): simple wrapper for cross-browser usage of the JavaScript Fullscreen API, which lets you bring the page or any element into fullscreen
- [Moment.js](https://momentjs.com/): parse, validate, manipulate, and display dates and times in JavaScript
- [Hammer](http://hammerjs.github.io/): lets you add multi-touch gestures to your Web Apps.
- [Masonry](https://masonry.desandro.com/): a JavaScript grid layout library
- [D3.js](https://d3js.org/): library for manipulating documents based on data
- [Slick](https://kenwheeler.github.io/slick/):  fully responsive, swipe-enabled, infinite looping, and more
- [Popper](https://popper.js.org/): provides a reliable and extensible positioning engine you can use to ensure all your popper elements are positioned in the right place.
- [Babel](https://babeljs.io/): a JavaScript compiler
- [Sanity](https://www.sanity.io/): he fastest, most flexible platform for delivering content to digital devices and products 
- [Flow](https://flow.org/):  a static type checker for your JavaScript code

### Utility

- [underscore](https://underscorejs.org/): a JavaScript library that provides a whole mess of useful functional programming helpers without extending any built-in objects.
- [Lodash](https://lodash.com/): a modern JavaScript utility library delivering modularity, performance & extras
- [Radmda.js](https://ramdajs.com/): a practical functional library for JavaScript programmers

### Builder

- [Vite](https://github.com/vitejs/vite): a new breed of frontend build tool that significantly improves the frontend development experience. 
- [Webpack](https://webpack.github.io/): a modern JavaScript tool that serves as a static module bundler
- [npm](https://www.npmjs.com/): build tool
- [Parcel](https://parceljs.org/): blazing fast, zero configuration web application bundler
- [Browserify](http://browserify.org/): lets you require('modules') in the browser by bundling up all of your dependencies
- [Brunch](https://brunch.io/): build tool
- [Rollup](https://rollupjs.org): a module bundler for JavaScript which compiles small pieces of code into something larger and more complex, such as a library or application.

### Repository Manager

- [Lerna](https://github.com/lerna/lerna): a tool for managing JavaScript projects with multiple packages.
- [Bit](https://github.com/teambit/bit): platform for collaborating on components
- [Nrwl-Nx](https://nx.dev/): a set of extensible dev tools for monorepos, which helps you develop like Google, Facebook, and Microsoft
- []():

### Rich Text Editor

- [summernote](https://summernote.org/): WYSIWYG editor
- [Quill](https://quilljs.com/): powerful rich text editor 


## Testing

- [Karma](https://karma-runner.github.io/latest/index.html): the main goal for Karma is to bring a productive testing environment to developers
- [Jasmine](https://jasmine.github.io/): behavior-Driven JavaScript
- [Selenium](https://www.selenium.dev/): a collection of language specific bindings to drive a browser
- [Jest](https://jestjs.io/): a delightful JavaScript Testing Framework with a focus on simplicity.
- [Nightwatch](https://nightwatchjs.org/): End-to-end testing, the easy way.
- [Cypress](https://www.cypress.io/): fast, easy and reliable testing for anything that runs in a browser. 
- [TestCafe](https://devexpress.github.io/testcafe/): a node.js tool to automate end-to-end web testing
- [Mocha](https://mochajs.org/): a feature-rich JavaScript test framework running on Node.js and in the browser, making asynchronous testing simple and fun.
- [Chai](https://www.chaijs.com/):  a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.
- [Taiko](https://taiko.dev/): an open source node.js library for testing modern web applications 

### Frameworks

- [Alpine.js](https://github.com/alpinejs/alpine): offers you the reactive and declarative nature of big frameworks like Vue or React at a much lower cost. You get to keep your DOM, and sprinkle in behavior as you see fit.
- [Flutter](https://flutter.dev/): Google’s UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase.
- [React](https://reactjs.org/): JavaScript library for building user interfaces
- [Vue.js](https://vuejs.org/):  a progressive framework for building user interfaces.
- [Preact](https://preactjs.com/): fast 3kB alternative to React with the same modern API
- [Svelte](https://svelte.dev/): a radical new approach to building user interfaces
- [Meteor](https://www.meteor.com/): an open source platform for web, mobile, and desktop
- [Next.js](https://nextjs.org/):  a free and open source web application framework based on React.js, Node.js, webpack and Babel.js for building server-side rendered and/or static web applications using React
- [Nuxt.js](https://nuxtjs.org/): an open source framework based on Vue.js
- [Gatsby](https://www.gatsbyjs.org/): is a free and open source framework based on React that helps developers build blazing fast websites and apps
- [Node.js](https://nodejs.org/en/): a JavaScript runtime built on Chrome's V8 JavaScript engine
- [Express](https://expressjs.com/): fast, unopinionated, minimalist web framework for Node.js
- [Koa](https://koajs.com/): a new web framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Nest](https://nestjs.com/): a progressive Node.js framework for building efficient, reliable and scalable server-side applications.


### UI

- [Bootstrap](https://getbootstrap.com/): popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins
- [Material](https://material.io/): design system that helps teams build high-quality digital experiences.
- [Semantic](https://semantic-ui.com/): a development framework that helps create beautiful, responsive layouts using human-friendly HTML
- [Foundation](https://get.foundation/): most advanced responsive front-end framework in the world
- [Font Awesome](https://fontawesome.com/): get vector icons and social logos on your website
- [Bulma](https://bulma.io/): a free, open source CSS framework based on Flexbox
- [Tailwind](https://tailwindcss.com/): a utility-first CSS framework packed with classes like flex, pt-4, text-center and rotate-90 that can be composed to build any design, directly in your markup.

### Complete Stack

- [Next.js]():
- [Chakra UI](https://chakra-ui.com/): a simple, modular and accessible component library that gives you all the building blocks you need to build your React applications
- [Playroom](https://github.com/seek-oss/playroom): simultaneously design across a variety of themes and screen sizes, powered by JSX and your own component library.
- [Storybook](https://storybook.js.org/): an open source tool for developing UI components in isolation for React, Vue, Angular, and more
- [Playwright](https://github.com/microsoft/playwright): a Node library to automate Chromium, Firefox and WebKit with a single API.
- [Preconstruct](https://github.com/preconstruct/preconstruct): dev and build your code painlessly in monorepos
- [Manypkg](https://github.com/Thinkmill/manypkg): a linter for package.json files in Yarn, Bolt or pnpm monorepos
- [ESLint](https://eslint.org/): find and fix problems in your JavaScript code
- [Prettier](https://prettier.io/): an opinionated code formatter
