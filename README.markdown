# shipa-django-sample

This is the example project used to show CI tool  integration into Shipa

## Configuration

Before deploying this app to Shipa, you need to add the host/domain name to `ALLOWED_HOSTS` configuration in `blog/settings.py`:

```
ALLOWED_HOSTS = ['my-app.cloud.example.com', 'example.domain.net', 'lvh.me']
```

To run locally, you can use `lvh.me` domain.
