---
title: "DocumentTableCollection"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Representa una colección de solo lectura de objetos DocumentTable./documenttable de una instancia particular de DocumentTableSet./documenttableset."
type: docs
weight: 130
url: /es/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

Representa una colección de solo lectura de objetos [`DocumentTable`](../documenttable) de una instancia particular de [`DocumentTableSet`](../documenttableset).

```csharp
public class DocumentTableCollection : IEnumerable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | Obtiene el número total de objetos [`DocumentTable`](../documenttable) en la colección. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | Obtiene una instancia de [`DocumentTable`](../documenttable) de la colección en el índice especificado. (2 indexadores) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | Devuelve un valor que indica si esta colección contiene la tabla especificada. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | Devuelve un valor que indica si esta colección contiene una tabla con el nombre especificado. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | Devuelve un enumerador para iterar los objetos [`DocumentTable`](../documenttable) de esta colección. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | Devuelve el índice de la tabla especificada dentro de esta colección. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | Devuelve el índice de una tabla con el nombre especificado dentro de esta colección. |

### Observaciones

La colección se llena automáticamente al cargar las tablas correspondientes de un documento y no puede modificarse. Sin embargo, las propiedades de los objetos [`DocumentTable`](../documenttable) contenidos en la colección pueden modificarse.

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
