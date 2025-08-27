# Project 3 - CLI Client

One-liner: Aplicación de línea de comandos en C# que consume la API de reservas (Project1) y permite consultar y gestionar datos desde terminal.  
Stack: .NET 8, HttpClient, System.CommandLine, JSON.

## Funcionalidades
- Autenticación contra la API de reservas (JWT).
- Listar reservas disponibles.
- Crear una nueva reserva.
- Consultar detalle de una reserva por ID.

## Requisitos
- .NET 8 SDK
- API de reservas (Project1) corriendo en `http://localhost:8080` o en Docker.

## Ejecutar local
1. Clona este repo y asegúrate de que Project1 está corriendo.
2. Restaura dependencias:
   ```bash
   dotnet restore
