# Python notes

## Virtual environments

```bash
python -m venv .venv
source .venv/bin/activate
```

## Type hints

```python
def greet(name: str) -> str:
    return f"hi {name}"
```

## Context managers

```python
with open("f.txt") as fh:
    data = fh.read()
```
