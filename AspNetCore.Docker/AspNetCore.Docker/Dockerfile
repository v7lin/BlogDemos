# --- build ---

FROM mcr.microsoft.com/dotnet/core/sdk:2.1 as build

# --- prod ---

FROM microsoft/dotnet:2.1-aspnetcore-runtime
WORKDIR /app
COPY . .
EXPOSE 80
ENTRYPOINT ["dotnet", "AspNetCore.Docker.dll"]
