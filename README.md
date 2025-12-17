# ServeBot, a Discord Bot.

## Requirements

* [Docker](https://www.docker.com/).
* [uv](https://docs.astral.sh/uv/) for Python package and environment management.
* [Discord Bot token](https://discord.com/developers/applications)

## Docker Compose

You can start the bot with Docker Compose

```console
$ docker compose watch
```

## UV

Or, with UV. The dependencies are managed with [uv](https://docs.astral.sh/uv/).

You can then install all the dependencies with:

```console
$ uv sync
```

You can then start the bot with:

```console
$ uv run bot.py
```
