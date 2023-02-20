README for Movie Spring Boot Application

Overview:
This is a Spring Boot application called "movie" which provides a simple REST API for managing movie information. The application allows users to perform CRUD (Create, Read, Update, Delete) operations on movie data.

Features:

Provides endpoints for adding, updating, deleting and retrieving movie data.
Supports CRUD operations on movie entities that consist of a title, genre, release year and director.
Uses a H2 in-memory database to store the movie data.
Implements basic input validation to ensure that data entered by users is of the correct format and length.
Uses Spring Data JPA to interact with the database.
Requirements:

Java 8 or above
Maven or Gradle build tools
A web browser or a tool like Postman to test the REST API endpoints.
Installation:

Clone or download the repository to your local machine.
Run the application using your preferred build tool (Maven or Gradle).
The application will start running at http://localhost:8080.
Usage:
To test the application, you can use a web browser or a tool like Postman to make HTTP requests to the following endpoints:

GET /api/v1/movies: Retrieve all movies in the database.
GET /api/v1/movies/{id}: Retrieve a movie with the specified ID.
POST /api/v1/movies: Create a new movie with the specified details.
PUT /api/v1//movies/{id}: Update an existing movie with the specified ID.
DELETE /api/v1/movies/{id}: Delete a movie with the specified ID.


GET /api/v1/reviews: Retrieve all movies in the database.
GET /api/v1/reviews/{id}: Retrieve a movie with the specified ID.
POST /api/v1/reviews: Create a new movie with the specified details.
PUT /api/v1/reviews/{id}: Update an existing movie with the specified ID.
DELETE /api/v1/reviews/{id}: Delete a movie with the specified ID.
Examples of requests:

To retrieve all movies, make a GET request to http://localhost:8080/movies.
To create a new movie, make a POST request to http://localhost:8080/movies with the following JSON payload:
{
"title": "Movie Title",
"genre": "Action",
"releaseYear": 2022,
"director": "Director Name"
}

To update an existing movie, make a PUT request to http://localhost:8080/api/v1/movies/{id} with the ID of the movie to be updated and the updated details in the JSON payload.
To delete a movie, make a DELETE request to http://localhost:8080/api/v1/movies/{id} with the ID of the movie to be deleted.
Contributing:
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or pull request on GitHub.

License:
This application is licensed under the MIT License. See LICENSE for more information.
