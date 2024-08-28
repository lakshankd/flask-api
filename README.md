# Flask REST API

A basic REST API built using Flask, providing CRUD operations for user management.

## Features

- **GET**: Retrieve all users or a specific user by ID.
- **POST**: Add a new user.
- **PATCH**: Update a user's details by ID.
- **DELETE**: Delete a user by ID.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lakshankd/flask-api.git
   cd flask-api
   ```

2. **Create a virtual environment:**
   ```bash
   python3 -m venv .venv
   ```

3. **Activate the virtual environment:**
    -  On macOS/Linux:    
        ```bash
        source .venv/bin/activate
        ```
    -  On Windows:    
        ```bash
        .venv\Scripts\activate
        ```

4. **Install the dependencies::**
   ```bash
   pip install -r requirements.txt
   ```

5. **Create the database:**
   ```bash
   python create_db.py
   ```

6. **Run the app:**
   ```bash
   python app.py
   ```

## API Endpoints
- GET /api/users: Get all users
- GET /api/users/<id>: Get a user by ID
- POST /api/users: Create a new user
- PATCH /api/users/<id>: Update a user's details
- DELETE /api/users/<id>: Delete a user


### Happy coding! 😊
