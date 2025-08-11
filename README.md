# 📚 LiterAlura: Catálogo de Libros en Java

![Banner de LiterAlura](./assets/banner.jpg)

## 🎯 Objetivo del Proyecto
**LiterAlura** es un catálogo de libros interactivo que consume la API de Gutendex, permitiendo a los usuarios buscar, guardar y analizar libros y autores desde la consola. Desarrollado como parte de un desafío de programación, combina:
- Consumo de APIs REST.
- Persistencia en PostgreSQL.
- Buenas prácticas de Java y Spring Boot.

## 🌟 Características Principales
| **Funcionalidad**               | **Descripción**                                                  |
|---------------------------------|------------------------------------------------------------------|
| 🔍 Búsqueda en API              | Obtén libros por título desde Gutendex.                          |
| 💾 Almacenamiento en PostgreSQL | Guarda libros y autores en una base de datos relacional.         |
| 🌍 Filtrado por idioma          | Español (`es`), Inglés (`en`), Francés (`fr`), Portugués (`pt`). |
| 📊 Estadísticas                 | Top 10 libros más descargados, autores vivos en un año.          |
| 🖥️ Interfaz intuitiva          | Menú de consola fácil de usar.                                   |

## 🛠️ Tecnologías Utilizadas
| **Tecnología**       | **Uso**                                      | **Versión** |
|----------------------|----------------------------------------------|-------------|
| Java                 | Lenguaje principal                           | 21          |
| Spring Boot          | Framework para backend                       | 3.1         |
| PostgreSQL           | Base de datos                                | 15          |
| Hibernate/JPA        | Mapeo objeto-relacional (ORM)                | -           |
| Jackson              | Procesamiento de JSON                        | 2.15        |
| Git                  | Control de versiones                         | -           |

## 📌 Capturas de Pantalla
### Menú Principal
![img.png](img.png)
## 📌 Capturas de Pantalla
### Libros Almacenados
![img_1.png](img_1.png)









## 📌 Metodología Ágil (Trello)
El proyecto se gestionó con **metodología ágil** usando un tablero Trello:
- **Listo para iniciar**: Tareas pendientes.
- **En desarrollo**: Funcionalidades en progreso.
- **Pausado**: Tareas detenidas temporalmente.
- **Concluido**: Elementos finalizados.

![trello.png](assets/trello.png)


## 🚀 Instalación y Ejecución
### Requisitos Previos
- Java 21
- PostgreSQL 15
- Maven
![img_2.png](img_2.png)
### Pasos:
1. **Clona el repositorio**:
   ```bash
   git@github.com:JonasRivadeneyra/LiterAlura.git