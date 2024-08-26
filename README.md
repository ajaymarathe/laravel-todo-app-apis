# To-Do API

## Endpoints

- **GET** `/todos` - List all to-dos
- **POST** `/todos` - Create a to-do
  - **Payload:**
    ```json
    {
      "title": "Task",
      "description": "Details",
      "is_completed": false
    }
    ```
- **GET** `/todos/{id}` - Get to-do by ID
- **PUT** `/todos/{id}` - Update to-do
  - **Payload:**
    ```json
    {
      "title": "Updated Task",
      "description": "Updated Details",
      "is_completed": true
    }
    ```
- **DELETE** `/todos/{id}` - Delete to-do

## Errors

- **404** - Not Found
- **400** - Bad Request
- **500** - Server Error

## Auth

No authentication required.
