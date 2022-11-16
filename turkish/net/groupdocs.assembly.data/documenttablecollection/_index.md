---
title: DocumentTableCollection
second_title: .NET API Başvurusu için GroupDocs.Assembly
description: Şunların salt okunur bir koleksiyonunu temsil ederDocumentTable./documenttable belirli bir nesneninDocumentTableSet./documenttableset örnek.
type: docs
weight: 50
url: /tr/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

Şunların salt okunur bir koleksiyonunu temsil eder:[`DocumentTable`](../documenttable) belirli bir nesnenin[`DocumentTableSet`](../documenttableset) örnek.

```csharp
public class DocumentTableCollection : IEnumerable
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | Toplam sayısını alır[`DocumentTable`](../documenttable) koleksiyondaki nesneler. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | [`DocumentTable`](../documenttable) belirtilen dizindeki koleksiyondan örnek. (2 indexers) |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | Bu koleksiyonun belirtilen tabloyu içerip içermediğini gösteren bir değer döndürür. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | Bu koleksiyonun belirtilen ada sahip bir tablo içerip içermediğini gösteren bir değer döndürür. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | Yinelenecek bir numaralandırıcı döndürür[`DocumentTable`](../documenttable) bu koleksiyonun nesneleri. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | Bu koleksiyondaki belirtilen tablonun dizinini döndürür. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | Bu koleksiyonda belirtilen ada sahip bir tablonun dizinini döndürür. |

### Notlar

Bir belgeden ilgili tablolar yüklenirken koleksiyon otomatik olarak doldurulur ve değiştirilemez. Ancak,[`DocumentTable`](../documenttable)koleksiyonda bulunan nesneler değiştirilebilir.

### Ayrıca bakınız

* ad alanı [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* toplantı [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->