# C# Build Tools -Development Workflow & Environment Setup

To be able to write and run code, we must install the right software on our machine.

By following this guide you will have a computer that is ready for coding in C#.

Please follow the instructions that are specific to your operating system.

## Objectives

- Install Visual Studio and other relevant software
- Experience C# development in Visual Studio AND Visual Studio Code
- Create / Open / Build / Execute / Debug New/Existing Projects
- Understand single, multi & XML comments
- Understand solution, project layout
- Nuget package manager

## Development Environment Setup

### Visual Studio Installation

[Windows Setup Instructions](windows-setup-instructions.md)

[macOS Setup Instructions](mac-setup-instructions.md)

### Other software installation

Please make sure to install:

- git (gitbash on windows) and setup github ssh keys
- Visual Studio Code (with the C# extension)
- nvm & nodejs (and ensure these can be called / launched from your terminal)

Instructions to install the software can be found in Boolean's [development environment guide](https://github.com/boolean-uk/developer-environment-setup).

### Verifying the installation is working

In your terminal (gitbash or powershell for Windows and just your Terminal.app on macOS):

- check that `dotnet --version` command works
- check that `nvm -v && node -v` give a valid output
- check that `ssh -T git@github.com` gives a working output
