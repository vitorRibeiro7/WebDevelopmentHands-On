<h1>Backend mission</h1>

Develop a **RESTful API** with **Node** using **Prisma**, which uses all methods 
<br>
(`GET`, `POST`, `PUT`, `PATCH`, `DELETE`).


### Specification
Assemble a vehicle base with the following structure:
```
vehicle: string
brand: string
year: integer
description: text
sold: bool
created: datetime
updated: datetime
```

Use **MySQL** or **SQLite** to store the data that the **API** will consume.

### API endpoints
`GET /vehicles`
<br>
Returns all vehicles

`GET /vehicles/find`
<br>

Returns the vehicles according to the term passed parameter `q`


`GET /vehicles/{id}`
<br>

Returns vehicle details


`POST /vehicles`
<br>

Adds a new vehicle

`PUT /vehicles/{id}`
<br>

Update vehicle data

`PATCH /vehicles/{id}`
<br>

Updates only some vehicle data

`DELETE /vehicles/{id}`
<br>

delete the vehicle

## Frontend mission

Develop a **UI (User Interface)** according to the prototype.

### Specification
- Consume **API** created above
- Create a screen that has...
    - Vehicle listing
    - Vehicle detail
    - Search
    - Vehicle new/edit form