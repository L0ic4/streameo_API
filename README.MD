# Streameo_API 🖥

## Technologies Used ⚙️
- Java
- Spring Boot
- Maven
- PostgreSQL
- Lombok

## Installation 🚀
1. Clone the repository.
2. Make sure you have Java and Maven installed.
3. Set up the PostgreSQL database and update the `application.properties` file with the correct database configurations.
4. Run the application using Maven: `mvn spring-boot:run`.

# API Endpoints

- `GET /movies`: Get all movies.
- `GET /movies/{name}`: Get movies by title.
- `GET /movie/random`: Get a random movie.
- `GET /movie/{id}`: Get movie details by ID.
- `POST /like`: Create a like for a movie.
- `DELETE /unLike`: Remove a like for a movie.
- `POST /comment`: Add a new comment.
- `GET /comments/{movieId}`: Get all comments for a specific movie.


## Additional Information ✔
- The project uses Lombok for reducing boilerplate code.
- The application.properties file contains database configuration.
- The project follows a service-controller-repository structure.