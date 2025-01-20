# RexLogger

A stylish console logger with colored output for Python applications.

## Installation

```bash
pip install rexlogger
```

## Usage

```python
from rexlogger import rex

rex.success("Operation successful!")
rex.error("Something went wrong!")
rex.debug("Debug information")
rex.warn("Warning message")
rex.ratelimit("Ratelimit message")
rex.input("Input")
```

## Screenshot
![image](https://github.com/user-attachments/assets/c044e76f-4162-4828-87ae-7ff1070a71ac)

## Features

- Colored output using colorama
- Timestamp prefix
- Four log levels: success, error, debug, and warn
- Easy to use interface

## Requirements

- Python 3.6+
- colorama>=0.4.4
