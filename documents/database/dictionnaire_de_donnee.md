# Dictionnaire de donnée

## User

| Champ     | Type               | Spécificités                        | Description              |
| --------- | ------------------ | ----------------------------------- | ------------------------ |
| email     | VARCHAR(128)       | UNIQUE, NOT NULL                    | The user address mail    |
| password  | VARCHAR(64)        | NOT NULL                            | The user password        |
| role      | VARCHAR(16)        | NOT NULL                            | The user role            |
| name      | VARCHAR(64)        | NOT NULL                            | The user name            |
| createdAt | DATETIME IMMUTABLE | NOT NULL, DEFAULT CURRENT_TIMESTAMP | The date created on user |
| updatedAt | DATETIME IMMUTABLE | NULL                                | The date updated on user |

## Finance

| Champ     | Type               | Spécificités                        | Description                 |
| --------- | ------------------ | ----------------------------------- | --------------------------- |
| name      | VARCHAR(64)        | NOT NULL                            | The finance name            |
| amount    | DECIMAL            | NOT NULL                            | The finance amount          |
| revenue   | BOOLEAN            | NOT NULL                            | if the finance is revenue   |
| fixe      | BOOLEAN            | NOT NULL                            | if the finance is fixe      |
| date      | DATETIME IMMUTABLE | NOT NULL                            | The finance date            |
| createdAt | DATETIME IMMUTABLE | NOT NULL, DEFAULT CURRENT_TIMESTAMP | The date created on finance |
| updatedAt | DATETIME IMMUTABLE | NULL                                | The date updated on finance |

## Type

| Champ     | Type               | Spécificités                        | Description              |
| --------- | ------------------ | ----------------------------------- | ------------------------ |
| name      | VARCHAR(64)        | NOT NULL                            | The type name            |
| revenue   | BOOLEAN            | NOT NULL                            | If the type is revenue   |
| createdAt | DATETIME IMMUTABLE | NOT NULL, DEFAULT CURRENT_TIMESTAMP | The date created on type |
| updatedAt | DATETIME IMMUTABLE | NULL                                | The date updated on type |
