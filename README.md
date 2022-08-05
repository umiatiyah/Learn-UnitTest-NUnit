# Learn Unit testing C# with NUnit and .NET Core

### Step
- create solution (sln)
    ```sh
    dotnet new sln
    ```
- create your project 
    ```sh
    dotnet new classlib
    ```
- add your project to sln
    ```sh
    dotnet sln add PrimeService/PrimeService.csproj
    ```
- create your project test (with NUnit)
    ```sh
    dotnet new nunit
    ```
- reference your project in tests project (run command in tests project)
    ```sh
    dotnet add reference ../PrimeService/PrimeService.csproj 
    ```
- add your tests project to sln
    ```sh
    dotnet sln add ./PrimeService.Tests/PrimeService.Tests.csproj
    ```

### Source

- Microsoft https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-nunit