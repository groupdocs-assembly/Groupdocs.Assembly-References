---
title: CsvDataSource
second_title: GroupDocs.Assembly for Java API Reference
description: Provides access to data of a CSV file or stream to be used while assembling a document.
type: docs
weight: 12
url: /java/com.groupdocs.assembly/csvdatasource/
---
**Inheritance:**
java.lang.Object
```
public class CsvDataSource
```

Provides access to data of a CSV file or stream to be used while assembling a document.

To access data of the corresponding file or stream while assembling a document, pass an instance of this class as a data source to one of [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). assembleDocument overloads.

In template documents, a [CsvDataSource](../../com.groupdocs.assembly/csvdatasource) instance should be treated in the same way as if it was a [DataTable](../../com.groupdocs.assembly.system.data/datatable) instance. For more information, see template syntax reference(https://docs.groupdocs.com/display/assemblyjava/Template+Syntax+-+Part+1+of+2.TemplateSyntax-Part1of2-UsingDataSources).

Data types of comma-separated values are determined automatically upon their string representations. So in template documents, you can work with typed values rather than just strings. The engine is capable to automatically recognize values of the following types:

 *   java.lang.Long 
 *   java.lang.Double 
 *   java.lang.Boolean 
 *   java.util.Date 
 *   java.lang.String 

Note that for automatic recognition of data types to work, string representations of comma-separated values should be formed using invariant culture settings.

To override default behavior of CSV data loading, initialize and pass a [CsvDataLoadOptions](../../com.groupdocs.assembly/csvdataloadoptions) instance to a constructor of this class.
## Constructors

| Constructor | Description |
| --- | --- |
| [CsvDataSource(String csvPath)](#CsvDataSource-java.lang.String-) | Creates a new data source with data from a CSV file using default options for parsing CSV data. |
| [CsvDataSource(String csvPath, CsvDataLoadOptions options)](#CsvDataSource-java.lang.String-com.groupdocs.assembly.CsvDataLoadOptions-) | Creates a new data source with data from a CSV file using the specified options for parsing CSV data. |
| [CsvDataSource(InputStream csvStream)](#CsvDataSource-java.io.InputStream-) | Creates a new data source with data from a CSV stream using default options for parsing CSV data. |
| [CsvDataSource(InputStream csvStream, CsvDataLoadOptions options)](#CsvDataSource-java.io.InputStream-com.groupdocs.assembly.CsvDataLoadOptions-) | Creates a new data source with data from a CSV stream using the specified options for parsing CSV data. |
### CsvDataSource(String csvPath) {#CsvDataSource-java.lang.String-}
```
public CsvDataSource(String csvPath)
```


Creates a new data source with data from a CSV file using default options for parsing CSV data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| csvPath | java.lang.String | The path to the CSV file to be used as the data source. |

### CsvDataSource(String csvPath, CsvDataLoadOptions options) {#CsvDataSource-java.lang.String-com.groupdocs.assembly.CsvDataLoadOptions-}
```
public CsvDataSource(String csvPath, CsvDataLoadOptions options)
```


Creates a new data source with data from a CSV file using the specified options for parsing CSV data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| csvPath | java.lang.String | The path to the CSV file to be used as the data source. |
| options | [CsvDataLoadOptions](../../com.groupdocs.assembly/csvdataloadoptions) | Options for parsing the CSV data. |

### CsvDataSource(InputStream csvStream) {#CsvDataSource-java.io.InputStream-}
```
public CsvDataSource(InputStream csvStream)
```


Creates a new data source with data from a CSV stream using default options for parsing CSV data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| csvStream | java.io.InputStream | The stream of CSV data to be used as the data source. |

### CsvDataSource(InputStream csvStream, CsvDataLoadOptions options) {#CsvDataSource-java.io.InputStream-com.groupdocs.assembly.CsvDataLoadOptions-}
```
public CsvDataSource(InputStream csvStream, CsvDataLoadOptions options)
```


Creates a new data source with data from a CSV stream using the specified options for parsing CSV data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| csvStream | java.io.InputStream | The stream of CSV data to be used as the data source. |
| options | [CsvDataLoadOptions](../../com.groupdocs.assembly/csvdataloadoptions) | Options for parsing the CSV data. |

