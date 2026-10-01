---
title: "DocumentTableSet"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Proporciona acceso a los datos de múltiples tablas o hojas de cálculo ubicadas en un documento externo para ser utilizados al ensamblar un documento. También permite definir relaciones padre‑hijo para las tablas del documento, simplificando así el acceso a datos relacionados dentro de los documentos de plantilla."
type: docs
weight: 200
url: /es/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

Proporciona acceso a los datos de múltiples tablas (o hojas de cálculo) ubicadas en un documento externo para ser utilizadas al ensamblar un documento. Además, permite definir relaciones padre-hijo para las tablas de documento, simplificando así el acceso a datos relacionados dentro de los documentos plantilla.

```csharp
public class DocumentTableSet
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | Crea una nueva instancia de esta clase cargando todas las tablas de un documento utilizando las [`DocumentTableOptions`](../documenttableoptions) predeterminadas. |
| [DocumentTableSet](documenttableset#constructor_2)(string) | Crea una nueva instancia de esta clase cargando todas las tablas de un documento utilizando las [`DocumentTableOptions`](../documenttableoptions) predeterminadas. |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | Crea una nueva instancia de esta clase. |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | Crea una nueva instancia de esta clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | Obtiene la colección de relaciones padre‑hijo definidas para las tablas de documento de este conjunto. |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | Obtiene la colección de objetos [`DocumentTable`](../documenttable) que representan las tablas de este conjunto. |

### Observaciones

Para documentos con formatos de archivo de hoja de cálculo, una instancia de [`DocumentTableSet`](../documenttableset) representa un conjunto de hojas. Para documentos con otros formatos de archivo, una instancia de [`DocumentTableSet`](../documenttableset) representa un conjunto de tablas.

Para acceder a los datos de las tablas correspondientes al ensamblar un documento, pase una instancia de esta clase como fuente de datos a una de las sobrecargas de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

En los documentos de plantilla, una instancia de [`DocumentTableSet`](../documenttableset) debe tratarse de la misma manera que si fuera una instancia de DataSet. Consulte la referencia de sintaxis de plantillas para obtener más información.

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
