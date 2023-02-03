ref - https://realpython.com/asynchronous-tasks-with-django-and-celery/#python-celery-basics

To receive tasks from your program and send results to a back end, Celery requires a message broker for communication.
Redis and RabbitMQ are two message brokers that developers often use together with Celery.


- Celery workers are worker processes that run tasks independently from one another and outside the context of your main service.
- Celery beat is a scheduler that orchestrates when to run tasks. You can use it to schedule periodic tasks as well.
