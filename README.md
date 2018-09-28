# Django2.1-Tutorial
https://docs.djangoproject.com/ja/2.1/intro/tutorial01/

Runnning Locally
---
Make sure you have [Docker Compose](https://docs.docker.com/compose/install/).

```sh
$ cp .env.example .env
$ docker-compose up
```

Your app should now be running on http://0.0.0.0:8000/polls/

Deploying to Heroku
---
1. Create [New tag](https://gitlab.com/jumpyoshim/django-polls/tags/new)
   - Tag naming rules conform to [Semantic Versioning](https://semver.org/)

1. Execute deploy job with the tag you created
