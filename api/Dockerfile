FROM mcr.microsoft.com/dotnet/core/aspnet:2.2.4

WORKDIR /app
COPY bin/Debug/netcoreapp2.2/publish .

ENTRYPOINT [ "dotnet", "api.dll" ]