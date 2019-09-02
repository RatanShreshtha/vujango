# Vujango

![Built With](https://img.shields.io/badge/Built%20With-cookiecutter-blue)
![![GitHub license](https://img.shields.io/badge/License-MIT-green)](https://github.com/RatanShreshtha/vujango/blob/master/LICENSE)

A cookiecutter template to create a project with backend in [Django](Django) + [Django REST framework](Django-Rest-Framework) and frontend in [Bootstrap](Bootstrap) + [Vue.js](Vue.js) for your full stack projects.

## Highlights

- [Docker](docker)
- [12 Factor](12-factor)
- Server: [Nginx](nginx)
- Backend: [Django](Django) + [Django REST framework](Django-Rest-Framework)
- Frontend: [Bootstrap](Bootstrap) + [Vue.js](Vue.js)
- Tests: [Jest](jest) + [pytest](pytest) + [Nightwatch.js](nightwatch.js)
- Database: [PostgreSQL](https://www.postgresql.org/)

## Requirements

Install `cookiecutter` command line: `pip install --user cookiecutter`

## Usage

Generate a new Cookiecutter template layout: `cookiecutter gh:RatanShreshtha/vujango`

You'll be prompted for some values. Provide them, then a project
will be created for you.

Answer the prompts with your own desired options.

    ----------------------------------------------- Basic ------------------------------------------------ []:
    project_name [My Awesome Project]:
    project_slug [my_awesome_project]:
    short_description [Analytical Engine - Web Version]:
    description [Web interface for The Analytical Engine, world's first general purpose computer.]:
    author [Ada Lovelace]:
    email [ada@lovelace.cool]:
    version [0.1.0]:
    ---------------------------------------------- Backend ----------------------------------------------- []:
    backend_folder [backend]:
    backend_service_name [backend]:
    ---------------------------------------------- Frontend ---------------------------------------------- []:
    frontend_folder [frontend]:
    frontend_service_name [frontend]:

## Authors

- **Ratan Kulshreshtha** - [RatanShreshtha](https://github.com/RatanShreshtha)

## License

This project is licensed under the terms of the [MIT License](/LICENSE)

## Contributing

Feedback and improvements are very welcome, just follow the steps below

1. Fork it.
2. Create your feature branch (`git checkout -b <feature>`).
3. Add your files (`git add <file_1> <file2> ..... <file_n>`).
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin <feature>`).
6. Create a new pull request.

## Acknowledgments

- Hat tip to anyone who's code was used
- Inspiration
- etc

<!-- Markdown link & img links -->

[12-factor]: http://12factor.net/
[bootstrap]: https://getbootstrap.com/
[django]: https://www.djangoproject.com/
[django-rest-framework]: https://www.django-rest-framework.org/
[docker]: https://docs.docker.com/install/
[docker-compose]: https://docs.docker.com/install/
[jest]: https://jestjs.io/
[nginx]: https://nginx.org/
[nightwatch.js]: https://nightwatchjs.org/
[pytest]: https://pytest.org/en/latest/
[vue.js]: https://vuejs.org/
[vujango]: https://github.com/RatanShreshtha/vujango
[vujango-shield]: https://img.shields.io/badge/Built%20With-vujango-blue
