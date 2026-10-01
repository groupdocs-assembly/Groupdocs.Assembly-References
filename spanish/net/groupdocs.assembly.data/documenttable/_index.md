---
title: "DocumentTable"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Proporciona acceso a los datos de una única tabla o hoja de cálculo ubicada en un documento externo para ser utilizada durante el ensamblado de un documento."
type: docs
weight: 120
url: /es/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

Proporciona acceso a los datos de una única tabla (o hoja de cálculo) ubicada en un documento externo para ser utilizada al ensamblar un documento.

```csharp
public class DocumentTable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | Crea una nueva instancia de esta clase utilizando los [`DocumentTableOptions`](../documenttableoptions) predeterminados. |
| [DocumentTable](documenttable#constructor_2)(string, int) | Crea una nueva instancia de esta clase utilizando los [`DocumentTableOptions`](../documenttableoptions) predeterminados. |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | Crea una nueva instancia de esta clase. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | Crea una nueva instancia de esta clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | Obtiene la colección de objetos [`DocumentTableColumn`](../documenttablecolumn) que representan las columnas de la tabla correspondiente. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | Obtiene el índice original basado en cero de la tabla correspondiente según el documento fuente. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | Obtiene o establece el nombre de esta tabla utilizado para acceder a los datos de la tabla en un documento de plantilla pasado a [`DocumentAssembler`](../../groupdocs.assembly/documentassembler). |

### Observaciones

Para documentos con formatos de archivo de hoja de cálculo, una instancia de [`DocumentTable`](../documenttable) representa una única hoja. Para documentos de otros formatos de archivo, una instancia de [`DocumentTable`](../documenttable) representa una única tabla.

Para acceder a los datos de la tabla correspondiente durante el ensamblado de un documento, pase una instancia de esta clase como fuente de datos a una de las sobrecargas de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

En los documentos de plantilla, una instancia de [`DocumentTable`](../documenttable) debe tratarse de la misma manera que si fuera una instancia de DataTable. Consulte la referencia de sintaxis de plantillas para obtener más información.

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
