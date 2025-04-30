# Use the previously built image as the base image
FROM petercantu/django

# Set the working directory
WORKDIR /app


ARG PROJECT_NAME=default_django_project

# Create a new Django project with the specified name
RUN django-admin startproject $PROJECT_NAME .

## Expose the port the Django app runs on
# EXPOSE 8000