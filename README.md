# Couchbase Sample Application

## Prerequisites

[.NET SDK](https://dotnet.microsoft.com/download) (2.1 or greater) - Note .NET Core is cross-platform that can run on Windows, MacOS and Linux.

## Building

First, you need to get a copy of the code. The easiest way to to do that is to clone the git repository.

```bash
git clone https://github.com/couchbaselabs/try-cb-dotnet.git
```

NOTE: The SDK 3.0 sample app is currently in it's own branch, so you need to switch over to that.

```bash
git checkout sdk-3.0
```

You can build and run the application using the `dotnet` CLI as follows. This will start the application, which can be seen at http://localhost:5000.

```bash
dotnet run --project try-cb-dotnet/try-cb-dotnet.csproj
```

Alternatively, if you're using [VSCode](https://code.visualstudio.com/), there is a debug task configured which will both build and run the sample application.
