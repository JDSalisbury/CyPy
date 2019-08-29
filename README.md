# Setting up A Celery Django App.

Following this
[Tutorial](https://stackabuse.com/asynchronous-tasks-in-django-with-redis-and-celery/)

The redis-server and celery task terminals described earlier need to be running

```

$ celery worker -A celery_test --loglevel=info

```

Celery workers must be restarted each time a celery task-related code change is made.
