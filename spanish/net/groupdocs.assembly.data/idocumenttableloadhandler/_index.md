---
title: "IDocumentTableLoadHandler"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Sobrescribe la carga predeterminada de objetos DocumentTable./documenttable al crear una instancia de DocumentTableSet./documenttableset."
type: docs
weight: 210
url: /es/net/groupdocs.assembly.data/idocumenttableloadhandler/
---
## IDocumentTableLoadHandler interface

Sobrescribe la carga predeterminada de objetos [`DocumentTable`](../documenttable) al crear una instancia de [`DocumentTableSet`](../documenttableset).

```csharp
public interface IDocumentTableLoadHandler
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Handle](../../groupdocs.assembly.data/idocumenttableloadhandler/handle)(DocumentTableLoadArgs) | Sobrescribe la carga predeterminada de un objeto [`DocumentTable`](../documenttable) en particular al crear una instancia de [`DocumentTableSet`](../documenttableset). |

### Observaciones

Implemente esta interfaz si desea descartar la carga de objetos [`DocumentTable`](../documenttable) específicos o proporcionar [`DocumentTableOptions`](../documenttableoptions) específicos para las tablas de documento que se están cargando.

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
