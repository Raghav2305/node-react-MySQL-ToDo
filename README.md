# To-Do List App

A simple to-do list application built with React, MySQL, and Node.js. This application allows you to create and manage to-do items.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Database Schema](#database-schema)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create new to-do items.
- Delete existing to-do items.
- View a list of all to-do items.
- Store to-do items in a MySQL database.

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

Before you begin, make sure you have the following tools installed:

- Node.js
- MySQL Server

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Navigate to the project directory::

   ```bash
   cd your-repo
   ```

3. Install the dependencies for the server:

   ```bash
   cd server
   npm install
   ```

4. Configure the MySQL database:
 - Create a new MySQL database for the project.
 - Update the config.js file in the server directory with your MySQL database connection details.

5. Migrate the database schema:

   ```bash
    npm run db:migrate
   ```

6. Install the dependencies for the client::

   ```bash
    cd ../client
    npm install
   ```

## Usage

1. Start the server:

   ```bash
    cd ../server
    npm start
   ```

2. Start the react client:
   ```bash
    cd ../client
    npm start
   ```

3. Open your web browser and navigate to http://localhost:3000 to access the to-do list application.

## API Endpoints:

- POST /notes/create: Create a new to-do item.
- GET /notes: Get a list of all to-do items.
- DELETE /notes/:id: Delete a to-do item by ID.

## Database Schema:

- id (Primary Key)
- title (String)
- contents (String)
- created (Timestamp)


## Contributing:

- Contributions are welcome! Please feel free to open an issue or submit a pull request.

## License:

- This project is licensed under the [MIT License](LICENSE.md).




   
