# Herdr SDK for Workshop

This SDK provides herdr, a terminal multiplexer for AI coding agents.
It enables agents to manage panes, persist sessions across disconnects,
and provides a socket API for agent automation and state tracking.

---

## Reference workshop

A minimal workshop:

```yaml
# workshop.yaml
name: herdr-demo
base: ubuntu@24.04
sdks:
  - name: herdr
    source: https://github.com/bschimke95/herdr-workshop-sdk
```

This demonstrates a basic environment with herdr available on the path.

---

## Using the SDK

### Launch and Primary workflow

Once the workshop is ready:

```bash
workshop shell
herdr
```

This launches the Herdr server and attaches your client. You can then
launch agents like `omp` directly within the Herdr panes. Sessions are
persisted in the background so you can safely detach (`Ctrl+B Q`).

---

## Documentation and guidance

- [Herdr official documentation](https://herdr.dev/docs)

---

## Contributions

All contributions, including code, documentation updates, and issue reports,
are welcome!

- Open issues or pull requests on the [official repository](https://github.com/bschimke95/herdr-workshop-sdk).

---

## License and copyright

Copyright 2026 bschimke95.

Licensed under the Apache License, Version 2.0.
