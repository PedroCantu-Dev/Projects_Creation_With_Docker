## Change the base image to a specific version if needed
## Using the official Flutter image (latest stable version) as the base image
FROM cirrusci/flutter:stable

## Accept a project name as a build argument
ARG PROJECT_NAME=default_flutter_project

## Create a new Flutter project with the specified name
RUN flutter create /app/$PROJECT_NAME

## Expose the port the Flutter app runs on
# EXPOSE 8080