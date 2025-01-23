1. Start linux environment with dotnet 9 sdk: `docker run -it -v .:/src mcr.microsoft.com/dotnet/sdk:9.0 bash`
2. Try to build project: `dotnet build -tl:off -v detailed /src/CompileTest`
