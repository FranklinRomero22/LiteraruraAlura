# LiteraruraAlura

Es una aplicación de consola construida con Java 17, Spring Boot 3.3.1 y PostgreSQL. Esta aplicación permite buscar libros por título usando la API de Gutendex, registrar libros en la base de datos, y listar libros y autores registrados, entre otras funcionalidades.

## Requisitos

Antes de ejecutar la aplicación, asegúrate de tener instalados los siguientes componentes:

- Java 17
- Maven
- PostgreSQL

## Configuración de la base de datos

1. Instala PostgreSQL y asegúrate de que está en funcionamiento.
2. Crea una base de datos llamada `library_db`:

## Cuando ejecutes la aplicación, verás el siguiente menú en la consola:
1.- Buscar un libro por titulo y registrarlo
2.- Listar libros registrados
3.- Listar autores registrados
4.- Listar autores vivos en un determinado año
5.- Listar libros por idioma
0.- Salir
Elige una opción: 

# Opciones del menú

Buscar un libro por título y registrarlo:

Ingresa el título del libro que deseas buscar. La aplicación buscará el libro usando la API de Gutendex y lo registrará en la base de datos si lo encuentra.

Listar libros registrados:

Esta opción lista todos los libros registrados en la base de datos.

Listar autores registrados:

Esta opción lista todos los autores registrados en la base de datos.

Listar autores vivos en un determinado año:

Ingresa el año para listar los autores que estaban vivos en ese año.

Listar libros por idioma:

Ingresa el idioma para listar todos los libros registrados en ese idioma.

Salir:

Esta opción cierra la aplicación.

## Dependencias
Las principales dependencias utilizadas en este proyecto son:

Spring Boot Starter Data JPA
PostgreSQL Driver
Jackson Databind

## Autor
Franklin Romero

