# code-with-quarkus

Project from the Quarkus archetype. I have changed Quarkus version from `3.14.4` to `3.8.3`.

Running:

```
podman run -it -v $(pwd):/usr/src/app:z -e LOG_LEVEL=debug renovate/renovate:38.80.0 --platform=local --repository-cache=reset --dry-run=full
```

Creates no PR.
