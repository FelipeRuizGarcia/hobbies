# Testing with Pytest and Unittest

Test Key Concepts, make sure to understand those in great detail.
```
Mock
Patch
Monkeypatch
Fixture
```

#### Pytest

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

https://realpython.com/python-mock-library/
<br>
https://realpython.com/pytest-python-testing/