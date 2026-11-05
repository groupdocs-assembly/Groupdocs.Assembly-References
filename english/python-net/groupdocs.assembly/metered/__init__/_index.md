---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new Metered instance."
type: docs
url: /python-net/groupdocs.assembly/metered/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new Metered instance.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.assembly import License, Metered

Metered().set_metered_key("PublicKey", "PrivateKey")
print("Licensed:", License().is_licensed)
```

### See Also
* class [`Metered`](/assembly/python-net/groupdocs.assembly/metered/)
