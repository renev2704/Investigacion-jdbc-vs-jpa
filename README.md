# JDBC vs. JPA/Hibernate: latencia y memoria en CRUD sobre un sistema de inventario de productos tecnológicos

Perfil de investigación — Entrega 1 de 4

## Integrantes

| Nombre | Usuario GitHub |
|---|---|
| Nombre Apellido | [@usuario1](https://github.com/usuario1) |
| Nombre Apellido | [@usuario2](https://github.com/usuario2) |
| Nombre Apellido | [@usuario3](https://github.com/usuario3) |

## Problema

En el desarrollo de sistemas de inventario para negocios de productos tecnológicos, la capa de acceso a datos impacta directamente sobre el rendimiento percibido por el usuario. Los dos enfoques más usados en Java son JDBC (SQL nativo) y JPA/Hibernate (mapeo objeto-relacional). Cuando el volumen de registros crece, las operaciones CRUD pueden volverse lentas, pero no existe un consenso claro sobre cuánta diferencia hay en latencia y consumo de memoria entre ambos enfoques, ni cómo escala esa diferencia con el volumen de datos. La mayoría de comparaciones disponibles se enfocan solo en SELECT, no reportan memoria y no declaran versiones exactas de las herramientas, lo que impide reproducir los resultados.

## Pregunta de investigación

**Principal:**

> ¿Qué diferencias de tiempo de respuesta y consumo de memoria existen entre JDBC y JPA/Hibernate al ejecutar operaciones SELECT, INSERT, UPDATE y DELETE sobre conjuntos de 1.000, 10.000 y 100.000 registros en SQL Server, desde una aplicación Java 21, considerando el promedio de 10 ejecuciones por combinación?


## Objetivos

**General:**


**Específicos:**



## Tecnologías previstas

| Herramienta | Versión | Licencia |
|---|---|---|
| Java (OpenJDK) | 21 | GPLv2 con Classpath Exception |
| Spring Boot | 3.3 | Apache 2.0 |
| JDBC | 4.3 | Especificación Java |
| Hibernate | 6.5 | LGPL 2.1 |
| SQL Server | 2022 | Propietaria (Developer Edition gratuita) |
| Docker | 27 | Apache 2.0 |
| Maven | 3.9 | Apache 2.0 |
| Git | 2.45 | GPLv2 |

## Estructura del repositorio
