# Herald
> Author [**Thiago Fialho**](https://br.linkedin.com/in/thiago-fialho-139ab116)



## Overview

Templates and [building blocks](https://medium.com/@tcfialho/building-blocks-fffb192d8389) to make faster develop .NET Core system.

## Installation

All herald packages publish in [nuget.org](https://www.nuget.org/packages?q=id%3Aherald+owner%3Atcfialho).

## Usage

## Templates (scaffolds)

Herald has templates for make easier create new projects.

- WebAPI
    + [Herald.Template.WebApi](https://github.com/tcfialho/Herald.Template.WebApi): Creates a new WebAPI project.
        > [![Nuget](https://buildstats.info/nuget/Herald.Template.WebApi)](https://www.nuget.org/packages/Herald.Template.WebApi)

- Worker
    + [Herald.Template.Worker](https://github.com/tcfialho/Herald.Template.Worker): Creates a new Worker project.
        > [![Nuget](https://buildstats.info/nuget/Herald.Template.Worker)](https://www.nuget.org/packages/Herald.Template.Worker)

- gRPC
    + [Herald.Template.Grpc](https://github.com/tcfialho/Herald.Template.Grpc): Creates a new gRPC project.
        > [![Nuget](https://buildstats.info/nuget/Herald.Template.Grpc)](https://www.nuget.org/packages/Herald.Template.Grpc)

## Building Blocks

Herald has different packages/libraries, each lib handle a 3rd library or focus utility for a field.

- Web
    + [Herald.Web.Swagger](https://github.com/tcfialho/Herald.Web.Swagger): Support add [Swagger](https://github.com/domaindrivendev/Swashbuckle) api documentation  automatically with a  single line of code.
        > [![Nuget](https://buildstats.info/nuget/Herald.Web.Swagger)](https://www.nuget.org/packages/Herald.Web.Swagger)
    + [Herald.ModelBinder](https://github.com/tcfialho/Herald.ModelBinder): Add support for controllers receive data throught path and body or path and querystring with same class.
        > [![Nuget](https://buildstats.info/nuget/Herald.ModelBinder)](https://www.nuget.org/packages/Herald.ModelBinder)
    + [Herald.JsonSnakeCaseNamingPolicy](https://github.com/tcfialho/Herald.JsonSnakeCaseNamingPolicy): Add support for snake case namming policy.
        > [![Nuget](https://buildstats.info/nuget/Herald.JsonSnakeCaseNamingPolicy)](https://www.nuget.org/packages/Herald.JsonSnakeCaseNamingPolicy)
    + [Herald.MediatR.Retry](https://github.com/tcfialho/Herald.MediatR.Retry): Add support for snake case namming policy.
        > [![Nuget](https://buildstats.info/nuget/Herald.MediatR.Retry)](https://www.nuget.org/packages/Herald.MediatR.Retry)
             
- Message Queues
    + [Herald.MessageQueue](https://github.com/tcfialho/Herald.MessageQueue): Working with different types of message brokers using a simple "foreach" abstraction..
        > [![Nuget](https://buildstats.info/nuget/Herald.MessageQueue)](https://github.com/tcfialho/Herald.MessageQueue)
    + [Herald.MessageQueue.HealthCheck](https://github.com/tcfialho/Herald.MessageQueue.HealthCheck): Health check support for different types of message brokers.
        > [![Nuget](https://buildstats.info/nuget/Herald.MessageQueue.HealthCheck)](https://github.com/tcfialho/Herald.MessageQueue.HealthCheck)

- Notification
    + [Herald.Notification](https://github.com/tcfialho/Herald.Notification): Extend of [Amazon SQS](https://aws.amazon.com/pt/sqs/), easier to setup and send e-mails, SMS or push notifications through SQS and HTTP Apis. (WIP)
        > [![Nuget](https://buildstats.info/nuget/Herald.Notification)](https://github.com/tcfialho/Herald.Notification)

- Observability
    + [Herald.Observability.Jaeger](https://github.com/tcfialho/Herald.Observability.Jaeger): Support add trace to the [Jaeger](https://github.com/jaegertracing/jaeger-client-csharp) automatically.
        > [![Nuget](https://buildstats.info/nuget/Herald.Observability.Jaeger)](https://buildstats.info/nuget/Herald.Observability.Jaeger)

- Database
    + [Herald.EntityFramework](https://github.com/tcfialho/Herald.EntityFramework): Easy repository pattern using entity framework.
        > [![Nuget](https://buildstats.info/nuget/Herald.EntityFramework)](https://buildstats.info/nuget/Herald.EntityFramework)

- Utilities
    + [Herald.Result](https://github.com/tcfialho/Herald.Result): Implements result pattern for return of mediatr requests.
        > [![Nuget](https://buildstats.info/nuget/Herald.Result)](https://buildstats.info/nuget/Herald.Result)

## Samples

Please access usage link from each package to explore the examples.

## License
Herald is licensed under the [MIT License](LICENSE).
