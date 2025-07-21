# Pre-commit hooks with darker ruff

Pre-commit hook, which runs ruff with darker.
To setup:
- Install [pre-commit](https://pre-commit.com/#intro)
- Add `.pre-commit-config.yaml` to your repo with following content:
```yaml
repos:
-   repo: https://github.com/Mr8lueSky/darker_ruff_pre_commit
    rev: 0a8703f
    hooks:
    -   id: darker-ruff-check
```
- Run `pre-commit install`
