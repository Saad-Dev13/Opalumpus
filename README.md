# Opalumpus - Travel and Tour Agency MERN Stack Application

Opalumpus is a full-stack web application for a travel and tour agency, built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to browse destinations and trips, while providing admins with a secure dashboard to manage trip listings.

## Features

- **User Interface:** Responsive React frontend for browsing destinations and trips.
- **Admin Panel:** Secure admin dashboard for managing trips (CRUD operations).
- **Authentication:** Admin login for secure access to management features.
- **API:** RESTful backend built with Node.js and Express.js.
- **Database:** MongoDB for storing trip and admin data.

## Tech Stack

- **Frontend:** React.js, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Saad-Dev13/Opalumpus.git
   cd opalumpus
   ```

2. **Backend Setup:**
   ```sh
   cd Backend
   npm install
   ```
   - Create a `.env` file in the `Backend` directory and add your MongoDB URI:
     ```
     MONGO_URI=your_mongodb_connection_string
     ```

   - Start the backend server:
     ```sh
     npm start
     ```

3. **Frontend Setup:**
   ```sh
   cd ../Opalumpus_frontEnd
   npm install
   npm start
   ```

4. **Access the Application:**
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend API: [http://localhost:5000](http://localhost:5000)

## Folder Structure

```
Opalumpus/
├── Backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── .env
└── Opalumpus_frontEnd/
    ├── src/
    └── public/
```

## Usage

- **Users:** Browse available trips and destinations.
- **Admins:** Sign in to the admin panel to add, edit, or delete trips.


---

*Feel free to contribute or open issues to improve the project!*
