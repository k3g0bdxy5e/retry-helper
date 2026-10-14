# retry-helper

A small retry helper with jittered exponential backoff and a max-elapsed guard.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install retry-helper
```

## Usage

```python
from retry_helper import retryHelper

result = retryHelper("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
