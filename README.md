# Mini LPR Session Manager (Node.js + PostgreSQL)

## Overview
This project consists of two main components:
- **Client**: The frontend application.
- **Server**: The backend application.

## Prerequisites
Ensure you have the following installed on your system:
- **Node.js** 
- **npm**
- **PostgreSQL** 
---

## Installation
### 1. Clone the Repository
```bash
git clone https://github.com/NickV05/Test-Project.git
cd Test-Project
```

### 2. Install Dependencies
#### Client
```bash
cd client
npm install
```
#### Server
```bash
cd ../server
npm install
```

---

## Database Setup
To set up a local PostgreSQL database:
1. Ensure PostgreSQL is installed and running on your machine.
2. Required databases will be intialized on the firts run of the server
3. Create the `.env` file in the `server` folder with the following configuration:
   ```env
   PORT = <your port number>, default/suggested is 3000
   ```

---

## Client Setup
To set up a local PostgreSQL database:
1. Ensure PostgreSQL is installed and running on your machine.
2. Required databases will be intialized on the firts run of the server
3. Create the `.env` file in the `client` folder with the following configuration:
   ```env
   VITE_SERVER_URL = <your client localhost >, default/suggested is 3000
   ```

---

## Running the Application
### Server
To start the backend server:
```bash
cd server
npm start
```

### Client
To start the frontend development server:
```bash
cd client
npm run dev
```

---

## Testing
### Client
Run end-to-end tests using Playwright:
```bash
cd client
npm run test:e2e
```

### Server
Run unit tests with Jest:
```bash
cd server
npm test

