---
title: DocumentTable
second_title: Referencia de API de GroupDocs.Assembly para .NET
description: Proporciona acceso a los datos de una sola tabla u hoja de cálculo ubicada en un documento externo que se utilizará mientras ensambla un documento.
type: docs
weight: 40
url: /es/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

Proporciona acceso a los datos de una sola tabla (u hoja de cálculo) ubicada en un documento externo que se utilizará mientras ensambla un documento.

```csharp
public class DocumentTable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | Crea una nueva instancia de esta clase usando el valor predeterminado[`DocumentTableOptions`](../documenttableoptions) . |
| [DocumentTable](documenttable#constructor_2)(string, int) | Crea una nueva instancia de esta clase usando el valor predeterminado[`DocumentTableOptions`](../documenttableoptions) . |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | Crea una nueva instancia de esta clase. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | Crea una nueva instancia de esta clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | Obtiene la colección de[`DocumentTableColumn`](../documenttablecolumn) objetos que representan columnas de la tabla correspondiente. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | Obtiene el índice de base cero original de la tabla correspondiente según el documento de origen. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | Obtiene o establece el nombre de esta tabla utilizada para acceder a los datos de la tabla en un documento de plantilla pasado a [`DocumentAssembler`](../../groupdocs.assembly/documentassembler) . |

### Observaciones

Para documentos de formato de archivo de hoja de cálculo, un[`DocumentTable`](../documenttable)instancia representa una sola hoja. Para documentos de otros formatos de archivo, un[`DocumentTable`](../documenttable) instancia representa una sola tabla.

Para acceder a los datos de la tabla correspondiente mientras ensambla un documento, pase una instancia de esta clase como una fuente de datos a uno de[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument sobrecargas.

En los documentos de plantilla, un[`DocumentTable`](../documenttable) instancia debe tratarse de la misma manera que si fuera unDataTable instancia. Consulte la referencia de sintaxis de la plantilla para obtener más información.

### Ver también

* espacio de nombres [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* asamblea [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->