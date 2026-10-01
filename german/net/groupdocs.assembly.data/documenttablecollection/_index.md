---
title: "DocumentTableCollection"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt eine schreibgeschützte Sammlung von DocumentTable./documenttable-Objekten einer bestimmten DocumentTableSet./documenttableset-Instanz dar."
type: docs
weight: 130
url: /de/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

Stellt eine schreibgeschützte Sammlung von [`DocumentTable`](../documenttable)-Objekten einer bestimmten [`DocumentTableSet`](../documenttableset)-Instanz dar.

```csharp
public class DocumentTableCollection : IEnumerable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | Ruft die Gesamtzahl der [`DocumentTable`](../documenttable)-Objekte in der Sammlung ab. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | Liest eine [`DocumentTable`](../documenttable)-Instanz aus der Sammlung am angegebenen Index. (2 Indexer) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | Gibt einen Wert zurück, der angibt, ob diese Sammlung die angegebene Tabelle enthält. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | Gibt einen Wert zurück, der angibt, ob diese Sammlung eine Tabelle mit dem angegebenen Namen enthält. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | Gibt einen Enumerator zurück, um die [`DocumentTable`](../documenttable)-Objekte dieser Sammlung zu iterieren. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | Gibt den Index der angegebenen Tabelle innerhalb dieser Sammlung zurück. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | Gibt den Index einer Tabelle mit dem angegebenen Namen innerhalb dieser Sammlung zurück. |

### Hinweise

Die Sammlung wird automatisch gefüllt, während die entsprechenden Tabellen aus einem Dokument geladen werden, und kann nicht geändert werden. Eigenschaften von [`DocumentTable`](../documenttable)-Objekten, die in der Sammlung enthalten sind, können jedoch geändert werden.

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
