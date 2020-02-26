# python-qbo
[![Build Status](https://travis-ci.com/SebRut/python-qbo.svg?branch=master)](https://travis-ci.com/SebRut/python-qbo)
[![PyPI](https://img.shields.io/pypi/v/python-qbo.svg)](https://pypi.org/project/python-qbo/)
[![Coverage Status](https://coveralls.io/repos/github/SebRut/python-qbo/badge.svg?branch=master)](https://coveralls.io/github/SebRut/python-qbo?branch=master)
[![CodeFactor](https://www.codefactor.io/repository/github/sebrut/python-qbo/badge)](https://www.codefactor.io/repository/github/sebrut/python-qbo)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FSebRut%2Fpython-qbo.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FSebRut%2Fpython-qbo?ref=badge_shield)

## This project is not being developed atm due to me not having access to a Qbo machine anymore

## Installation

`pip install python-qbo`

## Usage
Import the package: 
```python
from qbo import Qbo
```

Obtain a qbo instance:
```python
qbo = Qbo("https://{QBO_URL}/")
```

Get the name of the machine:
```python
print(qbo.name())
```

Get maintenance status:

```python
print(qbo.maintenance_status())
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FSebRut%2Fpython-qbo.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FSebRut%2Fpython-qbo?ref=badge_large)
