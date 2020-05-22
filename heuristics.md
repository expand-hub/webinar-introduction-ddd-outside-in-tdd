# Webinar Heuristics

## Readable and maintainable codebase
Be intentional with the codebase also applies to the tests. As such, we prefer to use the `Given` abstraction to instrument the state of the system under test.

## Avoid coupling, test behaviour
As software engineering community, we love to discuss coupling. One of the coupling forms is coupling your tests to the implementation. Focus on testing the behaviour, not the structure.

## Avoid sunken cost fallacy
As part of the TDD lifecycle, some tests will be deleted. They are there as scaffolding, as allows for quicker integration. However, delete it, once you test the expected behaviour.
