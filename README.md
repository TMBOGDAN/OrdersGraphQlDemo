# OrdersGraphQlDemo

Proiect demonstrativ ASP.NET Core pe .NET 10, cu pachetele HotChocolate pentru GraphQL.

În starea curentă, aplicația expune `GET /`, care returnează `Hello World!`. Endpoint-ul GraphQL nu este încă implementat.

## Cerințe

- .NET SDK `10.0.401`, conform fișierului `global.json`.

## Rulare locală

Din folderul proiectului:

```sh
dotnet restore OrdersGraphQlDemo.slnx
dotnet build OrdersGraphQlDemo.slnx
dotnet run --project OrdersGraphQlDemo.API/GraphQlDema.API.csproj --launch-profile http
```

Aplicația este disponibilă la <http://localhost:5077/>.

## Structură

- `OrdersGraphQlDemo.API/` — aplicația ASP.NET Core.
- `Directory.Packages.props` — versiunile pachetelor NuGet, administrate centralizat.
- `OrdersGraphQlDemo.slnx` — soluția proiectului.
