## Requirements
1. Java - 1.8.x
2. Maven - 3.x.x

## Steps to Setup
**Build and run the app using maven**

```bash
mvn package
java -jar target/easy-notes-1.0.0.jar
```

Alternatively, you can run the app without packaging it using -

```bash
mvn spring-boot:run
```

The app will start running at <http://localhost:8080>.

## Explore Rest APIs

The app defines following CRUD APIs.

    GET /api/notes
    POST /api/notes
    GET /api/notes/{noteId}
    PUT /api/notes/{noteId}
    DELETE /api/notes/{noteId}

You can test them using postman or any other rest client.
