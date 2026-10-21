# Flower classification MLOps

## Commit messages

Commit messages follow the Conventional Commits format:

```text
<type>[optional scope]: <description>
```

Common types are `feat`, `fix`, `docs`, `refactor`, `test`, `chore`, `build`, `ci`,
`perf`, `style`, and `revert`. Use `feat` instead of `add` when adding a feature.

Examples:

```text
feat(data): cache the flower dataset inside the project
fix(model): use the configured image dimensions
docs: explain how to train the model
```

Install the commit-message hook once after cloning the repository:

```shell
python -m pip install pre-commit==4.7.0
pre-commit install --install-hooks
```

The hook rejects invalid messages when `git commit` is executed.
