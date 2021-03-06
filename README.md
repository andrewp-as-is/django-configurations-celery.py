<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-configurations-celery.svg?maxAge=3600)](https://pypi.org/project/django-configurations-celery/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-configurations-celery.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-configurations-celery.py/actions)

### Installation
```bash
$ [sudo] pip install django-configurations-celery
```

#### Features
key | type | default value
-|-|-
`CELERY_ACCEPT_CONTENT` | list | `['application/json']`
`CELERY_ENABLE_UTC` | bool | `True`
`CELERY_IMPORTS` | list | `[]`
`CELERY_INCLUDE` | list | `[]`
`CELERY_TIMEZONE` | str | `'UTC'`
`CELERYBEAT_MAX_LOOP_INTERVAL` | int | `0`
`CELERYBEAT_SCHEDULE` | dict | `{}`
`CELERYBEAT_SCHEDULER` | str | `celery.beat:PersistentScheduler`
`CELERYBEAT_SCHEDULE_FILENAME` | str | `celerybeat-schedule`
`CELERYBEAT_SYNC_EVERY` | int | `0`
`BROKER_URL` | str | `None`
`BROKER_TRANSPORT_OPTIONS` | dict | `{}`
`BROKER_CONNECTION_TIMEOUT` | float | `4.0`
`BROKER_CONNECTION_RETRY` | bool | `True`
`BROKER_CONNECTION_MAX_RETRIES` | int | `100`
`BROKER_FAILOVER_STRATEGY` | str | `'round-robin'`
`BROKER_HEARTBEAT` | float | `120.0`
`BROKER_LOGIN_METHOD` | str | `'AMQPLAIN'`
`BROKER_POOL_LIMIT` | int | `10`
`BROKER_USE_SSL` | bool | `False`
`CELERY_CACHE_BACKEND_OPTIONS` | dict | `{}`
`CASSANDRA_COLUMN_FAMILY` | str | `None`
`CASSANDRA_ENTRY_TTL` | int | `None`
`CASSANDRA_KEYSPACE` | str | `None`
`CASSANDRA_PORT` | int | `9042`
`CASSANDRA_READ_CONSISTENCY` | str | `None`
`CASSANDRA_OPTIONS` | dict | `{}`
`S3_ACCESS_KEY_ID` | str | `None`
`S3_SECRET_ACCESS_KEY` | str | `None`
`S3_BUCKET` | str | `None`
`S3_BASE_PATH` | str | `None`
`S3_ENDPOINT_URL` | str | `None`
`S3_REGION` | str | `None`
`CELERY_COUCHBASE_BACKEND_SETTINGS` | dict | `{}`
`CELERY_ARANGODB_BACKEND_SETTINGS` | dict | `{}`
`CELERY_MONGODB_BACKEND_SETTINGS` | dict | `{}`
`CELERY_EVENT_QUEUE_EXPIRES` | float | `60.0`
`CELERY_EVENT_QUEUE_TTL` | float | `5.0`
`CELERY_EVENT_QUEUE_PREFIX` | str | `'celeryev'`
`CELERY_EVENT_SERIALIZER` | str | `json`
`CELERY_REDIS_DB` | str | `None`
`CELERY_REDIS_HOST` | str | `None`
`CELERY_REDIS_MAX_CONNECTIONS` | int | `None`
`CELERY_REDIS_PASSWORD` | str | `None`
`CELERY_REDIS_PORT` | int | `None`
`CELERY_REDIS_BACKEND_USE_SSL` | bool | `False`
`CELERY_RESULT_BACKEND` | str | `None`
`CELERY_MAX_CACHED_RESULTS` | bool | `False`
`CELERY_MESSAGE_COMPRESSION` | str | `None`
`CELERY_RESULT_EXCHANGE` | str | `None`
`CELERY_RESULT_EXCHANGE_TYPE` | str | `None`
`CELERY_RESULT_EXPIRES` | timedelta | 1 day
`CELERY_RESULT_PERSISTENT` | bool | `False`
`CELERY_RESULT_SERIALIZER` | str | `json`
`CELERY_RESULT_DBURI` | str | `None`
`CELERY_RESULT_ENGINE_OPTIONS` | dict | `{}`
`CELERY_RESULT_DB_TABLE_NAMES` | list | `[]`
`CELERY_SECURITY_CERTIFICATE` | str | `None`
`CELERY_SECURITY_CERT_STORE` | str | `None`
`CELERY_SECURITY_KEY` | str | `None`
`CELERY_ACKS_LATE` | bool | `False`
`CELERY_ACKS_ON_FAILURE_OR_TIMEOUT` | bool | `True`
`CELERY_ALWAYS_EAGER` | bool | `False`
`CELERY_ANNOTATIONS` | dict/list | `None`
`CELERY_COMPRESSION` | str | `None`
`CELERY_CREATE_MISSING_QUEUES` | bool | `True`
`CELERY_DEFAULT_DELIVERY_MODE` | str | `'persistent'`
`CELERY_DEFAULT_EXCHANGE` | ? | ?
`CELERY_DEFAULT_EXCHANGE_TYPE` | str | `'direct'`
`CELERY_DEFAULT_QUEUE` | str | `'celery'`
`CELERY_DEFAULT_RATE_LIMIT` | str | `None`
`CELERY_DEFAULT_ROUTING_KEY` | str | ?
`CELERY_EAGER_PROPAGATES` | bool | `False`
`CELERY_IGNORE_RESULT` | bool | `False`
`CELERY_PUBLISH_RETRY` | bool | `True`
`CELERY_PUBLISH_RETRY_POLICY` | ? | ?
`CELERY_QUEUES` | list | `None`
`CELERY_ROUTES` | list | `None`
`CELERY_SEND_SENT_EVENT` | bool | `False`
`CELERY_SERIALIZER` | str | `'json'`
`CELERYD_SOFT_TIME_LIMIT` | int | `None`
`CELERYD_TIME_LIMIT` | int | `None`
`CELERY_TRACK_STARTED` | bool | `False`
`CELERYD_AGENT` | str | `None`
`CELERYD_AUTOSCALER` | str | `'celery.worker.autoscale:Autoscaler'`
`CELERYD_CONCURRENCY` | int | `None`
`CELERYD_CONSUMER` | str | `'celery.worker.consumer:Consumer'`
`CELERY_WORKER_DIRECT` | bool | `False`
`CELERY_DISABLE_RATE_LIMITS` | bool | `False`
`CELERY_ENABLE_REMOTE_CONTROL` | bool | `True`
`CELERYD_HIJACK_ROOT_LOGGER` | bool | `True`
`CELERYD_LOG_COLOR` | bool | ?
`CELERYD_LOG_FORMAT` | str | `'[%(asctime)s: %(levelname)s/%(processName)s] %(message)s'`
`CELERYD_WORKER_LOST_WAIT` | float | `10.0`
`CELERYD_MAX_TASKS_PER_CHILD` | int | `None`
`CELERYD_POOL` | str | `'prefork'`
`CELERYD_POOL_RESTARTS` | bool | `False`
`CELERYD_PREFETCH_MULTIPLIER` | int | `4`
`CELERYD_REDIRECT_STDOUTS` | bool | `True`
`CELERYD_REDIRECT_STDOUTS_LEVEL` | str | `'WARNING'`
`CELERY_SEND_EVENTS` | bool | `False`
`CELERYD_STATE_DB` | str | `None`
`CELERYD_TASK_LOG_FORMAT` | str | `[%(asctime)s: %(levelname)s/%(processName)s][%(task_name)s(%(task_id)s)] %(message)s`
`CELERYD_TIMER` | str | `None`
`CELERYD_TIMER_PRECISION` | float | `1.0`

##### `settings.py`
```python
from django_configurations_celery import CeleryConfiguration
from kombu import Queue

class Base(CeleryConfiguration,...):
    CELERY_IMPORTS = (
        'celery_app',   # ./celery_app.py
        'tasks',        # ./tasks/
    )
    CELERY_QUEUES = (
        Queue('celery', routing_key='task.#'),
    )
```

##### `.env`
use `DJANGO_` prefix
```bash
DJANGO_BROKER_URL=redis://localhost:6379/0
DJANGO_CELERY_IMPORTS=tasks
```

#### Links
+   [django-configurations](https://github.com/jazzband/django-configurations)
+   [Celery configuration and defaults](https://docs.celeryproject.org/en/latest/userguide/configuration.html)

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
