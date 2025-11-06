# simple-modern-uv (Scripts Fork)

Fork of [jlevy/simple-modern-uv](https://github.com/jlevy/simple-modern-uv) adapted for Python scripts rather than packages. Removes package-building and PyPI publishing features while keeping modern dev tooling (uv, ruff, basedpyright, pytest).

For full documentation, see the [original README](https://github.com/jlevy/simple-modern-uv).

## Quick Start

Install uv:
```shell
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Install copier:
```shell
uv tool install copier
```

Use this template:
```shell
copier copy gh:maedmatt/simple-modern-uv YOURNEWPROJECT
```
