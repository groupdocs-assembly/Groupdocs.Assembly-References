---
title: "DocumentTableColumnCollection"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt eine schreibgeschützte Sammlung von DocumentTableColumn./documenttablecolumn‑Objekten einer bestimmten DocumentTable./documenttable‑Instanz dar."
type: docs
weight: 150
url: /de/net/groupdocs.assembly.data/documenttablecolumncollection/
---
## DocumentTableColumnCollection class

Stellt eine schreibgeschützte Sammlung von [`DocumentTableColumn`](../documenttablecolumn)-Objekten einer bestimmten [`DocumentTable`](../documenttable)-Instanz dar.

```csharp
public class DocumentTableColumnCollection : IEnumerable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecolumncollection/count) { get; } | Liest die Gesamtzahl der [`DocumentTableColumn`](../documenttablecolumn)-Objekte in der Sammlung. |
| [Item](../../groupdocs.assembly.data/documenttablecolumncollection/item) { get; } | Liest eine [`DocumentTableColumn`](../documenttablecolumn)-Instanz aus der Sammlung am angegebenen Index. (2 Indexer) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains)(DocumentTableColumn) | Gibt einen Wert zurück, der angibt, ob diese Sammlung die angegebene Spalte enthält. |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains_1)(string) | Gibt einen Wert zurück, der angibt, ob diese Sammlung eine Spalte mit dem angegebenen Namen enthält. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecolumncollection/getenumerator)() | Gibt einen Enumerator zurück, um die [`DocumentTableColumn`](../documenttablecolumn)-Objekte dieser Sammlung zu iterieren. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof)(DocumentTableColumn) | Gibt den Index der angegebenen Spalte innerhalb dieser Sammlung zurück. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof_1)(string) | Gibt den Index einer Spalte mit dem angegebenen Namen innerhalb dieser Sammlung zurück. |

### Hinweise

Die Sammlung wird automatisch beim Laden der entsprechenden Tabelle aus einem Dokument gefüllt und kann nicht geändert werden. Die Eigenschaften der im Sammlung enthaltenen [`DocumentTableColumn`](../documenttablecolumn)-Objekte können jedoch geändert werden.

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
