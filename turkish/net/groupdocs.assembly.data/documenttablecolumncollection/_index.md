---
title: "DocumentTableColumnCollection"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Belirli bir DocumentTable./documenttable örneğinin DocumentTableColumn./documenttablecolumn nesnelerinden oluşan salt okunur bir koleksiyonu temsil eder."
type: docs
weight: 150
url: /tr/net/groupdocs.assembly.data/documenttablecolumncollection/
---
## DocumentTableColumnCollection class

Belirli bir [`DocumentTable`](../documenttable) örneğinin [`DocumentTableColumn`](../documenttablecolumn) nesnelerinden oluşan salt okunur bir koleksiyonu temsil eder.

```csharp
public class DocumentTableColumnCollection : IEnumerable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecolumncollection/count) { get; } | Koleksiyondaki [`DocumentTableColumn`](../documenttablecolumn) nesnelerinin toplam sayısını alır. |
| [Item](../../groupdocs.assembly.data/documenttablecolumncollection/item) { get; } | Belirtilen dizindeki koleksiyondan bir [`DocumentTableColumn`](../documenttablecolumn) örneğini alır. (2 indeksleyici) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains)(DocumentTableColumn) | Bu koleksiyonun belirtilen sütunu içerip içermediğini gösteren bir değer döndürür. |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains_1)(string) | Bu koleksiyonun belirtilen ada sahip bir sütun içerip içermediğini gösteren bir değer döndürür. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecolumncollection/getenumerator)() | Bu koleksiyonun [`DocumentTableColumn`](../documenttablecolumn) nesneleri üzerinde yineleme yapmak için bir enumerator döndürür. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof)(DocumentTableColumn) | Bu koleksiyon içinde belirtilen sütunun indeksini döndürür. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof_1)(string) | Bu koleksiyon içinde belirtilen ada sahip bir sütunun indeksini döndürür. |

### Açıklamalar

Koleksiyon, ilgili tablo bir belgeden yüklenirken otomatik olarak doldurulur ve değiştirilemez. Ancak, koleksiyon içinde bulunan [`DocumentTableColumn`](../documenttablecolumn) nesnelerinin özellikleri değiştirilebilir.

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
