---
title: com.groupdocs.assembly
second_title: GroupDocs.Assembly for Java API Reference
description: Provides classes for generating documents in popular office file formats based upon template documents and data obtained from various sources including databases XML JSON OData objects of custom Java types and more.
type: docs
weight: 10
url: /java/com.groupdocs.assembly/
---

Provides classes for generating documents in popular office file formats based upon template documents and data obtained from various sources including databases, XML, JSON, OData, objects of custom Java types, and more.

The central class of this package is [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). This class incorporates a set of settings to control document generation and performs document generation through its  assembleDocument  overloads.


## Classes

| Class | Description |
| --- | --- |
| [BarcodeSettings](../com.groupdocs.assembly/barcodesettings) | Represents a set of settings controlling barcode generation while assembling a document. |
| [CsvDataLoadOptions](../com.groupdocs.assembly/csvdataloadoptions) | Represents options for parsing CSV data. |
| [CsvDataSource](../com.groupdocs.assembly/csvdatasource) | Provides access to data of a CSV file or stream to be used while assembling a document. |
| [DataSourceInfo](../com.groupdocs.assembly/datasourceinfo) | Provides information on a single data source object to be used to assemble a document from a template. |
| [DocumentAssembler](../com.groupdocs.assembly/documentassembler) | Provides routines to populate template documents with data and a set of settings to control these routines. |
| [DocumentAssemblyOptions](../com.groupdocs.assembly/documentassemblyoptions) | A utility class providing constants. |
| [DocumentTable](../com.groupdocs.assembly/documenttable) | Provides access to data of a single table (or spreadsheet) located in an external document to be used while assembling a document. |
| [DocumentTableCollection](../com.groupdocs.assembly/documenttablecollection) | Represents a read-only collection of [DocumentTable](../com.groupdocs.assembly/documenttable) objects of a particular [DocumentTableSet](../com.groupdocs.assembly/documenttableset) instance. |
| [DocumentTableColumn](../com.groupdocs.assembly/documenttablecolumn) | Represents a single column of a particular [DocumentTable](../com.groupdocs.assembly/documenttable) object. |
| [DocumentTableColumnCollection](../com.groupdocs.assembly/documenttablecolumncollection) | Represents a read-only collection of [DocumentTableColumn](../com.groupdocs.assembly/documenttablecolumn) objects of a particular [DocumentTable](../com.groupdocs.assembly/documenttable) instance. |
| [DocumentTableLoadArgs](../com.groupdocs.assembly/documenttableloadargs) | Provides data for the [IDocumentTableLoadHandler\#handle-com.groupdocs.assembly.DocumentTableLoadArgs-](../com.groupdocs.assembly/idocumenttableloadhandler\#handle-com.groupdocs.assembly.DocumentTableLoadArgs-) method. |
| [DocumentTableOptions](../com.groupdocs.assembly/documenttableoptions) | Provides a set of options to control extraction of data from a document table. |
| [DocumentTableRelation](../com.groupdocs.assembly/documenttablerelation) | Represents a parent-child relationship between two [DocumentTable](../com.groupdocs.assembly/documenttable) objects. |
| [DocumentTableRelationCollection](../com.groupdocs.assembly/documenttablerelationcollection) | Represents the collection of [DocumentTableRelation](../com.groupdocs.assembly/documenttablerelation) objects of a single [DocumentTableSet](../com.groupdocs.assembly/documenttableset) instance. |
| [DocumentTableSet](../com.groupdocs.assembly/documenttableset) | Provides access to data of multiple tables (or spreadsheets) located in an external document to be used while assembling a document. |
| [FileFormat](../com.groupdocs.assembly/fileformat) | A utility class providing constants. |
| [JsonDataLoadOptions](../com.groupdocs.assembly/jsondataloadoptions) | Represents options for parsing JSON data. |
| [JsonDataSource](../com.groupdocs.assembly/jsondatasource) | Provides access to data of a JSON file or stream to be used while assembling a document. |
| [JsonSimpleValueParseMode](../com.groupdocs.assembly/jsonsimplevalueparsemode) | A utility class providing constants. |
| [KnownTypeSet](../com.groupdocs.assembly/knowntypeset) | Represents an unordered set (that is, a collection of unique items) containing java.lang.Class objects which fully or partially qualified names can be used within document templates to invoke the corresponding types' static members, perform type casts, etc. |
| [License](../com.groupdocs.assembly/license) | Provides methods to license the component. |
| [LoadSaveOptions](../com.groupdocs.assembly/loadsaveoptions) | Specifies additional options for loading and saving of a document to be assembled. |
| [Metered](../com.groupdocs.assembly/metered) | Provides methods to work with metered licensing. |
| [XmlDataLoadOptions](../com.groupdocs.assembly/xmldataloadoptions) | Represents options for XML data loading. |
| [XmlDataSource](../com.groupdocs.assembly/xmldatasource) | Provides access to data of an XML file or stream to be used while assembling a document. |

## Interfaces

| Interface | Description |
| --- | --- |
| [IDocumentTableLoadHandler](../com.groupdocs.assembly/idocumenttableloadhandler) | Overrides default loading of [DocumentTable](../com.groupdocs.assembly/documenttable) objects while creating a [DocumentTableSet](../com.groupdocs.assembly/documenttableset) instance. |
