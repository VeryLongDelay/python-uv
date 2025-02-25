# python-uv

Lovingly forked from Owl Corp's [Python-Poetry-Base](https://github.com/owl-corp/python-template)

A base Dockerfile with uv pre-installed. Using this image as a base will allow you to forget about anything required to setup uv within your Docker environment.

Simply `COPY` your pyproject & uv lock file into your image, and `uv run`.

See the [examples](./examples/) folder for example usage.
