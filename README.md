# prometheus-summarized-uptime
### Requirements
* flask
* gunicorn
* pyyaml
* prometheus_api_client
* datetime
####
Run using ```gunicorn --bind 0.0.0.0:5000 main:app```

### Containerization
build:

```podman build . -t <registry.url>/uptime-summary:<version>``` 

push:

```podman push registry.url>/uptime-summary:<version>```

