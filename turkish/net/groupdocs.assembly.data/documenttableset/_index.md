---
title: "DocumentTableSet"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Bir belgeyi birleştirirken kullanılacak dış bir belgede bulunan birden fazla tablo veya elektronik tablo verisine erişim sağlar. Ayrıca belge tabloları için ebeveyn‑çocuk ilişkileri tanımlamayı mümkün kılar, böylece şablon belgelerindeki ilgili verilere erişimi basitleştirir."
type: docs
weight: 200
url: /tr/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

Bir belge oluşturulurken kullanılacak dış bir belgede bulunan birden fazla tablo (veya elektronik tablo) verilerine erişim sağlar. Ayrıca, belge tabloları için ebeveyn-çocuk ilişkilerini tanımlamayı mümkün kılar ve böylece şablon belgeler içinde ilgili verilere erişimi basitleştirir.

```csharp
public class DocumentTableSet
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | Bu sınıfın yeni bir örneğini, bir belgeden tüm tabloları varsayılan [`DocumentTableOptions`](../documenttableoptions) kullanarak yükleyerek oluşturur. |
| [DocumentTableSet](documenttableset#constructor_2)(string) | Bu sınıfın yeni bir örneğini, bir belgeden tüm tabloları varsayılan [`DocumentTableOptions`](../documenttableoptions) kullanarak yükleyerek oluşturur. |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | Bu sınıfın yeni bir örneğini oluşturur. |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | Bu sınıfın yeni bir örneğini oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | Bu kümenin belge tabloları için tanımlanan ebeveyn‑çocuk ilişkileri koleksiyonunu alır. |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | Bu kümenin tablolarını temsil eden [`DocumentTable`](../documenttable) nesnelerinin koleksiyonunu alır. |

### Açıklamalar

Elektronik tablo dosya formatındaki belgeler için, bir [`DocumentTableSet`](../documenttableset) örneği bir dizi sayfayı temsil eder. Diğer dosya formatlarındaki belgeler için ise bir [`DocumentTableSet`](../documenttableset) örneği bir dizi tabloyu temsil eder.

Bir belgeyi birleştirirken ilgili tabloların verilerine erişmek için, bu sınıfın bir örneğini bir veri kaynağı olarak [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument aşırı yüklemelerinden birine geçirin.

Şablon belgelerinde, bir [`DocumentTableSet`](../documenttableset) örneği, bir DataSet örneğiymiş gibi aynı şekilde ele alınmalıdır. Daha fazla bilgi için şablon sözdizimi referansına bakın.

### Ayrıca Bakınız

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
