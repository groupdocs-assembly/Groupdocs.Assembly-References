---
title: DocumentAssemblyOptions enumeration
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/documentassemblyoptions/
is_root: false
weight: 80
---

## DocumentAssemblyOptions enumeration

Specifies options controlling behavior of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler) while assembling a document.



The DocumentAssemblyOptions type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NONE | Specifies default options. |
| ALLOW_MISSING_MEMBERS | Specifies that missing object members should be treated as null literals by the assembler. This option <br/>affects only access to instance (that is, non-static) object members and extension methods. If this <br/>option is not set, the assembler throws an exception when encounters a missing object member. |
| UPDATE_FIELDS_AND_FORMULAS | Specifies that fields of result Word Processing documents and formulas of result Spreadsheet documents <br/>should be updated by the assembler. |
| REMOVE_EMPTY_PARAGRAPHS | Specifies that the assembler should remove paragraphs becoming empty after template syntax tags are <br/>removed or replaced with empty values. |
| INLINE_ERROR_MESSAGES | Specifies that the assembler should inline template syntax error messages into output documents. <br/>If this option is not set, the assembler throws an exception when encounters a syntax error. |
| USE_SPREADSHEET_DATA_TYPES | Relates to Spreadsheet documents only. Specifies that evaluated expression results should be mapped to <br/>corresponding Spreadsheet data types, which also affects their default formatting within cells. If this <br/>option is not set, expression results are always written as strings by the assembler. This option has <br/>no effect when expression results are formatted using template syntax - expression results are always <br/>written as strings then as well. |



### See Also
* module [`groupdocs.assembly`](..)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
