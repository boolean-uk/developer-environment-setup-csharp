# Development Environment Setup

To be able to write and run code, we must install the right software on our machine. By following this guide you will have a computer that is ready for coding in C#. Please follow the instructions that are specific to your operating system.

## Objectives


- Install Visual Studio 
- Create / Open / Build / Execute / Debug New/Existing Projects
- Understand single, multi & xml comments
- Understand solution, project layout
- Nuget package manager
- Github Integration
- Experience C# development in Visual Studio AND Visual Studio Code


## Setup Guide

[Windows Setup Instructions](windows-setup-instructions.md)

[macOS Setup Instructions](macOS-setup-instructions.md)


## Install Visual Studio

## Create / Open / Build / Execute / Debug New/Existing Projects
Lets start by creating a C# application:

If you are on Windows Open the Command Prompt and follow the steps in the image below:
![](./images/dotnet_new.JPG)


In NOTEPAD change the code so it reads:


// See https://aka.ms/new-console-template for more information

Console.WriteLine("What is your name?");

string name = Console.ReadLine();

Console.WriteLine($"Hello {name}, World!");


Now see if the code builds.  You should get a  ![#008000](Build succeeded. `#08000` message
if it doesn't build you can 
go back into notepad to check 
the code 

run it                            dotnet run

thats it. 




