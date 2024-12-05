FROM --platform=$BUILDPLATFORM mcr.microsoft.com/dotnet/sdk:9.0.101@sha256:fe8ceeca5ee197deba95419e3b85c32744970b730ae11645e13f1cb74a848d98 AS build
RUN echo foo

FROM mcr.microsoft.com/dotnet/aspnet:9.0.0-noble-chiseled-extra@sha256:e7662ee9385478d8be85fd99fbb04f10f3a10f837c5df53d8b3abd5b5ad09738 AS final
RUN echo bar
