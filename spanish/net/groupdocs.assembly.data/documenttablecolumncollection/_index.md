---
title: "DocumentTableColumnCollection"
second_title: "Referencia de API de GroupDocs.Assembly para .NET"
description: "Representa una colección de solo lectura de objetos DocumentTableColumn./documenttablecolumn de una instancia particular de DocumentTable./documenttable."
type: docs
weight: 150
url: /es/net/groupdocs.assembly.data/documenttablecolumncollection/
---
## DocumentTableColumnCollection class

Representa una colección de solo lectura de objetos [`DocumentTableColumn`](../documenttablecolumn) de una instancia particular de [`DocumentTable`](../documenttable).

```csharp
public class DocumentTableColumnCollection : IEnumerable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecolumncollection/count) { get; } | Obtiene el número total de objetos [`DocumentTableColumn`](../documenttablecolumn) en la colección. |
| [Item](../../groupdocs.assembly.data/documenttablecolumncollection/item) { get; } | Obtiene una instancia de [`DocumentTableColumn`](../documenttablecolumn) de la colección en el índice especificado. (2 indexadores) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains)(DocumentTableColumn) | Devuelve un valor que indica si esta colección contiene la columna especificada. |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains_1)(string) | Devuelve un valor que indica si esta colección contiene una columna con el nombre especificado. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecolumncollection/getenumerator)() | Devuelve un enumerador para iterar los objetos [`DocumentTableColumn`](../documenttablecolumn) de esta colección. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof)(DocumentTableColumn) | Devuelve el índice de la columna especificada dentro de esta colección. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof_1)(string) | Devuelve el índice de una columna con el nombre especificado dentro de esta colección. |

### Observaciones

La colección se llena automáticamente al cargar la tabla correspondiente desde un documento y no puede modificarse. Sin embargo, las propiedades de los objetos [`DocumentTableColumn`](../documenttablecolumn) contenidos en la colección pueden modificarse.

### Ver también

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Assembly.dll -->
