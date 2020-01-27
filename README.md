# Windows 10 Developer Machine Setup

This is the script for Luís Dias (forked from https://github.com/EdiWang/EnvSetup) to setup a new dev box. You can modify the scripts to fit your own requirements.

## Prerequisites

- A clean install of Windows 10 Enterprise v1909 en-us.

> This script has not been tested on other version of Windows, please be careful if you are using it on other Windows versions.

## How to Use

Download latest script here: https://go.edi.wang/aka/envsetup

### Optional

Import "Add_PS1_Run_as_administrator.reg" to your registry to enable context menu on the powershell files to run as Administrator.

### Run Install.ps1 as Administrator

- Set a New Computer Name
- Disable Sleep on AC Power
- Add 'This PC' Desktop Icon (need refresh desktop)
- Remove "Microsoft Edge" desktop shortcut icon
- Enable Developer Mode (for UWP Development)
- Enable Remote Desktop
- Install IIS
  - ASP.NET 4.8
  - Dynamic and Static Compression
  - Basic Authentication
  - Windows Authentication
  - Server Side Includes
  - WebSockets
- Install Chocolate for Windows
    - 7-Zip
    - Microsoft Edge Chromium-Based
    - Google Chrome
    - Firefox
    - .NET Core 3.1 SDK
    - Visual Studio 2019 Enterprise
    - Microsoft Teams
    - SysInternals
    - Lightshot
    - FileZilla
    - TeamViewer
    - Notepad++
    - Visual Studio Code
        - C-Sharp
        - C# Extensions
        - Icons
        - Angular 8 Snippets
        - Angular Files
        - Angular Language Service
        - Angular Snippets (Version 8)
        - Bracket Pair Colorizer
        - Community Material Theme
        - Debugger for Chrome
        - Docker
        - Git Merger
        - GitLens — Git supercharged
        - HTML Snippets
        - Indenticator
        - Kubernetes
        - Material Icon Theme
        - Material Theme
        - Material Theme Icons
        - NuGet Package Manager
        - Path Intellisense
        - PowerShell
        - Prettier - Code formatter
        - TypeScript Hero
        - YAML
    - DotPeek
    - LINQPad
    - Fiddler
    - Git
    - GitHub for Windows
    - FFMpeg
    - CURL
    - WGet
    - OpenSSL
    - Beyond Compare
    - Node.Js
    - Slack
    - Bitwarden
    - Putty
    - Spotify
    - SQL Server Management Studio
    - FortiClient VPN
    - Postman
    - Redis
    - RabbitMQ
    - Docker
    - MongoDB
    - Redis
    - Postgres
    - PgAdmin
- Remove a few pre-installed UWP applications
    - Messaging
    - People
    - Feedback Hub
    - Your Phone
