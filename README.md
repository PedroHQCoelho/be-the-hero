# Be The Hero

A web and mobile-oriented platform developed during **Rocketseat's OmniStack Week**. The project connects NGOs with people who want to help by sharing and managing cases that need support.

## About the project

NGOs can register on the platform, create an account using their generated ID and publish incidents with a title, description and requested amount. Each NGO can access its own profile to view and manage its registered cases.

## Features

- NGO registration with contact details and location.
- Login using the NGO ID.
- List and view registered incidents.
- Create incidents with a title, description and requested amount.
- View incidents associated with the authenticated NGO.
- Delete incidents from the NGO profile.
- API validation for request data.

## Technologies

**Frontend**
- React
- React Router
- Axios
- React Icons

**Backend**
- Node.js
- Express
- Knex.js
- SQLite
- Celebrate and Joi for request validation

**Testing**
- Jest
- Supertest

## Project structure

```text
be-the-hero/
├── backend/
│   └── src/
│       ├── controllers/
│       ├── database/
│       ├── utils/
│       ├── routes.js
│       └── server.js
└── frontend/
    └── src/
        ├── assets/
        ├── pages/
        ├── services/
        └── routes.js
```

## Running locally

You need **Node.js and npm** installed.

### 1. Clone the repository

```bash
git clone https://github.com/PedroHQCoelho/be-the-hero.git
cd be-the-hero
```

### 2. Start the backend

```bash
cd backend
npm install
npm start
```

The backend start script uses Nodemon and runs `src/server.js`.

### 3. Start the frontend

Open another terminal:

```bash
cd frontend
npm install
npm start
```

The frontend uses Create React App. Check the API base URL in `frontend/src/services/api.js` and make sure it points to the address where your backend is running.

## Tests

Backend tests can be run with:

```bash
cd backend
npm test
```

## Project context

Be The Hero was developed as a learning project during Rocketseat's OmniStack Week, exploring the integration of a React frontend with a Node.js API and a relational database.

## Repository

https://github.com/PedroHQCoelho/be-the-hero
