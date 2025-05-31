✅ 1. Voraussetzungen installieren
🔧 1.1 .NET SDK installieren

    Gehe auf: https://dotnet.microsoft.com/download

    Lade das aktuelle .NET SDK (nicht Runtime!) herunter und installiere es (.NET 8).


    Nach der Installation:
    $dotnet --version

🔧 1.2 VSCode + Erweiterungen
C# Dev Kit (empfohlen)


🛠️ 2. Neues Blazor WebAssembly Projekt erstellen
dotnet new blazorwasm -n RechnerBlazor
cd RechnerBlazor
code .

🧱 3. Aufbau eines Blazor WebAssembly Projekts
RechnerBlazor/
├── Program.cs
├── wwwroot/
├── Pages/
│   └── Index.razor ← hier bauen wir den Rechner ein
├── Components/
|   └── RechnerForm.razor
|   └── VerlaufListe.razor
└── App.razor


▶️ 5. Projekt starten (in Terminal)
Dann wird Blazor den lokalen Webserver starten, z. B.:
Now listening on: https://localhost:7213
Öffne die URL im Browser – dein Rechner ist online! 🎉


📦 Paket installieren
dotnet add package Blazored.LocalStorage

