
# week-3-assignment

In this homework a node.js server is created using express, jwt and fs modules.

## API Reference

#### Get All Users

```http
  GET /users
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `none` | `none` | none |

#### Get Given User

```http
  GET /users/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |
| `token`      | `Bearer Token` | **Required**. |

#### Insert New User

```http
  POST /users
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `token`      | `Bearer Token` | **Required**. |

#### Update Given User

```http
  PUT /users/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |
| `token`      | `Bearer Token` | **Required**. |

#### Patch Given User

```http
  PATCH /users/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |
| `token`      | `Bearer Token` | **Required**. |

#### Delete Given User

```http
  DELETE /users/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |
| `token`      | `Bearer Token` | **Required**. |

#### Create JWT Token

```http
  POST /users/create-token
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id to create token |



