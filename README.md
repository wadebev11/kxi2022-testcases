# KXI2022 Test Cases
====

## Organization

* `unit/` - Unit tests
* `integration/` - Integration tests
* Other types like acceptance tests, performance tests, and others can be added. The convention can be followed: `<type>/`

### Subtypes

If you want to add a subtype, you can add a directory with the same name as the type. For example, under `semantics/` there is the `double_decl/` directory.

## Unit Tests

### Naming

`<short_description>.<pass/fail>.kxi`

Each test should have a short description as the filename. For example, if you are testing that the if condition is in fact a boolean expression, the file name could be `bool_if_cond`.

Additionally, if the test is supposed to pass, add `.pass` after the description. If the test is supposed to fail, add `.fail` after the description.

### Writing tests

Some tests are simple enough, but please add comments to explain what is being tested if it is not obvious.

