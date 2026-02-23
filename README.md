# rust-example

Minimal Rust repository used to validate Janitor behavior.

## Files

- `src/main.rs`: small runnable program
- `Cargo.toml`: crate definition
- `.github/workflows/janitor.yml`: Janitor GitHub Actions workflow

## Run locally

```bash
cargo run
```

## Validate Janitor locally

From this directory, run:

```bash
janitor --no-commit
```

## CI behavior

`janitor.yml` runs on pushes and pull requests to `main` and executes Janitor in `no_commit` mode.
