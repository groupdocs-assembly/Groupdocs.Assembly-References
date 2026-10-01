---
title: "DocumentTableSet"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Crea una nueva instancia de esta clase cargando todas las tablas de un documento usando DocumentTableOptionsgroupdocs.assembly.data/documenttableoptions por defecto."
type: docs
weight: 10
url: /es/net/groupdocs.assembly.data/documenttableset/documenttableset/
---
## DocumentTableSet(string) {#constructor_2}

Crea una nueva instancia de esta clase cargando todas las tablas de un documento usando los valores predeterminados de [`DocumentTableOptions`](../../documenttableoptions).

```csharp
public DocumentTableSet(string documentPath)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| documentPath | String | La ruta a un documento que contiene tablas a las que se accederá. |

### Ver también

* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(string, IDocumentTableLoadHandler) {#constructor_3}

Crea una nueva instancia de esta clase.

```csharp
public DocumentTableSet(string documentPath, IDocumentTableLoadHandler loadHandler)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| documentPath | String | La ruta a un documento que contiene tablas a las que se accederá. |
| loadHandler | IDocumentTableLoadHandler | Una implementación de [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler) que controla cómo se cargan las tablas del documento. |

### Ver también

* interface [IDocumentTableLoadHandler](../../idocumenttableloadhandler)
* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(Stream) {#constructor}

Crea una nueva instancia de esta clase cargando todas las tablas de un documento usando los valores predeterminados de [`DocumentTableOptions`](../../documenttableoptions).

```csharp
public DocumentTableSet(Stream documentStream)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| documentStream | Stream | El flujo que contiene un documento con tablas a las que se accederá. |

### Ver también

* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(Stream, IDocumentTableLoadHandler) {#constructor_1}

Crea una nueva instancia de esta clase.

```csharp
public DocumentTableSet(Stream documentStream, IDocumentTableLoadHandler loadHandler)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| documentStream | Stream | El flujo que contiene un documento con tablas a las que se accederá. |
| loadHandler | IDocumentTableLoadHandler | Una implementación de [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler) que controla cómo se cargan las tablas del documento. |

### Ver también

* interface [IDocumentTableLoadHandler](../../idocumenttableloadhandler)
* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
