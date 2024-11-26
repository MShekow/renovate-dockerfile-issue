FROM --platform=$BUILDPLATFORM mcr.microsoft.com/dotnet/sdk:8.0.403@sha256:b38da1961b1358940c634560747e09ef8047234e66c71033f19ac2e777f60240 AS build
RUN echo foo

FROM mcr.microsoft.com/dotnet/aspnet:8.0.10-noble-chiseled-extra@sha256:814d813ef87531c6f9d1f779ce40680c9cc499412db527519e62870be7e1dc4f AS final
RUN echo bar
