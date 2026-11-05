---
title: set_metered_key method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Enables metered licensing for the component by specifying appropriate public and private metered keys."
type: docs
url: /python-net/groupdocs.assembly/metered/set_metered_key/
is_root: false
weight: 1030
---


## set_metered_key {#public_key-private_key}

Enables metered licensing for the component by specifying appropriate public and private metered keys.

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| public_key | `str` | The public metered key. |
| private_key | `str` | The private metered key. |

### Example

```python
from groupdocs.assembly import License, Metered

Metered().set_metered_key("PublicKey", "PrivateKey")
print("Licensed:", License().is_licensed)
```

### Aliases

These names call `set_metered_key` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `set_metered_key_file` | `set_metered_key_file(public_key, private_key)` |
| `set_metered_key_string` | `set_metered_key_string(public_key, private_key)` |

### See Also
* class [`Metered`](/assembly/python-net/groupdocs.assembly/metered/)
