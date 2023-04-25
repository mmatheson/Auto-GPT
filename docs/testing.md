## Run tests

To run all tests, run the following command:

```
pytest
```

To run just without integration tests:

```
pytest --without-integration
```

To run just without slow integration tests:

```
pytest --without-slow-integration
```

To run tests and see coverage, run the following command:

```
pytest --cov=autogpt --without-integration --without-slow-integration
```
