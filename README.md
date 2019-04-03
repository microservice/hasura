# Hasura
An OMG service to access Hasura, including it's console.

## Usage
### Expose the Hasura console
To expose the Hasura console via your app (eg: https://your_app.asyncyapp.com/console),
add the following to your `asyncy.yml` present in the root of your Asyncy app:
```yaml
expose:
  hasura_console:
    service: hasura
    name: console
    http:
      path: /console
```

## Coming soon
- Support for webhooks