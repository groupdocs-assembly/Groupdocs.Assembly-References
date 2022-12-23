---
title: AssembleDocument
second_title: GroupDocs.Assembly for .NET API Reference
description: Loads a template document from the specified source path populates the template document with data from the specified single or multiple sources and stores the result document to the target path using default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions.
type: docs
weight: 50
url: /net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path using default [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | The path to a template document to be populated with data. |
| targetPath | String | The path to a result document. |
| dataSourceInfos | DataSourceInfo[] | Provides information on data source objects to be used. |

### Return Value

A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the [`Options`](../options) property includes the InlineErrorMessages option.

### See Also

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path using the given [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | The path to a template document to be populated with data. |
| targetPath | String | The path to a result document. |
| loadSaveOptions | LoadSaveOptions | Specifies additional options for document loading and saving. |
| dataSourceInfos | DataSourceInfo[] | Provides information on data source objects to be used. |

### Return Value

A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the [`Options`](../options) property includes the InlineErrorMessages option.

### See Also

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Loads a template document from the specified source stream, populates the template document with data from the specified single or multiple sources, and stores the result document to the target stream using default [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | Stream | The stream to read a template document from. |
| targetStream | Stream | The stream to write a result document. |
| dataSourceInfos | DataSourceInfo[] | Provides information on data source objects to be used. |

### Return Value

A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the [`Options`](../options) property includes the InlineErrorMessages option.

### See Also

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Loads a template document from the specified source stream, populates the template document with data from the specified single or multiple sources, and stores the result document to the target stream using the given [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStream | Stream | The stream to read a template document from. |
| targetStream | Stream | The stream to write a result document. |
| loadSaveOptions | LoadSaveOptions | Specifies additional options for document loading and saving. |
| dataSourceInfos | DataSourceInfo[] | Provides information on data source objects to be used. |

### Return Value

A flag indicating whether parsing of the template document was successful. The returned flag makes sense only if a value of the [`Options`](../options) property includes the InlineErrorMessages option.

### See Also

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
