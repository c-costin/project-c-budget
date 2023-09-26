# Routes API

## Public

### Documentation

| Method | URL      | Description                                      |
| ------ | -------- | ------------------------------------------------ |
| GET    | /api/    | Documentation for developers                     |
| GET    | /api/doc | Open API - Documentation and test for developers |

### Authentification

| Method | URL              | Description             |
| ------ | ---------------- | ----------------------- |
| POST   | /api/login_check | Login User and send JWT |

### User

| Method | URL           | Description       |
| ------ | ------------- | ----------------- |
| POST   | /api/user/add | Register new User |

## Private

### User

| Method | URL                   | Description           |
| ------ | --------------------- | --------------------- |
| GET    | /api/user/read/{id}   | Read information User |
| PATCH  | /api/user/edit/{id}   | Edit information User |
| DELETE | /api/user/remove/{id} | Delete account User   |

### Revenue

| Method | URL                      | Description                      |
| ------ | ------------------------ | -------------------------------- |
| POST   | /api/revenue/add         | Add revenue                      |
| GET    | /api/revenue/read/{id}   | Add revenue                      |
| PATCH  | /api/revenue/edit/{id}   | Edit revenue with parameter Id   |
| DELETE | /api/revenue/remove/{id} | Remove revenue with parameter Id |

### Expense fixed

| Method | URL                            | Description                            |
| ------ | ------------------------------ | -------------------------------------- |
| POST   | /api/expense/fixed/add         | Add fixed expense                      |
| GET    | /api/expense/fixed/read/{id}   | Add fixed expense                      |
| PATCH  | /api/expense/fixed/edit/{id}   | Edit fixed expense with parameter Id   |
| DELETE | /api/expense/fixed/remove/{id} | Remove fixed expense with parameter Id |

### Expense variable

| Method | URL                               | Description                               |
| ------ | --------------------------------- | ----------------------------------------- |
| POST   | /api/expense/variable/add         | Add variable expense                      |
| GET    | /api/expense/variable/read/{id}   | Add variable expense                      |
| PATCH  | /api/expense/variable/edit/{id}   | Edit variable expense with parameter Id   |
| DELETE | /api/expense/variable/remove/{id} | Remove variable expense with parameter Id |
