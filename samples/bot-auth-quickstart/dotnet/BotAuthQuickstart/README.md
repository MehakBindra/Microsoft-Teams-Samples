# Bot Auth Quickstart - .NET (C#)

A Microsoft Teams bot with SSO authentication and Microsoft Graph integration.

## Features

- **SSO Authentication** - Single Sign-On with Microsoft Entra ID
- **Graph Integration** - Fetch user profile via Microsoft Graph


## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)
- [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) with [Microsoft 365 Agents Toolkit](https://learn.microsoft.com/microsoftteams/platform/toolkit/toolkit-v4/install-agents-toolkit-vs)

## Run the sample

### Using Microsoft 365 Agents Toolkit (Recommended)

1. Open the project in Visual Studio
2. Right-click on the **M365Agent** folder and select **Microsoft 365 Agents Toolkit**
3. Sign in with your Microsoft 365 account
4. Press `F5` to start debugging

### Using Command Line

1. Navigate to this directory:

```sh
cd dotnet/BotAuthQuickstart
```

2. Run the bot:

```bash
dotnet run
```

The bot will start listening on `http://localhost:5130`.

## Further Reading

See the [root README](../../README.md) for detailed setup and configuration instructions.

