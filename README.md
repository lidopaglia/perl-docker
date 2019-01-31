# perl-docker
Example compose file running Perl CGI

credit: https://medium.com/@lojorider/docker-with-cgi-perl-a4558ab6a329

## File Structure

```
|
compose
|  |
|  |--- docker-compose
|  |--- Dockerfile
|  |--- vhost.conf
|
html
   |
   |--- index.html
   |--- hello_world.pl
```

## Run Script

```
> cd compose
> docker-compose up -d --build
```

## Test

- http://localhost:8080/index.html
- http://localhost:8080/hello_world.pl
