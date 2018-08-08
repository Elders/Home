# Olympus 

###  These projects are stable and it will continue to be supported, maintained and will have further development

## List of projects that are ![Olympus](https://img.shields.io/badge/Status-olympus-green.svg) 

### Pandora 
[![Pandora NuGet](https://img.shields.io/nuget/v/Pandora.svg)](https://www.nuget.org/packages/Pandora)

- [Pandora](https://github.com/Elders/Pandora) - Pandora is a lightweight application configuration manager
- [Pandora.Consul](https://github.com/Elders/Pandora.Consul) - configuration store for Pandora using Consul
- [Cli](https://github.com/Elders/Pandora.Cli)

### Domain modeling
 [![Cronus.DomainModeling NuGet](https://img.shields.io/nuget/v/Cronus.DomainModeling.svg)](https://www.nuget.org/packages/Cronus.DomainModeling) 

- [DomainModeling](https://github.com/Elders/Cronus.DomainModeling) - Contracts for DDD/CQRS development

### Cronus 
[![Cronus NuGet](https://img.shields.io/nuget/v/Cronus.svg)](https://www.nuget.org/packages/Cronus)

- [Cronus](https://github.com/Elders/Cronus) - Cronus is a lightweight framework for dispatching and receiving messages between microservices with DDD/CQRS in mind
- [Cronus.Transport.RabbitMQ](https://github.com/Elders/Cronus.Transport.RabbitMQ) - message transport implementation with RabbitMQ
- [Cronus.Persistence.Cassandra](https://github.com/Elders/Cronus.Persistence.Cassandra) - event store implementation with Cassandra
- [Cronus.Serialization.NewtonsoftJson](https://github.com/Elders/Cronus.Serialization.NewtonsoftJson) - message serialization using NewtonsoftJson
- [Cronus.Projections.Cassandra](https://github.com/Elders/Cronus.Projections.Cassandra) - projection store using Cassandra
- [Cronus.Hystrix](https://github.com/Elders/Cronus.Hystrix) - circuit breaker middleware for Cronus
- [Cronus.AtomicAction.Redis](https://github.com/Elders/Cronus.AtomicAction.Redis) - aggregate distributed lock with Redis
- [Cronus.Serialization.Proteus](https://github.com/Elders/Cronus.Serialization.Proteus) ![styx](https://img.shields.io/badge/styx-orange.svg) - this has been the preferred serialization with Cronus v2. However, there is a huge warm up performance hit with big projects which needs to be resolved. Despite this, it works really fast. The implementation has small protocol changes
- [Cronus.Projection.ElasticSearch](https://github.com/Elders/Cronus.Projection.ElasticSearch) ![styx](https://img.shields.io/badge/styx-orange.svg) - builds projections dynamically. Very useful for projects which just started and changes occur frequently. However, it must be switched to another persister such as Cassandra after the initial stages of the project

### Push notifications
 [![PushNotifications.Api NuGet](https://img.shields.io/nuget/v/PushNotifications.Api.svg?label=PushNotifications.Api)](https://www.nuget.org/packages/PushNotifications.Api/) [![PushNotifications.WS.MSI NuGet](https://img.shields.io/nuget/v/PushNotifications.WS.MSI.svg?label=PushNotifications.WS.MSI)](https://www.nuget.org/packages/PushNotifications.WS.MSI/) [![PushNotifications.Client.Net NuGet](https://img.shields.io/nuget/v/PushNotifications.Client.Net.svg?label=PushNotifications.Client.Net)](https://www.nuget.org/packages/Pushnotifications.Client.Net/) 

- [Pushnotifications](https://github.com/Elders/Pushnotifications) - Generic application for sending push notification using Firebase and Pushy

### File storage
 [![FileStorage.Azure NuGet](https://img.shields.io/nuget/v/FileStorage.Azure.svg?label=FileStorage.Azure)](https://www.nuget.org/packages/FileStorage.Azure) [![FileStorage.AmazonS3 NuGet](https://img.shields.io/nuget/v/FileStorage.AmazonS3.svg?label=FileStorage.AmazonS3)](https://www.nuget.org/packages/FileStorage.AmazonS3)  [![FileStorage.FileSystem NuGet](https://img.shields.io/nuget/v/FileStorage.FileSystem.svg?label=FileStorage.FileSystem)](https://www.nuget.org/packages/FileStorage.FileSystem)

- [FileStorage](https://github.com/Elders/FileStorage) - File storage abstraction over AmazonS3, Azure FS and the file system

### Localizations
 [![Localizations NuGet](https://img.shields.io/nuget/v/Localizations.svg?label=Localizations)](https://www.nuget.org/packages/Localizations) [![Localizations.PhraseApp NuGet](https://img.shields.io/nuget/v/Localizations.PhraseApp.svg?label=Localizations.PhraseApp)](https://www.nuget.org/packages/Localizations.PhraseApp)

- [Localizations](https://github.com/Elders/Localizations) - Localization abstractions and PhraseApp implementation for .NET applications

### Nyx
 [![Nyx NuGet](https://img.shields.io/nuget/v/Nyx.svg)](https://www.nuget.org/packages/Nyx)

- [Nyx](https://github.com/Elders/Nyx) - Build script using FAKE which only purpose is to provide out of the box solution for most nasty tasks

### be-a-better-dev

- [be-a-better-dev](https://github.com/Elders/be-a-better-dev) - Tip, tricks, tutorials and presentations for modeling, DDD, best practices