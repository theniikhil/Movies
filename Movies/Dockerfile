ARG REPO=mcr.microsoft.com/dotnet/framework/runtime
FROM $REPO:4.6.2-windowsservercore-ltsc2016
ARG source
WORKDIR /inetpub/wwwroot
COPY ${source:-obj/Release/} .
