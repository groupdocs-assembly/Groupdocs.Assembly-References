---
title: "DocumentTable"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir belgeyi birleştirirken kullanılacak dış bir belgede bulunan tek bir tablo veya elektronik tablo verilerine erişim sağlar."
type: docs
weight: 120
url: /tr/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

Bir belge oluşturulurken kullanılacak dış bir belgede bulunan tek bir tablo (veya elektronik tablo) verilerine erişim sağlar.

```csharp
public class DocumentTable
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | Bu sınıfın yeni bir örneğini varsayılan [`DocumentTableOptions`](../documenttableoptions) kullanarak oluşturur. |
| [DocumentTable](documenttable#constructor_2)(string, int) | Bu sınıfın yeni bir örneğini varsayılan [`DocumentTableOptions`](../documenttableoptions) kullanarak oluşturur. |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | Bu sınıfın yeni bir örneğini oluşturur. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | Bu sınıfın yeni bir örneğini oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | İlgili tablonun sütunlarını temsil eden [`DocumentTableColumn`](../documenttablecolumn) nesnelerinin koleksiyonunu alır. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | Kaynak belgeye göre ilgili tablonun orijinal sıfır tabanlı indeksini alır. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | Bu tablonun adını alır veya ayarlar; bu ad, [`DocumentAssembler`](../../groupdocs.assembly/documentassembler) aracılığıyla geçirilen bir şablon belgesinde tablonun verilerine erişmek için kullanılır. |

### Açıklamalar

Elektronik tablo dosya formatlarına sahip belgeler için bir [`DocumentTable`](../documenttable) örneği tek bir sayfayı temsil eder. Diğer dosya formatlarına sahip belgeler için bir [`DocumentTable`](../documenttable) örneği tek bir tabloyu temsil eder.

Bir belgeyi birleştirirken ilgili tablonun verilerine erişmek için bu sınıfın bir örneğini bir veri kaynağı olarak [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument aşırı yüklemelerinden birine geçirin.

Şablon belgelerinde bir [`DocumentTable`](../documenttable) örneği bir DataTable örneği gibi ele alınmalıdır. Daha fazla bilgi için şablon sözdizimi referansına bakın.

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
