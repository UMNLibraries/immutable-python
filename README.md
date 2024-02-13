# immutable-python

Makes normally mutable Python objects immutable

## Immutable Modules

```python
# some_module.py:
import immutable
immutable.module(__name__)
```

Inspired by the [Existing Options](https://peps.python.org/pep-0726/#existing-options)
implementation in [PEP 726 – Module __setattr__ and __delattr__](https://peps.python.org/pep-0726/).
