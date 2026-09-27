# SecureDesk API

API REST desarrollada en C# con ASP.NET Core para gestionar tickets de soporte e incidentes internos.

El proyecto está pensado como práctica de backend, aplicando una estructura simple y conceptos básicos de una API real.

## Funcionalidades actuales

- Listar tickets
- Buscar ticket por ID
- Crear tickets
- Actualizar tickets
- Manejo de prioridades y estados
- Respuestas HTTP básicas

## Endpoints

```text
GET    /api/tickets
GET    /api/tickets/{id}
POST   /api/tickets
PATCH  /api/tickets/{id}
