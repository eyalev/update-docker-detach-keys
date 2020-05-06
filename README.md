
# update-docker-detach-keys

Adds `"detachKeys": "ctrl-e,e"` to `~/.docker/config.json` so that `Ctrl+P` would work properly inside a Docker container.

## Run with [pipx](https://github.com/pipxproject/pipx)

```
$ pipx run update-docker-detach-keys
```

## Related

- https://stackoverflow.com/questions/20828657/docker-change-ctrlp-to-something-else
