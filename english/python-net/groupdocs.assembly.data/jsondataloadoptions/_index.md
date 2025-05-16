---
title: JsonDataLoadOptions class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/jsondataloadoptions/
is_root: false
weight: 130
---

## JsonDataLoadOptions class

Represents options for parsing JSON data.



The JsonDataLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/__init__/#) | Initializes a new instance of this class with default options. |


### Properties
| Property | Description |
| :- | :- |
| [simple_value_parse_mode](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/simple_value_parse_mode) | Gets or sets a mode for parsing JSON simple values (null, boolean, number, integer, and string) <br/>while loading JSON. Such a mode does not affect parsing of date-time values. The default is <br/>[`JsonSimpleValueParseMode.LOOSE`](/assembly/python-net/groupdocs.assembly.data/jsonsimplevalueparsemode#LOOSE). |
| [exact_date_time_parse_format](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_format) | Gets or sets an exact format for parsing JSON date-time values while loading JSON. The default is **null** . |
| [exact_date_time_parse_formats](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/exact_date_time_parse_formats) | Gets or sets exact formats for parsing JSON date-time values while loading JSON. The default is **null** . |
| [always_generate_root_object](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/always_generate_root_object) | Gets or sets a flag indicating whether a generated data source will always contain an object for a JSON root<br/>element. If a JSON root element contains a single complex property, such an object is not created by default. |



### Remarks 


An instance of this class can be passed into constructors of [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource).

### See Also
* module [`groupdocs.assembly.data`](..)
* class [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource)
