---
title: AssembleDocument
second_title: Referencia de API de GroupDocs.Assembly para .NET
description: Carga un documento de plantilla desde la ruta de origen especificada rellena el documento de plantilla con datos de las fuentes únicas o múltiples especificadas y almacena el documento de resultados en la ruta de destino usando default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /es/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Carga un documento de plantilla desde la ruta de origen especificada, rellena el documento de plantilla con datos de las fuentes únicas o múltiples especificadas y almacena el documento de resultados en la ruta de destino usando default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourcePath | String | La ruta a un documento de plantilla que se completará con datos. |
| targetPath | String | La ruta a un documento de resultados. |
| dataSourceInfos | DataSourceInfo[] | Proporciona información sobre los objetos de origen de datos que se utilizarán. |

### Valor_devuelto

Un indicador que indica si el análisis del documento de plantilla se realizó correctamente. La bandera devuelta tiene sentido solo si un valor de la[`Options`](../options) propiedad incluye laInlineErrorMessages opción.

### Ver también

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* espacio de nombres [GroupDocs.Assembly](../../documentassembler)
* asamblea [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Carga un documento de plantilla desde la ruta de origen especificada, rellena el documento de plantilla con datos de las fuentes únicas o múltiples especificadas y almacena el documento de resultados en la ruta de destino utilizando el dado[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourcePath | String | La ruta a un documento de plantilla que se completará con datos. |
| targetPath | String | La ruta a un documento de resultados. |
| loadSaveOptions | LoadSaveOptions | Especifica opciones adicionales para cargar y guardar documentos. |
| dataSourceInfos | DataSourceInfo[] | Proporciona información sobre los objetos de origen de datos que se utilizarán. |

### Valor_devuelto

Un indicador que indica si el análisis del documento de plantilla se realizó correctamente. La bandera devuelta tiene sentido solo si un valor de la[`Options`](../options) propiedad incluye laInlineErrorMessages opción.

### Ver también

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* espacio de nombres [GroupDocs.Assembly](../../documentassembler)
* asamblea [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Carga un documento de plantilla de la secuencia de origen especificada, rellena el documento de plantilla con datos de las fuentes únicas o múltiples especificadas y almacena el documento de resultados en la secuencia de destino utilizando default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceStream | Stream | La secuencia desde la que leer un documento de plantilla. |
| targetStream | Stream | La secuencia para escribir un documento de resultados. |
| dataSourceInfos | DataSourceInfo[] | Proporciona información sobre los objetos de origen de datos que se utilizarán. |

### Valor_devuelto

Un indicador que indica si el análisis del documento de plantilla se realizó correctamente. La bandera devuelta tiene sentido solo si un valor de la[`Options`](../options) propiedad incluye laInlineErrorMessages opción.

### Ver también

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* espacio de nombres [GroupDocs.Assembly](../../documentassembler)
* asamblea [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Carga un documento de plantilla del flujo de origen especificado, rellena el documento de plantilla con datos de las fuentes únicas o múltiples especificadas y almacena el documento de resultados en el flujo de destino utilizando el dado[`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceStream | Stream | La secuencia desde la que leer un documento de plantilla. |
| targetStream | Stream | La secuencia para escribir un documento de resultados. |
| loadSaveOptions | LoadSaveOptions | Especifica opciones adicionales para cargar y guardar documentos. |
| dataSourceInfos | DataSourceInfo[] | Proporciona información sobre los objetos de origen de datos que se utilizarán. |

### Valor_devuelto

Un indicador que indica si el análisis del documento de plantilla se realizó correctamente. La bandera devuelta tiene sentido solo si un valor de la[`Options`](../options) propiedad incluye laInlineErrorMessages opción.

### Ver también

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* espacio de nombres [GroupDocs.Assembly](../../documentassembler)
* asamblea [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
