# interactor-aria-carbs

An Elixir library that drives the CARBS cost-aware Bayesian hyperparameter optimizer through embedded Python.

## What it is for

It suggests hyperparameters, records each observed result with what it cost to get, and keeps the optimizer's state in SQLite, so an Elixir program can tune ordinary and cost-related hyperparameters together. The optimizer's Python package is installed from git when the library first compiles. The `AriaCarbs` module docs describe the calls and the parameter-space formats.

## Build and run

```sh
mix deps.get
mix test
```

## Licence

MIT; see `LICENSE.txt`.
