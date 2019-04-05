# Isort hook for pre-commit

> Use [official plugin](https://github.com/pre-commit/mirrors-isort) instead this.

[Isort](https://pypi.python.org/pypi/isort) package for [pre-commit](http://pre-commit.com).

## Using isort with pre-commit

```yaml
-   repo: git://github.com/doublify/pre-commit-isort
    sha: master
    hooks:
    -   id: isort
```
