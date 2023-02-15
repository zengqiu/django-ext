Django Ext
==========

Some extensions for Django.

# Model

## TimestampModel

Add `created_at` and `updated_at` for model.

## TimeRangeModel

Add `started_at` and `ended_at` for model.

## UserTrackModel

Add `created_by` and `update_by` for model.

This model requires `django-currentuser`, and should add it to the middleware classes in your settings.py:

```
MIDDLEWARE = (
    ...,
    'django_currentuser.middleware.ThreadLocalUserMiddleware',
)
```
