# Guide to Learn NopCommerce step by step for NopCommerce Developer

In this tutorial you’ll set up and deploy a production-ready ASP.NET Core application NopCommerce with a MongoDb Server on Ubuntu 18.04 using Nginx.


## Resources

1. Prerequisites

   - [C#](https://www.pluralsight.com/paths/csharp)
   - [Entity Framework](https://www.pluralsight.com/search?q=entity%20framework%20core)
   - [ASP.NET Core](https://www.pluralsight.com/search?q=asp.net%20core)
   - SQL Fundamentals

2. Install
   1. .NET 9.x
   - Learn GIT, create a few repositories on GitHub, share your code with other people
   - Know HTTP(S) protocol, request methods (GET, POST, PUT, PATCH, DELETE, OPTIONS)
   - [How to Install and uninstall reinstall  upgrade .NET 6.x on Ubuntu 18.04*64 step by step](https://www.iaspnetcore.com/Blog/BlogPost/618a75d3635c733c81dc77c3/how-to-install-and-uninstall-reinstall-upgrade-net-6x-on-ubuntu-180464-step-by-step)
   - Learn [dotnet CLI](https://docs.microsoft.com/en-us/dotnet/core/tools/?tabs=netcore2x)
   - Read a few books about algorithms and data structures

3. Dependency Injection

   1. DI Containers
      - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-2.2)
      - [x] [AutoFac(used by nopcommerce)](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)   used by nopcommerce
      - [Ninject](http://www.ninject.org/)
      - [StructureMap](https://github.com/structuremap/structuremap)
      - [Castle Windsor](https://github.com/castleproject/Windsor)
   2. [Life Cycles](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-2.2#service-lifetimes)
   3. [Scrutor](https://github.com/khellang/Scrutor)

4. Databases

   1. Relational
      1. [x] [SQL Server(used by nopcommerce)](https://www.microsoft.com/en-us/sql-server/sql-server-2017)   used by nopcommerce
      2. [PostgreSQL(used by nopcommerce)](https://www.postgresql.org/)  used by nopcommerce
      3. [MariaDB](https://mariadb.org/)
      4. [MySQL(used by nopcommerce)](https://www.mysql.com/)  used by nopcommerce
   2. Cloud Databases
      - [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db)
      - [DynamoDB](https://aws.amazon.com/dynamodb/)
   3. Search Engines
      - [ElasticSearch](https://www.elastic.co/)
      - [Solr](http://lucene.apache.org/solr/)
      - [Sphinx](http://sphinxsearch.com/)
   4. NoSQL
      - [MongoDB](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-2.2&tabs=visual-studio)
      - [Redis](https://redis.io/)
      - [Apache Cassandra](http://cassandra.apache.org/)
      - [LiteDB](https://github.com/mbdavid/LiteDB)
      - [RavenDB](https://github.com/ravendb/ravendb)
      - [CouchDB](http://couchdb.apache.org/)

5. Caching

   1. Entity Framework 2nd Level Cache
      1. [EFSecondLevelCache.Core](https://github.com/VahidN/EFSecondLevelCache.Core)
      2. [EntityFrameworkCore.Cacheable](https://github.com/SteffenMangold/EntityFrameworkCore.Cacheable)
   2. [Distributed Cache](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/distributed?view=aspnetcore-2.2)
      1. [Redis(used by nopcommerce)](https://redis.io/)
      2. [Memcached](https://memcached.org/)
   3. [Memory Cache](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/memory?view=aspnetcore-2.2)

6. Logging

   1. Log Frameworks
      - [Serilog](https://github.com/serilog/serilog)
      - [NLog](https://github.com/NLog/NLog)
      - [Elmah](https://elmah.github.io/)
   2. Log Management System
      - [Sentry.io](http://sentry.io)
      - [Loggly.com](https://loggly.com)
      - [Elmah.io](http://elmah.io)
   3. own Log Frameworks
      - [own Log Frameworks]nopCommerce uses its own logging implementation (available in admin area)   used by nopcommerce

7. Template Engines
   1. [Razor](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/razor?view=aspnetcore-2.2)
   2. [DotLiquid](https://github.com/dotliquid/dotliquid)
   3. [Scriban](https://github.com/lunet-io/scriban)
   4. [Fluid](https://github.com/sebastienros/fluid)
8. Real-Time Communication

   1. [SignalR](https://docs.microsoft.com/en-us/aspnet/core/signalr)

9. Object Mapping

   - [AutoMapper(used by nopcommerce)](https://github.com/AutoMapper/AutoMapper)  used by nopcommerce
   - [Mapster](https://github.com/MapsterMapper/Mapster)
   - [AgileMapper](https://github.com/agileobjects/AgileMapper)
   - [ExpressMapper](http://expressmapper.org/)

10. API Clients

    1. REST
       - [OData](https://blogs.msdn.microsoft.com/odatateam/2018/07/03/asp-net-core-odata-now-available/)
       - [Sieve](https://github.com/Biarity/Sieve)
    2. GraphQL
       - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)

11. Good to Know

    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation(used by nopcommerce)](https://github.com/JeremySkinner/FluentValidation)
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [Polly](https://github.com/App-vNext/Polly)
    - [NodaTime](https://github.com/nodatime/nodatime)
    - [GenFu](https://github.com/MisterJames/GenFu)

12. Testing

    1. yarp Testing
       1. Creating a Reverse Proxy Server with YARP
          - [IHttpForwarder](https://www.cnblogs.com/TianFang/p/16357549.html)  - blog for custom IHttpForwarder -> local http://localhost:5132 
          - [IHttpForwarder](https://microsoft.github.io/reverse-proxy/articles/direct-forwarding.html) - custom IHttpForwarder & HttpTransformer -> local http://localhost:5132 
          - [IHttpForwarder](https://blog.csdn.net/sD7O95O/article/details/118616751)  - custom IHttpForwarder & HttpTransformer -> ConnectCallback -> remote http://localhost:5132 
       2. Intranet Penetration
          - [Intranet Penetration with YARP](https://blog.csdn.net/sD7O95O/article/details/118616751)  blog for Intranet Penetration with YARP  
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       3. Assertion
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
          - [Shouldly](https://github.com/shouldly/shouldly)
    2. Http Testing
       - [create simple HTTP web servers in C# using HttpListener class](https://www.iaspnetcore.com/blogpost-65e9b9ab4cc16d028431b9c7-create-simple-http-web-servers-in-c-using-httplistener-class)  blog
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
       - [LightBDD](https://github.com/LightBDD/LightBDD)
    3. Integration Testing
       - [WebApplicationFactory](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-2.2)
       - [TestServer](https://koukia.ca/integration-testing-in-asp-net-core-2-0-51d14ede3968)
    4. E2E Testing
       - [Selenium](https://www.automatetheplanet.com/webdriver-dotnetcore2/)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)

13. Task Scheduling

    - [HangFire](https://github.com/HangfireIO/Hangfire)
    - [Coravel](https://github.com/jamesmh/coravel)
    - [Fluent Scheduler](https://github.com/fluentscheduler/FluentScheduler)
    
14. MicroServices

    1. Message-Broker
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview)
    2. Message-Bus
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [CAP](https://github.com/dotnetcore/CAP)

15. SOLID

    - [Single Responsibility Principle (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [Open-Closed Principle (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [Liskov Substitution Principle (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [Interface Segregation Principle (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [Dependency Inversion Principle (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

16. Design-Patterns
    - [CQRS](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
    - [Decorator](https://www.dofactory.com/net/decorator-design-pattern)
    - [Strategy](https://www.dofactory.com/net/strategy-design-pattern)
    - [Observer](https://www.dofactory.com/net/observer-design-pattern)
    - [Builder](https://www.dofactory.com/net/builder-design-pattern)
    - [Singleton](https://www.dofactory.com/net/singleton-design-pattern)
    - [Facade](https://www.dofactory.com/net/facade-design-pattern)
    - [Mediator](https://www.dofactory.com/net/mediator-design-pattern)
17. NopCommerce Extensions
     - [nopCommerce v4.10 asp.net core 3 blazor server-side(single page eStore)](https://github.com/aybelanov/spaCommerce)  https://github.com/aybelanov/spaCommerce
18. NopCommerce training course
     - [online course for developers](https://www.nopcommerce.com/en/training?utm_source=docs_nopcommerce&utm_medium=documentation&utm_campaign=course&utm_content=Developers_Guide)  [https://github.com/aybelanov/spaCommerce](https://www.nopcommerce.com/en/training?utm_source=docs_nopcommerce&utm_medium=documentation&utm_campaign=course&utm_content=Developers_Guide)
     - Quickly run and configure websites of any complexity on nopCommerce
     - Create integrations with third-party software
     - Create and customize plugins and themes
    
    



### mozilla firefox download url


<a href="http://ftp.mozilla.org/" target="_blank">http://ftp.mozilla.org/</a>


