---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new FolderFontSource instance."
type: docs
url: /python-net/groupdocs.assembly/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Initializes a new FolderFontSource instance.

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| folder_path | `str` | Path to the folder that contains TrueType fonts. |
| search_option | `SearchOption` | Specifies whether to search the current folder, or the current folder and all sub‑folders. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `folder_path` is None. |
| `FileNotFoundError` | When the path specified in `folder_path` can't be located. |

### See Also
* class [`FolderFontSource`](/assembly/python-net/groupdocs.assembly/folderfontsource/)
