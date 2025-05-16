---
title: groupdocs.assembly.data
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/
is_root: false
weight: 10
---

Provides classes for accessing data of external documents to be used while assembling a document.

### Classes
| Class | Description |
| :- | :- |
| [`CsvDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions) | Represents options for parsing CSV data. |
| [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource) | Provides access to data of a CSV file or stream to be used while assembling a document. |
| [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) | Provides access to data of a single table (or spreadsheet) located in an external document to be used while <br/>assembling a document. |
| [`DocumentTableCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablecollection) | Represents a read-only collection of [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) objects of a particular [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) <br/>instance. |
| [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) | Represents a single column of a particular [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) object. |
| [`DocumentTableColumnCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection) | Represents a read-only collection of [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) objects of a particular <br/>[`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) instance. |
| [`DocumentTableLoadArgs`](/assembly/python-net/groupdocs.assembly.data/documenttableloadargs) | Provides data for the [`IDocumentTableLoadHandler.handle`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler/handle) method. |
| [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions) | Provides a set of options to control extraction of data from a document table. |
| [`DocumentTableRelation`](/assembly/python-net/groupdocs.assembly.data/documenttablerelation) | Represents a parent-child relationship between two [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) objects. |
| [`DocumentTableRelationCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablerelationcollection) | Represents the collection of [`DocumentTableRelation`](/assembly/python-net/groupdocs.assembly.data/documenttablerelation) objects of a single [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) <br/>instance. |
| [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) | Provides access to data of multiple tables (or spreadsheets) located in an external document to be used while <br/>assembling a document. Also, enables to define parent-child relations for the document tables thus simplifying<br/>access to related data within template documents. |
| [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler) | Overrides default loading of [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) objects while creating a [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) <br/>instance. |
| [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions) | Represents options for parsing JSON data. |
| [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource) | Provides access to data of a JSON file or stream to be used while assembling a document. |
| [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions) | Represents options for XML data loading. |
| [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource) | Provides access to data of an XML file or stream to be used while assembling a document. |


### Enumerations
| Enumeration | Description |
| :- | :- |
| [`JsonSimpleValueParseMode`](/assembly/python-net/groupdocs.assembly.data/jsonsimplevalueparsemode) | Specifies a mode for parsing JSON simple values (null, boolean, number, integer, and string) while loading JSON. <br/>Such a mode does not affect parsing of date-time values. |


