# Testing with Pytest and Unittest

#### Key Concepts
Test Key Concepts: make sure to understand those in great detail.
* Mock
https://docs.python.org/3/library/unittest.mock.html#quick-guide

* Patch
https://docs.python.org/3/library/unittest.mock.html#where-to-patch

    * Patch Decorators
    https://docs.python.org/3/library/unittest.mock-examples.html#patch-decorators
    
Monkeypatch 

Fixture | from Pytests
<br>
https://docs.pytest.org/en/latest/explanation/fixtures.html#what-fixtures-are

TestCase | from unittest
<br>
https://www.digitalocean.com/community/tutorials/how-to-use-unittest-to-write-a-test-case-for-a-function-in-python#defining-a-testcase-subclass
* setUp() method
* tearDown()

#### Types of testing

https://realpython.com/python-testing/#unit-tests-vs-integration-tests

* Unit Test
* Integration Tests
* Functional Test


### Pytest

Fixtures
pytests looks for the  `conftest.py` file in the file tree directory
you can use any fixture that are defined in a particular conftest.py throughout the files parent
directory and in any subdirectories. 



Pytest provides a monkeypatch fixture to replace values and behaviors at runtime and encapsulate it with local scope.


```
    @pytest.fixture(autouse=True)
    def disable_networks_call(monkeypatch):
        
```

Pytest Key features
```
#### Test Parametrization
#### Test Marks
```

#### Debug Pytest


```
Instead of
> import pdb; pdb.set_trace()
$ python3 -m pdb

Use
> import pytest; pytest.set_trace()
$ python3 -m pytest
```


## References
Read and get your hands dirty to master the key concepts

Unittest Python Library
<br>
https://docs.python.org/3/library/unittest.html
<br>

https://realpython.com/python-mock-library/
<br>
https://realpython.com/pytest-python-testing/
<br>
https://www.digitalocean.com/community/tutorials/how-to-use-unittest-to-write-a-test-case-for-a-function-in-python

