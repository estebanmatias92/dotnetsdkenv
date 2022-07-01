# https://hub.docker.com/_/microsoft-dotnet-sdk/
FROM mcr.microsoft.com/dotnet/sdk:6.0-bullseye-slim

ENV MYUSER="vscode"

RUN useradd -s /bin/bash -m $MYUSER
RUN groupadd docker && usermod -aG docker $MYUSER

USER $MYUSER

ENTRYPOINT ["sleep", "infinity"]