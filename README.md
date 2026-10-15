# Szkielet projektu — poprawa kolokwium

Projekt startowy ASP.NET Core do ćwiczeń przed poprawą kolokwium APBD. Zawiera Program.cs, konfigurację i zależność SqlClient; nie zawiera kontrolerów ani gotowej logiki zadania.

**Kategoria:** szkielety do kolokwiów · **Przedmiot:** APBD · **Rok akademicki:** 2024/2025

## Technologie

C#, .NET 9, ASP.NET Core, Microsoft.Data.SqlClient.

## Gdzie jest kod

- [Plik projektu](./KolokwiumPoprawa/KolokwiumPoprawa/KolokwiumPoprawa.csproj): `KolokwiumPoprawa/KolokwiumPoprawa/KolokwiumPoprawa.csproj`.
- Kod aplikacji znajduje się w katalogu tego projektu.

## Uruchomienie

Wymagany jest odpowiedni .NET SDK dla projektu (.NET 9); jeśli repozytorium zawiera `global.json`, uwzględnij również wskazaną w nim wersję SDK.

Z katalogu głównego repozytorium:

```sh
dotnet restore "KolokwiumPoprawa/KolokwiumPoprawa/KolokwiumPoprawa.csproj"
dotnet run --project "KolokwiumPoprawa/KolokwiumPoprawa/KolokwiumPoprawa.csproj"
```

## Nawigacja

[Wszystkie projekty i materiały ze studiów](https://github.com/Michlean30495)
