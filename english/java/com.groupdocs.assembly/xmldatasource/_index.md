---
title: XmlDataSource
second_title: GroupDocs.Assembly for Java API Reference
description: Provides access to data of an XML file or stream to be used while assembling a document.
type: docs
weight: 34
url: /java/com.groupdocs.assembly/xmldatasource/
---
**Inheritance:**
java.lang.Object
```
public class XmlDataSource
```

Provides access to data of an XML file or stream to be used while assembling a document.

To access data of the corresponding file or stream while assembling a document, pass an instance of this class as a data source to one of [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). assembleDocument overloads.

In template documents, if a top-level XML element contains only a list of elements of the same type, an [XmlDataSource](../../com.groupdocs.assembly/xmldatasource) instance should be treated in the same way as if it was a [DataTable](../../com.groupdocs.assembly.system.data/datatable) instance. Otherwise, an [XmlDataSource](../../com.groupdocs.assembly/xmldatasource) instance should be treated in the same way as if it was a [DataRow](../../com.groupdocs.assembly.system.data/datarow) instance. For more information, see template syntax reference(https://docs.groupdocs.com/display/assemblyjava/Template+Syntax+-+Part+1+of+2\#TemplateSyntax-Part1of2-UsingDataSources).

When XML Schema Definition is passed to a constructor of this class, data types of values of simple XML elements and attributes are determined according to the schema. So in template documents, you can work with typed values rather than just strings.

When XML Schema Definition is not passed to a constructor of this class, data types of values of simple XML elements and attributes are determined automatically upon their string representations. So in template documents, you can work with typed values in this case as well. The engine is capable to automatically recognize values of the following types:

 *   java.lang.Long 
 *   java.lang.Double 
 *   java.lang.Boolean 
 *   java.util.Date 
 *   java.lang.String 

Note that for automatic recognition of data types to work, string representations of values of simple XML elements and attributes should be formed using invariant culture settings.

To override default behavior of XML data loading, initialize and pass a [XmlDataLoadOptions](../../com.groupdocs.assembly/xmldataloadoptions) instance to a constructor of this class.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmlDataSource(String xmlPath)](#XmlDataSource-java.lang.String-) | Creates a new data source with data from an XML file using default options for XML data loading. |
| [XmlDataSource(InputStream xmlStream)](#XmlDataSource-java.io.InputStream-) | Creates a new data source with data from an XML stream using default options for XML data loading. |
| [XmlDataSource(String xmlPath, String xmlSchemaPath)](#XmlDataSource-java.lang.String-java.lang.String-) | Creates a new data source with data from an XML file using an XML Schema Definition file. |
| [XmlDataSource(InputStream xmlStream, InputStream xmlSchemaStream)](#XmlDataSource-java.io.InputStream-java.io.InputStream-) | Creates a new data source with data from an XML stream using an XML Schema Definition stream. |
| [XmlDataSource(String xmlPath, XmlDataLoadOptions options)](#XmlDataSource-java.lang.String-com.groupdocs.assembly.XmlDataLoadOptions-) | Creates a new data source with data from an XML file using the specified options for XML data loading. |
| [XmlDataSource(InputStream xmlStream, XmlDataLoadOptions options)](#XmlDataSource-java.io.InputStream-com.groupdocs.assembly.XmlDataLoadOptions-) | Initializes a new instance of this class. |
| [XmlDataSource(String xmlPath, String xmlSchemaPath, XmlDataLoadOptions options)](#XmlDataSource-java.lang.String-java.lang.String-com.groupdocs.assembly.XmlDataLoadOptions-) | Creates a new data source with data from an XML file using an XML Schema Definition file. |
| [XmlDataSource(InputStream xmlStream, InputStream xmlSchemaStream, XmlDataLoadOptions options)](#XmlDataSource-java.io.InputStream-java.io.InputStream-com.groupdocs.assembly.XmlDataLoadOptions-) | Initializes a new instance of this class. |
### XmlDataSource(String xmlPath) {#XmlDataSource-java.lang.String-}
```
public XmlDataSource(String xmlPath)
```


Creates a new data source with data from an XML file using default options for XML data loading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlPath | java.lang.String | The path to the XML file to be used as the data source. |

### XmlDataSource(InputStream xmlStream) {#XmlDataSource-java.io.InputStream-}
```
public XmlDataSource(InputStream xmlStream)
```


Creates a new data source with data from an XML stream using default options for XML data loading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | The stream of XML data to be used as the data source. |

### XmlDataSource(String xmlPath, String xmlSchemaPath) {#XmlDataSource-java.lang.String-java.lang.String-}
```
public XmlDataSource(String xmlPath, String xmlSchemaPath)
```


Creates a new data source with data from an XML file using an XML Schema Definition file. Default options are used for XML data loading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlPath | java.lang.String | The path to the XML file to be used as the data source. |
| xmlSchemaPath | java.lang.String | The path to the XML Schema Definition file that provides schema for the XML file. |

### XmlDataSource(InputStream xmlStream, InputStream xmlSchemaStream) {#XmlDataSource-java.io.InputStream-java.io.InputStream-}
```
public XmlDataSource(InputStream xmlStream, InputStream xmlSchemaStream)
```


Creates a new data source with data from an XML stream using an XML Schema Definition stream. Default options are used for XML data loading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream | The stream of XML data to be used as the data source. |
| xmlSchemaStream | java.io.InputStream | The stream of XML Schema Definition that provides schema for the XML data. |

### XmlDataSource(String xmlPath, XmlDataLoadOptions options) {#XmlDataSource-java.lang.String-com.groupdocs.assembly.XmlDataLoadOptions-}
```
public XmlDataSource(String xmlPath, XmlDataLoadOptions options)
```


Creates a new data source with data from an XML file using the specified options for XML data loading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlPath | java.lang.String | The path to the XML file to be used as the data source. |
| options | [XmlDataLoadOptions](../../com.groupdocs.assembly/xmldataloadoptions) | Options for XML data loading. |

### XmlDataSource(InputStream xmlStream, XmlDataLoadOptions options) {#XmlDataSource-java.io.InputStream-com.groupdocs.assembly.XmlDataLoadOptions-}
```
public XmlDataSource(InputStream xmlStream, XmlDataLoadOptions options)
```


Initializes a new instance of this class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream |  |
| options | [XmlDataLoadOptions](../../com.groupdocs.assembly/xmldataloadoptions) |  |

### XmlDataSource(String xmlPath, String xmlSchemaPath, XmlDataLoadOptions options) {#XmlDataSource-java.lang.String-java.lang.String-com.groupdocs.assembly.XmlDataLoadOptions-}
```
public XmlDataSource(String xmlPath, String xmlSchemaPath, XmlDataLoadOptions options)
```


Creates a new data source with data from an XML file using an XML Schema Definition file. The specified options are used for XML data loading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlPath | java.lang.String | The path to the XML file to be used as the data source. |
| xmlSchemaPath | java.lang.String | The path to the XML Schema Definition file that provides schema for the XML file. |
| options | [XmlDataLoadOptions](../../com.groupdocs.assembly/xmldataloadoptions) | Options for XML data loading. |

### XmlDataSource(InputStream xmlStream, InputStream xmlSchemaStream, XmlDataLoadOptions options) {#XmlDataSource-java.io.InputStream-java.io.InputStream-com.groupdocs.assembly.XmlDataLoadOptions-}
```
public XmlDataSource(InputStream xmlStream, InputStream xmlSchemaStream, XmlDataLoadOptions options)
```


Initializes a new instance of this class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlStream | java.io.InputStream |  |
| xmlSchemaStream | java.io.InputStream |  |
| options | [XmlDataLoadOptions](../../com.groupdocs.assembly/xmldataloadoptions) |  |

