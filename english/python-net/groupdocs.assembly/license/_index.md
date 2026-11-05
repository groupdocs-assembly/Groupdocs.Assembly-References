---
title: License class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides methods to license the component."
type: docs
url: /python-net/groupdocs.assembly/license/
is_root: false
weight: 120
---


## License class

Provides methods to license the component.

The License type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly/license/__init__/) | Initializes a new License instance. |

### Methods
| Method | Description |
| :- | :- |
| [set_license](/assembly/python-net/groupdocs.assembly/license/set_license/#license_name) | Licenses the component. |
| [set_license](/assembly/python-net/groupdocs.assembly/license/set_license/#stream) | Licenses the component. |

### Properties
| Property | Description |
| :- | :- |
| [is_licensed](/assembly/python-net/groupdocs.assembly/license/is_licensed/) | The property indicates whether a valid license has been applied; returns True if a license is applied, otherwise False. |

### Example

```python
from groupdocs.assembly import License
import os

# Apply license from a file path
License().set_license("GroupDocs.Assembly.lic")

# Apply license from a binary stream (e.g., when bundled as a resource)
license_path = os.environ.get("GROUPDOCS_LIC_PATH", "GroupDocs.Assembly.lic")
if os.path.exists(license_path):
    with open(license_path, "rb") as stream:
        License().set_license(stream)
    print("License applied successfully.")
else:
    print("License file not found. Running in evaluation mode.")
```

### See Also
* module [`groupdocs.assembly`](/assembly/python-net/groupdocs.assembly/)
