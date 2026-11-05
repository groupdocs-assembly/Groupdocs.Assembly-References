---
title: Metered class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides methods to work with metered licensing."
type: docs
url: /python-net/groupdocs.assembly/metered/
is_root: false
weight: 140
---


## Metered class

Provides methods to work with metered licensing.

A metered license is applied with the public and private keys of your subscription. Use `set_metered_key` before using the API, then read consumption via `get_consumption_quantity` and `get_consumption_credit`.

The Metered type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly/metered/__init__/) | Initializes a new Metered instance. |

### Methods
| Method | Description |
| :- | :- |
| [get_consumption_credit](/assembly/python-net/groupdocs.assembly/metered/get_consumption_credit/) | Returns the currently consumed number of credits. |
| [get_consumption_quantity](/assembly/python-net/groupdocs.assembly/metered/get_consumption_quantity/) | Returns the currently consumed number of megabytes. |
| [set_metered_key](/assembly/python-net/groupdocs.assembly/metered/set_metered_key/#public_key-private_key) | Enables metered licensing for the component by specifying appropriate public and private metered keys. |

### Example

```python
from groupdocs.assembly import Metered

# Apply metered license
Metered().set_metered_key("PublicKey", "PrivateKey")

# Read consumption data
print("Quantity:", Metered.get_consumption_quantity())
print("Credit:", Metered.get_consumption_credit())
```

### See Also
* module [`groupdocs.assembly`](/assembly/python-net/groupdocs.assembly/)
