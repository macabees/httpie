# HTTPie
The HTTPie command includes intuitive UI, JSON support, syntax highlighting, wget-like downloads, plugins, and more.

## httpie (Project Info)
[Website](https://httpie.org/)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/httpie/)

## Build image
`$ docker build -t macabees/httpie:latest .`

## Docker Push
`$ docker push -t macabees/httpie:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm macabees/httpie -v PUT httpbin.org/put API-Key:foo hello=world`

## Help
`$ docker run -it --rm macabees/httpie --help`
