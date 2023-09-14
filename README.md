
# PYxREL

This is a Python API wrapper for the official xREL API, providing an easy way to access xREL's service and data.


## Usage
You can use this package by importing the `xREL` class directly into your Python scripts. Here's how to do it:

```Python
from PYxREL import xREL

# Create an instance of the xREL class
xrel = xREL()

# Use the xREL API methods
result = xrel.SomeClass.some_method()
```
*SomeClass* should be replaced by *Search*, *P2P*, *ExtInfo* or any other class the xREL API offers methods for.

Please note that currently the OAuth authentication is not implemented. However, all other methods that do not require authentication are available for use. Feel free to make a pull request!


## Documentation

For further information on the implemented methods please have a look at the [official xREL-API documentation](https://www.xrel.to/wiki/1681/API.html).

