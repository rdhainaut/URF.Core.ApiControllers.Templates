# URF.Core.ApiControllers.Templates

Customizable Razor templates for ASP.NET Core Web API controllers

## Prerequisites

Install package and add ASP.NET Web API Templates:
- .NET SDK 2.0 or greater

Use the template to generate Web API controllers:
- Visual Studio 2017

Run and/or re-create the sample:
- SQL Server LocalDb
- SQL Server Management Studio

## Installation

To install the templates package open a terminal and run:
- For the latest _pre-release_ version:

    ```
    dotnet new -i "AspNetCore.ApiControllers.Templates::1.0.0-*"
    ```

- For the latest _stable_ version:

    ```
    dotnet new -i "AspNetCore.ApiControllers.Templates::*"
    ```

To set back your dotnet new list to "factory defaults" use this command:

    ```
    dotnet new --debug:reinit
    ```

## Usage

To install templates in an ASP.NET Core Web API project, open a terminal at the project root and run:

    ```
    dotnet new webapi
    ```

