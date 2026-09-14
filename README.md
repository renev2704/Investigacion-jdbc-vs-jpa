# Comparación del rendimiento web y Android al consumir una API REST para un sistema de inventario con SQL Server

Perfil de investigación — Entrega 1 de 4

## Integrantes

| Nombre | Usuario GitHub |
|---|---|
| Nombre Apellido | [@usuario1](https://github.com/usuario1) |
| Nombre Apellido | [@usuario2](https://github.com/usuario2) |
| Nombre Apellido | [@usuario3](https://github.com/usuario3) |
| Nombre Apellido | [@usuario4](https://github.com/usuario4) |
| Nombre Apellido | [@usuario5](https://github.com/usuario5) |
| Nombre Apellido | [@usuario6](https://github.com/usuario6) |

## Problema

En un sistema de inventario para negocios de productos tecnológicos, tanto el cliente web como el cliente Android consumen los mismos endpoints REST. Sin embargo, no se sabe cuál ofrece mejor rendimiento en tiempo de respuesta y consumo de memoria, ni cómo varía según el volumen de datos. La mayoría de comparaciones disponibles se enfocan solo en el backend y no reportan métricas comparables entre web y Android.

## Pregunta de investigación

**Principal:**

> ¿Qué diferencias de tiempo de respuesta y consumo de memoria existen entre un cliente web y un cliente Android al consumir una API REST de un sistema de inventario con SQL Server, al ejecutar operaciones CRUD sobre conjuntos de 1.000, 10.000 y 100.000 registros, considerando el promedio de 10 ejecuciones por combinación?

**Secundarias:**

1. ¿Cómo varía la diferencia entre web y Android según el tipo de operación?
2. ¿Qué configuración del cliente (caché, compresión, paginación) reduce la brecha?
3. ¿A partir de qué volumen la diferencia se vuelve significativa?

## Objetivos

**General:**

Comparar el tiempo de respuesta y el consumo de memoria entre un cliente web y un cliente Android al consumir una API REST de un sistema de inventario con SQL Server.

**Específicos:**

1. Implementar una API REST de inventario con SQL Server.
2. Implementar un cliente web y un cliente Android que consuman los mismos endpoints.
3. Instrumentar la medición de tiempo de respuesta y consumo de memoria en cada cliente.
4. Ejecutar 10 repeticiones por combinación y calcular promedio y desviación estándar.
5. Analizar umbrales donde la diferencia sea significativa.
6. Documentar recomendaciones de diseño para sistemas con doble canal.

## Tecnologías previstas

| Herramienta | Versión | Licencia |
|---|---|---|
| Java (OpenJDK) | 21 | GPLv2 con Classpath Exception |
| Spring Boot | 3.3 | Apache 2.0 |
| SQL Server | 2022 | Propietaria (Developer Edition gratuita) |
| Docker | 27 | Apache 2.0 |
| Android Studio | Koala | Apache 2.0 |
| Kotlin | 2.0 | Apache 2.0 |
| Retrofit | 2.11 | Apache 2.0 |
| Chrome | 128 | Propietaria (gratuita) |

## Estructura del repositorio
