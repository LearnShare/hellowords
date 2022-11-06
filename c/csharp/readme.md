# C#

[C#](https://en.wikipedia.org/wiki/C_Sharp_(programming_language))

## Tools

+ Editor: [Visual Studio Code](https://code.visualstudio.com/)
  + plugin: [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
+ Compiler: [.NET](https://dotnet.microsoft.com/en-us/download)
  + Windows: 
    + [Working with C#](https://code.visualstudio.com/docs/languages/csharp)
    + [Tutorial: Create a .NET console application using Visual Studio Code](https://learn.microsoft.com/en-us/dotnet/core/tutorials/with-visual-studio-code?pivots=dotnet-6-0)

## Hello, World!

```c#
using System;

namespace HelloWorld {
  class Program {
    static void Main(string[] args) {
      Console.WriteLine("Hello, World!");
    }
  }
}
```

## Create Project

```bash
dotnet new console
```

## Run

```bash
dotnet run
```

## Build and Run

```bash
# 1. publish
dotnet publish --configuration Release

# 2. cd to release dir
cd bin/Release/net6.0/

# 3. run
csharp
```
