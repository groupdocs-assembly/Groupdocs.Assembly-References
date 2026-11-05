---
title: assemble_document method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path…"
type: docs
url: /python-net/groupdocs.assembly/documentassembler/assemble_document/
is_root: false
weight: 1010
---


## assemble_document {#source_path-target_path-data_source_infos}

Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path using default [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/).

```python
def assemble_document(self, source_path, target_path, data_source_infos):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_path | `str` | The path to a template document to be populated with data. |
| target_path | `str` | The path to a result document. |
| data_source_infos | `list[DataSourceInfo]` | Provides information on data source objects to be used. |

**Returns:** bool: A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the `DocumentAssembler.Options` property includes the `DocumentAssemblyOptions.InlineErrorMessages` option.

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler

assembler = DocumentAssembler()
assembler.assemble_document(
    "inserting-hyperlink.msg",
    "inserting-hyperlink-report.msg",
    [
        DataSourceInfo("https://harborlane.example/", "uriExpression"),
        DataSourceInfo("Harbor Lane Provisions", "displayTextExpression"),
        DataSourceInfo("Harbor Lane Provisions <orders@harborlane.example>", "sender"),
        DataSourceInfo(
            ["Quayside Bistro <orders@quaysidebistro.example>", "jonas.weber@harborlane.example"],
            "recipients",
        ),
        DataSourceInfo("amara.osei@harborlane.example", "cc"),
        DataSourceInfo("Inserting hyperlink", "subject"),
    ],
)
```

## assemble_document {#source_path-target_path-load_save_options-data_source_infos}

Loads a template document from the specified source path, populates it with data from the given sources, and saves the result to the target path using the provided LoadSaveOptions.

```python
def assemble_document(self, source_path, target_path, load_save_options, data_source_infos):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_path | `str` | The path to a template document to be populated with data. |
| target_path | `str` | The path to a result document. |
| load_save_options | `LoadSaveOptions` | Specifies additional options for document loading and saving. |
| data_source_infos | `list[DataSourceInfo]` | Provides information on data source objects to be used. |

**Returns:** bool: A flag indicating whether parsing of the template document was successful. The flag is meaningful only if `DocumentAssembler.options` includes the `DocumentAssemblyOptions.inline_error_messages` option.

## assemble_document {#source_stream-target_stream-data_source_infos}

Loads a template document from the specified source stream, populates it with data from the given sources, and writes the result to the target stream using default [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/).

```python
def assemble_document(self, source_stream, target_stream, data_source_infos):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream | `io.RawIOBase` | The stream to read a template document from. |
| target_stream | `io.RawIOBase` | The stream to write the result document. |
| data_source_infos | `list[DataSourceInfo]` | Provides information on data source objects to be used. |

**Returns:** bool: True if parsing of the template document was successful. The flag is meaningful only when the `DocumentAssembler.Options` property includes the `DocumentAssemblyOptions.inline_error_messages` option.

### Example

```python
from datetime import datetime

from groupdocs.assembly import DataSourceInfo, DocumentAssembler

data = {"Title": "Quarterly stock report", "Date": datetime(2015, 3, 31)}

with open("report-cover.docx", "rb") as template, open("report-cover-report.docx", "wb") as report:
    assembler = DocumentAssembler()
    assembler.assemble_document(template, report, DataSourceInfo(data, "report"))
```

## assemble_document {#source_stream-target_stream-load_save_options-data_source_infos}

Loads a template document from the specified source stream, populates it with data from the given sources, and writes the result to the target stream using the provided LoadSaveOptions.

```python
def assemble_document(self, source_stream, target_stream, load_save_options, data_source_infos):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream | `io.RawIOBase` | The stream to read a template document from. |
| target_stream | `io.RawIOBase` | The stream to write the result document. |
| load_save_options | `LoadSaveOptions` | Specifies additional options for document loading and saving. |
| data_source_infos | `list[DataSourceInfo]` | Provides information on data source objects to be used. |

**Returns:** bool: True if parsing of the template document was successful; otherwise False. The flag is meaningful only when the `DocumentAssembler.Options` property includes the `DocumentAssemblyOptions.InlineErrorMessages` option.

### Example

```python
    from groupdocs.assembly import DocumentAssembler, DataSourceInfo, LoadSaveOptions

    with open("inserting-hyperlink.msg", "rb") as src, open("inserting-hyperlink-report.msg", "wb") as tgt:
        assembler = DocumentAssembler()
        assembler.assemble_document(
            src,
            tgt,
            LoadSaveOptions(),
            [
                DataSourceInfo("https://harborlane.example/", "uriExpression"),
                DataSourceInfo("Harbor Lane Provisions", "displayTextExpression"),
                DataSourceInfo("Harbor Lane Provisions <orders@harborlane.example>", "sender"),
                DataSourceInfo(
                    ["Quayside Bistro <orders@quaysidebistro.example>", "jonas.weber@harborlane.example"],
                    "recipients",
                ),
                DataSourceInfo("amara.osei@harborlane.example", "cc"),
                DataSourceInfo("Inserting hyperlink", "subject"),
            ],
        )
    ```

### Aliases

These names call `assemble_document` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `assemble_document_file` | `assemble_document_file(source_path, target_path, load_save_options, data_source_infos)`<br>`assemble_document_file(source_path, target_path, data_source_infos)` |
| `assemble_document_string` | `assemble_document_string(source_path, target_path, load_save_options, data_source_infos)`<br>`assemble_document_string(source_path, target_path, data_source_infos)` |
| `assemble_document_stream` | `assemble_document_stream(source_stream, target_stream, load_save_options, data_source_infos)`<br>`assemble_document_stream(source_stream, target_stream, data_source_infos)` |
| `assemble_document_streams` | `assemble_document_streams(source_stream, target_stream, load_save_options, data_source_infos)`<br>`assemble_document_streams(source_stream, target_stream, data_source_infos)` |

### See Also
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/)
