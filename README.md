## Docker container for the Phoenix framework
It is based on official [Elixir container](https://hub.docker.com/_/elixir/).

![Phoenix Framework](https://www.filepicker.io/api/file/9prSmznZTiaRRmI3t89E)

Github repo: https://github.com/kelostrada/docker-phoenix-framework

### How to use
    docker run -it --rm -v "$PWD":/code -w /code kelu/phoenix-framework mix phoenix.new /code/my_new_app

### Simillar repos:
* https://hub.docker.com/r/marcelocg/phoenix/
* https://hub.docker.com/r/joshwlewis/docker-heroku-phoenix/
