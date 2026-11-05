---
title: set_license method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Licenses the component."
type: docs
url: /python-net/groupdocs.assembly/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_name}

Licenses the component.

Tries to find the license in the following locations:

- Explicit path.
- The folder that contains the GroupDocs component assembly.
- The folder that contains the client's calling assembly.
- The folder that contains the entry (startup) assembly.
- An embedded resource in the client's calling assembly.

```python
def set_license(self, license_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| license_name | `str` | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode. |

### Example

```python
import os
from groupdocs.assembly import License

def set_license_from_stream():
    # Resolve the license path from the environment, with a local fallback
    license_path = os.environ.get("GROUPDOCS_LIC_PATH", "./GroupDocs.Assembly.lic")

    if os.path.exists(license_path):
        with open(license_path, "rb") as stream:
            License().set_license(stream)
        print("License set successfully.")
    else:
        print("License file not found. Running in evaluation mode.")
```

## set_license {#stream}

Licenses the component.

Use this method to load a license from a stream.

```python
def set_license(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | A stream that contains the license. |

### Example

```python
import os
from groupdocs.assembly import License

license_path = os.getenv("GROUPDOCS_LIC_PATH", "./GroupDocs.Assembly.lic")
if os.path.exists(license_path):
    with open(license_path, "rb") as stream:
        License().set_license(stream)
    print("License set successfully.")
else:
    print("License file not found. Running in evaluation mode.")
```

### Aliases

These names call `set_license` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `set_license_file` | `set_license_file(license_name)` |
| `set_license_string` | `set_license_string(license_name)` |
| `set_license_stream` | `set_license_stream(stream)` |
| `set_license_streams` | `set_license_streams(stream)` |

### See Also
* class [`License`](/assembly/python-net/groupdocs.assembly/license/)
