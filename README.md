# Java Docker Day 1 Exercise

## Learning Objectives

- Create a Spring Application with the usual end points
- Practice deploying the Spring Application to a Docker Container

## Instructions

1. Fork this repository
2. Clone your fork to your machine
3. Open the project in IntelliJ

## Core

Either create an API with the usual GET/PUT/POST/DELETE endpoints or reuse one of your previous APIs and copy it into this repository. You can even choose to reuse the Security Repo from the previous sessions.

Your API should connect to a Neon database instance that can be used for storing the data.

Create a `jar` file for the completed application make sure it is excluded from your GitHub solution!!!!!

Create a `Dockerfile` and any other associated files to allow you to deploy the application using a Docker Container save it and the jar file to a sensible folder in your project (make sure the JAR file does not get pushed to GitHub).

Exclude your `application.yml` file from GitHub as normal. 

To assess this we will clone your repository, add our own credentials to the cloned repository and use those to test that the application works as expected.

## Extension

Create a Docker container with a Postgres Database in it, that your API talks to instead of the instance in Neon.

