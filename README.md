# interactor-aria-carbs

An Elixir library that drives the CARBS cost-aware Bayesian hyperparameter optimizer through embedded Python.

## What it is for

It suggests hyperparameters and records each observed result with what it cost to get, so an Elixir program can tune ordinary and cost-related hyperparameters together. The optimizer instances live in memory for the life of the application. The optimizer's Python package is installed from git when the library first compiles. The `init/2` docs in `AriaCarbs` show the parameter-space formats.

## Use it

```elixir
{:aria_carbs, git: "https://github.com/V-Sekai-fire/interactor-aria-carbs.git"}
```

## Build and run

```sh
mix deps.get
mix test
```

## Licence

MIT; see `LICENSE.txt`.
