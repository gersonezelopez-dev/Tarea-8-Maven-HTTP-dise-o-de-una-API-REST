
# Control de Tareas Personales

## Descripción

Proyecto desarrollado para aplicar los fundamentos de Maven, HTTP y REST mediante una aplicación Java
para administrar tareas personales.

El programa permite crear diferentes tareas, almacenarlas en una colección y mostrar cuántas tareas están
pendientes y cuántas han sido completadas.

## Tecnologías utilizadas para el programa 

- Java 17
- Maven
- IntelliJ IDEA
- Git
- GitHub

## Datos del proyecto Maven

GroupId: com.estudiante

ArtifactId: control-tareas

Version: 1.0-SNAPSHOT

## Explicación de Maven

GroupId: identifica el grupo o paquete principal al que pertenece el proyecto.

ArtifactId: representa el nombre del proyecto.

Version: identifica la versión actual del proyecto.

## Compilación del proyecto

Para limpiar el proyecto:

mvn clean

Para compilar:

mvn compile

Para ejecutar las pruebas:

mvn test

Para generar el archivo JAR:

mvn package

Todo debe ser copilado con comandos o bien en la terminal Maven. 

## Diseño de API REST

| Operación | Método HTTP | Endpoint | Respuesta |
|---|---|---|---|
| Consultar todas las tareas | GET | /api/tareas | 200 OK |
| Consultar una tarea | GET | /api/tareas/{id} | 200 OK |
| Registrar una tarea | POST | /api/tareas | 201 Created |
| Modificar una tarea | PUT | /api/tareas/{id} | 200 OK |
| Eliminar una tarea | DELETE | /api/tareas/{id} | 204 No Content |
| Consultar tarea inexistente | GET | /api/tareas/{id} | 404 Not Found |

## Ejemplo JSON

{
"id": 1,

"titulo": "Comprar alimentos",

"descripcion": "Comprar productos para la semana",

"prioridad": "ALTA",

"completada": false

}

## Estudiante Ingenieria en Sistemas

Nombre: Gerson Ezequiel López Enriquez

Carné: 9941-25-22144


