# greeting-project

This will hold the source code for the Springboot content from the Niue nology course.

## Folders

- `./greeting-api` -> The Springboot Backend project.
- `./greeting-app` -> The React Fronent project.

## Branches

- `main` -> Current state of the project.
- `01-spring-intro-get-req` -> Lesson looking at spring boot & get requests, path variables and params.
- `02-MVC-CRUD` -> Lesson looking at the Model View Controller design pattern. We also added Create, Read, Update and Delete endpoints to our `GreetingController`.
- `03-repository-refactor` -> Lesson refactoring `GreetingController` to interact with `GreetingRepository`. We introduced `ResponseEntity` a way for us to control the status codes we send back. We add Error handling , and the ability to read from a json file.