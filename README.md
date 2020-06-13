<!--
https://pypi.org/project/readme-generator/
https://pypi.org/project/python-readme-generator/
-->

[![](https://img.shields.io/pypi/v/django-configurations-celery.svg?maxAge=3600)](https://pypi.org/project/django-configurations-celery/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![Travis](https://api.travis-ci.org/andrewp-as-is/django-configurations-celery.py.svg?branch=master)](https://travis-ci.org/andrewp-as-is/django-configurations-celery.py/)

#### Installation
```bash
$ [sudo] pip install django-configurations-celery
```

#### Features
key | type | default value | env
-|-|-|-
`CELERY_ACCEPT_CONTENT` | list | `['application/json']` | `DJANGO_CELERY_ACCEPT_CONTENT`
`CELERY_ENABLE_UTC` | bool | `True` | `DJANGO_CELERY_ENABLE_UTC`
`CELERY_IMPORTS` | list | `[]` | `DJANGO_CELERY_IMPORTS`
`CELERY_INCLUDE` | list | `[]` | `DJANGO_CELERY_INCLUDE`
`CELERY_TIMEZONE` | str | `'UTC'` | `DJANGO_CELERY_TIMEZONE`
`CELERYBEAT_MAX_LOOP_INTERVAL` | int | `0` | `DJANGO_CELERYBEAT_MAX_LOOP_INTERVAL`
`CELERYBEAT_SCHEDULE` | dict | `{}` |
`CELERYBEAT_SCHEDULER` | str | `celery.beat:PersistentScheduler` | `DJANGO_CELERYBEAT_SCHEDULER`
`CELERYBEAT_SCHEDULE_FILENAME` | str | `celerybeat-schedule` | `DJANGO_CELERYBEAT_SCHEDULE_FILENAME`
`CELERYBEAT_SYNC_EVERY` | int | `0` | `DJANGO_CELERYBEAT_SYNC_EVERY`
`BROKER_URL` | str | `None` | `DJANGO_BROKER_URL`
`BROKER_TRANSPORT_OPTIONS` | dict | `{}` |
`BROKER_CONNECTION_TIMEOUT` | float | `4.0` | `DJANGO_BROKER_CONNECTION_TIMEOUT`
`BROKER_CONNECTION_RETRY` | bool | `True` | `DJANGO_BROKER_CONNECTION_RETRY`
`BROKER_CONNECTION_MAX_RETRIES` | int | `100` | `DJANGO_BROKER_CONNECTION_MAX_RETRIES`
`BROKER_FAILOVER_STRATEGY` | str | `'round-robin'` | `DJANGO_BROKER_FAILOVER_STRATEGY`
`BROKER_HEARTBEAT` | float | `120.0` | `DJANGO_BROKER_HEARTBEAT`
`BROKER_LOGIN_METHOD` | str | `'AMQPLAIN'` | `DJANGO_BROKER_LOGIN_METHOD`
`BROKER_POOL_LIMIT` | int | `10` | `DJANGO_BROKER_POOL_LIMIT`
`BROKER_USE_SSL` | bool | `False` | `DJANGO_BROKER_USE_SSL`
`CELERY_CACHE_BACKEND_OPTIONS` | dict | `{}` |
`CASSANDRA_COLUMN_FAMILY` | str | `None` | `DJANGO_CASSANDRA_COLUMN_FAMILY`
`CASSANDRA_ENTRY_TTL` | int | `None` | `DJANGO_CASSANDRA_ENTRY_TTL`
`CASSANDRA_KEYSPACE` | str | `None` | `DJANGO_CASSANDRA_KEYSPACE`
`CASSANDRA_PORT` | int | `9042` | `DJANGO_CASSANDRA_PORT`
`CASSANDRA_READ_CONSISTENCY` | str | `None` | `DJANGO_CASSANDRA_READ_CONSISTENCY`
`CASSANDRA_OPTIONS` | dict | `{}` | `DJANGO_CASSANDRA_OPTIONS`
`S3_ACCESS_KEY_ID` | str | `None` | `DJANGO_S3_ACCESS_KEY_ID`
`S3_SECRET_ACCESS_KEY` | str | `None` | `DJANGO_S3_SECRET_ACCESS_KEY`
`S3_BUCKET` | str | `None` | `DJANGO_S3_BUCKET`
`S3_BASE_PATH` | str | `None` | `DJANGO_S3_BASE_PATH`
`S3_ENDPOINT_URL` | str | `None` | `DJANGO_S3_ENDPOINT_URL`
`S3_REGION` | str | `None` | `DJANGO_S3_REGION`
`CELERY_COUCHBASE_BACKEND_SETTINGS` | dict | `{}` |
`CELERY_ARANGODB_BACKEND_SETTINGS` | dict | `{}` |
`CELERY_MONGODB_BACKEND_SETTINGS` | dict | `{}` |
`CELERY_EVENT_QUEUE_EXPIRES` | float | `60.0` | `DJANGO_CELERY_EVENT_QUEUE_EXPIRES`
`CELERY_EVENT_QUEUE_TTL` | float | `5.0` | `DJANGO_CELERY_EVENT_QUEUE_TTL`
`CELERY_EVENT_QUEUE_PREFIX` | str | `'celeryev'` | `DJANGO_CELERY_EVENT_QUEUE_PREFIX`
`CELERY_EVENT_SERIALIZER` | str | `json` | `DJANGO_CELERY_EVENT_SERIALIZER`
`CELERY_REDIS_DB` | str | `None` | `DJANGO_CELERY_REDIS_DB`
`CELERY_REDIS_HOST` | str | `None` | `DJANGO_CELERY_REDIS_HOST`
`CELERY_REDIS_MAX_CONNECTIONS` | int | `None` | `DJANGO_CELERY_REDIS_MAX_CONNECTIONS`
`CELERY_REDIS_PASSWORD` | str | `None` | `DJANGO_CELERY_REDIS_PASSWORD`
`CELERY_REDIS_PORT` | int | `None` | `DJANGO_CELERY_REDIS_PORT`
`CELERY_REDIS_BACKEND_USE_SSL` | bool | `False` | `DJANGO_CELERY_REDIS_BACKEND_USE_SSL`
`CELERY_RESULT_BACKEND` | str | `None` | `DJANGO_CELERY_RESULT_BACKEND`
`CELERY_MAX_CACHED_RESULTS` | bool | `False` | `DJANGO_CELERY_MAX_CACHED_RESULTS`
`CELERY_MESSAGE_COMPRESSION` | str | `None` | `DJANGO_CELERY_MESSAGE_COMPRESSION`
`CELERY_RESULT_EXCHANGE` | str | `None` | `DJANGO_CELERY_RESULT_EXCHANGE`
`CELERY_RESULT_EXCHANGE_TYPE` | str | `None` | `DJANGO_CELERY_RESULT_EXCHANGE_TYPE`
`CELERY_RESULT_EXPIRES` | timedelta | 1 day |
`CELERY_RESULT_PERSISTENT` | bool | `False` | `DJANGO_CELERY_RESULT_PERSISTENT`
`CELERY_RESULT_SERIALIZER` | str | `json` | `DJANGO_CELERY_RESULT_SERIALIZER`
`CELERY_RESULT_DBURI` | str | `None` | `DJANGO_CELERY_RESULT_DBURI`
`CELERY_RESULT_ENGINE_OPTIONS` | dict | `{}` |
`CELERY_RESULT_DB_TABLE_NAMES` | list | `[]` | `DJANGO_CELERY_RESULT_DB_TABLE_NAMES`
`CELERY_SECURITY_CERTIFICATE` | str | `None` | `DJANGO_CELERY_SECURITY_CERTIFICATE`
`CELERY_SECURITY_CERT_STORE` | str | `None` | `DJANGO_CELERY_SECURITY_CERT_STORE`
`CELERY_SECURITY_KEY` | str | `None` | `DJANGO_CELERY_SECURITY_KEY`
`CELERY_ACKS_LATE` | bool | `False` | `DJANGO_CELERY_ACKS_LATE`
`CELERY_ACKS_ON_FAILURE_OR_TIMEOUT` | bool | `True` | `DJANGO_CELERY_ACKS_ON_FAILURE_OR_TIMEOUT`
`CELERY_ALWAYS_EAGER` | bool | `False` | `DJANGO_CELERY_ALWAYS_EAGER`
`CELERY_ANNOTATIONS` | dict/list | `None` |
`CELERY_COMPRESSION` | str | `None` | `DJANGO_CELERY_COMPRESSION`
`CELERY_CREATE_MISSING_QUEUES` | bool | `True` | `DJANGO_CELERY_CREATE_MISSING_QUEUES`
`CELERY_DEFAULT_DELIVERY_MODE` | str | `'persistent'` | `DJANGO_CELERY_DEFAULT_DELIVERY_MODE`
`CELERY_DEFAULT_EXCHANGE` | ? | ? |
`CELERY_DEFAULT_EXCHANGE_TYPE` | str | `'direct'` | `DJANGO_CELERY_DEFAULT_EXCHANGE_TYPE`
`CELERY_DEFAULT_QUEUE` | str | `'celery'` | `DJANGO_CELERY_DEFAULT_QUEUE`
`CELERY_DEFAULT_RATE_LIMIT` | str | `None` | `DJANGO_CELERY_DEFAULT_RATE_LIMIT`
`CELERY_DEFAULT_ROUTING_KEY` | ? | ? |
`CELERY_EAGER_PROPAGATES` | bool | `False` | `DJANGO_CELERY_EAGER_PROPAGATES`
`CELERY_IGNORE_RESULT` | bool | `False` | `DJANGO_CELERY_IGNORE_RESULT`
`CELERY_PUBLISH_RETRY` | bool | `True` | `DJANGO_CELERY_PUBLISH_RETRY`
`CELERY_PUBLISH_RETRY_POLICY` | ? | ? |
`CELERY_QUEUES` | list | `None` | `DJANGO_CELERY_QUEUES`
`CELERY_ROUTES` | list | `None` | `DJANGO_CELERY_ROUTES`
`CELERY_SEND_SENT_EVENT` | bool | `False` | `DJANGO_CELERY_SEND_SENT_EVENT`
`CELERY_SERIALIZER` | str | `'json'` | `DJANGO_CELERY_SERIALIZER`
`CELERYD_SOFT_TIME_LIMIT` | int | `None` | `DJANGO_CELERYD_SOFT_TIME_LIMIT`
`CELERYD_TIME_LIMIT` | int | `None` | `DJANGO_CELERYD_TIME_LIMIT`
`CELERY_TRACK_STARTED` | bool | `False` | `DJANGO_CELERY_TRACK_STARTED`

##### `settings.py`
```python
from django_configurations_celery import CeleryConfiguration
from kombu import Queue

class Base(CeleryConfiguration,...):
    CELERY_IMPORTS = (
        'celery_app',
        'tasks',
    )
    CELERY_QUEUES = (
        Queue('default', routing_key='task.#'),
    )
```

##### `.env`
```bash
DJANGO_BROKER_URL=redis://localhost:6379/0
DJANGO_CELERY_IMPORTS=celery_app,tasks
```

#### Links
+   [django-configurations](https://github.com/jazzband/django-configurations)
+   [Celery configuration and defaults](https://docs.celeryproject.org/en/latest/userguide/configuration.html)

<p align="center">
    <a href="https://pypi.org/project/python-readme-generator/">python-readme-generator</a>
</p>