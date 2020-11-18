# Conference planning tool: CfP, scheduling, speaker management

https://github.com/pretalx/pretalx

## Python/Django-based Conference tool

## Where to start?

https://github.com/pretalx/pretalx/blob/v1.1.2/src/pretalx/event/models/event.py

## Threads to pull on

Can you sketch a model of the Event & Schedule subsystems?

The `Event` model feels like it does a lot of things (not quite a God object)
what could be separated out?

What Celery tasks are used in Pretalx?
