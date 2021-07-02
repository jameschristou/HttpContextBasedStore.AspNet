# RequestContextBasedStore for ASP.NET Core
This repository provides an example of how to implement a request context based store for ASP.NET Core. RequestContextBasedStore is useful in situations where you need to make expensively retrieved data available in multiple places within a single Http request. Rather than retrieving the data multiple times, it can be retrieved once, stored on the HttpContext, and then subsequently reused.

## Usage
Put something here

## TestApp
Put something here

### Build
To build this application just run `dotnet build RequestContextBasedStore.AspNetCore.csproj` at the command line.

### Run
To run this application just run `dotnet run RequestContextBasedStore.AspNetCore.csproj` at the command line.