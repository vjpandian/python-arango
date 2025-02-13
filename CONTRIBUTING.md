# Contributing

Set up dev environment:
```shell
cd ~/your/repository/fork  # Activate venv if you have one (recommended)
pip install -e .[dev]      # Install dev dependencies (e.g. black, mypy, pre-commit)
pre-commit install         # Install git pre-commit hooks
```

Run unit tests with coverage:

```shell
py.test --cov=arango --cov-report=html  # Open htmlcov/index.html in your browser
```

For a more comprehensive test suite, run:

```shell
./tester.sh  # Requires docker
```

Build and test documentation:

```shell
python -m sphinx docs docs/_build  # Open docs/_build/index.html in your browser
```

Thank you for your contribution!
