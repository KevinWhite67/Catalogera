# Catálogo de Productos

<p align="center">
  <img src="https://img.shields.io/badge/Proyecto-Catálogo%20de%20Productos-000000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

---

## Descripción

Este proyecto es una aplicación desarrollada en **.NET** que permite gestionar un catálogo de productos conectado a **Supabase** como base de datos en la nube. Incluye operaciones de creación, lectura, actualización y eliminación (CRUD), permitiendo administrar productos de forma eficiente.

El sistema está diseñado como una API consumida y probada mediante **Postman**, facilitando la validación de endpoints y el flujo de datos.

---

## Problemática

Muchos sistemas de gestión de productos no cuentan con una estructura centralizada, lo que dificulta la administración de información como precios, descripciones, stock y categorías.

Este proyecto surge para implementar una solución simple, escalable y basada en API para la gestión de productos.

---

## Solución Propuesta

Se desarrolló una API en .NET que permite:

- Registro de productos
- Consulta de catálogo completo
- Actualización de información de productos
- Eliminación de productos
- Conexión en tiempo real con Supabase

La API puede ser consumida desde cualquier cliente (web, móvil o herramientas como Postman).

---

## Arquitectura

El sistema está basado en una arquitectura cliente-servidor:

- Backend desarrollado en **.NET (ASP.NET Core Web API)**
- Base de datos en **Supabase (PostgreSQL)**
- Consumo y pruebas de endpoints mediante **Postman**
- Comunicación mediante API REST

---

## Desarrollo del Proyecto

El desarrollo inició con la definición del modelo de datos para los productos y la estructura de la base de datos en Supabase.

Posteriormente se implementó la API en .NET, creando los controladores necesarios para manejar las operaciones CRUD.

Se realizaron pruebas de cada endpoint utilizando Postman para validar la correcta comunicación con la base de datos.

Finalmente se ajustaron validaciones y respuestas para asegurar consistencia en los datos.

---

## Tecnologías Utilizadas

### Backend
- .NET (ASP.NET Core Web API)
- C#

### Base de Datos
- Supabase (PostgreSQL)

### Herramientas
- Postman
- Visual Studio
- Git
- GitHub

---

## Resultados Obtenidos

Se obtuvo una API funcional capaz de gestionar un catálogo de productos completo con operaciones CRUD, conectada a una base de datos en la nube.

El sistema permite una administración eficiente y escalable de productos desde cualquier cliente.

---

## Impacto

Este proyecto demuestra la implementación de una arquitectura moderna basada en API REST, facilitando la integración con aplicaciones web y móviles.

Fortalece conocimientos en desarrollo backend con .NET, manejo de bases de datos en la nube y pruebas de APIs con Postman.

---

## Estado del Proyecto

En desarrollo
