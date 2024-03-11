# Todo-FastAPI
| Endpoint | Method | Description | Body Request | Body Response |
| -------- | ------ | ----------- | ------------ | ------------- |
| /createTask | POST | Create a Task by ID and Title. | `{ "id": {id}, "title": "{title}", "completed": false }` | `{ "id": {id}, "title": "{title}", "completed": false }` |
| /getTaskID/{task_id} | GET | Get a task by ID. | - | `{ "id": {id}, "title": "{title}", "completed": {completed} }` |
| /getTaskTitle/{title} | GET | Get a task by title. | - | `{ "id": {id}, "title": "{title}", "completed": {completed} }` |
| /deleteID/{task_id} | DELETE | Delete a task by ID. | `{ "id": {id}, "title": "{title}", "completed": false }` | - |
| /deleteTitle/{title} | DELETE | Delete a task by Title. | `{ "id": {id}, "title": "{title}", "completed": false }` | - |
| /deleteAll | DELETE | Delete every task | `{ "id": {id}, "title": "{title}", "completed": false }` | - |
| /getAllTasks | GET | Get every task | `{ "id": {id}, "title": "{title}", "completed": false }` | `{ "id": {id}, "title": "{title}", "completed": false }` |
| /updateTask/{task_id} | PUT | Update a task by requesting the new data | `{ "id": {id}, "title": "{title}", "completed": {completed} }` | `{ "id": {id}, "title": "{title}", "completed": false }` |
