### PROBLEM
Your application is composed of several services, like a frontend web page
and a database.

### SOLUTION
A multi-container app with a compose file.

### compose.yaml
This file tells Docker how to run your application.
It defines the application's services, networks, volumes, and more.

### Running the compose file/the app
This command essentially builds and runs the app.
More specifically, it reads the compose file; builds the networks, 
volumes, and services into containers; and starts the containers.
-d allows the app to run continuously in the background.

`docker compose up -d`

### Running with live updates
`docker compose watch`

Cancel with ctrl + c.

### Stopping the app
`docker compose down`

This deletes the containers.

### Volumes
A location on your local filesystem managed by Docker, used to persist data
when a container is deleted.
