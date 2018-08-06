# Home

The Home repository is the starting point for people to learn about Elders' projects. This repository contains pointers to the various GitHub repositories developed and maintained by Elders.

Projects in this organization have adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact opencode@microsoft.com with any additional questions or comments.

## Legend

| Name | Description |
|------|-------------|
| ![Olympus](https://img.shields.io/badge/Status-olympus-green.svg) | It is stable and it will continue to be supported, maintenance and future development |
| ![Styx](https://img.shields.io/badge/Status-styx-orange.svg) | The future is not clear. There are two possible paths from here - olympus or tartarus |
| ![Tartarus](https://img.shields.io/badge/Status-tartarus-red.svg) | Abandoned |

### Pandora

[![Pandora NuGet](https://img.shields.io/nuget/v/Pandora.svg)](https://www.nuget.org/packages/Pandora) ![olympus](https://img.shields.io/badge/olympus-green.svg)

Pandora is a lightweight application configuration manager

- [Pandora](https://github.com/Elders/Pandora)
- [Pandora.Consul](https://github.com/Elders/Pandora.Consul) - configuration store for Pandora using Consul
- [Cli](https://github.com/Elders/Pandora.Cli)

### Domain modeling

[![Cronus.DomainModeling NuGet](https://img.shields.io/nuget/v/Cronus.DomainModeling.svg)](https://www.nuget.org/packages/Cronus.DomainModeling) ![olympus](https://img.shields.io/badge/olympus-green.svg)

Contracts for DDD/CQRS development

- [DomainModeling](https://github.com/Elders/Cronus.DomainModeling)

### Cronus

[![Cronus NuGet](https://img.shields.io/nuget/v/Cronus.svg)](https://www.nuget.org/packages/Cronus) ![olympus](https://img.shields.io/badge/olympus-green.svg)

Cronus is a lightweight framework for dispatching and receiving messages between microservices with DDD/CQRS in mind

- [Cronus](https://github.com/Elders/Cronus)
- [Cronus.Transport.RabbitMQ](https://github.com/Elders/Cronus.Transport.RabbitMQ) - message transport implementation with RabbitMQ
- [Cronus.Persistence.Cassandra](https://github.com/Elders/Cronus.Persistence.Cassandra) - event store implementation with Cassandra
- [Cronus.Serialization.NewtonsoftJson](https://github.com/Elders/Cronus.Serialization.NewtonsoftJson) - message serialization using NewtonsoftJson
- [Cronus.Projections.Cassandra](https://github.com/Elders/Cronus.Projections.Cassandra) - projection store using Cassandra
- [Cronus.Hystrix](https://github.com/Elders/Cronus.Hystrix) - circuit breaker middleware for Cronus
- [Cronus.AtomicAction.Redis](https://github.com/Elders/Cronus.AtomicAction.Redis) - aggregate distributed lock with Redis
- [Cronus.Serialization.Proteus](https://github.com/Elders/Cronus.Serialization.Proteus) ![styx](https://img.shields.io/badge/styx-orange.svg) - this has been the preferred serialization with Cronus v2. However, there is a huge warm up performance hit with big projects which needs to be resolved. Despite this, it works really fast. The implementation has small protocol changes
- [Cronus.Projection.ElasticSearch](https://github.com/Elders/Cronus.Projection.ElasticSearch) ![styx](https://img.shields.io/badge/styx-orange.svg) - builds projections dynamically. Very useful for projects which just started and changes occur frequently. However, it must be switched to another persister such as Cassandra after the initial stages of the project

### Push notifications

![olympus](https://img.shields.io/badge/olympus-green.svg)

Generic application for sending push notification using Firebase and Pushy

- [Pushnotifications](https://github.com/Elders/Pushnotifications)
- [![PushNotifications.Api NuGet](https://img.shields.io/nuget/v/PushNotifications.Api.svg?label=PushNotifications.Api)](https://www.nuget.org/packages/PushNotifications.Api/)
- [![PushNotifications.WS.MSI NuGet](https://img.shields.io/nuget/v/PushNotifications.WS.MSI.svg?label=PushNotifications.WS.MSI)](https://www.nuget.org/packages/PushNotifications.WS.MSI/)
- [![PushNotifications.Client.Net NuGet](https://img.shields.io/nuget/v/PushNotifications.Client.Net.svg?label=PushNotifications.Client.Net)](https://www.nuget.org/packages/Pushnotifications.Client.Net/)

### File storage

File storage abstraction over AmazonS3, Azure FS and the file system

- [FileStorage](https://github.com/Elders/FileStorage)
- [![FileStorage.Azure NuGet](https://img.shields.io/nuget/v/FileStorage.Azure.svg?label=FileStorage.Azure)](https://www.nuget.org/packages/FileStorage.Azure) ![styx](https://img.shields.io/badge/styx-orange.svg)
- [![FileStorage.AmazonS3 NuGet](https://img.shields.io/nuget/v/FileStorage.AmazonS3.svg?label=FileStorage.AmazonS3)](https://www.nuget.org/packages/FileStorage.AmazonS3) ![styx](https://img.shields.io/badge/styx-orange.svg)
- [![FileStorage.FileSystem NuGet](https://img.shields.io/nuget/v/FileStorage.FileSystem.svg?label=FileStorage.FileSystem)](https://www.nuget.org/packages/FileStorage.FileSystem) ![styx](https://img.shields.io/badge/styx-orange.svg)

### Nyx

[![Nyx NuGet](https://img.shields.io/nuget/v/Nyx.svg)](https://www.nuget.org/packages/Nyx) ![olympus](https://img.shields.io/badge/olympus-green.svg)

Build script using FAKE which only purpose is to provide out of the box solution for most nasty tasks

- [Nyx](https://github.com/Elders/Nyx)

### be-a-better-dev

![styx](https://img.shields.io/badge/styx-orange.svg)

Tip, tricks, tutorials and presentations for modeling, DDD, best practices

- [be-a-better-dev](https://github.com/Elders/be-a-better-dev)

## Feedback

[![Slack](https://img.shields.io/badge/Elders-OSS-black.svg?logo=slack&colorA=black)](https://join.slack.com/t/eldersoss/shared_invite/enQtNDExMjY5MTQzMjk5LTEyZTQwZTVkZjI2NzQ1ZGU3YzUyYzBiOTFmZTZhMGY3ZWEwZWQxZDVkOTM3NzdkZGJjN2Q2ZmQ4ZDg3YTUyMDQ)

If you have any questions, suggestions and feedback, please don't hesitate to contact us at contact@eldersoss.com

Check out the contributing page to see the best places to log issues and start discussions.