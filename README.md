# Semantic Kernel Simple Plugin

A simple console application demonstrating the use of Microsoft's Semantic Kernel with Azure OpenAI.

## Prerequisites

- .NET 9.0
- Azure OpenAI account and API key
- Visual Studio 2022 or VS Code

## Setup

1. Clone the repository
2. Set up user secrets for the application:
   ```bash
   dotnet user-secrets init
   dotnet user-secrets set "ModelName" "your-model-name"
   dotnet user-secrets set "BaseUrl" "your-azure-openai-endpoint"
   dotnet user-secrets set "ApiKey" "your-api-key"
   ```
3. Build and run the application:
   ```bash
   dotnet build
   dotnet run
   ```

## Features

- Integration with Open AI or Azure OpenAI
- Chat completion functionality
- Custom plugin system
- Conversation history tracking

## License

MIT
