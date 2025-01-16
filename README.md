## Initializing Mock API using task-management-back with json-server and json-server-auth

To set up a mock API using the `task-management-back` repository and `json-server-auth`, follow these steps:

1. Clone the `task-management-back` repository:

```bash
git clone https://github.com/theorlan2/task-management-back.git
cd task-management-back
```

2. Install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the mock API server:

```bash
npm run start
# or
yarn run start
# or
pnpm run start
```

To modify the tasks data in the mock API, you can edit the db.json file located at task-management-back/db.json. Here's an example of how to add a new task:

```json
{
"tasks": [
  // Existing tasks...
  {
    "id": 4,
    "title": "New Task",
    "status": "TODO",
    "description": "Description for new task.",
    "userId": 1
  }
  // ...and more tasks...
]
}
```

After making changes, don't forget to save the file. The updated data will be available in the API when you restart the server or make a request.
