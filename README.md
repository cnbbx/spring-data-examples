[](#spring-data-examples)Spring数据示例
===================================

[![建立状态](https://camo.githubusercontent.com/b3051d33ee652f208d1274da85007e3b6fcc7a87/68747470733a2f2f7472617669732d63692e6f72672f737072696e672d70726f6a656374732f737072696e672d646174612d6578616d706c65732e7376673f6272616e63683d69737375652532462532333133)](https://travis-ci.org/spring-projects/spring-data-examples)

此存储库包含用于展示API以及如何使用模块提供的功能的不同Spring Data模块的示例项目。

我们为单个模块的示例提供了单独的文件夹：

[](#spring-data-jpa)Spring Data JPA
-----------------------------------

*   `eclipselink`\- 示例项目，展示如何将Spring Data JPA与Spring Boot和[Eclipselink一起使用](https://www.eclipse.org/eclipselink/)。
*   `example` \- 可能是你想先看看的项目。包含各种示例包，展示了可以使用Spring Data JPA的不同级别。查看`simple`最基本设置的包。
*   `interceptors` \- 如何使用AOP丰富存储库的示例。
*   `java8`\- 如何使用Java 8日期时间类型的Spring Data JPA审计以及`Optional`存储库方法的返回类型的使用示例。注意，此项目需要使用JDK 8构建。
*   `jpa21` \- 显示对JPA 2.1特定功能的支持（存储过程支持）。
*   `multiple-datasources`\- 如何将Spring Data JPA与多个`DataSource`s 一起使用的示例。
*   `query-by-example` \- 示例项目，显示使用Spring Data JPA的Query示例。
*   `security` \- 如何将Spring Data JPA存储库与Spring Security集成的示例。
*   `showcase` \- 重构展示了如何使用Spring Data JPA改进基于JPA的普通持久层（阅读：删除接近所有实现代码）。请按照`demo.txt`文件获取详细说明。
*   `vavr`\- 显示对[Vavr](https://www.vavr.io)集合类型的支持作为查询方法的返回类型。

[](#spring-data-mongodb)Spring Data MongoDB
-------------------------------------------

*   `aggregation` \- 展示MongoDB聚合框架支持的示例项目。
*   `example` \- 一般存储库功能（包括地理空间功能），Querydsl集成和高级主题的示例项目。
*   `fluent-api`\- 显示`MongoTemplate`与MongoDB交互的新流畅API（替代）的示例项目。
*   `geo-json`\- 显示[GeoJSON](http://geojson.org)与MongoDB一起使用的示例项目。
*   `gridfs` \- 显示使用MongoDB的gridFS的示例项目。
*   `java8`\- 如何将Spring Data MongoDB与Java 8日期时间类型一起使用以及作为`Optional`存储库方法的返回类型的使用示例。注意，此项目需要使用JDK 8构建。
*   `query-by-example` \- 显示使用MongoDB按示例查询的示例项目。
*   `reactive` \- 显示反应模板和存储库支持的示例项目。
*   `security` \- 显示使用MongoDB的Spring Security的示例项目。
*   `text-search` \- 显示MongoDB文本搜索功能用法的示例项目。
*   `transactions` \- 同步和反应式MongoDB 4.0事务支持的示例项目。

[](#spring-data-rest)Spring Data REST
-------------------------------------

*   `headers`\- 显示HTTP标头数量及其用于执行条件`GET`请求的示例。
*   `multi-store` \- 基于Spring Data JPA和Spring Data MongoDB的示例REST Web服务。
*   `projections` \- 示例REST Web服务，显示如何使用投影。
*   `security` \- 使用Spring Security保护的示例REST Web服务。
*   `starbucks` \- 使用Spring Data REST和MongoDB构建的REST Web服务示例。
*   `uri-customizations` \- 显示URI自定义功能的示例项目。

[](#spring-data-redis)Spring Data Redis
---------------------------------------

*   `cluster` \- Redis群集支持的示例。
*   `example` \- 基本Spring Data Redis设置示例。
*   `repositories` \- 在Redis之上演示Spring Data存储库抽象的示例。
*   `sentinel` \- Redis Sentinel支持示例。

[](#spring-data-for-apache-solr)Apache Solr的Spring数据
----------------------------------------------------

*   `example` \- Apache Solr的Spring Data存储库的示例项目。
*   `managed-schema` \- 显示托管架构集成的示例项目。

[](#spring-data-elasticsearch)Spring Data Elasticsearch
-------------------------------------------------------

*   `example` \- 示例如何使用基本文本搜索，地理空间搜索和构面。

[](#spring-data-neo4j)Spring Data Neo4j
---------------------------------------

*   `example` \- 显示基本节点和关系实体以及存储库使用情况的示例。

[](#spring-data-web-support)Spring Data Web支持
---------------------------------------------

*   `projections` \- 在投影接口上为JSONPath和XPath表达式提供Spring Data Web支持的示例。
*   `querydsl`\- Spring Data Querydsl Web集成示例（`Predicate`从Web请求创建）。
*   `web`\- Spring Data Web集成示例（将`Pageable`实例绑定到Spring MVC控制器方法，使用接口绑定Spring MVCrequest有效负载）。

[](#spring-data-for-apache-cassandra)Apache Cassandra的Spring数据
--------------------------------------------------------------

*   `example` \- 显示Apache Cassandra的核心Spring Data支持。
*   `java8` \- Java 8特定功能，如对象映射中对JSR-310类型的支持。
*   `reactive` \- 反应性支持的实例。

[](#spring-data-ldap)Spring Data LDAP
-------------------------------------

*   `example` \- Spring Data存储库的示例，用于访问LDAP存储。

[](#spring-data-jdbc)Spring Data JDBC
-------------------------------------

*   `basic` \- Spring Data JDBC的基本用法。

[](#miscellaneous)杂
-------------------

*   `bom` \- 示例项目如何在非Spring-Boot方案中使用Spring Data版本系列bom。
*   `map`\- 示例项目，显示如何使用`Map`-backed存储库。
*   `multi-store` \- 在一个项目中同时使用Spring Data MongoDB和Spring Data JPA的示例项目。
