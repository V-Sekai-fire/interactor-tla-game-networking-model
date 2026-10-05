# interactor-tla-game-networking-model

TLA+ specifications that model-check networking, consensus and storage designs for multiplayer games before they are built.

## What it is for

Each specification sits beside the model-checker configuration it runs with, so competing designs for queueing, commits, clocks and message scaling can be compared by checking them rather than by argument.

## Build and run

```sh
just run
```

It needs Java; the model checker is vendored in the repository.

## Licence

MIT; see `LICENSE`. The vendored third-party documents and tools keep their own terms.
