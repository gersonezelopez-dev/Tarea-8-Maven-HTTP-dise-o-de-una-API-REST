





| Operación | Método HTTP | Endpoint | Respuesta |
|---|---|---|---|
| Consultar todas las tareas | GET | `/api/tareas` | 200 OK |
| Consultar una tarea | GET | `/api/tareas/{id}` | 200 OK |
| Registrar una tarea | POST | `/api/tareas` | 201 Created |
| Modificar una tarea | PUT | `/api/tareas/{id}` | 200 OK |
| Eliminar una tarea | DELETE | `/api/tareas/{id}` | 204 No Content |
| Consultar tarea inexistente | GET | `/api/tareas/{id}` | 404 Not Found |

