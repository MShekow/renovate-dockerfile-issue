FROM --platform=$BUILDPLATFORM mcr.microsoft.com/dotnet/sdk:8.0.404@sha256:032381bcea86fa0a408af5df63a930f1ff5b03116c940a7cd744d3b648e66749 AS build
RUN echo foo

FROM mcr.microsoft.com/dotnet/aspnet:8.0.11-noble-chiseled-extra@sha256:6be902fba2fe81ec647687885f1fa93bed94a31307221188070a22553fd389de AS final
RUN echo bar
