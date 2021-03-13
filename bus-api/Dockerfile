#Depending on the operating system of the host machines(s) that will build or run the containers, the image specified in the FROM statement may need to be changed.
#For more information, please see https://aka.ms/containercompat

FROM mcr.microsoft.com/dotnet/core/sdk:2.1-stretch AS base
WORKDIR /app

COPY . /app/.

ENTRYPOINT ["dotnet", "Undani.ServerBus.Api.dll"]