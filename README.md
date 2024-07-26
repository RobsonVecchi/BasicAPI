# Video API

This project is a RESTful API for managing video data, built with Flask and Flask-RESTful. The API supports CRUD (Create, Read, Update, Delete) operations for video entries in a SQLite database.

## Features

- **Create**: Add new video entries with attributes for name, views, and likes.
- **Read**: Retrieve information about a specific video by its ID.
- **Update**: Modify details of an existing video.
- **Delete**: Remove a video from the database.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework.
- **Flask-RESTful**: An extension for Flask that adds support for quickly building REST APIs.
- **Flask-SQLAlchemy**: An extension for Flask that adds support for SQLAlchemy, a SQL toolkit.
- **SQLite**: A lightweight database engine used for data storage.

## Installation

1. Clone the repository;
2. Navigate to the project directory;
3. Create and activate a virtual environment (optional but recommended);
4. Install the required packages;
5. Initialize the database;

## Usage

1. Run the Flask application (The server will start on `http://127.0.0.1:5000/`)

2. **API Endpoints:**

    - **GET** `/video/<int:video_id>`: Retrieve a video by its ID.
    - **PUT** `/video/<int:video_id>`: Create a new video or replace an existing video by its ID.
    - **PATCH** `/video/<int:video_id>`: Update an existing video by its ID.
    - **DELETE** `/video/<int:video_id>`: Delete a video by its ID.

## Contact

For any questions or suggestions, please contact [robson.t.vecchi@gmail.com](mailto:robson.t.vecchi@gmail.com).
