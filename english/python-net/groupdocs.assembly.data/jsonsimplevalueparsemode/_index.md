---
title: JsonSimpleValueParseMode enumeration
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/jsonsimplevalueparsemode/
is_root: false
weight: 170
---

## JsonSimpleValueParseMode enumeration

Specifies a mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. 
Such a mode does not affect parsing of date-time values.



The JsonSimpleValueParseMode type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| LOOSE | Specifies the mode where types of JSON simple values are determined upon parsing of their string representations.<br/>For example, the type of 'prop' from the JSON snippet '{ prop: "123" }' is determined as integer in this mode. |
| STRICT | Specifies the mode where types of JSON simple values are determined from JSON notation itself.<br/>For example, the type of 'prop' from the JSON snippet '{ prop: "123" }' is determined as string in this mode. |



### See Also
* module [`groupdocs.assembly.data`](..)
