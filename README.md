# Todo-FastAPI
| Endpoint | Method | Description | Body Request | Body Response |
| --- | --- | --- | --- | --- |
| /createTask | POST | Create A Task by ID and Title. | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": false<br><br>} | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": false<br><br>} |
| --- | --- | --- | --- | --- |
| /getTaskID/{task_id} | GET | Get a task by ID. | \-  | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": {completed}<br><br>} |
| --- | --- | --- | --- | --- |
| /getTaskTitle/{title} | GET | Get a task by title. | \-  | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": {completed}<br><br>} |
| --- | --- | --- | --- | --- |
| /deleteID/{task_id} | DELETE | Delete a task by ID. | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": false<br><br>} | \-  |
| --- | --- | --- | --- | --- |
| /deleteTitle/{title} | DELETE | Delete a task by Title. | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": false<br><br>} | \-  |
| --- | --- | --- | --- | --- |
| /deleteAll | DELETE | Delete every task | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": false<br><br>} | \-  |
| --- | --- | --- | --- | --- |
| /getAllTasks | GET | Get every task | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": false<br><br>} | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": false<br><br>} |
| --- | --- | --- | --- | --- |
| /updateTask/{task_id} | PUT | Update a task by requesting a the new data | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": {completed}<br><br>} | {<br><br>"id": {id},<br><br>"title": "{title}",<br><br>"completed": false<br><br>} |
| --- | --- | --- | --- | --- |
