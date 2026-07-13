# Decodelabs.intern
Resturant Website code
# Project 2 - Backend API Development

## Developer
**Name:** Adeel Sattar

## Project Description
This project is developed as part of the DecodeLabs Full Stack Development Internship (Project 2).

The project demonstrates a simple Backend API using **Node.js** and **Express.js**. It provides REST API endpoints for retrieving and adding user data with basic validation.

---

## Technologies Used

- Node.js
- Express.js
- JavaScript
- JSON

---

## Project Structure

Project2-BackendAPI/
│
├── controllers/
│ └── userController.js
│
├── routes/
│ └── users.js
│
├── data/
│ └── users.json
│
├── server.js
├── package.json
└── README.md

---

## Installation

1. Clone or download the project.

2. Open terminal inside the project folder.

3. Install dependencies:

```bash
npm install
```

4. Start the server:

```bash
npm start
```

or

```bash
node server.js
```

---

## API Endpoints

### Home

GET /

Returns server status.

---

### Get All Users

GET /users

Returns all users.

---

### Get User By ID

GET /users/:id

Example:

GET /users/1

---

### Add New User

POST /users

Request Body

```json
{
  "name": "John",
  "email": "john@gmail.com"
}
```

---

## Validation

- Name is required.
- Email is required.
- Email must be in a valid format.

---

## Success Responses

- 200 OK
- 201 Created

---

## Error Responses

- 400 Bad Request
- 404 Not Found

---

## Author

Adeel Sattar

DecodeLabs Internship 2026
