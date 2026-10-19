# OrdersGraphQlDemo

A demo ASP.NET Core project built with .NET 10, using HotChocolate packages for GraphQL.

Currently, the application exposes a `GET /` endpoint that returns `Hello World!`. The GraphQL endpoint has not been implemented yet.

## Requirements

- .NET SDK `10.0.401`, as specified in the `global.json` file.

## Running Locally

From the project's root directory, run:

```sh
dotnet restore OrdersGraphQlDemo.slnx
dotnet build OrdersGraphQlDemo.slnx
dotnet run --project OrdersGraphQlDemo.API/GraphQlDema.API.csproj --launch-profile http
```

The application will be available at <http://localhost:5077/>.

## Project Structure

- `OrdersGraphQlDemo.API/` — ASP.NET Core application.
- `Directory.Packages.props` — centrally managed NuGet package versions.
- `OrdersGraphQlDemo.slnx` — .NET solution file.
