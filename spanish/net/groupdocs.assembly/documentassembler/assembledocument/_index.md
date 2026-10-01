---
title: "AssembleDocument"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Carga un documento plantilla desde la ruta de origen especificada, rellena el documento plantilla con datos de la(s) fuente(s) única(s) o múltiples especificadas y guarda el documento resultante en la ruta de destino usando los valores predeterminados de LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /es/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Carga un documento plantilla desde la ruta de origen especificada, rellena el documento plantilla con datos de la(s) fuente(s) única(s) o múltiples especificadas y guarda el documento resultante en la ruta de destino usando los valores predeterminados de [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| sourcePath | String | La ruta a un documento plantilla que será rellenado con datos. |
| targetPath | String | La ruta a un documento resultante. |
| dataSourceInfos | DataSourceInfo[] | Proporciona información sobre los objetos de origen de datos a utilizar. |

### Valor de retorno

Una bandera que indica si el análisis del documento plantilla fue exitoso. La bandera devuelta solo tiene sentido si el valor de la propiedad [`Options`](../options) incluye la opción InlineErrorMessages.

### Ver también

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Carga un documento plantilla desde la ruta de origen especificada, rellena el documento plantilla con datos de la(s) fuente(s) única(s) o múltiples especificadas y guarda el documento resultante en la ruta de destino usando las [`LoadSaveOptions`](../../loadsaveoptions) dadas.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| sourcePath | String | La ruta a un documento plantilla que será rellenado con datos. |
| targetPath | String | La ruta a un documento resultante. |
| loadSaveOptions | LoadSaveOptions | Especifica opciones adicionales para la carga y guardado de documentos. |
| dataSourceInfos | DataSourceInfo[] | Proporciona información sobre los objetos de origen de datos a utilizar. |

### Valor de retorno

Una bandera que indica si el análisis del documento plantilla fue exitoso. La bandera devuelta solo tiene sentido si el valor de la propiedad [`Options`](../options) incluye la opción InlineErrorMessages.

### Ver también

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Carga un documento plantilla desde el flujo de origen especificado, rellena el documento plantilla con datos de la(s) fuente(s) única(s) o múltiples especificadas y guarda el documento resultante en el flujo de destino usando los valores predeterminados de [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| sourceStream | Stream | El flujo para leer un documento plantilla. |
| targetStream | Stream | El flujo para escribir un documento resultante. |
| dataSourceInfos | DataSourceInfo[] | Proporciona información sobre los objetos de origen de datos a utilizar. |

### Valor de retorno

Una bandera que indica si el análisis del documento plantilla fue exitoso. La bandera devuelta solo tiene sentido si el valor de la propiedad [`Options`](../options) incluye la opción InlineErrorMessages.

### Ver también

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Carga un documento plantilla desde el flujo de origen especificado, rellena el documento plantilla con datos de la(s) fuente(s) única(s) o múltiples especificadas y guarda el documento resultante en el flujo de destino usando las [`LoadSaveOptions`](../../loadsaveoptions) proporcionadas.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| sourceStream | Stream | El flujo para leer un documento plantilla. |
| targetStream | Stream | El flujo para escribir un documento resultante. |
| loadSaveOptions | LoadSaveOptions | Especifica opciones adicionales para la carga y guardado de documentos. |
| dataSourceInfos | DataSourceInfo[] | Proporciona información sobre los objetos de origen de datos a utilizar. |

### Valor de retorno

Una bandera que indica si el análisis del documento plantilla fue exitoso. La bandera devuelta solo tiene sentido si el valor de la propiedad [`Options`](../options) incluye la opción InlineErrorMessages.

### Ver también

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
