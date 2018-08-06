# Home

The Home repository is the starting point for people to learn about Elders' projects. This repository contains pointers to the various GitHub repositories developed and maintained by Elders.

Projects in this organization have adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact opencode@microsoft.com with any additional questions or comments.

## Legend

| Name | Description |
|------|-------------|
| ![Elders](https://img.shields.io/badge/Status-olympus-green.svg) | It is stable and it will continue to be supported, maintenance and future development |
| ![Elders](https://img.shields.io/badge/Status-styx-orange.svg) | The future is not clear. There are two possible paths from here - olympus or tartarus |
| ![Elders](https://img.shields.io/badge/Status-tartarus-red.svg) | Abandoned |

### Pandora

[![NuGet](https://img.shields.io/nuget/v/Pandora.svg)](https://www.nuget.org/packages/Pandora) ![Elders](https://img.shields.io/badge/Status-olympus-green.svg)

Pandora is a lightweight application configuration manager

- [Pandora](https://github.com/Elders/Pandora)
- [Pandora.Consul](https://github.com/Elders/Pandora.Consul) - configuration store for Pandora using Consul
- [Cli](https://github.com/Elders/Pandora.Cli)

### Domain modeling

[![NuGet](https://img.shields.io/nuget/v/Cronus.DomainModeling.svg)](https://www.nuget.org/packages/Cronus.DomainModeling) ![Elders](https://img.shields.io/badge/Status-olympus-green.svg)

Contracts for DDD/CQRS development

- [DomainModeling](https://github.com/Elders/Cronus.DomainModeling)

### Cronus

[![NuGet](https://img.shields.io/nuget/v/Cronus.svg)](https://www.nuget.org/packages/Cronus) ![Elders](https://img.shields.io/badge/Status-olympus-green.svg)

Cronus is a lightweight framework for dispatching and receiving messages between microservices with DDD/CQRS in mind

- [Cronus](https://github.com/Elders/Cronus)
- [Cronus.Transport.RabbitMQ](https://github.com/Elders/Cronus.Transport.RabbitMQ) - message transport implementation with RabbitMQ
- [Cronus.Persistence.Cassandra](https://github.com/Elders/Cronus.Persistence.Cassandra) - event store implementation with Cassandra
- [Cronus.Serialization.NewtonsoftJson](https://github.com/Elders/Cronus.Serialization.NewtonsoftJson) - message serialization using NewtonsoftJson
- [Cronus.Projections.Cassandra](https://github.com/Elders/Cronus.Projections.Cassandra) - projection store using Cassandra
- [Cronus.Hystrix](https://github.com/Elders/Cronus.Hystrix) - circuit breaker middleware for Cronus
- [Cronus.AtomicAction.Redis](https://github.com/Elders/Cronus.AtomicAction.Redis) - aggregate distributed lock with Redis
- [Cronus.Serialization.Proteus](https://github.com/Elders/Cronus.Serialization.Proteus) ![Elders](https://img.shields.io/badge/Status-styx-orange.svg) - this has been the prefered serialization with Cronus v2. However, there is a huge warm up performance hit with big projects which needs to be resolved. Despite this, it works really fast. The implementation has small protocol changes
- [Cronus.Projection.ElasticSearch](https://github.com/Elders/Cronus.Projection.ElasticSearch) ![Elders](https://img.shields.io/badge/Status-styx-orange.svg) - builds projections dynamically. Very useful for projects which just started and changes occur frequently. However, it must be switched to another persister such as Cassandra after the initial stages of the project

### Push notifications

[![NuGet](https://img.shields.io/nuget/v/PushNotifications.Api.svg)](https://www.nuget.org/packages/PushNotifications.Api) ![Elders](https://img.shields.io/badge/Status-olympus-green.svg)

Generic application for sending push notification using Firebase and Pushy

- [Pushnotifications](https://github.com/Elders/Pushnotifications)
- [.Net client](https://github.com/Elders/Pushnotifications.Client.Net)

### File storage

![Elders](https://img.shields.io/badge/Status-styx-orange.svg)

File storage abstraction over AmazonS3, Azure FS and the file system

- [FileStorage](https://github.com/Elders/FileStorage)
- [Azure](https://www.nuget.org/packages/FileStorage.Azure) [![NuGet](https://img.shields.io/nuget/v/FileStorage.Azure.svg)](https://www.nuget.org/packages/FileStorage.Azure)
- [AmazonS3](https://www.nuget.org/packages/FileStorage.AmazonS3) [![NuGet](https://img.shields.io/nuget/v/FileStorage.AmazonS3.svg)](https://www.nuget.org/packages/FileStorage.AmazonS3)
- [FileSystem](https://www.nuget.org/packages/FileStorage.FileSystem) [![NuGet](https://img.shields.io/nuget/v/FileStorage.FileSystem.svg)](https://www.nuget.org/packages/FileStorage.FileSystem)

### Nyx

[![NuGet](https://img.shields.io/nuget/v/Nyx.svg)](https://www.nuget.org/packages/Nyx) ![Elders](https://img.shields.io/badge/Status-olympus-green.svg)

Build script using FAKE which only purpose is to provide out of the box solution for most nasty tasks

- [Nyx](https://github.com/Elders/Nyx)

### be-a-better-dev

![Elders](https://img.shields.io/badge/Status-styx-orange.svg)

Tip, tricks, tutorials and presentations for modeling, DDD, best practices

- [be-a-better-dev](https://github.com/Elders/be-a-better-dev)

## Feedback

[![Slack](https://img.shields.io/badge/Elders-OSS-red.svg?longCache=true&style=flat&logo=slack)](https://join.slack.com/t/eldersoss/shared_invite/enQtNDExMjY5MTQzMjk5LTEyZTQwZTVkZjI2NzQ1ZGU3YzUyYzBiOTFmZTZhMGY3ZWEwZWQxZDVkOTM3NzdkZGJjN2Q2ZmQ4ZDg3YTUyMDQ)

If you have any questions, suggestions and feedback, please don't hesitate to contact us at contact@eldersoss.com 

Check out the contributing page to see the best places to log issues and start discussions.