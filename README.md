# mr6400sms
This is HomeAssistant HACS integration that works a lot faster than tp-connected due to eliminated js2py based cryptography.

This code however is based on tp-connected.

## Add to notify: section
```yaml
- platform: mr6400sms
  name: mr6400sms
  router_ip: <IP of the router>
  router_pwd: <admin password>
```

## Calling the service
- Similar like other notifivations.
- Title parameter is ignored.
- Use target to provide a list of numbers.