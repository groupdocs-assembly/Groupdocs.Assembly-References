---
title: "DocumentTableCollection"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Belirli bir DocumentTableSet./documenttableset örneğine ait DocumentTable./documenttable nesnelerinin yalnızca okunabilir bir koleksiyonunu temsil eder."
type: docs
weight: 130
url: /tr/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

Belirli bir [`DocumentTableSet`](../documenttableset) örneğine ait [`DocumentTable`](../documenttable) nesnelerinin salt okunur bir koleksiyonunu temsil eder.

```csharp
public class DocumentTableCollection : IEnumerable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | Koleksiyondaki [`DocumentTable`](../documenttable) nesnelerinin toplam sayısını alır. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | Belirtilen indeksteki koleksiyondan bir [`DocumentTable`](../documenttable) örneğini alır. (2 indeksleyici) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | Bu koleksiyonun belirtilen tabloyu içerip içermediğini gösteren bir değeri döndürür. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | Bu koleksiyonun belirtilen ada sahip bir tabloyu içerip içermediğini gösteren bir değeri döndürür. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | Bu koleksiyonun [`DocumentTable`](../documenttable) nesneleri üzerinde yineleme yapmak için bir enumeratör döndürür. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | Bu koleksiyon içinde belirtilen tablonun indeksini döndürür. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | Bu koleksiyon içinde belirtilen ada sahip bir tablonun indeksini döndürür. |

### Açıklamalar

Koleksiyon, bir belgeden ilgili tablolar yüklenirken otomatik olarak doldurulur ve değiştirilemez. Ancak, koleksiyon içinde bulunan [`DocumentTable`](../documenttable) nesnelerinin özellikleri değiştirilebilir.

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
