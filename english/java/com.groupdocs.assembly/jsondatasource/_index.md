---
title: JsonDataSource
second_title: GroupDocs.Assembly for Java API Reference
description: Provides access to data of a JSON file or stream to be used while assembling a document.
type: docs
weight: 27
url: /java/com.groupdocs.assembly/jsondatasource/
---
**Inheritance:**
java.lang.Object
```
public class JsonDataSource
```

Provides access to data of a JSON file or stream to be used while assembling a document.

To access data of the corresponding file or stream while assembling a document, pass an instance of this class as a data source to one of [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). assembleDocument overloads.

In template documents, if a top-level JSON element is an array, a [JsonDataSource](../../com.groupdocs.assembly/jsondatasource) instance should be treated in the same way as if it was a [DataTable](../../com.groupdocs.assembly.system.data/datatable) instance. If a top-level JSON element is an object, a [JsonDataSource](../../com.groupdocs.assembly/jsondatasource) instance should be treated in the same way as if it was a [DataRow](../../com.groupdocs.assembly.system.data/datarow) instance. For more information, see template syntax reference(https://docs.groupdocs.com/display/assemblyjava/Template+Syntax+-+Part+1+of+2\#TemplateSyntax-Part1of2-UsingDataSources).

In template documents, you can work with typed values of JSON elements. For convenience, the engine replaces the set of JSON simple types with the following one:

 *   java.lang.Long 
 *   java.lang.Double 
 *   java.lang.Boolean 
 *   java.util.Date 
 *   java.lang.String 

The engine automatically recognizes values of the extra types upon their JSON representations.

To override default behavior of JSON data loading, initialize and pass a [JsonDataLoadOptions](../../com.groupdocs.assembly/jsondataloadoptions) instance to a constructor of this class.
## Constructors

| Constructor | Description |
| --- | --- |
| [JsonDataSource(String jsonPath)](#JsonDataSource-java.lang.String-) | Creates a new data source with data from a JSON file using default options for parsing JSON data. |
| [JsonDataSource(String jsonPath, JsonDataLoadOptions options)](#JsonDataSource-java.lang.String-com.groupdocs.assembly.JsonDataLoadOptions-) | Creates a new data source with data from a JSON file using the specified options for parsing JSON data. |
| [JsonDataSource(InputStream jsonStream)](#JsonDataSource-java.io.InputStream-) | Creates a new data source with data from a JSON stream using default options for parsing JSON data. |
| [JsonDataSource(InputStream jsonStream, JsonDataLoadOptions options)](#JsonDataSource-java.io.InputStream-com.groupdocs.assembly.JsonDataLoadOptions-) | Initializes a new instance of this class. |
### JsonDataSource(String jsonPath) {#JsonDataSource-java.lang.String-}
```
public JsonDataSource(String jsonPath)
```


Creates a new data source with data from a JSON file using default options for parsing JSON data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jsonPath | java.lang.String | The path to the JSON file to be used as the data source. |

### JsonDataSource(String jsonPath, JsonDataLoadOptions options) {#JsonDataSource-java.lang.String-com.groupdocs.assembly.JsonDataLoadOptions-}
```
public JsonDataSource(String jsonPath, JsonDataLoadOptions options)
```


Creates a new data source with data from a JSON file using the specified options for parsing JSON data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jsonPath | java.lang.String | The path to the JSON file to be used as the data source. |
| options | [JsonDataLoadOptions](../../com.groupdocs.assembly/jsondataloadoptions) | Options for parsing JSON data. |

### JsonDataSource(InputStream jsonStream) {#JsonDataSource-java.io.InputStream-}
```
public JsonDataSource(InputStream jsonStream)
```


Creates a new data source with data from a JSON stream using default options for parsing JSON data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jsonStream | java.io.InputStream | The stream of JSON data to be used as the data source. |

### JsonDataSource(InputStream jsonStream, JsonDataLoadOptions options) {#JsonDataSource-java.io.InputStream-com.groupdocs.assembly.JsonDataLoadOptions-}
```
public JsonDataSource(InputStream jsonStream, JsonDataLoadOptions options)
```


Initializes a new instance of this class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jsonStream | java.io.InputStream |  |
| options | [JsonDataLoadOptions](../../com.groupdocs.assembly/jsondataloadoptions) |  |

