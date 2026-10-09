# Git and Docker Starter Application 
This repository contains a small Python web application used to practice Git, GitHub, and Docker workflows
 


## Running and Using the Application

The application listens on port 8000 and returns a text response when accessed over HTTP.

## Verification

The running application should be verified using an HTTP request to port 8000.

## Usage

Build the Docker image with:

    docker build -t git-docker-app:test .

Run the application on host port 8080:

    docker run -d --name app-test -p 8080:8000 git-docker-app:test

Verify the running application with:

    curl http://localhost:8080
