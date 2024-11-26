FROM --platform=$BUILDPLATFORM mcr.microsoft.com/dotnet/sdk:8.0.404@sha256:f91f9181d68b5ed2c8dea199dbbd2f6d172e60bdc43f8a67878b1ad140cf8d6b AS build
RUN echo foo

FROM mcr.microsoft.com/dotnet/aspnet:8.0.11-noble-chiseled-extra@sha256:6be902fba2fe81ec647687885f1fa93bed94a31307221188070a22553fd389de AS final
RUN echo bar
