# Redis Exercise

This repository contains a simple Node.js application that uses Redis for caching request. The application provides a REST API for querying information about different fish species.

## Prerequisites

To run this application, you will need to have Docker and Docker Compose installed on your machine.

## Running the Application

- Clone this repository to your local machine.
- Navigate to the root directory of the project.
- Open a terminal window and run the following command to start the application: `docker-compose up`
- Once the application is running, open a web browser or API testing tool and make a GET request to the following endpoint to retrieve information about a specific fish species: `http://localhost:3000/fish/:species`.
- Replace `:species` with the name of the fish species you want to query. For example, to retrieve information about red snapper, make a GET request to the following URL: `http://localhost:3000/fish/red-snapper`
- The response should include information about the fish species you queried in JSON format.

## Stopping the Application

To stop the application, press `Ctrl + C` in the terminal window where you ran the `docker-compose up` command, and then run the following command:
