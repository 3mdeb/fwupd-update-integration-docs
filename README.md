# About

This repository contains source code for firmware update integration product
webpage

# Local development

## Environment setup

```bash
$ virtualenv -p $(which python3) venv
$ source venv/bin/activate
$(venv) pip install mkdocs mkdocs-material pymdown-extensions
```

## Build

```bash
$(venv) mkdocs build
```

## Preview

```bash
$(venv) mkdocs serve
```

# Contribution

Please use GitHub `Pull Request` and `Issues` to collaborate.
