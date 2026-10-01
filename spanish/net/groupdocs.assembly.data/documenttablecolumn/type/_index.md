---
title: "Type"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Obtiene o establece el tipo de valores de celda en esta columna."
type: docs
weight: 40
url: /es/net/groupdocs.assembly.data/documenttablecolumn/type/
---
## DocumentTableColumn.Type property

Obtiene o establece el tipo de valores de celda en esta columna.

```csharp
public Type Type { get; set; }
```

### Observaciones

Para documentos de formatos de archivo que no son hojas de cálculo, el tipo inicial siempre se determina automáticamente como cadena. Para documentos de formatos de hoja de cálculo, el tipo inicial se determina automáticamente según los valores de celda correspondientes.

Si las celdas de una columna de hoja de cálculo particular contienen valores de diferentes tipos, entonces el tipo inicial de la columna también se determina automáticamente como cadena.

### Ver también

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
