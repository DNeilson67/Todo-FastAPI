![image](https://github.com/DNeilson67/Todo-FastAPI/assets/114067292/24bb5eed-2285-4589-aa97-f36f9bb07d83)# Todo-FastAPI
| Endpoint | Method | Description | Body Request | Body Response | Error Response |
| -------- | ------ | ----------- | ------------ | ------------- | ----------- |
| /createTask | POST | Create a Task by ID and Title. | `{ "id": {id}, "title": "{title}", "completed": false }` | `{ "id": {id}, "title": "{title}", "completed": false }` | `{"error": "Task not found"}` |
| /getTaskID/{task_id} | GET | Get a task by ID. | - | `{ "id": {id}, "title": "{title}", "completed": {completed} }` | `{"error": "Task not found"}` |
| /getTaskTitle/{title} | GET | Get a task by title. | - | `{ "id": {id}, "title": "{title}", "completed": {completed} }` | `{"error": "No tasks found with title '{title}'"}` |
| /deleteID/{task_id} | DELETE | Delete a task by ID. | `{ "id": {id}, "title": "{title}", "completed": false }` | `{"message": "Task deleted successfully"}` |
| /deleteTitle/{title} | DELETE | Delete a task by Title. | `{ "id": {id}, "title": "{title}", "completed": false }` | `{"message": "All tasks with title '{title}' deleted successfully"}`|
| /deleteAll | DELETE | Delete every task | `{ "id": {id}, "title": "{title}", "completed": false }` | `{"message": "All tasks deleted successfully"}` | - |
| /getAllTasks | GET | Get every task | `{ "id": {id}, "title": "{title}", "completed": false }` | `{ "id": {id}, "title": "{title}", "completed": false }` | - |
| /updateTask/{task_id} | PUT | Update a task by requesting the new data | `{ "id": {id}, "title": "{title}", "completed": {completed} }` | `{"message": "Task updated successfully"}` | `{"error": "Task not found"}`|
