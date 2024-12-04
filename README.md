# Recipe RESTful Api

This project showcases a RESTful API built with Django 4.2 and Django REST Framework (DRF), illustrating how to leverage these powerful tools to create a robust and well-structured API for managing recipes. The API features CRUD operations, user authentication via JWT, and seamless image uploads. It leverages PostgreSQL for reliable data storage and emphasizes quality through extensive testing (with 80% coverage) and CI/CD pipelines for automated workflows. The application is also uses Docker for easy deployment and scalability.

#### Stack:

- [Python](https://www.python.org/downloads/)
- [PostgreSQL](https://www.postgresql.org/)
- [Django](https://www.djangoproject.com/)
- [DRF](https://www.django-rest-framework.org/)
- [Docker](https://www.docker.com/)

## Local Developing

All actions should be executed from the source directory of the project and only after installing all requirements.

1. Firstly, create a docker container:
```
  docker build .
```

2. Second create docker-compose file:
```
  docker-compose up
```
