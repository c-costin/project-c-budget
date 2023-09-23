# Routes WEB

## Public

| Method | URL          | Description   |
| ------ | ------------ | ------------- |
| GET    | /            | Home page     |
| GET    | /connexion   | Login page    |
| GET    | /inscription | Register page |

## Private

| Method | URL                       | Description                      |
| ------ | ------------------------- | -------------------------------- |
| GET    | /deconnexion              | Logout                           |
| GET    | /{name}                   | Dashboard home page              |
| GET    | /{name}/compte            | Dashboard profil page            |
| GET    | /{name}/revenu            | Dashboard revenue page           |
| GET    | /{name}/depenses/fixe     | Dashboard fixed expenses page    |
| GET    | /{name}/depenses/variable | Dashboard variable expenses page |
