# Contributing

## Ground rules

* Source lives under `src/PackageUpdateSearch/`. Keep pull requests focused on
  one change.
* Run the test suite before opening a pull request.

## Local development

```bash
pip install -e .
pip install -e ".[test]"   # optional, for tests
```

## Tests

```bash
pytest
```

## Releases

Published to TestPyPI (https://test.pypi.org/project/PackageUpdateSearch/).
Dr. Berhe owns the TestPyPI project; student contributors are maintainers.
See `readme.md` for the ownership/role breakdown.

## Commit messages

Short imperative subject, then a body explaining why. Reference issues where
relevant.
