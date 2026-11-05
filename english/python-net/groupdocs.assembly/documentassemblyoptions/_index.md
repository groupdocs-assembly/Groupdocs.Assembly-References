---
title: DocumentAssemblyOptions class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "DocumentAssemblyOptions enum — GroupDocs.Assembly for Python via .NET API reference."
type: docs
url: /python-net/groupdocs.assembly/documentassemblyoptions/
is_root: false
weight: 40
---


## DocumentAssemblyOptions class

The DocumentAssemblyOptions type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| [NONE](/assembly/python-net/groupdocs.assembly/documentassemblyoptions/none/) | Specifies default options. |
| [ALLOW_MISSING_MEMBERS](/assembly/python-net/groupdocs.assembly/documentassemblyoptions/allow_missing_members/) | Specifies that missing object members should be treated as null literals by the assembler. This option affects only access to instance (that is, non-static) object members and extension methods. If this option is not set, the assembler throws an exception when encounters a missing object member. |
| [UPDATE_FIELDS_AND_FORMULAS](/assembly/python-net/groupdocs.assembly/documentassemblyoptions/update_fields_and_formulas/) | Specifies that fields of result Word Processing documents and formulas of result Spreadsheet documents should be updated by the assembler. |
| [REMOVE_EMPTY_PARAGRAPHS](/assembly/python-net/groupdocs.assembly/documentassemblyoptions/remove_empty_paragraphs/) | Specifies that the assembler should remove paragraphs becoming empty after template syntax tags are removed or replaced with empty values. |
| [INLINE_ERROR_MESSAGES](/assembly/python-net/groupdocs.assembly/documentassemblyoptions/inline_error_messages/) | Specifies that the assembler should inline template syntax error messages into output documents. If this option is not set, the assembler throws an exception when encounters a syntax error. |
| [USE_SPREADSHEET_DATA_TYPES](/assembly/python-net/groupdocs.assembly/documentassemblyoptions/use_spreadsheet_data_types/) | Relates to Spreadsheet documents only. Specifies that evaluated expression results should be mapped to corresponding Spreadsheet data types, which also affects their default formatting within cells. If this option is not set, expression results are always written as strings by the assembler. This option has no effect when expression results are formatted using template syntax - expression results are always written as strings then as well. |

### See Also
* module [`groupdocs.assembly`](/assembly/python-net/groupdocs.assembly/)
