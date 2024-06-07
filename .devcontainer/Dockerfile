FROM alpine
RUN apk add --no-cache nodejs npm dotnet6-sdk
RUN dotnet new --install AElf.ContractTemplates
RUN dotnet tool install --global aelf.deploy
RUN npm install -g aelf-command