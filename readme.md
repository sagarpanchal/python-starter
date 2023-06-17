# Python Starter

A python boilerplate with Visual Studio Code integration (linting, formatting and debugging)

## Getting Started

- Clone and open the directory in Visual Studio Code.

### Create virtual environment

```shell
python -m venv .venv
```

> Before adding packages via pip, activate virtual environment
>
> > In Visual Studio Code, when recommanded extensions are installed, integrated terminal will automatically activate virtual environment on init.

### Activate virtual environment

```shell
source /.venv/bin/activate
```

### Installing requirements

```shell
pip install -r requirements.txt
```

### Adding new requirements

- install numpy
  ```shell
  pip install numpy
  ```
- save all dependencies to requirements.txt
  ```shell
  pip freeze > requirements.txt
  ```
