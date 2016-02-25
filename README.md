
## Phenomenal Service front webserver and home

Dockercontainer with NGINX php-enabled webserver containing service webpage

<strong>Input:</strong> bla

## Header 2

Text

```
$ docker build -t phenomenalsevicefrontweb .
```

To run the service with local html files you need to ........

```
$ docker run --name phenomenalsevicefrontweb -p 7777:80 -v ~/projekt/docker/frontweb/html:/usr/share/nginx/html:ro -d phenomenalsevicefrontweb
```
