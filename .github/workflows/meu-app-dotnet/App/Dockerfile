# Use a imagem oficial do .NET como base
FROM mcr.microsoft.com/dotnet/sdk:8.0

# Crie um diretório de trabalho dentro do container
WORKDIR /app

# Copie o projeto .NET para o container
COPY . .

# Compile o aplicativo
RUN dotnet build -c Release

# Execute o aplicativo
CMD ["dotnet", "run"]
