# Academia API

A simple REST API for managing schools

## REST API Specification

| Endpoint       | HTTP   | Description                     | Done |
| -------------- | ------ | ------------------------------- | ---- |
| `/schools`     | GET    | List all schools                | ✅   |
| `/schools/:id` | GET    | Get a school by ID              | ✅   |
| `/schools`     | POST   | Create a new school             | ✅   |
| `/schools`     | DELETE | Delete All Schools              | ✅   |
| `/schools/:id` | DELETE | Delete a school by ID           | ✅   |
| `/schools/:id` | PUT    | Update a school by ID           | ✅   |
| `/schools/:id` | PATCH  | Partially update a school by ID | ✅   |

## ERD Diagram

![ERD Diagram](/public/erd.png)
[ERD Diagram](https://dbdiagram.io/d/Academia-API-6867c5fdf413ba35084f6b3d)

## Getting Started

To install dependencies:

```sh
bun install
```

To run:

```sh
bun run dev
```

open http://localhost:3000
