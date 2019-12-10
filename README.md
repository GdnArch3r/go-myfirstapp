# go-myfirstapp

## APIs
### Primary Service ([krithisekar/first-todo-app](https://github.com/krithisekar/first-todo-app))
- POST `/account/{account-name}` - To create a new account
- POST `/account/{account-name}/tasks/{task-name}` - To create a new task under an account
- GET `/account/{account-name}/tasks` - To get all the tasks of an account

### Account Service ([Lakshman2105/My_First_Go_Project](https://github.com/Lakshman2105/My_First_Go_Project))
- POST `/account/{account-name}` - Returns `201` if the account is created successfully
- GET `/account/{account-name}` - Returns `200` if the account exists; returns `404` if the account doesn't exist

### Task Service ([GdnArch3r/go-myfirstapp](https://github.com/GdnArch3r/go-myfirstapp))
- POST `/account/{account-name}/tasks/{task-name}` - Returns `201` if the task is created successfully
- GET `/account/{account-name}/tasks` - Returns `200` along with the tasks, if the account exists
