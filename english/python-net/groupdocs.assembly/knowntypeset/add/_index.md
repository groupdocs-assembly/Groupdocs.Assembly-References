---
title: add method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Adds the specified type object to the set."
type: docs
url: /python-net/groupdocs.assembly/knowntypeset/add/
is_root: false
weight: 1010
---


## add {#type}

Adds the specified `type` object to the set.

```python
def add(self, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | `System.Type` | A `type` object to add. |

| Raises | Description |
| :- | :- |
| `ValueError` | - `type` is None. - `type` represents a void type. - `type` represents an invisible type (non-public type or a public nested type with a non-public outer type). - `type` represents a generic type. - `type` represents an array type. - `type` has already been added to the set. |

### Aliases

These names call `add` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `add_type` | `add_type(type)` |

### See Also
* class [`KnownTypeSet`](/assembly/python-net/groupdocs.assembly/knowntypeset/)
