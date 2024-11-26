FROM --platform=$BUILDPLATFORM mcr.microsoft.com/dotnet/sdk:9.0.100@sha256:7d24e90a392e88eb56093e4eb325ff883ad609382a55d42f17fd557b997022ca AS build
RUN echo foo

FROM mcr.microsoft.com/dotnet/aspnet:9.0.0-noble-chiseled-extra@sha256:e7662ee9385478d8be85fd99fbb04f10f3a10f837c5df53d8b3abd5b5ad09738 AS final
RUN echo bar
