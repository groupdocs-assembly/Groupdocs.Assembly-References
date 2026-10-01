---
title: "IndexInDocument"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene el índice original basado en cero de la tabla correspondiente según el documento fuente."
type: docs
weight: 30
url: /es/net/groupdocs.assembly.data/documenttable/indexindocument/
---
## DocumentTable.IndexInDocument property

Obtiene el índice original basado en cero de la tabla correspondiente según el documento fuente.

```csharp
public int IndexInDocument { get; }
```

### Observaciones

Dependiendo de la implementación de [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler) proporcionada, este índice puede diferir del índice de esta instancia de [`DocumentTable`](../../documenttable) dentro de la colección de tablas de la instancia correspondiente de [`DocumentTableSet`](../../documenttableset), si la hay.

### Ver también

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
