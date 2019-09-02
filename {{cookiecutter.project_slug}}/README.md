# {{cookiecutter.project_name}}

> Short blurb about what your product does.

[![Built With](vujango-shield)](vujango-shield)

{{cookiecutter.description}}

## Project Structure

Project id divided between {{cookiecutter.backend_folder}} and {{cookiecutter.frontend_folder}} folders, {{cookiecutter.backend_folder}} contains backend built with [Django](Django) + [Django REST framework](Django-Rest-Framework) and {{cookiecutter.frontend_folder}} contains a progressive simgle page application built with [Bootstrap](Bootstrap) + [Vue.js](Vue.js).

## Pre-Requisites

You need to have [Docker](Docker) and [Docker Compose](Docker-Compose) installed in your system.

## Usage

To get development environment up and running, run `$ docker-compose up --build` it will spin up the django development server and vue development server.

### {{cookiecutter.backend_service_name}} service commands

The general way to run commands for {{cookiecutter.backend_service_name}} service is like `$ docker-compose run {{cookiecutter.backend_service_name}} python manage.py <command> [options]`

- To make migrations run `$ docker-compose run {{cookiecutter.backend_service_name}} python manage.py makemigrations`
- To migrate database run `$ docker-compose run {{cookiecutter.backend_service_name}} python manage.py migrate`
- To create a superuser run `$ docker-compose run {{cookiecutter.backend_service_name}} python manage.py createsuperuser`
- To collect static files run `$ docker-compose run {{cookiecutter.backend_service_name}} python manage.py collectstatic`

### {{cookiecutter.frontend_service_name}} service commands

The general way to run commands for {{cookiecutter.frontend_service_name}} service is like `$ docker-compose run {{cookiecutter.frontend_service_name}} npm run <command> [options]`

- To lint the code run `$ docker-compose run {{cookiecutter.frontend_service_name}} npm run lint --fix`
- To start development server run `$ docker-compose run {{cookiecutter.frontend_service_name}} npm run serve`
- To unit tests run `$ docker-compose run {{cookiecutter.frontend_service_name}} npm run test:unit`
- To e2e tests run `$ docker-compose run {{cookiecutter.frontend_service_name}} npm run test:e2e`

## Meta

**{{cookiecutter.author}}** - {{cookiecutter.email}}

## Acknowledgments

- Hat tip to anyone who's code was used
- Inspiration and Coffee
- stack overflow
- etc

<!-- Markdown link & img dfn's -->

[bootstrap]: https://getbootstrap.com/
[django]: https://www.djangoproject.com/
[django-rest-framework]: https://www.django-rest-framework.org/
[docker]: https://docs.docker.com/install/
[docker-compose]: https://docs.docker.com/install/
[vue.js]: https://vuejs.org/
[vujango]: https://github.com/RatanShreshtha/vujango
[vujango-shield]: https://img.shields.io/badge/Built%20With-vujango-blue
