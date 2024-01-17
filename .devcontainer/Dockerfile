FROM mcr.microsoft.com/dotnet/sdk:6.0

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
       unzip \
       nano \
       && apt-get clean \
       && rm -rf /var/lib/apt/lists/*

# Ajoutez d'autres installations ou configurations si nécessaires
