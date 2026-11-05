---
title: get_consumption_credit method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Returns the currently consumed number of credits."
type: docs
url: /python-net/groupdocs.assembly/metered/get_consumption_credit/
is_root: false
weight: 1010
---


## get_consumption_credit

Returns the currently consumed number of credits.

```python
def get_consumption_credit(cls):
    ...
```

**Returns:** The currently consumed number of credits.

### Example

```python
    from groupdocs.assembly import Metered

    # Ensure a metered license is set before calling
    credit = Metered.get_consumption_credit()
    print("Consumed credit:", credit)
    ```

### See Also
* class [`Metered`](/assembly/python-net/groupdocs.assembly/metered/)
