# e-commerce-fullstack
Making a simple website that uses react typescript, redux and c#

## Getting Started
1. Setting up the project with api
   ```
   dotnet new sln
   dotnet new webapi -o API
   dotnet sln add API
   ```
2. Adding extentions
   - C#
   - Material Icon Theme
   - NuGet Gallary
   - SQLite  (for testing)
   - Auto Rename Tag
3. In command palette, we open `>nuget gallery` to install the following packages:
   ```
   Microsoft.EntityFrameworkCore.Sqlite
   Microsoft.EntityFrameworkCore.Design
   ```
4. Creating a DbContext class + constructor
5. Install nuget dotnet-ef: `dotnet tool --global dotnet-ef --version 7.0.3`