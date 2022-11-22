# Todo App
npm install @takesure/common - use for error handling

### This app allows user to list all their todos, but before they start posting, view, updating and deleting, they should register first.

- user and todo endpoints can only be accessed by authenticated users

### Authentification endpoints:

- /auth/signup 
- /auth/signin
- /auth/signout
- auth/currentUser

#### User endpoints
- /user/getUsers
- /user/getUser
- /user/updateUser
- /user/deleteUser

#### Todo endpoints

##### When getting all todos user can filter, sort, and do pagination of their todos
- /todo/getAllTodo
- /todo/getTodo
- /todo/updateTodo
- /todo/deleteTodo

